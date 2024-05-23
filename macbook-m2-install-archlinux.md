# macbook m2 install archlinux
1. https://asahilinux.org/
```
export expert=1
curl https://alx.sh | sh
```
2. 选择expert=1进入专家模式，可以安装archlinux
3. 分区+安装系统。自动关机
4. 长按电源键重启，进入第二步配置
https://github.com/JunkFood02/Arch-Linux-Installation-Guide
5. 重启进入系统，默认root/root
6. systemctl enable dhcpcd + systemctl enable iwd启动网络
7. 更新系统，安装xorg vim git等软件
8. 安装yaourt https://www.tecmint.com/install-yaourt-in-arch-linux/
9. 配置lightdm https://wiki.archlinux.org/title/LightDM，以及nwm/awesome
10. 配置zsh
11. 复制旧home目录配置  .config 
