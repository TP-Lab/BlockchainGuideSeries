## 区块链钱包发展史

```
说起数字货币，就离不开数字货币钱包。比特币已诞生10年，区块链也经历了1.0 - 3.0三个时期的迭代。
在这期间钱包由单资产钱包、单链钱包发展为多链多资产钱包，从单一的转账收款钱包，发展为区块链生态服务平台。
```


### 钱包1.0时期

**（2009年 - 2013年）**

2009年，比特币主网上线，这个时期的区块链刚刚起步，作为一个巨大的分布式账本，比特币仅有简单的转账、记账功能。

受限于区块链的发展，这时的钱包就是用来存储比特币。**<font color=#2980fe>也就是单资产钱包形态，一个钱包只能支持一种币种。</font>**

> 2011年6月29日，比特币支付处理商BitPay推出了第一个用于智能手机的比特币电子钱包。同年7月6日，一个免费的比特币数字钱包App现身安卓应用商店，这是第一款与比特币相关的智能手机App。


### 钱包2.0时期

**（2014年 - 2018年）**

2014年，以太坊项目启动宣示着区块链进入2.0时代，智能合约开始运用于区块链。
此时的钱包除了进行转账收款外，还能进行链上合约操作，但由于此时的区块链速度较慢，钱包仅能进行非瞬时反应合约服务。

> 以太坊的出块速度为15秒，不考虑网络环境等问题，一个交易要被记录在区块链上，大概要15秒的时间。  
> 
> 智能合约就是一套不需要第三方的情况下还可以保证合同得到执行的计算机程序，任何人都可以基于此进行运算及开发应用层。


### 钱包3.0时期

**（2018年 - 至今）**


2018年开始，针对区块链2.0速度慢、高昂矿工费等问题进行优化，实现区块链的高并发、高可拓展等性能标志着区块链进入3.0时期，而其中最为代表的便是EOS。

> EOS的出块速度为0.5秒，不考虑网络环境等问题，一个交易被记录在区块链上，仅需0.5秒


此时的钱包，除了基础的存储转账功能外，还能与链上合约进行即时交互；钱包不再是简单的资产管理工具，更是一个公链生态服务平台；与此同时，单链钱包已无法满足用户需求，**<font color=#2980fe>越来越多的钱包往多链方向发展</font>**。
现如今，用户通过钱包可体验资产管理、资产交易、DApp、社交、资讯、行情等功能。

钱包已逐渐承担起它作为区块链世界入口的⻆色。


## 区块链钱包的基本知识点

```
要学会使用区块链钱包，一定要掌握以下五个相关名词定义，即公钥、私钥、助记词、Keystore、密码。
```

### 公钥

+ 公钥=账号=转账地址，相当于你的银行卡号，公钥是可以对外随意公开的，没有任何风险，就像别人知道了你的银行卡号一样，除了给你转账啥也干不了。

### 私钥

+ 私钥=账号+密码=身份认证，相当于你的银行卡号+密码。私钥是由数字和大小写字母组成，不同区块链的私钥⻓度一般不一样。通过私钥可以推导出公钥。需要注意的是，一旦你的私钥丢失或遗忘，将无法再找回，所以一定要妥善保管好。

### 助记词

+ 由于私钥不方便记忆，因此出现了助记词，助记词只是私钥的另一种展现形式。一般由12或24个英文单词组成，为了方便国内用户，也有提供汉字版本助记词。只要你记住这些单词，按照顺序在钱包中输入，就能恢复钱包并且进行任意操作。如果别人拿到了你的助记词，就相当于拿到了你的私钥，就可以对你的资产进行掌控了。

### Keystore

+ Keystore=卡号，**<font color=#2980fe>Keystore的本质是加密后的私钥，Keystore必须配合你的钱包密码来使用才有效。</font>** Keystore、私钥、助记词是所有钱包通用的，钱包服务商可能会因为产品设计原因，仅为用户提供其中一种或多种方式，但是如果存在同一方式在某钱包无法正常恢复，则该钱包可能存在一定的问题。

### 密码

+ 为了进一步增强安全性，大部分钱包会采取密码的方式对私钥做二次加密。每个钱包的加密方法和存储方式是不一样的。这也是为什么你使用钱包进行交易的时候，总需要进行授权，这背后其实涉及了钱包使用密码进行私钥解密，然后再使用私钥对交易进行签名等复杂的过程。

### 钱包安全小贴士

> + 公钥是可以曝光的，对你的资产安全无影响。相当于你告诉人家你的银行卡账号一样。

> + 助记词、私钥一旦泄露，资产将有很大风险被他人掌控，此时你需要立即转移资产到其他地址，原先的账户或地址不再使用。

> + keystore泄露，不管密码有没有泄露，都存在他人掌控资产的⻛险，因此需要赶快把资产转移其他地址。

> + 如果是EOSIO（包括EOS、BOS、WAX等）和IOST的账号私钥泄露时，还可以采取更换新私钥的方式，阻止他人掌控自己的资产。

> + 在存储私钥、助记词时，我们都建议采用离线形式（手抄、打印等）进行数据备份，同时将备份好的内容妥善保管。对于keystore这样的信息，采用抄写进行备份是很不科学并且很容易出错的，所以用户可以将keystore存储为文件形式，然后可以将其存储在U盘中再妥善管理好U盘；其中，我们非常不建议您进行截屏、网络传输（QQ、微信）、云端存储等方式备份，这些方式都有可能遭遇黑客攻击，从而造成资产损失。


## 区块链钱包分类

```
我们将从私钥的存储和私钥的生成两个方向对钱包进行分类。
```

### 私钥存储

根据私钥的存储方式，即用户是否掌握了私钥，我们可以把钱包划分为，**<font color=#2980fe>“中心化钱包”</font>及<font color=#2980fe>“去中心化钱包”</font>**。

> 存储方式是指存在哪，只有用户持有私钥且导入钱包后，私钥仅存储在用户设备上的才叫“去中心化”，而无私钥，或者私钥有上传存储在服务商的服务器里的，则就是“中心化”。

