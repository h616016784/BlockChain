# 一、fabric开发者模式
主要参考地址[Hyperledger Fabric:最简单的方式测试你的链码](https://www.cnblogs.com/cbkj-xd/p/11940323.html)

其次也可以参考[Fabric2.0 使用开发模式(dev 模式)测试](https://blog.csdn.net/weixin_43839871/article/details/107002767)

# 二、生产部署参考
参考地址[Hyperledger Fabric 2.0 手动生成CA证书(TLS)搭建Fabric网络-Raft协议](https://segmentfault.com/a/1190000023337696)

参考地址[Hyperledger Fabric手动生成CA证书搭建Fabric网络](https://www.cnblogs.com/cbkj-xd/p/12006275.html)

主要是参考以上两个方法综合起来配置的。


# 三、学习网站收集
参考地址[开发模式下的测试：简化我们对链码的测试过程](https://www.chaindesk.cn/witbook/11/119)

java链码的实例教程参考：
参考地址[github教程](https://github.com/hooj0/fabric-chaincode-java)

参考地址[使用Java开发Fabric智能合约Chaincode](https://blog.csdn.net/DamonREN/article/details/105554491)

参考地址[fabric单机部署](https://www.cnblogs.com/llongst/p/9571321.html)

# 四、数据防篡改

关于数据备份与恢复：peer在加入channel的时候，会自动同步其他peer点上的数据，所以fabric不用备份数据，如果为了保险备份，则可以进行手动备份。

数据的备份与恢复参考地址[Hyperledger Fabric的容灾备份及恢复方法简介](https://www.jianshu.com/p/455b8f8dd2e7);
[Hyperledger Fabric: Ledger Backup and Restore](http://www.bchainledger.com/2019/02/hyperledger-fabric-ledger-backup-and.html)

参考地址[当人们可以直接更改couchdb数据时，Hyperledger Fabric中的数据如何安全](https://stackoom.com/question/3NWC8/%E5%BD%93%E4%BA%BA%E4%BB%AC%E5%8F%AF%E4%BB%A5%E7%9B%B4%E6%8E%A5%E6%9B%B4%E6%94%B9couchdb%E6%95%B0%E6%8D%AE%E6%97%B6-Hyperledger-Fabric%E4%B8%AD%E7%9A%84%E6%95%B0%E6%8D%AE%E5%A6%82%E4%BD%95%E5%AE%89%E5%85%A8)

数据的备份和恢复参考地址[如何从备份中恢复 Hyperledger Fabric](https://www.devprovider.com/how-to-restore-hyperledger-fabric-from-backup/)

# 五、linux的curl操作couchdb
参考地址[curl操作CouchDB](https://www.cnblogs.com/MikeZhang/p/curlOptCouchDB20141007.html)

# 六、fabrci常用功能集合
## 1、Fabric SDK监听节点链码事件
主要参考的地址为[SDK监听节点链码事件](https://blog.csdn.net/fangdengfu123/article/details/80454581)

相关的知识，参考地址为[Hyperledger Fabric Java SDK上的Chaincode Event监听器教程](https://blog.csdn.net/shixin_0125/article/details/105548831)
