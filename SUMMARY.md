# Table of contents

* [Introduction](README.md)
* [Wallets](wallets/README.md)
  * [Ledger](wallets/ledger/README.md)
    * [Download & Setup](wallets/ledger/download-and-setup.md)
    * [Ledger with HMY CLI](wallets/ledger/using-with-hmy-cli.md)
    * [Ledger with Staking Dashboard](wallets/ledger/using-with-staking-dashboard/README.md)
      * [Sign In With Ledger](wallets/ledger/using-with-staking-dashboard/sign-in-with-ledger.md)
      * [Sending transactions via Ledger](wallets/ledger/using-with-staking-dashboard/send-tx.md)
      * [Staking Transactions via Ledger](wallets/ledger/using-with-staking-dashboard/sign-delegation.md)
  * [Trust Wallet](wallets/trustwallet.md)
  * [ONE Wallet](wallets/one-wallet.md)
  * [Math Wallet](wallets/mathwallet/README.md)
    * [Download & Setup](wallets/mathwallet/download-and-setup.md)
    * [Create/Import/Export Wallet](wallets/mathwallet/create-import-wallet.md)
    * [Sending Transactions via Math Wallet](wallets/mathwallet/send-tx.md)
    * [Staking Transactions via Math Wallet](wallets/mathwallet/staking-transactions.md)
  * [Harmony Chrome Extension](wallets/chrome-extension.md)
  * [Harmony CLI](wallets/harmony-cli/README.md)
    * [Download & Setup](wallets/harmony-cli/download-setup.md)
    * [Create or Import Wallet](wallets/harmony-cli/create-import-wallet.md)
    * [Sending Transactions](wallets/harmony-cli/send-tx.md)
    * [Staking Transactions](wallets/harmony-cli/staking-transactions.md)
    * [Querying Balances](wallets/harmony-cli/querying-balances.md)
    * [Querying the Blockchain](wallets/harmony-cli/querying-the-blockchain.md)
    * [List of Transaction Error Messages](wallets/harmony-cli/list-of-transaction-error-messages.md)
    * [Cookbook](wallets/harmony-cli/cookbook.md)
    * [Other CLI References](wallets/harmony-cli/other-cli-references.md)
  * [Sprout](wallets/sprout.md)
  * [Safepal](wallets/safepal/README.md)
    * [Download & setup](wallets/safepal/download-and-setup.md)
    * [Create/import account](wallets/safepal/create-import-account.md)
    * [Send transaction](wallets/safepal/send-transaction.md)
  * [Wallet Management](wallets/wallet-management/README.md)
    * [Private Key Management](wallets/wallet-management/key-management.md)
    * [Missing Funds on Exchanges](wallets/wallet-management/missing-funds-on-exchange.md)
* [Delegators](delegator/README.md)
  * [Staking Dashboard](delegator/staking-dashboard/README.md)
    * [Walkthrough](delegator/staking-dashboard/choosing-a-validator.md)
    * [Staking Transactions](delegator/staking-dashboard/staking-transactions.md)
    * [Sending Transactions](delegator/staking-dashboard/sending-transactions.md)
    * [Open Staking — Frequently Asked Questions](delegator/staking-dashboard/open-staking-frequently-asked-questions.md)
  * [Informational Videos](delegator/delegator-journey.md)