去中心化钱包，我们又可根据私钥存储过程中是否接触网络，划分为**<font color=#2980fe>“冷钱包”</font>**和**<font color=#2980fe>“热钱包”</font>**；这里的接触网络是指，钱包是否联网了，而不是私钥是否在网络中传输的意思。

常见的热钱包有桌面钱包、手机钱包和网⻚钱包。而冷钱包一般是指纸钱包、硬件钱包这些不联网或无法联网的工具。

![钱包类别 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576071056328.png "钱包类别")

根据钱包的去中心化程度又可将钱包分为全节点钱包、轻节点钱包、中心化钱包。

全节点钱包就是将区块链上所有数据同步到钱包，这样会占用很大的存储空间，所以大部分全节点钱包都是桌面钱包。其中最为代表有比特币核心钱包、Geth、Parity等等。正因为全节点钱包需要同步所有区块数据，所以其可以实现完全去中心化。

> 根据DApptotal数据，截止到2019年9月份：以太坊的全节点数据大小为433GB，EOS的为430GB，而比特币为279GB

轻钱包就是依赖区块链网络中的其他全节点的钱包，比如TP钱包会运行一个全节点，同步所有数据，然后根据不同的钱包地址将数据进行划分，按需下发，这样用户便可以既快又方便的使用钱包。常见的手机钱包和网页钱包就是轻钱包。

去中心化钱包的数据都是区块链上的数据，而中心化钱包的数据则依赖钱包服务商自己的账本。举个例子，我们在交易所的钱包就是中心化钱包，我们往交易所指定的某个地址转账，然后交易所在自己的账本上记录了我们的充值记录，此后我们每做一次充值转账，交易所直接在他的账本上进行加或减。而这整个过程，完全没有发生在区块链上。

![节点钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576071528679.png "节点钱包")


### 私钥生成
**（本小节内容稍微超纲）**

从私钥的生成，我们可以把钱包划分为，“非确定性钱包”、“确定性钱包”及“分层确定性钱包”，而其中“分层确定性钱包”是“确定性钱包”的加强版本。


**<font color=#2980fe>非确定性钱包</font>**

在钱包中生成的私钥之间没有任何关系，是相互独立的。

![非确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070497680.png "非确定性钱包")

**<font color=#2980fe>确定性钱包</font>**

私钥都是由一个“种子”通过算法生成，比如“助记词”就是种子的形式。通过这个方式生成的私钥，只要算法一致，私钥就可以保持前后一致；且一个种子可以派生出无限的私钥地址。

![确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070721576.png "确定性钱包")


> 为了更好理解，我们可以“确定性钱包”比喻一根树枝，树枝上不同位置的叶子不同，  
> 但是只要你选择的位置一样，那个位置的叶子永远是同一片。而这里的叶子就是我们提到的“私钥”。

**<font color=#2980fe>分层确定性钱包</font>**

是确定性钱包的加强版，为确定性钱包引入“主私钥”概念，即HD钱包。它的层级结构是，从主私钥生成的私钥，本身就可以成为一把主私钥，再通过上述方法生成一个确定性钱包。

![分层确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070849616.png "分层确定性钱包")

> 同样的，我们可以把“分层确定性钱包”比喻成树干；  
> 一个树干上有很多树枝，每一根树枝上的叶子都是确定的。  
> 所以，只要我们确定了某一树枝上的某一个位置，那这片叶子就是确定的。也就是私钥是确定的。


## 区块链钱包功能介绍

钱包是区块链的入口，拥有包含资产管理在内的丰富功能，可以满足用户各式各样的需求。

### 创建区块链账号

区块链钱包的展现形式分为地址和账号，我们这里统称为账号；  
不同区块链的账号是不一样的，⻓度也可能不一样的。  
不同区块链账号的创建费用也是不一样的，例如以太坊、比特币的账号是免费的，但是EOS的账号是需要消耗一定费用进行创建的。

由于区块链账号的创建是一个复杂的过程，钱包的存在就是帮助用户简化这些过程。  
一般创建完账号过程中，钱包都会引导用户进行私钥或助记词备份，然后再进行二次验证，以确保用户备份的私钥或助记词准确无误。  
而在需要通过支付创建账号的区块链上，钱包一般会帮助用户使用传统支付工具完成支付过程，以降低用户的使用难度。

对于小白用户来说，掌握私钥或许太麻烦了，因此TokenPocket基于EOS设计了去中心化的手机号/邮箱注册账号方式，这种方式支持用户在忘记私钥的时候通过验证码方式找回，和我们平常使用互联网产品一样，忘记密码就通过验证码登录，大大降低了用户使用钱包的难度。


### 数字资产管理

**<font color=#2980fe>数字资产主要指的是区块链上的各种代币（Token）</font>**，钱包的存在极大的方便了用户对于自己所拥有的资产管理，主要包括转账、收款、查看资产详情、交易详情等。  
功能类似银行的APP，你可以看到自己当前拥有什么资产，数量多少，以及对你的资产进行转账等操作。

> 需要注意的是，不同区块链之间的资产是不能直接转账的，即你无法向以太坊账号转入BTC（比特币），也无法向比特币账号转入ETH（以太坊）。

### 数字资产交易

当前钱包支持的数字资产交易主要包括以下三种情况：币币兑换、交易所交易、OTC交易。

**<font color=#2980fe>币币兑换</font>**

通过币币兑换，可以将不同区块链上的资产进行兑换，例如你可以将自己拥有的BTC（比特币）直接兑换成EOS。  

> 一般的交易只能通过一个基本对的形式进行交易，再通过基本对交易成最终目的币。  
> 例如我要从A换成C，则需要通过中介B实现，A -> B, B -> C;  
> 而币币兑换则简化这个过程，直接将A兑换成C

**<font color=#2980fe>交易所交易</font>**

