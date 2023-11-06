# zcash
---
If you have time, please see [backtrader_binance](https://github.com/WISEPLAT/backtrader_binance) library wich one is helping to create crypto trading robots.

[Backtrader_binance](https://github.com/WISEPLAT/backtrader_binance) library create Binance API integration with [Backtrader](https://github.com/WISEPLAT/backtrader).

With this integration you can do:
 - Backtesting your strategy on historical data from the exchange [Binance](https://www.binance.com/?ref=CPA_004RZBKQWK ) + [Backtrader](https://github.com/WISEPLAT/backtrader )  // Backtesting 
 - Launch trading systems for automatic trading on the exchange [Binance](https://www.binance.com/?ref=CPA_004RZBKQWK) + [Backtrader](https://github.com/WISEPLAT/backtrader ) // Live trading
 - Download historical data for cryptocurrencies from the exchange [Binance](https://www.binance.com/?ref=CPA_004RZBKQWK)
---

zcashd

Just compiled zcash daemon versions for windows and linux

+ zcash 5.5.1
+ zcash 5.6.0

How to create them:

install vm ubuntu 20.04

```
sudo apt install openssh-server

wget https://github.com/adityapk00/zcash/archive/refs/tags/v5.4.2.zip
sudo apt install unzip
unzip v5.4.2.zip
cd zcash-5.4.2/

./buildall.sh --version v5.5.1

sudo apt install docker.io 
sudo apt install docker-compose

https://stackoverflow.com/questions/48957195/how-to-fix-docker-got-permission-denied-issue
sudo groupadd docker
sudo usermod -aG docker admin2
newgrp docker

admin2@ubunt2004:~/zcash-5.4.2$ newgrp docker
admin2@ubunt2004:~/zcash-5.4.2$ ./buildall.sh --version v5.5.1

```
