# Abount keth
keth is a sidechain of ethereum for game players   

[block explorer](http://b.kexingqiu.net)  
[block chain game app download](https://krypton.world)




# How to sync with geth node
Assume your geth data is /data/geth/data
## Step 1 
Init geth with genesis.json  
./geth init genesis.json --datadir=/data/geth/data

## Step 2
copy static-nodes to /data/geth/data/


## Step 3 
start geth with networkdid 65536  
./geth --networkid=65536 --datadir=/data/geth/data




