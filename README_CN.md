# myip

一键查看本机/外网IP的控制台命令

## 安装/使用

要求: Node.js 6+, npm 3+

``` sh
$ npm install -g myip-cli
$ myip

# 或者直接
$ npx myip-cli
```

你可以看到如下输出信息

``` js
internal: { en0: 'x.x.x.x', vnic0: 'x.x.x.x' }
external: { ip: 'x.x.x.x', region: 'region information' }
```

> internal 是本机IP信息，如果有多网卡(或者虚拟机的情况)可以看到多个IP地址。  
> external 是外网IP信息，信息来至搜狐接口。  
