## rpm-python3
https://www.python.org/downloads/

Generate RPM packages based on the official version


## python version introduction
```
Python 3.6 ~ 3.9 版本: 与 OpenSSL 1.0.2、1.1.0 和 1.1.1 兼容;
Python 3.10 版本: 仅支持 OpenSSL 1.1.1 LTS 或更高版本
```

## System support list:
------------------------------
centos 7.9  

rocky  9.x


## install:
``` 
yum install <rpm package file>
# Example
yum install ./Python-3.9.18-1.el9.x86_64.rpm

# 升级安装
rpm -Uvh --replacefiles --replacepkgs ./Python-3.9.18-1.el9.x86_64.rpm
# 降级安装
rpm -Uvh --replacefiles --replacepkgs --oldpackage ./Python-3.9.18-1.el9.x86_64.rpm

```
