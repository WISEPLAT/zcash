# zcash download
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
+ zcash 5.7.0

    As files have big size, additionally I have published them here:
    
    zcash-linux-amd64-v5.7.0.tar.gz - https://disk.yandex.ru/d/PsRyLWUYMdx1OQ
    
    and 
    
    zcash-windows-v5.7.0.zip - https://disk.yandex.ru/d/E3UK-khaWwGKNg

    and 
  
    file by file archive are available in folders

For Windows:
```
   Directory of ..\zcash\zcashd-5.7.0\zcash-windows-v5.7.0

06.11.2023  18:36    <DIR>          .
06.11.2023  18:48    <DIR>          ..
06.11.2023  17:10               246 sha256sum.txt
06.11.2023  17:10        63 320 576 zcash-cli.exe
06.11.2023  17:22        56 396 092 zcash-cli.zip
06.11.2023  17:10         5 317 102 zcashd-wallet-tool.exe
06.11.2023  17:22         1 593 104 zcashd-wallet-tool.zip
06.11.2023  17:10        72 003 072 zcashd.exe
06.11.2023  17:22        59 814 510 zcashd.zip
               7 File(s)    258 444 702 bytes
```

For Linux:
```
 Directory of ..\zcash\zcashd-5.7.0\zcash-linux-amd64-v5.7.0

07.11.2023  06:51    <DIR>          .
06.11.2023  18:48    <DIR>          ..
06.11.2023  17:25               234 sha256sum.txt
06.11.2023  16:12        64 504 216 zcash-cli
06.11.2023  17:25        64 512 000 zcash-cli-v5.7.0.tar
06.11.2023  16:12        73 130 392 zcashd
06.11.2023  17:25        73 134 080 zcashd-v5.7.0.tar
06.11.2023  16:12         5 110 992 zcashd-wallet-tool
06.11.2023  17:25         5 120 000 zcashd-wallet-tool-v5.7.0.tar
               7 File(s)    285 511 914 bytes
```

U can write me to Telegram: https://t.me/OlegSh777

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

---

Do you want an updated compiled file for Zcashd? Or you want just say - Thanks)))

Just donate here:

ETH(ERC20) 0xfd546640c911ba90d1409a4fbbb4322ae73e7814

or

BTC 1ENhx1HUMJZjGAfYaT1vfsqwKHgVkqwX1D

or

USDT(TRC20) TEHaXZX7KLjAm4eLWdf4VKfsqRUQpv8fTT

Thank you!
