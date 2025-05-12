# Ubuntu-Software
Ubuntu系统常用软件

## 一、Firefox

### 1. 卸载预装的Firefox

```bash
sudo apt purge firefox firefox-locale-en -y
sudo apt autoremove -y
```

Ubuntu系统预装的Firefox版本较老，可能不支持一些自定义操作。

### 2. 安装Firefox

Firefox团队维护了一个官方PPA，提供最新稳定版下载安装：

```bash
sudo add-apt-repository ppa:mozillateam/ppa -y
sudo apt update
sudo apt install firefox -y
```

### 3. 插件记录

Tabliss
