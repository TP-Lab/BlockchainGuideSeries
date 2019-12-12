## 区块链科普专题

# 区块链钱包

# 从入⻔到精通

Blockchain Wallet

Blockchain Guide Series

From Rookie to Master


### 目录

###### catalog

#### 01 区块链钱包发展史
###### The History of Blockchain Wallets


#### 02 区块链钱包分类
###### The Sorts of Blockchain Wallets

#### 03 区块链钱包基本知识点
###### The Basic Knowledge of Blockchain Wallets

#### 04 区块链钱包功能介绍
###### The Functions of Blockchain Wallets

#### 05 如何选择区块链钱包
###### How to Choose a Blockchain Wallet

#### 06 区块链钱包操作指南
###### The Directory of Blockchain Wallets

#### 07 区块链钱包知识自测
###### The Guide of Blockchain Wallets

#### 08 区块链钱包导航
###### The Test of Blockchain Wallet Knowledge


## 区块链钱包发展史

###### The History of Blockchain Wallets

```
说起数字货币，就离不开数字货币钱包。比特币已诞生10年，区块链也经历了1.0-3.0三个时期的迭代。
在这期间钱包由单资产钱包、单链钱包发展为多链多资产钱包，从单一的转账收款钱包，发展为区块链生态服务平台。
```


### 区块链1.0时期

**（ 2009 年-2013年）**

2009年，比特币主网上线，这个时期的区块链刚刚起步，作为一个巨大的分布式账本，比特币仅有简单的转账、记账功能。

最早期的钱包，主要作用就是用来存储比特币。<font color=#2980fe>也就是单资产钱包形态，一个钱包只能支持一种币种。</font>

2011年6月29日，比特币支付处理商BitPay推出了第一个用于智能手机的比特币电子钱包。同年7月6日，一个免费的比特币数字钱包App现身安卓应用商店，这是第一款与比特币相关的智能手机App。


### 区块链2.0时期

**（ 2014 年-2018年）**


2014 年，以太坊项目启动宣示着区块链进入2.0时代，智能合约开始运用于区块链。

智能合约就是一套不需要第三方的情况下还可以保证合同得到执行的计算机程序，任何人都可以基于此进行运算及开发应用层。

此时的钱包除了进行转账收款外，还能进行链上合约操作，但由于此时的区块链速度较为慢，钱包仅能进行非瞬时反应合约服务。


### 区块链3.0时期

**（ 2018 年-至今）**


2018 年区块链开始进入3.0时期，针对区块链2.0速度慢、高昂矿工费等问题进行优化，实现区块链的高并发、高可拓展等性能，而其中最为代表的便是EOS。

除了基础的存储转账功能外，还能与链上合约进行即时交互；钱包不再是简单的资产管理工具，更是一个公链生态服务平台；与此同时，单链钱包已无法满足用户需求，<font color=#2980fe>越来越多的钱包往多链方向发展</font>，比如TokenPocket，既支持EOS的资产，又支持比特币及以太坊上的资产。


现如今，钱包的功能也不再仅限于数字货币存储等功能，用户通过钱包可体验资产管理、资产交易、DApp、社交、资讯、行情等功能。

钱包已逐渐承担起它作为区块链世界入口的⻆色。


## 区块链钱包分类

######The Sorts of Blockchain Wallets

```
我们将从私钥的生成和私钥的存储两个维度对钱包进行分类。
```

### 私钥生成

**Generate the Key**

从私钥的生成，我们可以把钱包划分为，“非确定性钱包”、“确定性钱包”及“分层确定性钱包”，而其中“分层确定性钱包”是“确定性钱包”的加强版本。


**<font color=#2980fe>非确定性钱包</font>**

在钱包中生成的私钥之间没有任何关系，是相互独立的。

![非确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070497680.png "非确定性钱包")

**<font color=#2980fe>确定性钱包</font>**

私钥都是由一个“种子”通过算法生成，比如“助记词”就是种子的形式。通过这个方式生成的私钥，只要算法一致，私钥就可以保持前后一致；且一个种子可以派生出无限的私钥地址。

![确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070721576.png "确定性钱包")


**<font color=#2980fe>分层确定性钱包</font>**

是确定性钱包的加强版，为确定性钱包引入“主私钥”概念，即HD钱包。它的层级结构是，从主私钥生成的私钥，本身就可以成为一把主私钥，再通过上述方法生成一个确定性钱包。

