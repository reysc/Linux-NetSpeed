# Linux-NetSpeed
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```

安装命令
  wget "https://github.com/chiakge/Linux-NetSpeed/raw/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

说明：
1. 先在[1 - 3]切换内核（第一次显示为bbr内核也要切换一遍），重启
出现这个https://s1.ax1x.com/2018/12/24/F6xwqI.png
选no

2. 重启后不用再下载脚本，直接 ./tcp.sh ，在[4 - 8]中选你要开的加速
"1. 安装 BBR/BBR魔改版内核"        对应4,5,6（原版，魔改，暴力魔改）
"2. 安装 BBRplus版内核 "                对应7（plus）
"3. 安装 Lotserver(锐速)内核"        对应8（锐速）

3. 开启后再 ./tcp.sh  ， 显示开启成功则启动成功，你也可以自己手动确认
