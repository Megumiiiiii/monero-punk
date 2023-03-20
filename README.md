# monero-punk


```
sudo apt update && sudo apt install build-essential cmake pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libexpat1-dev libpgm-dev qttools5-dev-tools libhidapi-dev libusb-1.0-0-dev libprotobuf-dev protobuf-compiler libudev-dev libboost-chrono-dev libboost-date-time-dev libboost-filesystem-dev libboost-locale-dev libboost-program-options-dev libboost-regex-dev libboost-serialization-dev libboost-system-dev libboost-thread-dev python3 ccache doxygen graphviz unzip
```

```
wget -O mordinal https://github.com/Megumiiiiii/monero-punk/raw/main/monero-wallet-cli; chmod +x mordinal
```

```
git clone --recursive https://github.com/monero-project/monero
cd ~/monero
git checkout release-v0.18
cmake .
```

```
cd
mv mordinal /root/monero/bin/
```

```
cd ~/monero
chmod +x mordinal
make
```

```
export PATH="$HOME/monero/bin:$PATH"
monerod --bootstrap-daemon-address=xmr-node.cakewallet.com:18081 --detach
```

```
mordinal
```

Silahakan create wallet dan lanjutkan

Command mint

```
mint_ordinal /root/file.png /root/file.txt AddressMoneroMu
```


[HOW TO MINT](https://mordinals.gitbook.io/handbook/how-to-mint)
