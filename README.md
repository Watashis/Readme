# Readme
## Настройка общего доступа в VMWare
1. Добавить папки

[![Alt text](https://i.imgur.com/0FpLrV9.png)](http://example.com/)

2. Выполнить в терминале следующие команды:
```bash
$ sudo apt-get update
$ sudo apt-get install git fuse
$ git clone https://github.com/rasa/vmware-tools-patches.git
$ cd vmware-tools-patches
$ sudo ./patched-open-vm-tools.sh
$ cd vmware-tools-patches (you see user@debian:~/vmware-tools-patches/vmware-tools-patches$)
$ cd vmware-tools-distrib
$ sudo ./vmware-install.pl
```
[Спасибо](https://askubuntu.com/questions/762755/no-vmhgfs-file-system-installed-to-use-use-shared-folder "askubuntu")
