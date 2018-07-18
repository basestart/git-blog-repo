---
title: 使用sinopia在vps上搭建私人npm仓库
date: 2018-07-15 19:15:31
tags: ['sinopia', '私有npm', 'vps']
---


在实际业务开发中， 希望团队之间共享代码， 同时又想保密， 选择搭建私有npm仓库是一个不错的选择

需要用到的工具包：

- sinopia
- nrm
- pm2

## vsp服务端

- 全局安装sinopia

```
    npm install pm2 -g sinopia
```

- 运行sinopia指令

```
    sinopia
    //此时会在当前目录下生成./config配置文件夹, 
```

- 在.configsinopia/config.yaml配置sinopia的监听端口

```
    listen: 0.0.0.0:4873 //监听4873端口 如果没有listen字段， 则添加
```

- 后台启动sinopia

```
    pm2 start sinopia 
```

然后通过http://{vps ip}:4873 就可以访问sinopia搭建的私有npm仓库了

## 客户端

- 安装nrm

```
    npm install -g nrm // 切换npm源
```

- 添加nrm源， 指向私有npm

```
    nrm add {name} {http://ip:port/}

    nrm use {name}
```

- 添加用户

```
    npm adduser --registry {http://ip:port/}
```

- 发布npm包

```
    // 本地创建npm包之后发布到仓库[如果有更新， 需要变动版本号]
    npm publish
```

## 如何使用私有npm包

`先切换nrm源`到自己制定的npm指令名， 然后如正常使用其他包一样安装和使用即可

比如创建了一个hello的包， 安装时直接 `npm install hello` 即可， 