* [Validators](validators/README.md)
  * [Terms & Concepts](validators/definitions/README.md)
    * [Validator, BLS key, Instance](validators/definitions/validator-keys-and-bids/README.md)
      * [Shard Assignment](validators/definitions/validator-keys-and-bids/shard-assignment.md)
    * [Slots Bidding and Election](validators/definitions/slots-bidding-and-election.md)
    * [Effective Proof-of-Stake](validators/definitions/effective-proof-of-stake-bidding-process.md)
    * [Block Reward](validators/definitions/block-reward.md)
    * [Epoch Transition](validators/definitions/epoch-transition.md)
    * [Slashing](validators/definitions/others.md)
    * [Undelegation](validators/definitions/undelegation.md)
  * [Cloud Setup](validators/cloud-setup/README.md)
    * [Requirements](validators/cloud-setup/requirements.md)
    * [Cloud Guides](validators/cloud-setup/cloud-guides/README.md)
      * [Digital Ocean](validators/cloud-setup/cloud-guides/digital-ocean.md)
      * [Vultr](validators/cloud-setup/cloud-guides/vultr.md)
      * [AWS](validators/cloud-setup/cloud-guides/aws.md)
      * [Google Cloud](validators/cloud-setup/cloud-guides/google-cloud.md)
      * [Ankr](validators/cloud-setup/cloud-guides/ankr.md)
  * [Node Setup](validators/node-setup/README.md)
    * [AutoNode Setup](validators/node-setup/autonode-setup/README.md)
      * [Install & Run](validators/node-setup/autonode-setup/install-and-run.md)
      * [Update](validators/node-setup/autonode-setup/update.md)
      * [Monitor](validators/node-setup/autonode-setup/monitor.md)
      * [BLS key management](validators/node-setup/autonode-setup/bls-key-management.md)
      * [Collect Rewards](validators/node-setup/autonode-setup/collect-rewards.md)
      * [Maintenance](validators/node-setup/autonode-setup/maintenance.md)
      * [Troubleshoot](validators/node-setup/autonode-setup/troubleshoot.md)
      * [Extra](validators/node-setup/autonode-setup/extra.md)
    * [Manual Setup](validators/node-setup/manual-setup/README.md)
      * [HMY CLI Download](validators/node-setup/manual-setup/hmy-cli-download.md)
      * [Setting up BLS Keys](validators/node-setup/manual-setup/generating-a-bls-key.md)
      * [Syncing with Rclone](validators/node-setup/manual-setup/using-rclone.md)
      * [Running a Node](validators/node-setup/manual-setup/running-a-node.md)
      * [Creating A Wallet](validators/node-setup/manual-setup/creating-a-wallet.md)
      * [Creating A Validator](validators/node-setup/manual-setup/creating-a-validator.md)
      * [Setup Cheatsheet](validators/node-setup/manual-setup/validator-cheat-sheet.md)
  * [Managing Your Validator](validators/managing-your-validator/README.md)
    * [Checking Validator Information](validators/managing-your-validator/checking-validator-information.md)
    * [Changing Validator Information](validators/managing-your-validator/changing-validator-information.md)
    * [Delegating To A Validator](validators/managing-your-validator/delegating-to-a-validator.md)
    * [Undelegating From A Validator](validators/managing-your-validator/undelegating-to-a-validator.md)
    * [Check Your Delegations](validators/managing-your-validator/seeing-stakers.md)
    * [Collecting Rewards](validators/managing-your-validator/collecting-rewards.md)
    * [Adding A Validator Logo](validators/managing-your-validator/adding-a-validator-logo.md)
  * [Staking Dashboard Basics](validators/staking-dashboard.md)
  * [Validator Information Terms](validators/validator-info-doc.md)
  * [Validator Security Tips](validators/validator-security.md)
  * [Network Status Monitoring](validators/network-status.md)
  * [Troubleshooting](validators/validator-troubleshooting/README.md)
    * [My validator is not elected](validators/validator-troubleshooting/why-am-i-not-elected-in-the-epos-committee.md)
    * [Frequently Asked Questions \(FAQ\)](validators/validator-troubleshooting/frequently-asked-questions-faq.md)
  * [Tools](validators/tools/README.md)
    * [Telegram Bots](validators/tools/telegram-bots.md)
    * [Dashboards](validators/tools/dashboards.md)
    * [Reward Calculators](validators/tools/calculators.md)
    * [Text User Interface \(TUI\)](validators/tools/text-user-interface-tui.md)
    * [Mobile Apps](validators/tools/mobile-apps/README.md)
      * [One Validator Dashboard](validators/tools/mobile-apps/one-validator-dashboard.md)
      * [Termux](validators/tools/mobile-apps/termux.md)
  * [Under Construction](validators/under-construction/README.md)
    * [Installing A Node](validators/under-construction/installing-node/README.md)
      * [Using Binary CLI](validators/under-construction/installing-node/using-binary-cli.md)
      * [Using AutoNode](validators/under-construction/installing-node/using-autonode/README.md)
        * [Install & Run](validators/under-construction/installing-node/using-autonode/install-and-run.md)
        * [Update](validators/under-construction/installing-node/using-autonode/update.md)
        * [Monitor](validators/under-construction/installing-node/using-autonode/monitor.md)
        * [BLS Key Management](validators/under-construction/installing-node/using-autonode/bls-key-management.md)
        * [Collect Rewards](validators/under-construction/installing-node/using-autonode/collect-rewards.md)
        * [Maintenance](validators/under-construction/installing-node/using-autonode/maintenance.md)
        * [Troubleshoot](validators/under-construction/installing-node/using-autonode/troubleshoot.md)
        * [Extra](validators/under-construction/installing-node/using-autonode/extra.md)
      * [Using Node.sh](validators/under-construction/installing-node/using-node.sh.md)
    * [Updating A Node](validators/under-construction/upgrading-node/README.md)
      * [Using Binary CLI](validators/under-construction/upgrading-node/using-binary-cli.md)
      * [Using AutoNode](validators/under-construction/upgrading-node/using-autonode.md)
      * [Using Node.sh](validators/under-construction/upgrading-node/using-node.sh.md)
    * [Checking A Node](validators/under-construction/checking-node-status.md)
