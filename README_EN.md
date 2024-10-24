# Moonveil Buy Nodes

Moonveil Buy Nodes is an automated python tool designed to automatically buy Moonveil nodes according to user-defined specifications. The tool allows users to specify the desired node type and quantity to purchase, and automatically applies a 10% discount, which Moonveil will provide two weeks after purchase.

Project information: https://t.me/blacktaraxacum/2689

## Features
- Automatic purchase of Moonveil nodes according to specified characteristics (range and quantity).
- Application of automatic 10% discount.
- Easy to set up and use.
- If you have your own Arbitrum node, replace the value “NODE_RPC” in the cfg.py file
- It is possible and even desirable to run the code in advance. It will check if your wallets have enough $USDC and make uprules for node seel contracts

## Settings
[**How to run the code without installing it on your pc**](https://teletype.in/@eazer/how_to_start_code_in_chrome)

- Python 3.10

```
git clone https://github.com/Eazer1/moonveil_buy_nodes
```
```
cd moonveil_buy_nodes
```
```
pip install -r requirements.txt
```

Loading in wallets.txt wallets in the format prkey;tier;amount where:
- prkey - The private key of your wallet
- tier - Tier of the node you plan to buy
- amount - Number of nodes you plan to buy

It is possible to upload more than 1 wallet line by line
example:
```
0x0000000000000000000000000000000000000;1;1
0x0000000000000000000000000000000000001;4;3
0x0000000000000000000000000000000000002;12;10
```

## Note

#### Note that:

- You need to have the token $USDC on your wallet, not $ETH or $wETH
- The code automatically makes $USDC to the address to buy nodes (not more than you planned to buy), so don't be scared.

- The code was created by the admin of https://t.me/Eazercrypto channel.
