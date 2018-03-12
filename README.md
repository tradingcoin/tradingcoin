Omega coin is a powerful mode-based PoW + PoS-based cryptocurrency.

Block Spacing: 80 Seconds Stake Minimum Age: 8 Hours

Port: 7777 RPC Port: 7778


BUILD LINUX (https://github.com/tradingcoinnetwork/tradingcoin/blob/master/doc/build-unix.md)
--------------------

git clone https://github.com/tradingcoinnetwork/tradingcoin

cd tradingcoin

./autogen.sh

./configure

make

make install

strip tradingcoind

sudo cp tradingcoind /usr/local/bin
