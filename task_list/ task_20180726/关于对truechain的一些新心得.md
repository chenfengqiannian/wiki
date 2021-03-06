 # 关于对truechain的一些心得
 [原文链接 https://www.jianshu.com/p/d1403b8dc6fb](https://www.jianshu.com/p/d1403b8dc6fb)
 ## 目前主流区块链模型
 
 现在的主流区块链共识算法POW，POS，DPOS，其中最为人所熟知的是BTC的UTXO模型POW共识机制，和ETH的account模型POW共识机制（后期可能转为POS机制），而在经历了第一代区块链模型（BTC为代表），


第二代区块链模型（ETH为代表），现在的区块链的发展方向主要是在，高TPS方向，增加区块操作系统的性能，由此引发了这一次的公链大爆发，true也是在解决高性能，扩展性上的一个公链。

![BTC模型](https://upload-images.jianshu.io/upload_images/14031180-1c7cf1a2c00211ea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
 ## fPoW共识算法
 
  因为POW的抢占式共识机制，必然导致的TPS底下的原因，第三代区块链都在致力于提出各种各样的解决方案，比如**truechain提出的混合共识方案，将 PBFT的高效与 PoW 的去中心化相结合的混合共识机制。在保证去中心化本质的基础上，实现高性能、高可靠性的无需许可链，以承载规模化商用 Dapp 运行的目标。**
  
   其中最强，也最引人瞩目的是fPoW共识算法，fPoW 是一种全新的设计挖矿设计理念，初链采用了水果链（FruitChain）的设计，在挖矿过程中保证所有参与者的公平性。在挖矿过程中，PBFT 生产大区块，而水果链负责将大区块分成若干个水果，这些水果具有保鲜期，每个水果中记录了若干条交易信息，普通挖矿只用验证这些交易信息即可，并不需要投入大量的挖矿设备、电力和带宽，水果链的轻节点设计理念，可以让普通参与者使用普通的计算机，甚至于使用手机就能实现挖矿。水果链最大的特点是公平可靠，解决了普通中 PoW 共识算法中存在的 25%攻击，大矿池联合挖矿以及交易费不稳定等问题。
   
   ## 个人理解
   而我对这个的理解就是分成了两条链，一条交易链，一条水果链，通过快慢链条的方式来加速交易和保证安全，这样就可以兼顾安全和速度。
   ## 总结
   唯有不断创新才能开创新的方向，而truechain的新的混合机制让我们看到了区块链未来的方向。