![分层确定性钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576070849616.png "分层确定性钱包")


### 私钥存储

**Store the Key**

根据私钥的存储方式，即用户是否掌握了私钥，我们可以把钱包划分为，<font color=#2980fe>“中心化钱包”</font>及<font color=#2980fe>“去中心化钱包”</font>。

![钱包类别 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576071056328.png "钱包类别")


去中心化钱包，我们又可根据私钥存储过程中是否接触网络，划分为<font color=#2980fe>“冷钱包”</font>和<font color=#2980fe>“热钱包”</font>；

热钱包又可分为桌面钱包、手机钱包和网⻚钱包。
**<font color=#2980fe>冷钱包，冷即离线、断网，也就是说，私钥存储的位置不能被
网络所访问。例如纸钱包、脑钱包、硬件钱包等等。</font>**

======

![节点钱包 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576071528679.png "节点钱包")

根据区块链数据的维护方式和钱包的去中心化程度又可将钱包分为全节点钱包、轻节点钱包、中心化钱包。

全节点钱包大部分都属于桌面钱包，其中的代表有Bitcoin-Core核心钱包、Geth、Parity等等，此类钱包需要同步所有区块链数据，占用很大的存储空间，但可以实现完全去中心化。

而手机钱包和网⻚钱包大部分属于轻节点钱包，轻钱包依赖区块链网络中的其他全节点，仅同步与自己相关的交易数据，基本可以实现去中心化。

中心化钱包的交易数据不存储在区块链中，所有的数据均从服务商的服务器中获取；但是交易效率很高，可以实时到账，比如你在交易平台中注册的账号就是中心化钱包。


## 区块链钱包的基本知识点

######The Basic Knowledge of Blockchain Wallets

```
要学会使用区块链钱包，一定要掌握以下五个相关名词定义，即公钥、私钥、助记词、keystore、密码。
```

###<font color=#2980fe>公钥 ---- 锁</font>

+ 公钥=账号=转账地址，相当于你的银行卡号，公钥是可以对外随意公开的，没有任何风险。

###<font color=#2980fe>私钥 ---- 钥匙</font>

+ 私钥是由数字和大小写字母组成，不同区块链的私钥⻓度一般不一样。私钥=密码=身份认证，通过私钥可以推导出公钥。需要注意的是，一旦你的私钥丢失或遗忘，将无法再找回。

###<font color=#2980fe>助记词</font>

+ 由于私钥不方便记忆，因此出现了助记词。私钥可以由助记词通过算法算出来，一般情况下，助记词由一些单词组成，只要你记住这些单词，按照顺序在钱包中输入，就能恢复钱包并且进行任意操作。如果别人拿到了你的助记词，就相当于拿到了你的私钥，就可以对你的资产进行掌控。

###<font color=#2980fe>Keystore</font>

+ <font color=#2980fe>Keystore的本质是加密后的私钥，Keystore必须配合你的钱包密码来使用才有效。</font>keystore = 私钥/助记词 + 密码，keystore、私钥、助记词是所有钱包通用的，钱包服务商可能会因为产品设计原因，仅为用户提供其中一种或多种方式，但是如果存在同一方式在某钱包无法正常恢复，则该钱包可能存在一定的问题。

###<font color=#2980fe>密码</font>

+ 为了进一步增强安全性，大部分钱包会采取密码的方式对私钥做二次加密。每个钱包的加密方法和存储方式是不一样的。当你把私钥导入钱包后，你的每一次授权操作，都需要输入密码来解密以确保安全。


##钱包安全小贴士
######Tips for Security

```
1.公钥是可以曝光的，对你的资产安全无影响。
```

```
2.助记词、私钥、keystore一旦泄露，资产所有权将立刻被他人掌控，此时你需要立即转移资产到其他地址，原先的账户不再使用。
```

```
3.keystore泄露，不管密码有没有泄露，都存在他人掌控资产的⻛险，因此需要赶快把资产转移其他地址。
```

```
4.如果是EOSIO（包括EOS、BOS、ENU等）和IOST的账号私钥泄
露时，还可以采取更换新私钥的方式，阻止他人掌控自己的资产。
```

