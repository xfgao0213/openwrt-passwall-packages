src-git passwall https://github.com/xiaorouji/openwrt-passwall-packages.git
./scripts/feeds update passwall
./scripts/feeds install -a -f -p passwall
