# Deployment with UDC using Protostar 

* Replace your wallet address in the protostar.toml file
* Create a .env file and paste your private key

### Build the project
```
protostar build
```

### Deploy testnet

```
protostar -p testnet declare ./build/main.json --max-fee auto

protostar -p testnet deploy replaceClassHash --max-fee auto
```

### Deploy testnet2

```
protostar -p testnet2 declare ./build/main.json --max-fee auto

protostar -p testnet2 deploy replaceClassHash --max-fee auto
```

[Tutorial](https://medium.com/@dpinoness/deployando-un-contrato-con-udc-utilizando-protostar-44d08692aca4)