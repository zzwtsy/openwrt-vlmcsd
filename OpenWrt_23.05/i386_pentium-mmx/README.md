OpenWrt 23.05 i386_pentium-mmx repository for vlmcsd
========

Binaries built from this repository on 2025-03-04 can be downloaded from <https://zzwtsy.github.io/openwrt-vlmcsd/>.

To install the vlmcsd package, run

```
echo "src/gz openwrt-vlmcsd https://zzwtsy.github.io/openwrt-vlmcsd/OpenWrt_23.05/i386_pentium-mmx/base" >> /etc/opkg/customfeeds.conf
opkg update
opkg install vlmcsd
```
