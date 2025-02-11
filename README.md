# XrayR-alpine
原版：感谢<a href="https://github.com/mingge9527">mingge9527</a>大佬  
适用于Alpine系统的XrayR-v0.9.0一键脚本  
安装目录位于/etc/XrayR

# 修改调整
- 部分Alpine无法很好的适配最新版XrayR，因此固定下载安装v0.9.0版本的XrayR  
- 去除自动生成XrayR配置，请安装后直接修改config.yml文件

# 使用方法
一键脚本
```shell script
wget -O /usr/bin/xrayr https://raw.githubusercontent.com/ryyyzer/XrayR-alpine/refs/heads/main/xrayr.sh
```
设置权限
```shell script
chmod 777 /usr/bin/xrayr
```
启动脚本
```shell script
xrayr
```
