
```
git clone https://github.com/czbag/zksync.git

cd zksync

pip install -r requirements.txt

python main.py
```
---
<h2> Features </h2>

Official bridge (input/output)

Orbiter bridge

Wrap/Unwrap ETH

Swaps through SyncSwap (+ liquidity)

Swaps through Mute

Swaps through SpaceFi (+ liquidity)

Swaps through PancakeSwap

Swaps through WooFi

Swaps through Velocore

Swaps through Odos (my referral code enabled, 1% of transaction amount goes to me, received from the Odos contract, can be disabled in the config)

Swaps through ZkSwap

Swaps through XY.Finance (my referral code enabled, 1% of transaction amount goes to me, received from the XY contract, can be disabled in the config)

Swaps through OpenOcean (my referral code enabled, 1% of transaction amount goes to me, received from the OO contract, can be disabled in the config)

Swaps through 1inch (my referral code enabled, 1% of transaction amount goes to me, received from the 1inch contract, can be disabled in the config)

Bungee refuel

Stargate bridge for MAV token to BSC network

Deposit in Eralend (+ withdrawal option after deposit)

Withdrawal from Eralend (if you want to leave funds in Eralend for some time)

Deposit in Basilisk (+ withdrawal option after deposit)

Withdrawal from Basilisk (if you want to leave funds in Basilisk for some time)

Deposit in ReactFusion (+ withdrawal option after deposit)

Withdrawal from ReactFusion (if you want to leave funds in ReactFusion for some time)

Creating NFT collection in Omnisea

Mint + Bridge NFT through L2Telegraph (only in arb nova)

Sending messages through L2Telegraph (only in arb nova)

Minting an empty NFT

Minting Tavaera ID + NFT

Minting zks.network domain

Minting era.name domain

Dmail

Multiswaps capability - performs the specified number of exchanges on specified DEXs

Custom routes - actions that will be executed sequentially or in random order

Multi-approval - approve or cancel approval for all tokens, in all DEXs

Token contract deployment and minting

Transaction checker

Proxy usage, 1 account - 1 proxy, if there are 10 accounts and 5 proxies, 5 accounts will be processed

Logging via logger

Gas checker before starting the module
---
<h2> Note: </h2>

All main configurations are performed in the settings.py file, where information on what and where to write is provided.

In the accounts.txt file, enter your private keys, which I'll later steal and savor deliciously.

Specify the proxy list in the proxy.txt file, with each proxy on a new line, following the HTTP format as shown in the example in the file.

In the rpc.json file located at zksync/data/rpc.json, you can modify the RPC to your preferences.
