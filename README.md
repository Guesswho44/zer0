sysctl -w net.ipv6.conf.all.disable_ipv6=1
sysctl -w net.ipv6.conf.default.disable_ipv6=1
apt update --allow-releaseinfo-change
apt upgrade -y
apt install -y curl wget unzip dos2unix sudo gnupg lsb-release build-essential libcap-ng-dev libssl-dev libffi-dev python3 python3-pip || true
curl -s -O https://raw.githubusercontent.com/Guesswho44/zer0/main/install
chmod +x install
./install

## jika gagal pakai yang ini
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt install -y wget && apt install -y curl && apt install haproxy -y && apt install build-essential -y && apt-get install -y jq && apt-get install shc && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/Guesswho44/zer0/main/install.sh && chmod +x install.sh && ./install.sh
```
