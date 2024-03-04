# Chavinci-Network
https://explorer.cha.network/

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
# Backup Wallet (All in one)
Backup file ** wallet.dat**
```
cd $HOME/.chachain/testnet1/wallets/
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