```
5. 在存储私钥、助记词时，我们都建议采用离线形式（手抄、打印等）进行数据备份，同时将备份好的内容妥善保管。对于keystore这样的信息，采用抄写进行备份是很不科学并且很容易出错的，所以用户可以将keystore存储为文件形式，然后可以将其存储在U盘中再妥善管理好U盘；其中，我们非常不建议您进行截屏、网络传输（QQ、微信）、云端存储等方式备份，这些方式都有可能遭遇黑客攻击，从而造成资产损失。
```

## 区块链钱包功能介绍

######The Functions of Blockchain Wallets

钱包是区块链的入口，拥有包含资产管理在内的丰富功能，可以满足用户各式各样的需求。

###创建区块链账号

区块链钱包的展现形式分为地址和账号，我们这里统称为账号；不同区块链的账号是不一样的，⻓度也可能不一样的。不同区块链账号的创建费用也是不一样的，例如以太坊、比特币的账号是免费的，但是EOS的账号是需要消耗一定的EOS创建的。

由于区块链账号的创建是通过算法生成的，过程十分复杂，钱包的存在就是帮助用户简化这些过程。例如在TokenPocket钱包中，注册一个ETH账号，只需要你设置一个不少于 8 位数的密码，并进行二次确认，立刻就能获得一个ETH账号。EOS账号是需要花费EOS才能创建的，为了降低用户的⻔槛，让没有EOS的新人也能快速拥有EOS账号，TokenPocket采取激活码创建账号的方式，用户创建EOS账号时，只需要购买一个激活码，由TP采取代付账号费用的形式，即可快速拥有EOS账号。

对于小白来说，掌握私钥或许太麻烦了，TokenPocket还为此设计了去中心化的手机号/邮箱注册EOS账号方式，这种方式支持用户在忘记私钥的时候通过TP找回，大大降低了用户使用钱包的难度。当然，为了满足不同层次用户的需求，TokenPocket还提供了冷钱包、观察钱包、批量创建、合约创建、好友创建等方式。


###数字资产管理
######Tips for Assets Management

<font color=#2980fe>数字资产主要指的是区块链上的各种代币（Token）</font>，钱包的存在极大的方便了用户对于自己所拥有的资产管理，主要包括转账、收款、查看资产详情、交易详情等，功能类似银行的APP，你可以看到自己当前拥有什么资产，数量多少，以及对你的资产进行转账等操作。

需要注意的是，不同区块链之间的资产是不能直接转账的，即你无法向以太坊账号转入比特币。

当前钱包支持的数字资产交易主要包括以下三种情况：币币兑换、交易所交易、OTC交易。

通过币币兑换，可以将不同区块链上的资产进行兑换，例如你可以将自己拥有的BTC（比特币）兑换成EOS，其背后则是通过多种方式实现撮合。

当前交易所有 3 种形态，分别是中心化交易所、去中心化交易所、 <font color=#2980fe>聚合交易所</font> 。中心化交易所常⻅的有火币、币安、OKEX等，去中心化交易所目前ETH上有IDEX，EOS上NewDex、鲸交所、DEXEOS等。

首先我们需要了解一下交易的过程，一般来说，用户先要把资产安全托管在某个地方，既资产安全的前提下可以用于交易。一旦有交易的需求，他便发布交易指令，这时就需要一个流动性充足的场所为用户找到合适的匹配，满足这个交易指令。在找到合适匹配后，买卖双方在安全的环境下进行交易，这时也需要在客观上加以一定的限制，防止一方欺诈或跳票。最后，当交易完成后，双方对交易进行结算清算，也就是根据这笔交易信息更新各自现有资产的价值。二者最大的不同就是，中心化交易所需要我们把币托管在交易所账户里，而去中心化交易所将币托管到我们自己的钱包中。这大大降低了交易所被盗或跑路导致用户资产流失的⻛险。通过智能合约完成的撮合交易和链上完成的结算清算，在提升透明度的同时，也大大减少了对中心媒介的依赖。

###数字资产交易

###### Assets Trading

<font color=#2980fe>聚合交易所聚集了所有交易所而形成一个交易平台,让用户随时随地跨平台交易,无需下载众多app。聚合交易所共享其他交易所的深度和其他交易所的交易对。例如你注册了聚合交易所账号后，你每次买卖BTC（比特币）时，你可以从不同的交易所当前BTC比特币的价格中挑选性价比最高的来进行交易。</font>

