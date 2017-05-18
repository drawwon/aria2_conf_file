# aria2_conf_file
这是Pandora_box的aria2下载器的配置文件

内存交换的命令
```
dd if=/dev/zero of=/mnt/sda1/swapfile bs=1024 count=62142
mkswap /mnt/sda1/swapfile
swapon /mnt/sda1/swapfile
```

还要在rc.local里面添加
`swapon /mnt/sda1/swapfile`
