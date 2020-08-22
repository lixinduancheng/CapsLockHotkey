
## 前言 ##
&emsp;&emsp;CapsLockPlusMix是根据CapsLockPlus[（作者版本）](https://github.com/PatrickShieh/CapsLockPlus)再次修改，混合了CapsLock+[（原作者版本）](https://github.com/wo52616111/capslock-plus)中的部分取消功能，添加了无面板的谷歌翻译。在两位作者的布局基础上尽量保持原布局的同时进行了优化，以适合自己日常使用。布局参考下面按键说明（如布局图片挂了可用浏览器查看文件hotkey_layout.html，或者在compiled文件夹查看图片)。如果是经常用键盘输入文字（如程序员），相信你在半天时间就能完全上手。<br/>
&emsp;&emsp;感谢CapsLock+开源这款工具， 2020-04-25作者重新更新了，但是新的布局很不友好，交流了一下，作者说有时间了会继续优化，可以关注并打赏原作者[（开源作者）](https://github.com/wo52616111/capslock-plus)。

&emsp;&emsp;如CapsLockPlus作者所说：本人是个键盘党，还是个程序猿，非常不喜欢敲代码敲得嗨时，还要去碰鼠标、右手移动一段距离去操作方向键，删除键等等。噢，对了，还很讨厌Ctrl键，因为使用Ctrl组合键时，左手要离开键盘一段距离，神烦。试想下，双手不用离开字母区，是不是很爽，嘿嘿。



>**CapsLockPlusMix：[下载地址](https://github.com/zszq/CapsLockPlusMix/releases/tag/v1.0.0)**



**已知可能会出现的问题：**<br/>
  1、ctrl + v 进行粘贴时会出现 ctrl不起作用，只有v键起作用了。 解决方法：删除 v 输出内容重新粘贴就好了，或者用软件带的 capslock + v 进行粘贴。<br/>
  2、自带大小写切换失效。 解决方法：可以用 shift + capslock 进行切换<br/>
  3、**启动之后不报错按键没有任何反应，请查看360等安全软件是否拦截了模拟按键**


**以下内容引用CapsLockPlus作者的介绍页面，只对更新部分作出说明。**

## 概述 ##

CapslockPlus是一个加强 Capslock 键的功能，以提高效率的工具。让你拥有更多的组合键，例如：

- CapsLock + 全键
- CapsLock + Alt + 全键
- CapsLock + Shift + 全键
- CapsLock + Ctrl + 全键



## 版本对比 ##

>CapsLock按键省略为Caps，Key为各种按键，下面对比的是大功能模块，后面再详细介绍各种小功能，QBar，QWeb，QSearch不太喜欢，所以没加上（已加上并更新到原作者最新版本），但是原来的代码还在，想要的话自己改下。

功能| CapsLock+（原版） | CapsLockPlus（新版） | CapsLockPlusMix（自用版） 
:-:                 | :-:   | :-: |:-:                 
Caps + Key          | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font> 
Caps + Alt + Key    | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font> 
Caps + Shift + Key  | <font color="#dd0000">✘</font>     | <font color="#00dd00">✔</font>| <font color="#00dd00">✔</font> 
Caps + Ctrl + Key   | <font color="#dd0000">✘</font>     | <font color="#00dd00">✔</font>| <font color="#00dd00">✔</font> 
TabScript           | TabScript     | TabSnippet| TabSnippet 
WinBind             | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font>| <font color="#00dd00">✔</font> 
QBar                | <font color="#00dd00">✔</font>     | <font color="#dd0000">✔</font>| <font color="#00dd00">✔</font>（原作者最新版） 
TransplatePanel     | <font color="#00dd00">✔</font>     | <font color="#00dd00">✔</font>| <font color="#00dd00">✔</font> （添加谷歌翻译国内版） 
DAAS                | <font color="#dd0000">✘</font>     | <font color="#00dd00">✔</font>| <font color="#00dd00">✔</font> 



## 按键说明 ##
#### 1. Caps + Key ####
>以下省略了CapsLock键，默认是要加上的，未设置功能键的可自行设置。
>
![](https://i.imgur.com/UJONhYR.png)

**1.1 CapsLock + 鼠标**

按键| 功能说明
:-:| :-:
鼠标左键|✘
鼠标中键|✘
鼠标右键|✘
鼠标滚轮向前|音量加
鼠标滚轮向后|音量减

#### 2. Caps + Alt + Key
>以下省略了CapsLock键，默认是要加上的，未设置功能键的可自行设置。
>
![](https://i.imgur.com/nfoWpR6.png)

**2.1 CapsLock + Alt + 鼠标**

按键| 功能说明
:-:| :-:
鼠标左键|双显示器有效，将当前软件移动到另外显示器
鼠标中键|记录当前鼠标灵敏度(Dpi)
鼠标右键|✘
鼠标滚轮向前|鼠标灵敏度(Dpi)增加
鼠标滚轮向后|鼠标灵敏度(Dpi)减少

#### 3. Caps + Shift + Key
>以下省略了CapsLock键，默认是要加上的，未设置功能键的可自行设置。
>
![](https://i.imgur.com/on4rfRq.png)

**3.1 CapsLock + Shift + 鼠标**

按键| 功能说明
:-:| :-:
鼠标左键|显示/关闭 AutohotKey窗口信息
鼠标中键|✘
鼠标右键|✘
鼠标滚轮向前|✘
鼠标滚轮向后|✘

#### 4. Caps + Ctrl + Key
>以下省略了CapsLock键，默认是要加上的，未设置功能键的可自行设置。
>
![](https://i.imgur.com/4RUEasF.png)

**4.1 CapsLock + Ctrl + 鼠标**

按键| 功能说明
:-:| :-:
鼠标左键|✘
鼠标中键|记录当前鼠标灵敏度(Dpi)
鼠标右键|✘
鼠标滚轮向前|✘
鼠标滚轮向后|✘

## TabSnippet 热字符串 ##
#### 按键
    CapsLock + Tab

#### 说明
>举个例子，在CapsLockPlusSettings.ini文件的[TabHotString]段下有这么一条设置：email=123456789@abc.com，那么在任意能输入文字的地方输入：asdfghjklemail，按下Capslock+Tab，就会变成asdfghjkl123456789@abc.com，有点像IDE的代码段功能



## WinBind ##

#### 如何绑定
    绑定窗口:CapsLock + Alt + (`或1~9)

>关于绑定:原版有3种模式，此版本有4模式，多了1种，下面做介绍：
<ul>
  <li>模式1：单击，绑定当前激活的窗口到相应按键；</li>
  <li>模式2：双击，追加绑定当前激活的窗口到相应按键；</li>
  <li>模式3：三击，绑定当前激活的窗口所属程序所拥有的所有窗口到相应按键;</li>
  <li>模式4：四击，绑定当前激活的窗口，与相应按键并列窗口，即同时打开同时隐藏；</li>
</ul>

#### 如何激活
    激活窗口:CapsLock + (`或1~9)
>激活/最小化绑定在该按键的窗口

#### 说明
    关于绑定
>1.模式1和模式3会覆盖当前按键上已有的绑定窗口;<br/>
>2.模式2绑定在按键现有模式是模式1或模式2时会追加窗口，是模式3时不追加，而会覆盖原绑定设置，绑定当前激活窗口（与模式1效果一样）;<br/>
>3.模式2操作示例：<br/>
>&emsp;a.窗口A处于最前的情况下，依次按下CapslockAlt不放，再按两次1；<br/>
>&emsp;b.激活窗口B，同样操作；<br/>
>&emsp;c.激活窗口C，同样操作；<br/>
>&emsp;d.按下Capslock不放，（多次）按下1来在A,B,C三个窗口之间实现类似Alt+Tab的窗口切换。<br/>
>4.模式3只要在需要绑定的程序的其中一个窗口做类似模式2的操作（需要三击）即可绑定该程序所有窗口（包括绑定操作过后才打开的）。<br/>
>5.模式2原有的绑定窗口被关闭至只剩下1个窗口时，将自动转换成模式1绑定（可以激活 / 最小化窗口）<br/>
>6.模式4只有在模式1，2和4情况下才有效。<br/>

    关于窗口激活/最小化
>1.模式1下，在原窗口不存在时，激活动作会自动绑定窗口所属程序的另一个窗口;<br/>
>2.模式1和模式3下，在原绑定窗口所属程序未启动时，激活动作将启动该程序;<br/>
>3.模式2和模式3下，多窗口中，最近使用本功能激活的窗口在下次使用本功能时会优先激活;<br/>
>4.绑定的窗口只有一个时，模式1和模式3会激活 / 最小化该窗口，模式2会自动转换成模式1;<br/>
>5.模式4，窗口A、B、C和D绑定按键1，当激活按键1时，窗口A、B、C和D同时激活;<br/>

## DAAS ##
    生成应用快捷键配置文件 CapsLock + F9
#### 说明
>DAAS:动态适配应用快捷键(Dynamic Adaptation Application Shortcuts)，假如说对应用A配置快捷键Caps+A，对应用B配置快捷键Caps+A，当处于应用A下则执行应用A的快捷键，处于应用B则执行应用B的快捷键，当既不处于应用A，也不处于应用B的情况下，则执行默认的快捷键.

#### 配置软件快捷键
>a.打开应用A，在应用A下执行CapsLock+F9，成功时会弹窗提示配置成功。<br/>
>b.到根目录下找到AllKeys文件夹，这里存放所有应用的配置文件，此时找到对应的配置文件，例如A.ini。<br/>
>c.[FileInfos]下的内容切勿修改，在[Keys]下添加相应的快捷键配置即可，例:<br/>
>&emsp;&emsp;找到同级目录下的userAHK文件夹，可在UserKeySet里设置功能函数，如函数名userKeyFunc_IDEDeleteLine，然后回到你的应用配置文件里，在[Keys]下添加，caps_d=userKeyFunc_IDEDeleteLine保存即可，Caps+F11重启。


## 如何自行设置全局的按键
>在CapsLockPlusSettings.ini里[Keys]设置，请对照 CapsLockPlussettingsDemo.ini 来配置相关设置，里面说的很详细
