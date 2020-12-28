## [OpenWrt](https://github.com/elarkasi/openwrt)

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/elarkasi/raspi-openwrt/blob/master/LICENSE)
    
### 前言

本项目基于[Lean's OpenWrt](https://github.com/coolsnowwolf/lede) 与 [P3TERX/Action-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

参考[SuLingGG/OpenWrt-Rpi-Docker](https://github.com/SuLingGG/OpenWrt-Rpi-Docker)
    
特此鸣谢!

### 说明
- 主要用于有线旁路由，每周日更新
- openwrt:rpi4 仅支持树莓派4 64位系统
- openwrt:x86_64 支持x86_64系统
- 精简组件，仅保留去广告插件adbyby-plus与科学看书插件ssr-plus
- 集成 [xiaoqingfengATGH/luci-theme-infinityfreedom](https://github.com/xiaoqingfengATGH/luci-theme-infinityfreedom) 皮肤

<img src="https://github.com/xiaoqingfengATGH/luci-theme-infinityfreedom/blob/master/screenshots/000.Login.jpg" alt="" width="400" height="247"><img src="https://github.com/xiaoqingfengATGH/luci-theme-infinityfreedom/blob/master/screenshots/001.Overview.jpg" alt="" width="400" height="247">

### 问题
- 启动时报warning，不影响使用，原因暂时未知
- 删除container时会引起树莓派重启，原因暂时未知
  
### 状态
![rpi4-openwrt autobuild action](https://github.com/elarkasi/raspi-openwrt/workflows/rpi4-openwrt%20autobuild%20action/badge.svg)

![x86_64-openwrt autobuild action](https://github.com/elarkasi/openwrt/workflows/x86_64-openwrt%20autobuild%20action/badge.svg)
