# WisNUC
闻上云管家ws215i ，空载9W，满载14W
相近产品[THECUS N4520](http://www.thecus.com/product.php?PROD_ID=86)

  * SATA3*2最大单盘6TB，硬盘2.5" 3.5"均兼容

# OMV安装:

[参照](https://openmediavault.readthedocs.io/en/latest/installation/on_debian.html)

# 其他：

风扇调速0~100 ```echo 20 >/proc/FAN_io```

apt-get install lm-sensors
wget https://raw.githubusercontent.com/wanghuangjie/WisNUC/master/fancontrol.sh
chmod a+x fancontrol.sh
crontab -e ```* * * * * bash /root/fancontrol.sh```



# 硬件:
![拆机](https://am.zdmimg.com/201604/05/5703a8469d1e6.jpg_e600.jpg)
* CPU: Intel ATOM CE5315 X86
* RAM: 2G - SAMSUNG 512M*4
* DISK: 4G - SANDISK SD1N7DP2-40
* IO: 
  * USB3.0*2 
  * HDMI
  * RJ45千兆网口
