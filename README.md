```
     _                   ____
    / \   __  __ ___    / ___| ___   _ __  ___ 
   / _ \  \ \/ // _ \  | |    / _ \ | '__|/ _ \
  / ___ \  >  <| (_) | | |___| (_) || |  |  __/
 /_/   \_\/_/\_\\___/   \____|\___/ |_|   \___|
```
V1.0.0.0

Axo Core is the wallet used for the Axo cryptocurrency. It is used to store the coins that you can later spend using your Axo Card.


## Axo Specifications

| Specification | Value |
|:-----------|:-----------|
| Block time | `60 seconds` |
| PoS minimum age | `1 hour` |
| MN minimum age| `24 hours` |
| PoS rewards | `20% PoS / 80% MN`|
| Main port | `10314` |
| RPC port | `10318` |

## Social Channels

| Site | Link |
|:-----------|:-----------|
| Bitcointalk | https://bitcointalk.org/index.php?topic=5204369 |
| Discord | https://discord.gg/W3UM8VF |
| Website | http://axocard.io |



BUILD ON LINUX
-----------
Install the dependencies required to build Axo Core:
```
sudo apt-get install build-essential libssl-dev libboost-all-dev libqrencode-dev pkg-config libminiupnpc-dev qt5-default qttools5-dev-tools libgmp3-dev autoconf automake libtool

sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev
```
Execute the following commands in the Terminal to install Axo Core:
1. `git clone https://github.com/axoteam/AxoCore`

2. `cd `AxoCore`

3. To compile the headless daemon (axod), enter the following:
    * `./autogen.sh`

    * `./configure`

    * `make`

The resulting commandline binaries will be:
    * `src/axod'

    * `src/axo-cli`

    * `src/axo-tx`

The resulting graphical (Qt) binaires will be:
    * `src/qt/axo-qt`

For more information please visit the website:

http://axocard.io
