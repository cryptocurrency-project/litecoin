## Litecoin Core
[litecoin core](https://download.litecoin.org/litecoin-0.17.1/linux/)

## Litecoin Formula
[litecoin-project/litecoin](https://github.com/litecoin-project/litecoin)

## Litecoin API
[Litecoin CLI API](https://www.kompulsa.com/litecoin-cli-commands/)

## Litecoin Explorer
[cryptoid ltc](https://chainz.cryptoid.info/ltc/)  
[blockcypher ltc](https://live.blockcypher.com/ltc/)

## Build method
docker build --build-arg LITECOIN_VERSION=0.17.1 --build-arg GOSU_VERSION=1.11 -t ltc-core:v0.17.1 -f Dockerfile .