当前交易所有 3 种形态，分别是<font color=#2980fe>中心化交易所、去中心化交易所、聚合交易所</font> 。  
中心化交易所常⻅的有火币、币安、OKEX等。去中心化交易所有如以太坊上的IDEX，EOS上NewDex、鲸交所、DEXEOS等。

> 中心化交易所需要我们把币托管在交易所账户里，然后交易仅发生在交易所的中心化数据中。  
> 而去中心化交易所则无需这个过程。  
> 这大大降低了交易所被盗或跑路导致用户资产损失的⻛险。  
> 去中心化交易所，用户通过钱包将币往智能合约转账，智能合约完成链上撮合交易，再将币转回给用户。  
> 合约交易，在提升透明度的同时，也大大减少了对中心媒介的依赖。


**<font color=#2980fe>聚合交易所</font>**

聚合交易所是聚集了所有交易所而形成一个交易平台,让用户简易进行跨平台交易,无需下载众多app。聚合交易所共享其他交易所的深度和其他交易所的交易对。例如你注册了聚合交易所账号后，你每次买卖BTC（比特币）时，你可以从不同的交易所中挑选性价比最高的来进行交易。

> 当前部分钱包已经开始支持聚合交易，如TokenPocket钱包预计在2019年12月上线聚合交易所，到时候用户可通过TokenPocket直接在火币、OKEX及币安等大交易所进行交易。

**<font color=#2980fe>OTC</font>**

OTC（Over The Counter）交易就是在交易所外，由第三方担保，客户点对点的交易方式。在区块链中的OTC，通常指的是场外用户之间法币与数字货币一对一的买卖交易。  
当前最大的OTC主要以交易所的OTC为主，也有部分钱包接入了提供该项服务的第三方渠道商。

> 例如TokenPocket接入了币买卖的OTC服务，用户使用TP钱包时，可以很方便的将自己手中的数字货币卖出，换成法币；或是使用法币购买数字货币。

### 参与生态建设

目前部分公链设计中，都激励生态中的用户积极参与公链生态建设。主要的形式有**<font color=#2980fe>节点投票、公投、Staking等</font>**。

**<font color=#2980fe>节点投票</font>**  
以EOS为例，EOS总共有21个超级节点，用户通过将手中的EOS进行抵押后，最多可以投给30个节点，投票的目的在于让用户选出能为生态发展与贡献自己力量的节点，从而推动生态的稳定发展。

**<font color=#2980fe>公投</font>**  
公投指的是区块链生态中，参与者可以发起自己认为对社区有利的提案，并由整个区块链持币者进行投票，当投票数超过一定标准时，提案自动生效。公投的方式有利于社区用户积极参与区块链治理。

**<font color=#2980fe>Staking</font>**  
Staking中文名权益质押，目前部分公链采取Staking的形式来鼓励持币者质押token，并以此产生稳定节点。如COSMOS质押可以使质押者获得一定的年化收益（以质押币结算），类似你在银行投了一个活期理财。

### 体验DApp应用

DApp是Decentralized Application的缩写，译为去中心化应用，指的是以区块链为底层进行应用开发。

目前DApp主要集中在以太坊和EOS、TRON、IOST等区块链上。DApp与底层平台的关系，就好比APP与iOS和Android系统的关系。

例如EOS的DApp无法在ETH底层上运行，正如安卓的APP无法在iOS系统上运行。你可以在钱包中体验ETH上的去中心化金融MakerDAO，体验在EOSRacing中开赛⻋赢取EOS奖励，也可以在IOST上的猎币矿池进行挖矿理财。


目前一些大型游戏是以第三方独立APP的形式存在，当体验这些APP形式的DApp时，你同样需要钱包作为登录和交易授权的媒介。

![DApp商店 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576074058171.png "DApp商店")

> 目前TokenPocket支持EOS三国、EOSKnights、EOS加密骑士团、加密剑与魔法、CryptoLegends等多个热⻔游戏。并且为了免去用户体验DApp时，来回切换钱包的繁琐操作，TP研发了MiniWallet模式，用户开启MiniWallet模式后，仅需一次授权操作后，即可一直停留在游戏中进行娱乐。

### 领取糖果奖励

拥有钱包的好处是可以不定时获得糖果。  
市面上常⻅的糖果发放方式有：**<font color=#2980fe>注册领取、持币空投、广告糖果、Airgrab、转账空投</font>**等方式。

> 糖果指的是区块链上免费获得的Token

**<font color=#2980fe>注册领取：</font>**  
通常在项目前期推广时经常会有免费领糖果活动，只要在项目方的活动⻚面上注册并登记自己的区块链账号（如ETH地址、EOS账号等），等待项目方发放奖励后就能获得免费的糖果了。

**<font color=#2980fe>持币空投：</font>**  
持币空投常⻅的有2种方式，一种是分叉币，例如BTC（比特币）分叉出BCH，所有分叉前持有BTC（比特币）的用户，根据BTC（比特币）持有量都会获得相应的BCH。  

另外一种是直接针对持币者进行另外一种Token的奖励发放，例如EOS上的第一个空投币ADD，在EOS主网上线时，就对全网账号进行了快照，然后对持有EOS的账号进行糖果发放。

**<font color=#2980fe>广告糖果：</font>**   
当前很多项目为了宣传自己的产品，会给持币者发送小额的转账，并在转账信息里带上自己的广告memo

> memo指的是区块链转账信息中的备注

![糖果空投 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576073859331.png "糖果空投")

**<font color=#2980fe>Airgrab：</font>**  
中文可以称为糖果抓手，这是一种EOS上糖果分发的方式，需要消耗用户的内存（每种代币大概需要0.25KB左右）。执行Airgrab后需要等待项目方空投即可。

**<font color=#2980fe>转账空投：</font>**  
转账空投是指用户向某个合约账号发送小额代币后，合约会把代币原路返回的同时，发送一定量的糖果给用户。  
较为出名的转账空投如EIDOS，用户仅需向其合约账号发送0.0001 EOS，合约就会在返回0.0001 EOS的同时，赠送其合约账号当前剩余EIDOS的 0.01%

