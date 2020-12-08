# Syncing with Rclone

{% hint style="warning" %}
This document introduces another centralized fast state syncing method using rclone. Please use it with caution. This guide is mainly used for a newly started node to catch up with the blockchain faster. Otherwise, the blockchain syncing may take weeks from genesis block.
{% endhint %}

Rclone db snapshot is sync'ed with blockchain frequently. However, there maybe a potential race condition when the rclone may fail due to our nodes were updating the db files at the same time. In this case, just re-run the rclone command to re-sync again.

## 1. Installing Rclone

For installing Rclone, please follow the instructions at [https://rclone.org](https://rclone.org/).

TL;DR, on a Linux system, you may run the following command.

```text
curl https://rclone.org/install.sh | sudo bash
```

## 2. Configuring Rclone

To check the location of the `rclone.conf`file run:

```bash
rclone config file
```

The `rclone.conf` file is usually located at `~/.config/rclone/rclone.conf` . 

Now run the following command to create the rclone.conf file.

```bash
cat<<-EOF > ~/.config/rclone/rclone.conf
[mainnet]
type = s3
provider = AWS
env_auth = false
region = us-west-1
acl = public-read
server_side_encryption = AES256
storage_class = REDUCED_REDUNDANCY
EOF
```

{% hint style="info" %}
The above rclone config also work for the pangaea testnet network
{% endhint %}

## 3. Running Rclone

Below is the command to sync the shard you want. Replace `<ShardID>`with the shard number you want to sync.  
As of 8 Dec 2020: 
- Shard 0 is around 10.7 Gb  
- Each rclone snapshot is around 3.6 Gb

It may take up to 10 minutes to download depending on your network connection.

{% tabs %}
{% tab title="Mainnet" %}
```bash
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_<ShardID> harmony_db_<ShardID>
```
{% endtab %}

{% tab title="Testnet" %}
```
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_<ShardID> harmony_db_<ShardID>
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Nodes in shard 0 just need to sync `harmony_db_0`

Nodes in shard 1, 2, 3 need to sync both `harmony_db_0`, and `harmony_db_<ShardID>`
{% endhint %}

## 4. Cheat Sheet

#### shard0:

{% tabs %}
{% tab title="Mainnet" %}
```bash
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_0 harmony_db_0
```
{% endtab %}

{% tab title="Testnet" %}
```
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_0 harmony_db_0
```
{% endtab %}
{% endtabs %}

#### Shard 1:

{% tabs %}
{% tab title="Mainnet" %}
```bash
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_1 harmony_db_1
```
{% endtab %}

{% tab title="Testnet" %}
```
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_1 harmony_db_1
```
{% endtab %}
{% endtabs %}

#### Shard 2:

{% tabs %}
{% tab title="Mainnet" %}
```bash
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_2 harmony_db_2
```
{% endtab %}

{% tab title="Testnet" %}
```
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_2 harmony_db_2
```
{% endtab %}
{% endtabs %}

#### Shard 3:

{% tabs %}
{% tab title="Mainnet" %}
```bash
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/mainnet.min/harmony_db_3 harmony_db_3
```
{% endtab %}

{% tab title="Testnet" %}
```
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_0 harmony_db_0
rclone -P sync mainnet:pub.harmony.one/testnet.min/harmony_db_3 harmony_db_3
```
{% endtab %}
{% endtabs %}

After the sync, you may use `du -h harmony_db_*` command to check the size of the downloaded snapshots.

{% hint style="info" %}
`-P` will display a download progress & ETA.
{% endhint %}



