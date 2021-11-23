# Genesis Pillar Migration tutorial

## Step 1

Open a ssh connection to the machine where the Genesis Pillar is deployed.

Download the `znn-alphanet-bundle-linux-amd64.zip` and unzip it:

```
wget https://github.com/zenon-network/znn-bundle/releases/download/v0.0.1-alphanet/znn-alphanet-bundle-linux-amd64.zip
```
```
unzip znn-alphanet-bundle-linux-amd64.zip
```

## Step 2

Run `./znn-controller` and select option `1) Migrate`

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

- Run `./znn-controller` and select option `2) Deploy`
- If you don't have enough resources on the machine, a prompt is displayed. Type `Y` (Yes) in order to proceed with the deployment.
- `Producer configuration detected. Continue using the existing configuration?`. Type `Y` (Yes).
- Check the downloaded znnd node version: `znnd version v0.0.1`

## Step 4

Wait a couple of minutes, run `./znn-controller` again and select option `3) Status`. `znnd` should output `Initialized NoM. Height 1` and the `Pillar detected` message.

## Step 5

Keep the Genesis Pillar up and running for the Alphanet Big Bang.
