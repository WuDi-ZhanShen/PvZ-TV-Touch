# PvZ-TV-Touch
逆向得到的安卓PvZ-TV版的Java源代码,并适配了触控操作。注意：只逆向了Java源代码，而不是整个游戏的源代码。

Android Studio Project by Reverse Engineering The Popcap Game "PvZ-TV" and Adapting Touch Controls. Note: Only the Java source code has been reverse-engineered, not the entire source code of the game.
# 如何使用这份源代码？ How to build this source code?  
下载release中的压缩包，解压并导入Android Studio，然后编译即可。 

Download the sourceCode.zip from the "release" section, and import it into Android Studio to build the project.
# 这份源代码有其他改动吗？ Have you made any modifications?
适配了高版本安卓系统，去除了一些不需要的代码和权限，加入了一些设置项。

Adapted for higher versions of Android system, removed unnecessary code and permissions, and added some new settings options.
# 还有什么缺陷？ What are the remaining flaws or defects?
1.花园工具使用后会自动变回水壶；(触控的缺陷)

2.冒险模式有三次关卡结束后会进入戴夫商店并和戴夫交谈，此时无法触控；(触控的缺陷)

3.路灯花照不透罐子；(游戏本身的缺陷)

4.模仿者变的植物不是灰色；(游戏本身的缺陷)

5.小游戏“坚不可摧”无法在开始游戏前的准备时期种植物；(游戏本身的缺陷)

6.图鉴界面最后一行的触控判定位置偏上；且图鉴界面的"查看植物"和"查看僵尸"按钮会持续起作用 (游戏本身的缺陷)



1.ZenGarden tools automatically revert back to the watering can after use. (Touchscreen issue)

2.In Adventure mode, after completing three levels, entering Dave's shop and interacting with Dave becomes unresponsive. (Touchscreen issue)

3.Plantern does not illuminate the vase. (Inherent game issue)

4.Imitator's transformed plants are not gray. (Inherent game issue)

5.In the mini-game "Last Stand", plants cannot be planted during the preparation phase before the game starts. (Inherent game issue)

6.The touchscreen detection for the last row in the Almanac interface is slightly off, and the "View Plant" and "View Zombie" buttons in the Almanac interface remain active continuously. (Inherent game issue)
