```
docker run --rm --name eosio -d eosio/eos-dev /bin/bash -c "nodeos -e -p eosio --plugin eosio::wallet_api_plugin --plugin eosio::wallet_plugin --plugin eosio::producer_plugin --plugin eosio::history_plugin --plugin eosio::chain_api_plugin --plugin eosio::history_api_plugin --plugin eosio::http_plugin -d /mnt/dev/data --config-dir /mnt/dev/config --http-server-address=0.0.0.0:8888 --access-control-allow-origin=* --contracts-console"
crappy

https://worthdoingbadly.com/xnuqemu/

Get decrypted kernelcache

URL for iOS 10 Beta 1 for iPhone 6s taken from http://pastebin.com/FRMfanmT

wget -q http://apple.co/28R9rhS -O ios10beta1-iphone6s.zip

mkdir ios10beta1

unzip -q ios10beta1-iphone6s.zip -d ios10beta1

cd ios10beta1

wget -q http://nah6.com/%7Eitsme/cvs-xdadevtools/iphone/tools/lzssdec.cpp

g++ -o lzssdec lzssdec.cpp

./lzssdec -o 439 < AssetData/boot/kernelcache.release.n71 >kernelcache.decrypted # 439 is offset byte count to 0xFFCFFAEDFE header

xxd kernelcache.decrypted | head -1

file kernelcache.decrypted
```
