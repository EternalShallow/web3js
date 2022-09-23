# web3.js简介与入门
[官方文档](https://web3js.readthedocs.io/en/v1.7.4/getting-started.html)
1. web3.js 是一个JavaScript api库，主要用于开发基于ETH链及基于Go Ethereum（Geth）协议的硬分叉的公链等（比如说bsc、heco）
2. web3.js通过初始化rpc建立节点与本地之间的通信关系,它可以用于任何暴露了RPC层的以太坊节点(可以申请[infura测试节点](https://infura.io/)  教程的网上有人多，[传送门](https://www.cnblogs.com/wanghui-garcia/p/9719399.html)）
3. web3.js 包含了五大模块 
    1. web3.eth   与以太坊区块链和以太坊智能合约进行交互 （初始化智能合约需要用到）
    2. web3-net   与以太坊节点的网络属性进行交互
    3. web3-bzz   与去中心化文件存储 swarm 进行交互
    4. web3-shh   与用于广播的耳语协议进行交互
    5. web3.utils 以太坊 dapps 和其他 web3.js 包提供实用功能（用的最多）
# 安装浏览器插件小狐狸
## 介绍
MetaMask是一款嵌入在浏览器里的钱包扩展应用。它可以帮助您与去中心化应用程序（dApps）进行交互。MetaMask可以非常方便的接入以太坊或Ropsten测试测试网络。
[小狐狸官方文档](https://docs.metamask.io/guide/)
## 安装步骤
1. 安装小狐狸插进[MetaMask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=zh-CN)
2. 点击启用 设置登录密码

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/92dcd29a6bd94aa997caaf6b3839a464~tplv-k3u1fbpfcp-watermark.image?)
-   安装好之后，点击MetaMask的小狐狸图标打开扩展程序。
-   创建一个新的账户。
-   您将会看到由12个单词组成的助记词，拷贝这12个助记词到一个只有你自己知道的安全的地方。
-   将网络从`以太坊主网络（Main Ethereum Network）`切换到`Ropsten测试网络（Ropsten Test Network）`。
## 向您的地址转入以太币
### 您可以通过以下步骤获取到测试网络的Gas代币（主流测试网手续费代币）：
[测试网水龙头测试币获取](https://juejin.cn/post/7125708269007405063/)
-   在文本框中粘贴您的地址
-   点击“Send me test Ether（给我打钱）”按钮
-   回到MetaMask扩展确认是否到账。

现在你就有了可以使用的ETH啦~
**<p align=center>初始准备工作就是这么多的，下篇文章我们就开始介绍web3.js 链接小狐狸钱包以及一些简单操作</p>**