当前市面上去中心化的钱包都支持去中心化交易所，部分钱包支持聚合交易。如TokenPocket钱包预计将在 2019 年 12 月上线聚合交易所。OTC（Over The Counter）交易就是在交易所外，由第三方担保，客户点对点的交易方式。在区块链中的OTC，通常指的是场外用户之间法币与数字货币一对一的买卖交易。当前最大的OTC主要以交易所的OTC为主，但目前大部分钱包也接入了提供该项服务的第三方渠道商。例如TokenPocket接入了币买卖的OTC服务，用户使用TP钱包时，可以很方便的将自己手中的数字货币卖出，换成法币；或是使用法币购买数字货币。

###参与生态建设

###### Ecology Building

目前部分公链设计中，都激励生态中的用户积极参与公链生态建设。主要的形式有投票、公投、Staking等。以EOS为例，EOS总共有 21 个超级节点，用户通过将手中的EOS进行抵押后，最多可以投给 30 个节点，投票的目的在于让用户选出能为EOS生态发展与扩大贡献自己力量的节点。

公投指的是区块链生态中，参与者可以发起自己认为对社区有利的提案，并由整个区块链持币者进行投票，当投票数超过一定标准时，提案自动生效。公投的方式有利于社区用户积极参与区块链治理。

Staking中文名权益质押，目前部分公链采取Staking的形式来鼓励持币者质押token，如COSMOS质押可以使质押者获得一定的年化收益（以质押币结算），类似你在银行投了一个活期理财。

###体验DApp应用

###### Experience the DApp

目前大部分的钱包都可以支持在钱包中打开DApp，DApp是Decentralized Application的缩写，译为去中心化应用。

DApp是基于区块链底层技术进行开发的应用，目前DApp主要集中在以太坊和EOS、TRON三条区块链上。DApp与底层平台的关系，就好比APP与IOS和Android系统。

即是说EOS的DApp无法在ETH底层上运行，正如安卓的APP无法在iOS系统上运行。你可以在钱包中体验ETH上的去中心化金融
MakerDAO，体验在EOSRacing中开赛⻋赢取EOS奖励，也可以在IOST上的猎币矿池进行挖矿。目前一些大型游戏是以第三方
APP的形式存在，当体验这些APP形式的DApp时，你同样需要钱包作为登录和操作、交易授权的媒介。

![DApp商店 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576074058171.png "DApp商店")

目前TokenPocket支持EOS三国、EOSKnights、EOS加密骑士团、加密剑与魔法、CryptoLegends等多个热⻔游戏。并且为了免去用户体验DApp时，来回切换钱包的繁琐操作，TP研发了MiniWallet模式，用户开启MiniWallet模式后，仅需一次授权操作后，即可一直停留在游戏中进行娱乐。

###领取糖果奖励
######Claim Candy Airdrop

拥有钱包的好处是可以不定时获得糖果（指区块链上免费获得的Token）。市面上常⻅的糖果发放方式有：注册领取、持币空投、广告糖果、Airgrab、转账空投等方式。

**<font color=#2980fe>注册领取：</font>** 通常在项目前期推广时经常会有免费领糖果活动，只要在项目方的活动⻚面上注册并登记自己的区块链地址（如ETH、EOS账号等），等待项目方发放奖励后就能获得免费的糖果了。

**<font color=#2980fe>持币空投：</font>** 持币空投常⻅的有 2 种方式，一种是分叉币，例如BTC（比特币）分叉出BCH，所有分叉前持有BTC（比特币）的用户，根据BTC（比特币）持有量都会获得相应的BCH。另外一种是直接针对持币者进行另外一种Token的奖励发放，例如EOS上的第一个空投币ADD，在EOS主网上线时，就对全网账号进行了快照，然后对持有EOS的账号进行糖果发放。

**<font color=#2980fe>广告糖果：</font>** 当前很多项目为了宣传自己的产品，会给持币者发送小额的转账，并在转账信息里带上自己的广告

![糖果空投 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576073859331.png "糖果空投")

**<font color=#2980fe>Airgrab：</font>** 中文可以称为糖果抓手，这是一种EOS上糖果分发的方式，需要消耗用户的内存（每种代币大概需要0.25KB左右）。执行Airgrab后需要等待项目方空投。在TokenPocket钱包中，专⻔为Airgrab制作了一个信息整合⻚面【糖果抓手】，上面列出了当前可以领取的各个项目方的糖果情况，用户只需要点击【AirGrab】按钮，即可完成糖果申领操作。