![转账空投 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576073996350.png "转账空投")

因为在钱包中是可以快速登录去中心化交易所，所以很多用户领取糖果后即可直接在交易所中卖出换成ETH、EOS、USDT等， **<font color=#2980fe>免费羊毛的感觉真棒。</font>**

### 资产增值

钱包天然就具有金融属性，当前钱包已经集合了包括**<font color=#2980fe>矿池、理财、挖矿、项目投资</font>**等多种金融工具与功能，可以满足用户资产增值的需求。

**<font color=#2980fe>矿池： </font>**  
当前挖矿主要是PoW挖矿与PoS挖矿这 2 种方式。  
PoW（Proof of Work）就是算力挖矿，也是我们熟悉的BTC（比特币）挖矿; PoS（Proof of Stake）挖矿是模仿 PoW 算力挖矿，持币人可以将代币抵押给验证人节点，来获得奖励分红。

> 目前钱包的矿池基本上是以PoS挖矿为主。也有部分钱包支持购买云算力，进行BTC（比特币）挖矿。

**<font color=#2980fe>理财： </font>**  
钱包里的理财产品与传统理财产品十分相似，唯一不同的是结算的方式。通常会约定一个预估收益率，用户用Token购买该理财产品后，根据约定的结算日期进行定期结算，到期可以取回或续约。

**<font color=#2980fe>挖矿： </font>**  
挖矿以DApp挖矿为主，钱包中集合了一些DApp矿机产品，使用矿机可以便捷快速的获得想挖的Token。以最近大火的EIDOS为例，EIDOS矿机可以帮助用户实现自动转账挖矿。这些挖出来的Token可以拿去交易所卖出换成EOS从而获取收益。

**<font color=#2980fe>项目投资： </font>**  
以⻁符钱包的HOO Labs为例，你可以在上面使用USDT支持项目，并以支持USDT的数量按照一定比例获得项目的Token。

### 社交


部分区块链钱包还拥有社交功能，你可以在钱包里跟其他用户进行沟通与交流。如TokenPocket和块信的聊天频道，你可以加入不同的群，与群内成员自由交谈。并且还可以在聊天群里收发数字货币红包。

以社交作为主打功能的钱包Sense.Chat，允许你在APP上与其他成员自由聊天，所有的聊天信息都是加密的，只有你和联系人之间才能解密信息。此外MIXIN也是一个以聊天为主要功能的钱包。

Trybe是一个由数字货币激励的社交网络和媒体发布社区，用户通过创建精美的内容，对他人的内容进行评级或邀请朋友，都可以获得Trybe送出的数字货币！


### 硬件钱包配套管理工具

硬件钱包通常会搭配一个软件钱包作为管理工具。硬件钱包厂商如Ledger、Trezor、库神、YubiKey等，都有研发自己配套的软件钱包。

同样的，软件钱包厂商也会与硬件钱包厂商合作，开发自己产品专属的硬件钱包，如比特派的硬件钱包比特盾、imToken的imKey等。

### 区块链资讯获取

绝大多数钱包用户都有交易需求，因此通常钱包都会把Token行情融入到产品中。除此外，还会把快讯、文章、甚至项目推特等这些内容模块加到产品中。

与其他区块链媒体不同的是，钱包快讯、文章方面则主要以当前钱包支持的区块链相关内容为主，更有针对性。

## 如何选择区块链钱包

```
首先我们需要了解中心化钱包和去心化钱包区别，再结合自身需求进行选择。
```


| **中心化钱包**                                                                               | **去中心化钱包**                                                                               |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| 私钥由平台方掌控                                                                             | 私钥由用户掌控                                                                                 |
| 资产存储在平台方的钱包                                                                       | 资产存储在用户的钱包                                                                           |
| 密码可找回                                                                                   | 密码不可找回                                                                                   |
| 转账需要平台审核                                                                             | 转账不需要平台审核                                                                             |
| 中心化账号在其他钱包平台不可用                                                               | 去中心化账号在其他钱包通用                                                                     |
| 平台内部转账无手续费，资产提现有手续费                                                       | 资产转账仅需支付区块链网络费用                                                                 |
| 平台丢币风险来源：平台方钱包被黑客攻击、服务器被攻击、运营商倒闭（钱包服务关闭）、运营商作弊 | 钱包丢币风险来源：私钥泄漏与遗忘、私钥未备份、安装钱包的设备丢失（手机、电脑）、安装了木马钱包 |

## 区块链钱包导航

### 去中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- TokenPocket -->
<a class="tp-custom" href="https://www.tokenpocket.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TokenPocket.png"/>
    <div class="tp-content">
        <h5>TokenPocket</h5>
        <p>https://www.tokenpocket.pro</p>
    </div>
</a>


<!-- Trust Wallet -->
<a class="tp-custom" href="https://www.trustwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TrustWallet.png"/>
    <div class="tp-content">
        <h5>Trust Wallet</h5>
        <p>https://www.trustwallet.com</p>
    </div>
</a>
</main>

</main>

<!-- 2 -->

<main class="tp-main">
<!-- Bitpie -->
<a class="tp-custom" href="https://bitpie.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitpie.png"/>
    <div class="tp-content">
        <h5>Bitpie</h5>
        <p>https://bitpie.com</p>
    </div>
</a>


<!-- imToken -->
<a class="tp-custom" href="https://token.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ImToken.png"/>
    <div class="tp-content">
        <h5>imToken</h5>
        <p>https://token.im</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- Huobi -->
<a class="tp-custom" href="https://www.huobiwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/HuobiWallet.png"/>
    <div class="tp-content">
        <h5>Huobi Wallet</h5>
        <p>https://www.huobiwallet.com</p>
    </div>
</a>


