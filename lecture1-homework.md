# 第1课 课后作业

## 第1题

不再是零知识，零知识证明包含正确性和完备性、零知识性三种特性。

因为如果可以任意选择，那么它实际无法保证零知识证明的正确性，即相邻两节点必定不同色的情况。

## zkmessage.xyz

解释为什么你需要生成并保存一个“秘密值” ： 秘密值即非对称加密的私钥值，能够计算得对应的公钥及数据签名信息

用白话写出 ZK 中正在证明的陈述：这条massage属于这个用户集合里面的某一个人所发，但是无法确认到底由谁创建发送

从不同的浏览器或计算机登录到相同的 zkmessage 帐户。 解释为什么 zkmessage 不能像大多数社交应用程序一样，只使用简单的“用户名/密码” ：

这是一种更加web3的方式，即分布式的数字身份：用户将自己的公私钥保存在本地，只通过私钥验签来确认自己的身份确实属于自己，但不向中心化服务器泄漏自己的私钥数据，这样能够保证自己账户的安全性，同时这样也能保证，即使有恶意第三方登录了zkmessage的中心化服务器，他也无法使用用户的私钥来伪造信息
