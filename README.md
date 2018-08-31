# iOS逆向

## 准备工作

### 配置免登陆

```sh
ssh-keygen -t rsa -P ''
ssh-copy-id -i /Users/username/.ssh/id_rsa root@ip
```

### 安装 Fridav

* 电脑上 `pip3 install frida-tools`
* 手机上 添加源 `https://build.frida.re` 并安装 `Frida`
* sudo pip3 install -r requirements.txt --upgrade
* iproxy 2222 22
* ./dump -l
* ./dump.py Display name or Bundle identifier

### 安装 IDA Pro （失败）

```sh
sudo spctl --master-disable
```

## cydia 插件
[ssl-kill-](https://github.com/nabla-c0d3/ssl-kill-switch2) 用来解决 ssl 验证问题
