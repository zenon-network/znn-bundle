# Full Node deployment tutorial

## Step 1

Download the `znn-alphanet-bundle-windows-amd64.zip` and unzip it:

```
https://github.com/zenon-network/znn-bundle/releases/download/v0.0.1-alphanet/znn-alphanet-bundle-windows-amd64.zip
```

## Step 2

Double click `znn-controller.exe` and select option `1) Migrate`

The required genesis and peers files can be downloaded from a decentralized peer-to-peer network, the Interplanetary File System.

- URL to download the initial peers: 
```
https://ipfs.io/ipfs/QmeAUQkpoEMNRQ9SFcBV2kmRTXT3WLKAoMxvAtX2ErZubJ?filename=peers.json
```
- URL to download the Alphanet genesis: 
```
https://ipfs.io/ipfs/QmVFyGWNt3Ph2mn9MoxZyTgjuMGSs2cDdqXP3B8Ri5AYY5?filename=genesis.json
```

## Step 3

- Double click `znnd.exe` and leave it running.

## Step 4

Wait until the Full Node is fully synced with the network.

## Step 5

Open syrius, navigate to Settings, go to the Node Management widget and connect to the local node `ws://127.0.0.1:35998`
