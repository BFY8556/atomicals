下载地址：https://github.com/BFY8556/atomicals/releases/tag/atomicals

使用教程：https://twitter.com/bfy8556/status/1749008048893698432

1、首次运行EXE文件会自动生成10个钱包，钱包地址和私钥都是你本地生成的，你可以用，也可以不用，但是不要删除这个txt文件，不然启动exe会重复生成。

2、使用软件前先编辑env文件，根据要求设置参数即可。

3、软件运行只会按照env设置的funding私钥和收币地址执行。


#安全科普
本软件不开源，但是所有的计算都是在本地进行，不会获取钱包信息，如果不信任您可以funding钱包都用小钱包。


用任何人的工具，脚本，不管开源不开源，都要注意，fuding用小钱包，然后指定自己的收币地址，收币地址不暴露私钥和助记词。正确传导，不是开源就安全，即便开源，你也不一定会看安全还是不安全。甚至有时候官方的js审核都不够严谨，这个就是目前的状况，毕竟新兴市场就是这样。


谨记，千万不要用你的收币钱包去任何网站min或者任何工具作为funding钱包使用，这样会有烧伤资产的风险。

软件优势：

1、不会打废，软件原理是打印了2步raw才提交第一步。不存在扣钱了丢第二步。

2、对新人非常友好，软件易看易用，全中文输出。

3、固定gas，可以浮动gas，可以挂机到你想到的gas才工作。

4、软件用rust语言，非常高效，普通电脑几十秒一张，cpu好的10秒一张，高性能服务器可以做到1秒几张。

5、不依赖官方节点，自有技术，再卷的时候也能确保你可以打成功，更不会丢失第二笔。

6、高效模式：可以多个funding地址打1个收币地址，自动轮换，随便打几千张上万张都可以。

7、无需拆分utxo，单独一笔utxo可以连打


联系方式：微信 BFY8556  telegram：https://t.me/BFY8556


后续会更新更多功能
欢迎留下宝贵意见
