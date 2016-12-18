# V2Ray 安装脚本

**注意：如果你使用的了官方的脚本安装 V2Ray，那么使用本脚本之前请先备份你的配置文件并且执行 `./v2ray-installation-script.sh -r` 将原来的 V2Ray 卸载。**
本脚本修改自 V2Ray [官方的安装脚本](https://github.com/v2ray/v2ray-core/blob/master/release/install-release.sh)，有以下特点：
* 添加卸载功能
* 对于使用 systemd 的系统，增大 ulimit 数值
* 简化选项， `--version`和 `-local`可用 `v`和 `-f` 替代
* 修改安装路径。官方脚本将 V2Ray 安装到 /usr/bin/v2ray/v2ray，本脚本将之安装到 /usr/bin/v2ray，可不必输入完整路径执行 V2Ray