![转账空投 示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576073996350.png "转账空投")

**<font color=#2980fe>转账空投：</font>** 转账空投是指用户向某个合约账号发送小额代币后，合约会把代币原路返回的同时，发送一定量的糖果给用户。较为出名的转账空投则如EIDOS，用户仅需向其合约账号发送0.0001EOS的代币，合约就会在返回0.0001EOS的同时，赠送其合约账号当前剩余EIDOS的0.01%

因为在钱包中是可以快速登录去中心化交易所，所以很多用户领取糖果后即可直接在交易所中卖出换成ETH、EOS、USDT等， **<font color=#2980fe>免费羊毛的感觉真棒。</font>**

###资产增值

###### Assets Investment


钱包天然就具有金融属性，当前钱包已经集合了包括矿池、理财、挖矿、项目投资等多种金融工具与功能，可以满足用户资产增值的需求。

<font color=#2980fe>矿池： </font>当前挖矿主要是POW 挖矿与POS 挖矿这 2 种方式，其中PoS还可以细分出DPoS挖矿。PoW就是算力挖矿，也是我们熟悉的BTC（比特币）挖矿，目前钱包的矿池基本上是以PoS挖矿为主。PoS（Proof of Stake）挖矿是模仿 PoW 算力挖矿，持币人可以将代币抵押给验证人节点，来获得奖励分红。


以TokenPocket的BOS矿池为例，矿池收益主要来源投票矿池的节点收益和REX资源收益。REX是BOS链上的BOS持有者参与的一个CPU与NET资源租赁市场，参与者可以通过买卖REX池中的REX来借出或收回他们的现有资源，并以此来赚取收益。在钱包参与矿池非常简单，只需要在矿池⻚面，选择需要抵押的Token数量，矿池奖励将会按照规则定时发送到钱包账号中。

<font color=#2980fe>理财： </font>钱包里的理财产品与传统理财产品十分相似，唯一不同的是结算的方式。通常会约定一个预估收益率，用户用Token购买该理财产品后，根据约定的结算日期进行定期结算，到期可以取回或续约。TokenPocket将于 12 月上线USDT理财产品，预计年化12%，限量发售，感兴趣的用户可以关注我们的公众号等消息渠道。

<font color=#2980fe>挖矿： </font>挖矿以DApp挖矿为主，钱包中集合了一些DApp矿机产品，使用矿机可以便捷快速的获得想挖的Token。以最近大火的EIDOS为例，TokenPocket开发的EIDOS矿机可以帮助用户实现自动转账挖矿。这些挖出来的Token可以拿去交易所卖出换成EOS从而获取收益。

<font color=#2980fe>项目投资： </font>以⻁符钱包的HOO LABS为例，你可以在上面使用USDT支持项目，并以支持USDT的数量按照一定比例获得项目的Token。

###社交

###### Social

部分区块链钱包还拥有社交功能，你可以在钱包里跟其他用户进行沟通与交流。如TokenPocket的聊天频道，你可以加入不同的群，与群内成员自由交谈。并且还可以在聊天群里收发数字货币红包。

以社交作为主打功能的钱包Sense.Chat，允许你在APP上与其他成员自由聊天，所有的聊天信息都是加密的，只有你和联系人之间才能解密信息。此外MIXIN也是一个以聊天为主要功能的钱包。

Trybe是一个由数字货币激励的社交网络和媒体发布社区，用户通过创建精美的内容，对他人的内容进行评级或邀请朋友，都可以获得Trybe送出的数字货币！


###硬件钱包配套管理工具

###### Hardware wallet Tool kit

硬件钱包通常会搭配一个软件钱包作为管理工具。硬件钱包厂商如Ledger、Trezor、库神、YubiKey等，都有研发自己配套的软件钱包。

同样的，软件钱包厂商也会与硬件钱包厂商合作，开发自己产品专属的硬件钱包，如比特派的硬件钱包比特盾、imToken的imKey等。

###区块链资讯获取
######Access the Blockchain News

![资讯示意图](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576074428714.png "资讯")


绝大多数钱包用户都有交易需求，因此通常钱包都会把Token行情融入到产品中。除此外，还会把快讯、文章、甚至项目推特等这些内容模块加到产品中。

以TokenPocket钱包为例，TP钱包为去中心化交易所的Token行情搭建了专属的⻚面，用户无须进入交易所，也可以快速了解当天的价格，并做了快速跳转交易所的功能。