* [Developers](developers/README.md)
  * [Which ONE are you?](developers/which-one-are-you.md)
  * [SDK](developers/sdk.md)
  * [API](developers/api/README.md)
    * [Methods](developers/api/methods/README.md)
      * [Account Methods](developers/api/methods/account-methods/README.md)
        * [hmy\_getBalanceByBlockNumber](developers/api/methods/account-methods/hmy_getbalancebyblocknumber.md)
        * [hmy\_getTransactionCount](developers/api/methods/account-methods/hmy_gettransactioncount.md)
        * [hmy\_getBalance](developers/api/methods/account-methods/hmy_getbalance.md)
        * [address](developers/api/methods/account-methods/getexploreraddress.md)
      * [Filter Methods](developers/api/methods/filter-methods/README.md)
        * [hmy\_getFilterLogs](developers/api/methods/filter-methods/hmy_getfilterlogs.md)
        * [hmy\_newFilter](developers/api/methods/filter-methods/hmy_newfilter.md)
        * [hmy\_newPendingTransactionFilter](developers/api/methods/filter-methods/hmy_newpendingtransactionfilter.md)
        * [hmy\_newBlockFilter](developers/api/methods/filter-methods/hmy_newblockfilter.md)
        * [hmy\_getFilterChanges](developers/api/methods/filter-methods/hmy_getfilterchanges.md)
        * [hmy\_getLogs](developers/api/methods/filter-methods/hmy_getlogs.md)
      * [Transaction Related Methods](developers/api/methods/transaction-related-methods/README.md)
        * [hmy\_getStakingTransactionByBlockHashAndIndex](developers/api/methods/transaction-related-methods/hmy_getstakingtransactionbyblockhashandindex.md)
        * [hmy\_getStakingTransactionByBlockNumberAndIndex](developers/api/methods/transaction-related-methods/hmy_getstakingtransactionbyblocknumberandindex.md)
        * [hmy\_getStakingTransactionByHash](developers/api/methods/transaction-related-methods/hmy_getstakingtransactionbyhash.md)
        * [hmy\_getCurrentTransactionErrorSink](developers/api/methods/transaction-related-methods/hmy_getcurrenttransactionerrorsink.md)
        * [hmy\_getPendingCrossLinks](developers/api/methods/transaction-related-methods/hmy_getpendingcrosslinks.md)
        * [hmy\_getPendingCXReceipts](developers/api/methods/transaction-related-methods/hmy_getpendingcxreceipts.md)
        * [hmy\_getCXReceiptByHash](developers/api/methods/transaction-related-methods/hmy_getcxreceiptbyhash.md)
        * [hmy\_pendingTransactions](developers/api/methods/transaction-related-methods/hmy_pendingtransactions.md)
        * [hmy\_sendRawStakingTransaction](developers/api/methods/transaction-related-methods/hmy_sendrawstakingtransaction.md)
        * [hmy\_getTransactionsHistory](developers/api/methods/transaction-related-methods/hmy_gettransactionshistory.md)
        * [hmy\_sendRawTransaction](developers/api/methods/transaction-related-methods/hmy_sendrawtransaction.md)
        * [hmy\_getTransactionReceipt](developers/api/methods/transaction-related-methods/hmy_gettransactionreceipt.md)
        * [hmy\_getBlockTransactionCountByHash](developers/api/methods/transaction-related-methods/hmy_getblocktransactioncountbyhash.md)
        * [hmy\_getBlockTransactionCountByNumber](developers/api/methods/transaction-related-methods/hmy_getblocktransactioncountbynumber.md)
        * [hmy\_getTransactionByHash](developers/api/methods/transaction-related-methods/hmy_gettransactionbyhash.md)
        * [hmy\_getTransactionByBlockNumberAndIndex](developers/api/methods/transaction-related-methods/hmy_gettransactionbyblocknumberandindex.md)
        * [hmy\_getTransactionByBlockHashAndIndex](developers/api/methods/transaction-related-methods/hmy_gettransactionbyblockhashandindex.md)
        * [hmy\_getBlockByNumber](developers/api/methods/transaction-related-methods/hmy_getblockbynumber.md)
        * [hmy\_getBlockByHash](developers/api/methods/transaction-related-methods/hmy_getblockbyhash.md)
        * [hmy\_getBlocks](developers/api/methods/transaction-related-methods/hmy_getblocks.md)
        * [tx](developers/api/methods/transaction-related-methods/getexplorerblocks.md)
      * [Contract Related Methods](developers/api/methods/contract-related-methods/README.md)
        * [hmy\_estimateGas](developers/api/methods/contract-related-methods/hmy_estimategas.md)
        * [hmy\_getStorageAt](developers/api/methods/contract-related-methods/hmy_getstorageat.md)
        * [hmy\_call](developers/api/methods/contract-related-methods/hmy_call.md)
        * [hmy\_getCode](developers/api/methods/contract-related-methods/hmy_getcode.md)
      * [Protocol Related Methods](developers/api/methods/blockchain-related-methods/README.md)
        * [hmy\_isLastBlock](developers/api/methods/blockchain-related-methods/hmy_islastblock.md)
        * [hmy\_epochLastBlock](developers/api/methods/blockchain-related-methods/hmy_epochlastblock.md)
        * [hmy\_latestHeader](developers/api/methods/blockchain-related-methods/hmy_latestheader.md)
        * [hmy\_getShardingStructure](developers/api/methods/blockchain-related-methods/hmy_getshardingstructure.md)
        * [hmy\_blockNumber](developers/api/methods/blockchain-related-methods/hmy_blocknumber.md)
        * [hmy\_syncing](developers/api/methods/blockchain-related-methods/hmy_syncing.md)
        * [hmy\_gasPrice](developers/api/methods/blockchain-related-methods/hmy_gasprice.md)
        * [net\_peerCount](developers/api/methods/blockchain-related-methods/net_peercount.md)
        * [hmy\_getEpoch](developers/api/methods/blockchain-related-methods/hmy_getepoch.md)
        * [hmy\_getLeader](developers/api/methods/blockchain-related-methods/hmy_getleader.md)
      * [Staking Related Methods](developers/api/methods/staking-related-methods/README.md)
        * [hmy\_getCirculatingSupply](developers/api/methods/staking-related-methods/hmy_getcirculatingsupply.md)
        * [hmy\_getTotalSupply](developers/api/methods/staking-related-methods/hmy_gettotalsupply.md)
        * [hmy\_getStakingNetworkInfo](developers/api/methods/staking-related-methods/hmy_getstakingnetworkinfo.md)
        * [hmy\_getAllValidatorInformation](developers/api/methods/staking-related-methods/hmy_getallvalidatorinformation.md)
        * [hmy\_getCurrentUtilityMetrics](developers/api/methods/staking-related-methods/hmy_getcurrentutilitymetrics.md)
        * [hmy\_getDelegationsByValidator](developers/api/methods/staking-related-methods/hmy_getdelegationsbyvalidator.md)
        * [hmy\_getDelegationsByDelegatorAndValidator](developers/api/methods/staking-related-methods/hmy_getdelegationsbydelegatorandvalidator.md)
        * [hmy\_getDelegationsByDelegator](developers/api/methods/staking-related-methods/hmy_getdelegationsbydelegator.md)
        * [hmy\_getValidatorMetrics](developers/api/methods/staking-related-methods/hmy_getvalidatormetrics.md)
        * [hmy\_getMedianRawStakeSnapshot](developers/api/methods/staking-related-methods/hmy_getmedianrawstakesnapshot.md)
        * [hmy\_getActiveValidatorAddresses](developers/api/methods/staking-related-methods/hmy_getactivevalidatoraddresses.md)
        * [hmy\_getAllValidatorAddresses](developers/api/methods/staking-related-methods/hmy_getallvalidatorsaddresses.md)
        * [hmy\_getCurrentStakingErrorSink](developers/api/methods/staking-related-methods/hmy_getcurrentstakingerrorsink.md)
        * [hmy\_getValidatorInformation](developers/api/methods/staking-related-methods/hmy_getvalidatorinformation.md)
        * [hmy\_getValidators](developers/api/methods/staking-related-methods/hmy_getvalidators.md)
        * [hmy\_getSignedBlocks](developers/api/methods/staking-related-methods/hmy_getsignedblocks.md)
        * [hmy\_isBlockSigner](developers/api/methods/staking-related-methods/hmy_isblocksigner.md)
        * [hmy\_getBlockSigners](developers/api/methods/staking-related-methods/hmy_getblocksigners.md)
    * [Sample Code](developers/api/sample-code.md)
    * [Sample nodejs CLI Application](developers/api/sample-nodejs-cli-application.md)
  * [Smart Contracts](developers/smart-contracts/README.md)
    * [Deploying an Ethereum Smart Contract onto Harmony](developers/smart-contracts/deploying-an-ethereum-smart-contract-onto-harmony.md)
    * [Smart Contract Development using Truffle](developers/smart-contracts/smart-contract-development-using-truffle.md)
    * [Sample Files](developers/smart-contracts/sample-files.md)
  * [Grant Proposals](developers/grant-proposals.md)
  * [Block Explorers](developers/block-explorers.md)
  * [Faucets](developers/faucets.md)
* [Ecosystem](partners/README.md)
  * [Case Studies](partners/case-studies.md)
  * [Cross-Border Finance](partners/cross-border-finance.md)
  * [Partners](partners/ecosystem.md)
  * [Reference](partners/on-boarding-process.md)
  * [Onboarding](partners/onboard-process-walkthrough.md)
  * [Governance](partners/governance.md)
* [Showcases](showcases/README.md)
  * [Fiat](showcases/fiat.md)
  * [Apps](showcases/apps.md)
  * [Staking Wallets](showcases/staking-wallets.md)
  * [Mobile Wallets](showcases/mobile-wallets.md)
  * [Hardware Wallets](showcases/hardware-wallets.md)
  * [Exchanges](showcases/exchanges.md)
  * [DEX/Swaps](showcases/dex-swaps.md)
  * [Grants](showcases/grants.md)
  * [DeFi](showcases/defi/README.md)
    * [1EARN Demo App](showcases/defi/1earn-demo-app.md)
    * [Maker Demo steps](showcases/defi/maker-demo-steps.md)
* [Applications](demos.md)
* [Community/Angels](community-angels.md)

