OpenWrt 24.10 loongarch64_generic repository for vlmcsd
========

Binaries built from this repository on 2025-01-06 can be downloaded from <https://dwfreed.github.io/openwrt-vlmcsd/>.

To install the vlmcsd package, run

```
echo "src/gz openwrt-vlmcsd https://dwfreed.github.io/openwrt-vlmcsd/OpenWrt_24.10/loongarch64_generic/base" >> /etc/opkg/customfeeds.conf
opkg update
opkg install vlmcsd
```