与其他区块链媒体不同的是，TokenPocket快讯、文章方面则主要以当前钱包支持的区块链相关内容为主，更有针对性。

## 如何选择区块链钱包

######How to Choose a Blockchain Wallet

```
首先我们需要了解中心化钱包和去心化钱包区别，再结合自身需求进行选择。
```


## 如何选择区块链钱包

```
How to Choose a Blockchain Wallet
```

| **中心化钱包**                                               | **去中心化钱包**                                             |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 私钥由平台方掌控                                             | 私钥由用户掌控                                               |
| 资产存储在平台方的钱包                                       | 资产存储在用户的钱包                                         |
| 密码可找回                                                   | 密码不可找回                                                 |
| 转账需要平台审核                                             | 转账不需要平台审核                                           |
| 中心化账号在钱包平台不可用                                   | 去中心化账号在其他钱包通用                                   |
| 平台内部转账无手续费，资产提现有手续费                       | 资产转账仅需支付区块链网络费用                               |
| 平台丢币风险来源：平台方钱包被黑客攻击、服务器被攻击、运营商倒闭（钱包服务关闭）、运营商作弊 | 钱包丢币风险来源：私钥泄漏与遗忘、私钥未备份、安装钱包的设备丢失（手机、电脑）、安装了木马钱包 |


## 区块链钱包导航

######The Directory of Blockchain Wallet


**去中心化钱包**

```
TokenPocket
https://www.tokenpocket.pro/
```

```
huobi wallet
https://www.huobiwallet.com/
```

```
AToken
https://www.atoken.com/
```

```
BPEAL Wallet
https://www.bepal.pro/
```

```
Starteos
https://www.starteos.io/#/
```

```
Bitkeep
https://www.bitkeep.com/
```

```
Meetone
https://meet.one/

```

```
Tronlink
https://www.tronlink.org/

```

```
Lynx
https://lynxwallet.io/

```

```
scatter
https://get-scatter.com/

```

```
matamast
https://metamask.io/

```

```
ENJIN wallet
https://enjin.io/products/wallet

```

```
jaxx wallet
https://jaxx.io/

```

```
HB Wallet
https://www.hb-wallet.com/

```

```
kcash
https://www.kcash.com/

```

```
35

```

```
bitpie
https://bitpie.com/

```

```
Hyperpay
http://www.hyperpay.tech/

```

```
Trust Wallet
https://www.trustwallet.com/

```

```
imToken
https://token.im/

```

```
Conibase wallet
https://www.coinbase.com/

```

**去中心化钱包**

```
Uphold
https://uphold.com/

```

**硬件钱包**

```
Ledger
https://www.ledger.com/

```

```
Trezor
https://www.trezor.io/

```

```
keep key
https://shapeshift.io/keepkey/

```

```
库神(ColdLar）
https://www.coldlar.com/

```

```
比特护盾（BITHD)
https://bithd.com/

```

```
imKey
https://imkey.im/?locale=zh-cn

```

```
keep key
https://shapeshift.io/keepkey/

```

```
库神(ColdLar）
https://www.coldlar.com/

```

```
比特护盾（BITHD)
https://bithd.com/

```

```
imKey
https://imkey.im/

```

```
Cobo金库
https://cobo.com/

```

```
BEPAL Pro S

```

```
华特钱包
https://www.orientwalt.com/

```

**中心化&去中心化**

```
Cobo
https://cobo.com/

```

```
库神
https://www.coldlar.com/

```

```
keep key
https://shapeshift.io/keepkey/

```

```
⻁符
https://hoo.com/ 36

```

```
Edge
https://edge.app/

```

```
Renrenbit
https://www.renrenbit.com/

```

```
math wallet
http://www.mathwallet.org/cn/

```

```
币信
https://bixin.com/

```

```
https://www.bepal.pro

```

```
37

```

## 区块链钱包操作指南

###### The Guide of Blockchain Wallets

```
以下问题均发布在TokenPocket钱包
官网帮助中心

```

```
网址：https://help.mytokenpocket.vip/hc/zh-cn

```

