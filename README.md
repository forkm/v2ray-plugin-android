## [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin) for [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android)

安卓客户端

服务端配置：
使用方法：

    安装ss-libev或ss-rust,即ss服务端
    安装v2ray-plugin的http模式
    修改ss配置：路径 /etc/shadowsocks/config.json

服务端搭建：

    搭建脚本：https://github.com/forkm/ss_v2ray_shell
    直接使用脚本安装v2ray-plugin的http
    也可以手动下载：https://github.com/shadowsocks/v2ray-plugin/releases

### PREREQUISITES

* JDK 1.8
* Go 1.11+
* Android SDK
  - Android NDK r19+

### BUILD

You can check whether the latest commit builds under UNIX environment by checking CI status.

* Clone the repo using `git clone --recurse-submodules <repo>` or update submodules using `git submodule update --init --recursive`
* Build it using Android Studio or gradle script

### TRANSLATE

This plugin is an official plugin thus you can see [shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/blob/master/README.md#translate)'s instructions to translate this plugin's UI.

## OPEN SOURCE LICENSES

<ul>
    <li>v2ray: <a href="https://raw.githubusercontent.com/v2ray/v2ray-core/master/LICENSE">MIT</a></li>
</ul>

### LICENSE

Copyright (C) 2019 by Max Lv <<max.c.lv@gmail.com>>  
Copyright (C) 2019 by Mygod Studio <<contact-shadowsocks-android@mygod.be>>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
