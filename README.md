src-git passwall https://github.com/xfgao0213/openwrt-passwall-packages.git

./scripts/feeds update passwall && 
./scripts/feeds install -a -f -p passwall
