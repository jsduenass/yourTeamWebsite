---
title: "Raspbery pi"
date: 2022-04-6
description: working with the Raspbery Pi  
menu:
  sidebar:
    name: "Raspbery pi"
    identifier: raspi
    parent: programming
    weight: 4
---

Getting started with a raspberry pi

## Configuration

There are many ways of configuring network interfaces via modifying configuration files .  

```
sudo raspi-config
```

```bash
sudo nano /etc/dhcpcd.conf
```

```
service networking reload
service networking restart
```


## Find Raspbery PI

```
hostname
whoami    #username

```


```
ping <hostname>.local -4

ssh <username>.<hostname>

sudo ifconfig eth0 up

sudo matlab-rpi-setup

```

<!--
      ```
      ping jsds.local -4
      ```
-->



### Configure SSH

Multiple private keys can be added using ```ssh-add``. However for this to work the _ssh-agent_ must be activated. To check if it activated Open power shell  and get information about the service if it is stoped, ```ssh-add`` won't work. Configure the service as manual so it will be activated  via ```ssh-agent```. With the agent running locate the file path of the private key you want to add and pass is a ```ssh-add``` if lJ  . 

```Powershell
Get-Service -Name ssh-agent

Get-Service -Name ssh-agent | Set-Service -StartupType Manual
ssh-agent
ssh-add [private-key-path]

```

[multiple ssh keys](https://coderwall.com/p/7smjkq/multiple-ssh-keys-for-different-accounts-on-github-or-gitlab)
## Proxy

```
sudo nano /etc/environment
```
[](

)

## git configure
```
git config --global core.editor "code --wait"
```

## Reference

[^gitee-tcpip]: probando 

[tcp ip configuration](https://gitee.com/jikexianfeng/documentation/blob/master/configuration/tcpip/README.md) 

[^proxy-config]: 
[proxy](https://theailearner.com/2018/03/13/connecting-raspberry-pi-to-proxy-server/)


