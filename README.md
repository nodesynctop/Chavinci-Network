# Chavinci-Network

Explorer: https://explorer.cha.network/

Guide dev: https://docs.cha.network/developer/node/manually-setup/

Twitter: https://twitter.com/ChavinciNetwork

Discord: https://discord.gg/zfJEzYEnVD

# Auto Install
```
sudo apt install curl -y && source <(curl -s https://raw.githubusercontent.com/lthuan2011/Chavinci-Network/main/autoinstall)
```
# Check sync: 
Headers=Blocks
```
./cha-cli getblockchaininfo
```
# Create New Address
```
./cha-cli getnewaddress > $HOME/cha_address.txt
```
# View and Backup Address 
```
cat $HOME/cha_address.txt
```
**You can now send CHA to this address, initiating the verification process and earning rewards for each validated block.**

Faucet on discord channel **#node-setup** and request (upload screen shot of your node and wallet address)

# Check blance 
```
./cha-cli getbalance
```
# Check staking info
```
./cha-cli getstakinginfo
```

# Backup Wallet (All in one)
Backup file **wallet.dat** to local PC (you can use Mobaxterm, WinSCP, Terminus)
```
/root/.chachain/testnet1/wallets/
```
# Delete node
```
cd $HOME
./cha-cli stop
rm -rf cha-cli
rm -rf chad
rm -rf .chachain
rm -rf chavinci-linux.zip
```