<!-- AToken -->
<a class="tp-custom" href="https://www.atoken.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/AToken.png"/>
    <div class="tp-content">
        <h5>AToken</h5>
        <p>https://www.atoken.com</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- BPEAL Wallet -->
<a class="tp-custom" href="https://www.bepal.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BPEALWallet.png"/>
    <div class="tp-content">
        <h5>BPEAL Wallet</h5>
        <p>https://www.bepal.pro</p>
    </div>
</a>


<!-- Starteos -->
<a class="tp-custom" href="https://www.starteos.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Starteos.png"/>
    <div class="tp-content">
        <h5>Starteos</h5>
        <p>https://www.starteos.io</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- BitKeep -->
<a class="tp-custom" href="https://www.bitkeep.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitkeep.png"/>
    <div class="tp-content">
        <h5>BitKeep</h5>
        <p>https://www.bitkeep.com</p>
    </div>
</a>


<!-- MEET.ONE -->
<a class="tp-custom" href="https://www.meet.one" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Meetone.png"/>
    <div class="tp-content">
        <h5>MEET.ONE</h5>
        <p>https://www.meet.one</p>
    </div>
</a>
</main>

<!-- 6 -->

<main class="tp-main">
<!-- Tronlink -->
<a class="tp-custom" href="https://www.tronlink.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>Tronlink</h5>
        <p>https://www.tronlink.org</p>
    </div>
</a>


<!-- Lynx -->
<a class="tp-custom" href="https://lynxwallet.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Lynx.png"/>
    <div class="tp-content">
        <h5>Lynx</h5>
        <p>https://lynxwallet.io</p>
    </div>
</a>
</main>

<!-- 7 -->

<main class="tp-main">
<!-- Scatter -->
<a class="tp-custom" href="https://get-scatter.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/scatter.png"/>
    <div class="tp-content">
        <h5>Scatter</h5>
        <p>https://get-scatter.com</p>
    </div>
</a>


<!-- MetaMask -->
<a class="tp-custom" href="https://metamask.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MetaMask.png"/>
    <div class="tp-content">
        <h5>MetaMask</h5>
        <p>https://metamask.io</p>
    </div>
</a>
</main>

<!-- 8 -->

<main class="tp-main">
<!-- ENJIN Wallet -->
<a class="tp-custom" href="https://enjin.io/products/wallet" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ENJINWallet.png"/>
    <div class="tp-content">
        <h5>ENJIN Wallet</h5>
        <p>https://enjin.io/products/wallet</p>
    </div>
</a>


<!-- jaxx wallet -->
<a class="tp-custom" href="https://jaxx.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/JaxxWallet.png"/>
    <div class="tp-content">
        <h5>jaxx wallet</h5>
        <p>https://jaxx.io</p>
    </div>
</a>
</main>

<!-- 9 -->
<main class="tp-main">
<!-- 块信 -->
<a class="tp-custom" href="https://chattle.vip/#/" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576249499924.png"/ width=50>
    <div class="tp-content">
        <h5>块信</h5>
        <p>https://chattle.vip</p>
    </div>
</a>


<!-- KCASH -->
<a class="tp-custom" href="https://www.kcash.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div>
</a>
</main>


<!-- 10 -->
<main class="tp-main">
<!-- Conibase Wallet -->
<a class="tp-custom" href="https://www.coinbase.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Coinbase Wallet</h5>
        <p>https://www.coinbase.com</p>
    </div>
</a>

<!-- KCASH -->
<a class="tp-custom" style="border:none" target="_blank">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div> -->
</a>
</main>

### 中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- 币信 -->
<a class="tp-custom" href="https://bixin.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/bixin.png"/>
    <div class="tp-content">
        <h5>币信</h5>
        <p>https://bixin.com</p>
    </div>
</a>


<!-- Edge -->
<a class="tp-custom" href="https://edge.app" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Edge.png"/>
    <div class="tp-content">
        <h5>Edge</h5>
        <p>https://edge.app</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">


<!-- Uphold -->
<a class="tp-custom" href="https://uphold.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Uphold.png"/>
    <div class="tp-content">
        <h5>Uphold</h5>
        <p>https://uphold.com</p>
    </div>
</a>

<!-- Conibase Wallet -->
<a class="tp-custom" style="border:none">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Conibase Wallet</h5>
        <p>https://www.coinbase.com</p> -->
    <!-- </div> -->
</a>

</main>

### 硬件钱包

<!-- 1 -->

<main class="tp-main">
<!-- Ledger -->
<a class="tp-custom" href="https://www.ledger.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Ledger.png"/>
    <div class="tp-content">
        <h5>Ledger</h5>
        <p>https://www.ledger.com</p>
    </div>
</a>


<!-- Trezor -->
<a class="tp-custom" href="https://www.trezor.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Trezor.png"/>
    <div class="tp-content">
        <h5>Trezor</h5>
        <p>https://www.trezor.io</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- keep key -->
<a class="tp-custom" href="https://shapeshift.io/keepkey" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/keepkey.png"/>
    <div class="tp-content">
        <h5>keep key</h5>
        <p>https://shapeshift.io/keepkey</p>
    </div>
</a>


<!-- 库神(ColdLar） -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神(ColdLar）</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- 比特护盾（BITHD) -->
<a class="tp-custom" href="https://bithd.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BITHD.png"/>
    <div class="tp-content">
        <h5>比特护盾（BITHD)</h5>
        <p>https://bithd.com</p>
    </div>
</a>


<!-- imKey -->
<a class="tp-custom" href="https://imkey.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/imKey.png"/>
    <div class="tp-content">
        <h5>imKey</h5>
        <p>https://imkey.im</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- Cobo金库 -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo金库</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- BEPAL Pro S -->
<a class="tp-custom" href="https://www.bepal.pro/bepal-q" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BEPALProS.png"/>
    <div class="tp-content">
        <h5>BEPAL Pro S</h5>
        <p>https://www.bepal.pro/bepal-q</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- 华特钱包 -->
