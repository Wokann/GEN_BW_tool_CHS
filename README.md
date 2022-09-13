@::::::::::::::::::::::::::::::::::::::::::::::::::@
|                                                  |
| 宝可梦GEN5存档工具by suloku '16-21  |
|                                                  |
@::::::::::::::::::::::::::::::::::::::::::::::::::@

由卧看微尘（Wokann）汉化。

源代码见此: https://github.com/suloku/BW_tool
汉化版源代码见此: https://github.com/Wokann/GEN_BW_tool_CHS

这是第 5 代游戏的多功能存档游戏编辑器。

当前特色功能:
_________________

黑白黑2白2通用：

* 连入之森编辑 (*见附注)
* 训练家信息及徽章编辑 (含黑白2劲敌名)
* 物品箱编辑
* 存档块导出/注入 (也可也说明/重写已知的加密块，例如连入之森数据块)
* 校验值确认/修正

仅黑白2:

* 隐藏洞穴和大量出现编辑
* 汇合大道编辑 (可导出导入顾客)**
* 钥匙系统编辑 (可解锁所有钥匙和更改游戏设置)
* 奖牌编辑：仍处在基本的编辑操作状态，但支持解锁所有奖牌(及设定获得时间).
* 记忆连接编辑：可以编辑训练家姓名，TID，SID。可以导出导入记忆连接存档块。可以从黑白1的存档导入姓名，TID，SID和名人堂数据。旗标目前仍待研究。
* 3DS连接编辑：这可以让你编辑3DS连接的数据，仅用于3DS的AR搜寻器。默认为合法模式，你只能设置AR搜寻器里存在的宝可梦和道具。所有模式，可以让你设置所有的宝可梦和道具。主要目的是允许AR搜寻器专属宝可梦（如三云灵兽形态）状态恢复接收而不需要依赖AR搜寻器。你也可以清除捕获旗标来让你的存档再次接收传说宝可梦。

**附带了4个顾客文件。


*关于连入之森编辑:

可以使用两种文件：phl文件（可以与pockestock和pikaedit协同的AREA区域文件；efdd文件（基本是解密的森林块，所以它包含了所有区域及森林设置）。附带了来自黑1的合法的efdd文件（其中包含若干梦世界宝可梦和PGL阿尔宙斯）；以及一个来自白2的合法efdd文件（包含一对事件宝可梦及9个梦世界宝可梦）。

最有趣的是“梦世界模拟器”，它带有些方便的按键可以处理梦世界区域，让你导入来自梦世界的宝可梦到连入之森。宝可梦仅限于梦世界存在的每个宝可梦允许选择它的招式槽位A，B，C***以及适用的性别 (注意5代只有雌性的宝可梦可以孵出带有隐藏特性的蛋)。

类似“梦世界模拟器”，有一个PGL促销 按钮，允许导入PGL配信的宝可梦。注意部分宝可梦只能在部分语言获得，在其它语言上接收会为非法。为方便起见，可以接收的语言直接列出来了。此外，这些宝可梦有固定性别和招式。

要明晰一下：所有通过梦世界和PGL按键导入的宝可梦，数据均和在线服务器接收的完全一致（除了区域外PGL宝可梦，因为编辑器没有区域过滤器）。


*** 梦世界招式
A: 等级提升招式
B: 遗传招式
C: 梦世界专属招式或遗传招式（视宝可梦而定）


未来可能的功能:
_________________

* 完成奖牌编辑和训练家记录：这些功能仍待研究，因为一些奖牌与游戏内的其他记录相关联。目标是使编辑尽可能合法，至少对于无法在获得的在线专属奖牌，及几乎不可能获得的奖牌（如30人庆典任务等等）。
* 记忆连接导入/编辑器（黑白2），可能从黑白1的存档中导入数据。


注意：有一个训练家记录按键，这是未来可能功能，并未锁定它以供发布。
注意2：存档可以拖拽放置来加载。


鸣谢：
__________

许多曾提供帮助的人我或许已记不清名字，但有那么几位无论如何也不会忘记的：提供了许多研究和信息的BlackShark，我用以参考的kaphotic的pkhex的源代码及其在projectpokemon论坛上的研究。