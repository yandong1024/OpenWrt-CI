# OpenWrt-CI

- 基于原版 OpenWrt
- 集成 OpenClash
- 集成简体中文

**配置详情：**

```
Target System > x86

Subtarget > x86_64

Target Images > squashes
Target Images > Build GRUB EFI…
Target Images > Use Console Terminal
Target Images > Gzip images
Target Images > Kernel size 64
Target Images > Root size 512

LuCI > Collections > Luci
LuCI > Moudles > Translations - Chinese
LuCI > Modules > luci-compat
LuCI > Applications > luci-app-openclash

Base System - dnsmasq（取消勾选）

Network > Files Transfer > wget-ssl 
Network > Files Transfer > wget-nossl 
```