<a class="tp-custom" href="https://www.orientwalt.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/orientwalt.png"/>
    <div class="tp-content">
        <h5>华特钱包</h5>
        <p>https://www.orientwalt.com</p>
    </div>
</a>


<!-- SafePal-->
<a class="tp-custom" href="https://safepal.io/" target="_blank">
    <img class="tp-logo" width=50 src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576591843263.png"/>
    <div class="tp-content">
        <h5>SafePal</h5>
        <p>https://safepal.io/</p>
    </div>
</a>
</main>



### 中心化&去中心化

<!-- 1 -->

<main class="tp-main">
<!-- Cobo -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- 库神 -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- 虎符 -->
<a class="tp-custom" href="https://hoo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hoo.png"/>
    <div class="tp-content">
        <h5>虎符</h5>
        <p>https://hoo.com</p>
    </div>
</a>


<!-- RenrenBit -->
<a class="tp-custom" href="https://www.renrenbit.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Renrenbit.png"/>
    <div class="tp-content">
        <h5>RenrenBit</h5>
        <p>https://www.renrenbit.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- HyperPay -->
<a class="tp-custom" href="http://www.hyperpay.tech" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hyperpay.png"/>
    <div class="tp-content">
        <h5>HyperPay</h5>
        <p>http://www.hyperpay.tech</p>
    </div>
</a>


<!-- Math Wallet -->
<a class="tp-custom" href="http://www.mathwallet.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MathWallet.png"/>
    <div class="tp-content">
        <h5>Math Wallet</h5>
        <p>http://www.mathwallet.org</p>
    </div>
</a>
</main>

## 区块链钱包操作指南

以下问题均发布在TokenPocket钱包官网帮助中心

网址：https://help.mytokenpocket.vip/hc/zh-cn

<img src="https://gz.bcebos.com/v1/tp-statics/logo/QA-code.jpg" width="250">

### BTC(比特币)钱包常⻅问题

1.[如何创建BTC比特币钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037208612-%E5%9C%A8TokenPocket%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BABTC%E9%92%B1%E5%8C%85-)

2.[如何备份BTC比特币私钥](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037208872-%E5%A6%82%E4%BD%95%E5%A4%87%E4%BB%BDBTC%E6%AF%94%E7%89%B9%E5%B8%81%E7%A7%81%E9%92%A5-)

3.[BTC比特币私钥丢了怎么办](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037208972-BTC%E7%A7%81%E9%92%A5%E4%B8%A2%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E-)

4.[如何修改BTC比特币钱包密码](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037209032-%E5%A6%82%E4%BD%95%E9%87%8D%E7%BD%AEBTC%E9%92%B1%E5%8C%85%E5%AF%86%E7%A0%81-)

5.[如何将BTC比特币私钥导入钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037211032-%E5%A6%82%E4%BD%95%E5%B0%86btc%E7%A7%81%E9%92%A5%E5%AF%BC%E5%85%A5%E9%92%B1%E5%8C%85-)

6.[如何用钱包把BTC比特币转账到交易所](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037209852-%E5%A6%82%E4%BD%95%E7%94%A8%E9%92%B1%E5%8C%85%E6%8A%8Abtc%E8%BD%AC%E5%85%A5%E4%BA%A4%E6%98%93%E6%89%80-)

7.[如何设置BTC比特币矿工费](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037576691-%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AEbtc%E7%9A%84%E7%9F%BF%E5%B7%A5%E8%B4%B9-)

8.[BTC比特币转账慢可以加速吗？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037211172-BTC%E6%AF%94%E7%89%B9%E5%B8%81%E8%BD%AC%E8%B4%A6%E6%85%A2%E5%8F%AF%E4%BB%A5%E5%8A%A0%E9%80%9F%E5%90%97)

9.[什么是BTC隔离见证？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037362692-%E4%BB%80%E4%B9%88%E6%98%AFBTC%E9%9A%94%E7%A6%BB%E8%A7%81%E8%AF%81-)

10.[比特币的工作量证明（POW）是什么？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037363992-BTC%E6%AF%94%E7%89%B9%E5%B8%81%E7%9A%84%E5%B7%A5%E4%BD%9C%E9%87%8F%E8%AF%81%E6%98%8E-POW-%E6%98%AF%E4%BB%80%E4%B9%88-)

