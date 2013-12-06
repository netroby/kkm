kkm
===

Debian apt tools wrapper

If you are using debian, you may hate apt-get and apt-cache command.

Want search package? use apt-cache search

Want install package? use apt-get install packagename

Want upgrade system ? use apt-get update && apt-get dist-upgrade

Want show info of package? use apt-cache show packagename

Want list package that installed in system ? use dpkg --list | grep packagename

Can we make things easier?

yes we can.

Install
---------
```
mkdir /opt
cd /opt && git clone https://github.com/netroby/kkm.git && ln -s /opt/kkm/kkm /usr/sbin/kkm && chmod a+x /usr/sbin/kkm
```
Usage
---------
```
kkm clean		#clean and remove unused packages
kkm search  packagename		#search packages
kkm show  packagename		#display information of  packages
kkm update		#update package database
kkm upgrade		#upgrade all installed package
kkm install		#packagename	install packages
kkm list		#list installed packages
```

