# monero-punk


```
sudo apt update && sudo apt install build-essential cmake pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libexpat1-dev libpgm-dev qttools5-dev-tools libhidapi-dev libusb-1.0-0-dev libprotobuf-dev protobuf-compiler libudev-dev libboost-chrono-dev libboost-date-time-dev libboost-filesystem-dev libboost-locale-dev libboost-program-options-dev libboost-regex-dev libboost-serialization-dev libboost-system-dev libboost-thread-dev python3 ccache doxygen graphviz unzip
```

```
git clone --recursive https://github.com/mooonero/mordinals
```

```
cd mordinals
make cmake-release
cd build/Linux/master/release
make simplewallet daemon
```

```
export PATH="$PATH:$HOME/mordinals/build/Linux/master/release/bin"
monerod --log-file monerod.log --bootstrap-daemon-address=xmr-node.cakewallet.com:18081 --detach
```

```
monero-wallet-cli
```

Silahakan create wallet dan lanjutkan

Command mint



[HOW TO](https://mordinals.gitbook.io/handbook/wallet-commands)