[点击前往查看更多](https://help.mytokenpocket.vip/hc/zh-cn/sections/360007340872-%E6%AF%94%E7%89%B9%E5%B8%81-BTC-%E9%92%B1%E5%8C%85%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

### ETH(以太坊)钱包常⻅问题

1.[怎样创建ETH钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037514271-%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BAETH%E9%92%B1%E5%8C%85-)

2.[怎样找回之前的ETH钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037151792-%E5%A6%82%E4%BD%95%E6%89%BE%E5%9B%9E%E4%B9%8B%E5%89%8D%E7%9A%84ETH%E9%92%B1%E5%8C%85-)

3.[怎样购买ETH资产](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037152332-%E6%80%8E%E6%A0%B7%E8%B4%AD%E4%B9%B0ETH%E8%B5%84%E4%BA%A7-)

4.[怎样充值ETH到钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037153092-%E6%80%8E%E6%A0%B7%E5%85%85%E5%80%BCETH%E5%88%B0%E9%92%B1%E5%8C%85-)

5.[钱包里的ETH如何卖出变现](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037153552-%E9%92%B1%E5%8C%85%E9%87%8C%E7%9A%84ETH%E5%A6%82%E4%BD%95%E5%8D%96%E5%87%BA%E5%8F%98%E7%8E%B0-)

6.[ETH转账记录怎么看？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037153712-ETH%E8%BD%AC%E8%B4%A6%E8%AE%B0%E5%BD%95%E6%80%8E%E4%B9%88%E7%9C%8B-)

7.[怎么向他人转账/收取ETH？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037516471-%E6%80%8E%E4%B9%88%E5%90%91%E4%BB%96%E4%BA%BA%E8%BD%AC%E8%B4%A6-%E6%94%B6%E5%8F%96ETH-)

8.[ETH转账的手续费和gas费什么意思？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037516511-ETH%E8%BD%AC%E8%B4%A6%E7%9A%84%E6%89%8B%E7%BB%AD%E8%B4%B9%E5%92%8Cgas%E8%B4%B9%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-)

9.[从TokenPocket钱包创建的ETH钱包可以转移到其他钱包吗？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037516591-%E5%A6%82%E4%BD%95%E5%BE%80%E9%92%B1%E5%8C%85%E5%85%85%E5%80%BC%E5%9F%BA%E4%BA%8EETH%E5%85%AC%E9%93%BE%E7%9A%84%E5%85%B6%E4%BB%96Token-)

10.[如何往钱包充值基于ETH公链的其他币种？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037516591-%E5%A6%82%E4%BD%95%E5%BE%80%E9%92%B1%E5%8C%85%E5%85%85%E5%80%BC%E5%9F%BA%E4%BA%8EETH%E5%85%AC%E9%93%BE%E7%9A%84%E5%85%B6%E4%BB%96Token-)

[点击前往查看更多](https://help.mytokenpocket.vip/hc/zh-cn/sections/360007354652-ETH-%E4%BB%A5%E5%A4%AA%E5%9D%8A-%E9%92%B1%E5%8C%85%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

### EOS(柚子)钱包常⻅问题

1.[如何获得EOS柚子？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037250532-%E5%A6%82%E4%BD%95%E5%9C%A8TokenPocket%E9%92%B1%E5%8C%85%E8%B4%AD%E4%B9%B0EOS-)

2.[如何从交易所提取EOS到钱包](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037250712-%E5%A6%82%E4%BD%95%E4%BB%8E%E4%BA%A4%E6%98%93%E6%89%80%E6%8F%90%E5%8F%96EOS%E5%88%B0TokenPocket%E9%92%B1%E5%8C%85-)

3.[如何注册EOS账号](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037250892-%E5%A6%82%E4%BD%95%E6%B3%A8%E5%86%8CEOS%E8%B4%A6%E5%8F%B7)

4.[如何进行EOS的转账、收款](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037620971-%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8CEOS%E7%9A%84%E8%BD%AC%E8%B4%A6-%E6%94%B6%E6%AC%BE-)

5.[EOS的资源又哪些？RAM（内存） cpu（网络资源） net（计算资源）是什么意思？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037623871-EOS%E7%9A%84%E8%B5%84%E6%BA%90%E5%8F%88%E5%93%AA%E4%BA%9B-RAM-%E5%86%85%E5%AD%98-cpu-%E7%BD%91%E7%BB%9C%E8%B5%84%E6%BA%90-net-%E8%AE%A1%E7%AE%97%E8%B5%84%E6%BA%90-%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-)

6.[不小心把TokenPocketAPP卸载了 ,私钥也没保存能否找回?](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037254452-%E4%B8%8D%E5%B0%8F%E5%BF%83%E6%8A%8ATokenPocket-APP%E5%8D%B8%E8%BD%BD%E4%BA%86-%E7%A7%81%E9%92%A5%E4%B9%9F%E6%B2%A1%E4%BF%9D%E5%AD%98%E8%83%BD%E5%90%A6%E6%89%BE%E5%9B%9E-)

7.[eos转账有手续费吗？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037505611-EOS%E8%BD%AC%E8%B4%A6%E6%9C%89%E6%89%8B%E7%BB%AD%E8%B4%B9%E5%90%97-)

8.[如何备份EOS私钥？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037505551-%E5%A6%82%E4%BD%95%E5%A4%87%E4%BB%BDEOS%E7%A7%81%E9%92%A5)

9.[EOS观察模式怎么使用？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037505191-TokenPocke%E9%92%B1%E5%8C%85%E4%B8%AD-%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8EOS%E8%A7%82%E5%AF%9F%E6%A8%A1%E5%BC%8F)

10.[没有CPU的时候怎么办？TokenPokcet的顺畅模式如何使用？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037255072-%E6%B2%A1%E6%9C%89CPU%E7%9A%84%E6%97%B6%E5%80%99%E6%80%8E%E4%B9%88%E5%8A%9E-TokenPokcet%E7%9A%84%E9%A1%BA%E7%95%85%E6%A8%A1%E5%BC%8F%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8-)

[点击前往查看更多](https://help.mytokenpocket.vip/hc/zh-cn/sections/360007442911-EOS%E9%92%B1%E5%8C%85%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

### TRON(波场)钱包常见问题

1.[如何获得TRX波场？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037354052-%E5%A6%82%E4%BD%95%E8%8E%B7%E5%BE%97TRX%E6%B3%A2%E5%9C%BA-)

2.[如何从交易所提取TRX到钱包？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037725931-%E5%A6%82%E4%BD%95%E4%BB%8E%E4%BA%A4%E6%98%93%E6%89%80%E6%8F%90%E5%8F%96TRX%E5%88%B0%E9%92%B1%E5%8C%85-)

3.[如何注册及导入TRX账号？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037354672-%E5%A6%82%E4%BD%95%E6%B3%A8%E5%86%8C%E5%8F%8A%E5%AF%BC%E5%85%A5TRX%E8%B4%A6%E5%8F%B7-)

4.[如何进行TRX的转账、收款？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037726591-%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8CTRX%E7%9A%84%E8%BD%AC%E8%B4%A6-%E6%94%B6%E6%AC%BE-)

5.[波场上的宽带、能量是什么意思？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037730011-%E6%B3%A2%E5%9C%BA%E4%B8%8A%E7%9A%84%E5%AE%BD%E5%B8%A6-%E8%83%BD%E9%87%8F%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-)

6.[波场上资源冻结和解冻如何操作？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037726871-%E6%B3%A2%E5%9C%BA%E4%B8%8A%E8%B5%84%E6%BA%90%E5%86%BB%E7%BB%93%E5%92%8C%E8%A7%A3%E5%86%BB%E5%A6%82%E4%BD%95%E6%93%8D%E4%BD%9C-)

7.[如何玩波场上的DApp？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037355372-%E5%A6%82%E4%BD%95%E7%8E%A9%E6%B3%A2%E5%9C%BA%E4%B8%8A%E7%9A%84DApp-)

8.[波场钱包如何进行备份？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037358892-%E6%B3%A2%E5%9C%BA%E9%92%B1%E5%8C%85%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8C%E5%A4%87%E4%BB%BD-)

9.[没有能量的时候怎么办？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037358952-%E6%B2%A1%E6%9C%89%E8%83%BD%E9%87%8F%E5%92%8C%E5%AE%BD%E5%B8%A6%E7%9A%84%E6%97%B6%E5%80%99%E6%80%8E%E4%B9%88%E5%8A%9E-)

10.[如何进行波场投票？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037359032-%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8C%E6%B3%A2%E5%9C%BA%E6%8A%95%E7%A5%A8-)

[点击前往查看更多](https://help.mytokenpocket.vip/hc/zh-cn/sections/360007395352-Tron-%E6%B3%A2%E5%9C%BA-%E9%92%B1%E5%8C%85%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)


### IOST钱包常见问题

1.[如何创建IOST账号？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037990432-%E5%A6%82%E4%BD%95%E5%88%9B%E5%BB%BAIOST%E8%B4%A6%E5%8F%B7-)

2.[如何把交易所的IOST提币到钱包账户？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037990332-%E5%A6%82%E4%BD%95%E6%8A%8A%E4%BA%A4%E6%98%93%E6%89%80%E7%9A%84IOST%E6%8F%90%E5%B8%81%E5%88%B0%E9%92%B1%E5%8C%85%E8%B4%A6%E6%88%B7-)

3.[如何导入之前的IOST账号？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360038358591-%E5%A6%82%E4%BD%95%E5%AF%BC%E5%85%A5%E4%B9%8B%E5%89%8D%E7%9A%84IOST%E8%B4%A6%E5%8F%B7-)

4.[如何进行IOST收款？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360040722751-IOST%E9%92%B1%E5%8C%85%E7%9A%84%E6%94%B6%E6%AC%BE)

5.[IOST钱包如何转账](https://help.mytokenpocket.vip/hc/zh-cn/articles/360040721791-IOST%E9%92%B1%E5%8C%85%E5%A6%82%E4%BD%95%E8%BD%AC%E8%B4%A6)

6.[IOST账号的资源是什么？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360038358491-IOST%E8%B4%A6%E5%8F%B7%E7%9A%84%E8%B5%84%E6%BA%90%E6%98%AF%E4%BB%80%E4%B9%88-)

7.[IOST怎么抵押/赎回资源？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037990292-IOST%E6%80%8E%E4%B9%88%E6%8A%B5%E6%8A%BC-%E8%B5%8E%E5%9B%9E%E8%B5%84%E6%BA%90-)

8.[如何玩IOST上的Dapp应用？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037990272-%E5%A6%82%E4%BD%95%E7%8E%A9IOST%E4%B8%8A%E7%9A%84Dapp%E5%BA%94%E7%94%A8-)

9.[如何进行IOST投票？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360038358451-%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8CIOST%E6%8A%95%E7%A5%A8-)

10.[如何查看IOST转账的详细区块记录？](https://help.mytokenpocket.vip/hc/zh-cn/articles/360037990072-%E5%A6%82%E4%BD%95%E6%9F%A5%E7%9C%8BIOST%E8%BD%AC%E8%B4%A6%E7%9A%84%E8%AF%A6%E7%BB%86%E5%8C%BA%E5%9D%97%E8%AE%B0%E5%BD%95-)

[点击前往查看更多](https://help.mytokenpocket.vip/hc/zh-cn/sections/360007631251-IOST-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)




## 区块链钱包知识自测


```
学习自检时间到了，以下有 100 道关于
区块链钱包的问题，你能答对吗？
```


<div class="ask-code">
<div>扫码自测</div>
<img src="https://tp-upload.cdn.bcebos.com/banner/tokenpocket-1591686643906.jpeg" width="250">
</div>

<!-- <img src="https://tp-statics.tokenpocket.pro/news/tokenpocket-1576125777304.png" width="250"> -->
<!-- ![](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576125777304.png) -->


**商务微信：laurali0815**

**公众号：** TokenPocket钱包

**Telegram：** https://t.me/tokenPocket_en

**Twitter：** https://twitter.com/TokenPocket_TP

**Medium：** https://medium.com/@tokenpocket.gm

**Facebook：** [http://www.facebook.com/TokenPocket/](http://www.facebook.com/TokenPocket/)

**Github：** https://github.com/TP-Lab

**Email ：** service@tokenpocket.pro


### 版权申明

#### 《区块链钱包从入门到精通》，又称为钱包小白书。由TokenPocket钱包联合创始人Marcus主编，内容涵盖钱包发展史、钱包功能及钱包分类等八大板块，是目前市面上最为详细的数字钱包科普资料之一。Marcus，毕业于华南理工大学，TokenPocket钱包联合创始人兼CMO，一年时间带领TokenPocket钱包从0发展到百万用户。原迅雷高级开发工程师，2019年被聘为韩国知名区块链投资机构 Hashed Labs 市场顾问。

##### 1.本文版权归TokenPocket所有。

##### 2.在征得作者同意的情况下，作品允许非盈利性引用，需要注明并请注明出处和作者，以尊重作者的劳动成果。

##### 3.出处：https://tp-lab.github.io/BlockchainGuideSeries/#/  作者：TokenPocket。

##### 4.未经允许，严禁转载。对非法转载者，TokenPocket和作/译者保留采用法律手段追究的权利。

##### 5.对于本文和本声明以及其修改权、更新权及最终解释权均属TokenPocket。

##### 6.以上声明的解释权归“TokenPocket”所有。
