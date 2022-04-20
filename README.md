
准备在离线机子上用，主要就是脚本里有大量的请求问题需要处理

需要安装smartmontools(smartctl)

# I/O bench and system info



高级用法  
```
No IP                bash <(wget -qO- git.io/ceshi) -a
No IPIP              bash <(wget -qO- git.io/ceshi) -b
No IOtest            bash <(wget -qO- git.io/ceshi) -c
No IP, IPIP, IOTEST  bash <(wget -qO- git.io/ceshi) -abc
IOPS test            bash <(wget -qO- git.io/ceshi) -j
```

![00](https://github.com/Aniverse/A/raw/i/pictures/00.png)
![Seedbox-USB-SSD](https://github.com/Aniverse/A/raw/i/pictures/Seedbox-USB-SSD.png)
![Seedbox-SH-HDD](https://github.com/Aniverse/A/raw/i/pictures/Seedbox-SH-HDD.png)
![Seedbox-FH-HDD](https://github.com/Aniverse/A/raw/i/pictures/Seedbox-FH-HDD.png)
![Seedbox-FH-SSD](https://github.com/Aniverse/A/raw/i/pictures/Seedbox-FH-SSD.png)
![Seedbox-PM](https://github.com/Aniverse/A/raw/i/pictures/Seedbox-PM.png)
![Hetzner_HW_RAID](https://github.com/Aniverse/A/raw/i/pictures/Hetzner_HW_RAID.png)
![OP-10Euro](https://github.com/Aniverse/A/raw/i/pictures/OP-10Euro.png)
![Ikoula-20Euro-SSD](https://github.com/Aniverse/A/raw/i/pictures/Ikoula-20Euro-SSD.png)


# Troubleshooting

如果碰到 `-sh: syntax error near unexpected token ('` 的提示，先输入 `bash`，再执行脚本  
已知未解决的问题：某些软／硬 RAID 硬盘检测不到  


# 放弃&跑路说明
ZFS会多检测空间，并不会进行ZFS的IO测试