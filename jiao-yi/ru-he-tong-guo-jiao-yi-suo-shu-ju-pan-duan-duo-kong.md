# 如何通过交易所数据判断多空

我一直都很奇怪币安合约的交易数据为什么要整“大户多空比”、“多空人数比”这种弯弯绕绕的东西，而不是直接告诉我多头比较多还是空头多。结果一问 GPT，原来是我无知了。

合约的多头与空头必须 1:1 成对存在，如果某个时刻市场上有 100 张多头，那就一定有 100 张空头。

那怎么看到多空方向呢？

我们需要结合币安里的多个交易数据来看：

首先【多空人数比值】这个指标很可能是反指，韭菜几乎总是站在行情的对立面。

而相比于【大户多空比（按账户数统计）】，【大户多空比（按持仓量统计）】才是暴露了大户们真实的仓位。

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

正所谓“多军的敌人是多军”，大家都抄底做多，那就会有更多饿狼盯上这块肥肉。

如果你只是看到这 3 个指标都是多头而抄底做多，很可能就被埋了，我们需要更多其他的数据。

下一个是【合约持仓量】，分为按币计算的持仓总数量和按 U 计算的持仓总价值。

你也可以在 K 线图上找到这个指标，O.I. 是指未平仓的币数量，O.I.NV 是指未平仓的 U 价值。

持仓币数量上涨，趋势会延续。持仓币数量下降，趋势减弱。 举几个例子：

价格上涨 + OI 上升 → 多头主动开仓，行情健康\
价格上涨 + OI 下跌 → 空头在被挤爆（强制平仓），假上涨\
价格下跌 + OI 上升 → 空头主动开仓，跌势真实\
价格下跌 + OI 下跌 → 多头被逼平仓，恐慌性踩踏

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

【合约主动买量】是短线方向性最准确的指标，因为它看的是谁主动吃掉挂单，谁能真实反映当下的力量是多还是空。

主动买入量更多，看多力量强；\
主动卖出量更多，看空力量强。

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

最后一个是【基差】，如果合约价格大于现货价格，说明多头强势，反之则是空头强势。

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

我们散户想要赚钱，只有利用好身边的一切数据。作为全球最大的交易所，币安提供的数据还是很有参考意义的！

如果你还没有注册币安，可以使用我的邀请链接或邀请码注册省 20% 手续费，不填就没有了\
https://binance.com/join?ref=SRXT5KUM\
邀请码 SRXT5KUM 合约邀请码 416378774

链上 Web3 钱包省手续费：\
https://web3.binance.com/referral?ref=RP3AEJ2M\
邀请码 RP3AEJ2M （9 折）

一个比较方便判断“多空主力到底是谁更强”的指标是累计成交量差 CVD （Cumulative Volume Delta）

也就是主动买入成交量−主动卖出成交量的累计值

如果主动买的人多，CVD 就往上走；主动卖的人多，CVD 就往下走

你可以在&#x20;@coinglass\_com&#x20;的 K 线中免费使用这两个指标，分别是合约 CVD 和现货 CVD

如果价格在跌，但 CVD 不再下降 → 主动卖压停止 → 别人可能在悄悄吸筹

如果价格在涨，但 CVD 不涨 → 说明主动买盘弱 → 很可能是拉盘、诱多。

相比于合约 CVD 体现杠杆的情绪方向，现货 CVD 更能说明有人在真金白银地买入和卖出

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>