![二维码](https://tp-statics.tokenpocket.pro/news/tokenpocket-1576074939866.png)


**BTC比特币钱包常⻅问题**

```
1 .如何创建BTC比特币钱包
2 .如何备份BTC比特币私钥
3 .BTC比特币私钥丢了怎么办
4 .如何修改BTC比特币钱包密码
5 .BTC比特币钱包密码丢了怎么办
6 .如何删除BTC比特币钱包
7 .如何将BTC比特币私钥导入钱包
8 .如何用钱包把BTC比特币转账到交易所
9 .如何设置BTC比特币矿工费
10 .BTC比特币转账慢可以加速吗
11 .BTC比特币私钥可以修改吗
12 .通过BTC比特币地址可以查询该地址的余额吗
13 .如何把BTC比特币从交易所提到自己的钱包
14 .如何在链上查询某笔BTC比特币交易是否成功
15 .BTC比特币转账为什么要支付矿工费
16 .去哪可以把我的比特币BTC比特币换成钱
17 .我在钱包里面可以直接买比特币吗
18 .BTC转账为什么老是失败
19 .我可以把我的比特币在钱包里面兑换成EOS吗？
20 .BTC闪兑的手续费是多少？
21 .如何同时给多个BTC地址转账？
22 .tp钱包可以自动归集比特币吗？
23 .我币已经转出去了，对方说没有收到怎么办？
24 .我可以创建多个BTC地址吗
25 .TokenPocket钱包里面最多可以创建多少个比特币地址？
26 .手抄的备份老是丢，我可以不备份BTC私钥吗？
27 .usdt可以转账到我的比特币地址吗？
28 .为什么我的usdt要转账到比特币地址会提示地址错误？
29 .比特币BTC转账为什么手续费这么高
30 .我BTC转账矿工费给的挺高的，为什么几个小时了还没成功？
31 .什么是BTC隔离⻅证？
32 .如何导出BTC私钥？
33 .我矿工费最低可以给多少能够转账成功
34 .BTC比特币转账失败会扣矿工费吗
35 .BTC比特币地址为什么不能添加币种
36 .BTC比特币可以拿来玩dapp吗
37 .BTC比特币的最小单位是什么
38 .BTC比特币怎么转到闪电网络
39 .闪电网络的比特币怎么转到tp钱包
40 .BTC比特币地址是多少位的‘
41 .BTC比特币的地址开头必须是数字吗
42 .TokenPocket钱包里面的价格是根据哪里的价格显示的？
43 .我把比特币BTC存到TokenPocket钱包会不会给我利息？
44 .我可以用TokenPocket钱包挖BTC比特币吗？
45 .比特币BTC网络上面都有什么币
46 .我存在TokenPocket钱包的比特币会不会丢失？钱包会不会盗取我的
BTC？
47 .我断网的时候别人给我转BTC比特币我是不是能收到？
48 .TokenPocket钱包里面有比特币浏览器吗？怎么使用？
49 .怎么更换BTC比特币钱包名称？

```

**BTC比特币钱包常⻅问题**

```
1. 怎样创建ETH钱包
2. 怎样找回之前的ETH钱包
3. 怎样购买ETH资产
4. 怎样充值ETH到钱包
5. 钱包里的ETH如何卖出变现
6. 怎么用TokenPocket钱包玩dapp
7. 怎么向他人转账/收取ETH？
8. ETH转账的手续费和gas费什么意思？
9. 玩ETH dapp要考虑CPU不足的问题吗
11.如何从TokenPocket钱包创建的ETH钱包？创建的ETH地址可以转移到其他钱包吗？
11. 如何往钱包充值基于ETH公链的其他币种？
12.ETH转账记录怎么看？
13.ETH转账一般多久到账？ETH手续费怎么算？
14. ETH转账转错账号怎么办？
15. 如何用闪兑功能进行EOS/ETH/IOST兑换
16. ETH钱包无法绑定手机号会丢失或者被盗吗？
17. TokenPocket钱包有无便捷交易ETH的方式？
18. 玩ETH dapp赚取的币如何进钱包？
19.ETH交易在国内合法吗？
20.ETH、BTC比特币、BCH、LTC等这些币有什么关系吗？
21.ETH2.0/分叉是什么意思？
22.ETH会归 0 吗？
23.手机可以挖ETH吗？
24.ETH可以成为法定货币吗？
25.一个ETH值多少钱？

```

**ETH钱包常⻅问题**

```
1.如何获得EOS柚子？
2.如何从交易所提取EOS到钱包
3.如何注册EOS账号
4.如何进行EOS的转账、收款
5.如何玩 EOS上的DApp
6.如何进行EOS理财
7.如何进行EOS资源抵押等操作
8.如何修改EOS钱包密码
9.EOS上，什么是owner权限，什么是active权限
10.如何修改EOS钱包的owner，active权限？
11.EOS上有没有多签？多签有何作用，如何使用？
12.EOS的资源又哪些？RAM（内存） cpu（网络资源） net（计算资源）是什么意思？
13.没有CPU的时候怎么办？TokenPokcet的顺畅模式如何使用？
14.商店版为什么没有dapp了，怎么能进入？
15.pro版本过期了该怎么办
16.手机邮箱注册的eos账号不能用手机或者邮箱登陆了？
17.过了 24 小时了怎么还是显示我的cpu可用为 0 ？
18.改抵押多少个eos才能够正常操作？
19.怎么切换EOS节点 ，什么时候该换节点，用哪个节点合适？
20.怎么添加EOS白名单，白名单有什么作用？
21.怎么使用EOS浏览器，eos的浏览器哪个好用？
22.什么情况下会消耗ram？消耗的ram去哪里了 ？什么地方可以查到
23.dapp是什么？EOS 上的DApp有哪些？
24.TokenPocket商店版和pro版本之间怎么做数据迁移?
25.不小心把TokenPocketAPP卸载了 ,私钥也没保存能否找回?
26.cpu是怎么样的释放机制，cpu的价格是怎么样的机制?
27.TokenPocket钱包内领取到的空投币怎么交易？
28.闪兑功能怎么使用，有啥便利的？
29.eos账号的格式是怎么样的？
30.eos的短账号怎么注册？.tp短号如何注册？
31.怎么方便快捷的购买到eos？
32.怎么使用eos购买到eos链上的其他dapp代币？
33.eos转账有手续费吗
34.如何备份EOS私钥
35.EOS私钥和助记词有啥区别
36.为什么不能使用助记词导入eos账号
37.为啥eos不能导出助记词
38.EOS观察模式怎么使用
39.TokenPocket钱包，私钥导入和手机/邮箱登陆有啥不同
40.冷钱包怎么使用？
41.怎么参与EOS主网的投票，EOS投票有收益吗，投票安全吗？
42.怎么购买rex
43.EOS购买REX的收益高吗
44.EOS上怎么购买ram，cpu，net？
45.EOS内存（RAM）的价格怎么是变动的
46.把eos放在TokenPocket钱包安全吗？要是TokenPocket钱包跑路了该怎么办？
47.我把eos转错账号了怎么办？
48.EOS转账时要我填写memo，memo是什么意思，钱包里哪里找memo？
49.TokenPocket钱包能放些什么币？
50.TokenPocket钱包里的币能快速的变现吗？
51.我进行EOS转账时，cpu ram net提示不足了 是啥意思？该怎么办？
52.为什么我赎回的eos没有立刻到账？
53.怎么在REX中租cpu和net？
54.TokenPocket钱包安全吗？会保存我的私钥吗？
55.把EOS放在TokenPocket钱包，可以获得空投？
56.为什么创建eos账号需要花钱，这个钱是谁拿了？
57.EOS转账了怎么确定对方是否收到了？
58.如何从交易所提币到钱包，如何从钱包充值到交易所？
59.我收到了某个币为什么钱包没有显示？
60.从哪里看自己的eos地址，转账的时候是用公钥还是用eos账户名？
61.EOS扫码转账的时候为什么扫码扫不出？
62.TokenPocket钱包可以导入多个eos账号吗？上限是多少？
The Guide of Blockchain Wallets区块链钱包操作指南

```

## 区块链钱包知识自测

######The Test of Blockchain Wallet Knowledge

```
学习自检时间到了，以下有 100 道关于
区块链钱包的问题，你能答对吗？

```


```
扫码自测

```

**商务微信：laurali0815**

**公众号：** TokenPocket钱包

**Telegram：** https://t.me/tokenPocket_en

**Twitter：** https://twitter.com/TokenPocket_TP

**Medium：** https://medium.com/@tokenpocket.gm

**Facebook：** [http://www.facebook.com/TokenPocket/](http://www.facebook.com/TokenPocket/)

**Github：** https://github.com/TP-Lab

**Email ：** service@tokenpocket.pro

```
更多TokenPocket信息

```
