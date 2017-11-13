﻿<center>  
<font size=6><学士之路>
</font size>
</center>
<center>  
<font size=10>需求规格说明书
</center>

<br/>

<br/>

<br/>

<br/>
<br/>
<center>  
<font size=6>作者：<u>  ___Dipper___    </u>

<font size=6>完成日期：<u>  ___2017.10.20___    </u>
</center>


<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>







<center>  
<font size=6>修订历史记录
</center>





<table width="700" height="100" border="1" align="center">
  <tr align="center" valign="middle">
    <td> 日期</td>
    <td>版本</td>
    <td>说明</td>
     <td>作者</td>
  </tr>
  <tr align="center" valign="middle">
    <td>2017.10.20</td>
    <td>v1.0.0</td>
    <td>第一个版本，完成了基础内容的细化</td>
    <td>Dipper</td>
  </tr>
  <tr align="center" valign="middle">
    <td>2017.10.26</td>
    <td>v1.1.0</td>
    <td>删除性能需求，修正用例图，修改部分验收标准为表格形式</td>
    <td>Dipper</td>
  </tr>
   <tr align="center" valign="middle">
    <td>2017.10.27</td>
    <td>v1.2.0</td>
    <td>添加了团队项目时间计划，调整了时间安排</td>
    <td>Dipper</td>
  </tr>
</table>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>




#目录
[TOC]

<br/>

<br/>

<br/>

<br/>




## 1.引言
-------------------------------------------------------------
<br/>

### 1.1 编写目的

&emsp; &emsp;该文档首先给出项目的整体结构和功能结构的概貌，试图从总体架构上给出整个系统的轮廓。同时对功能需求、性能需求进行详细的描述，以便于用户、开发人员进行理解和交流，反映出用户问题的结构，可以作为软件工作开发的基础依据以及确认测试和验收的依据。

<br/>

### 1.2 项目背景

*	软件名称：学士之路
*	项目开发者：福州大学软件工程实践Dipper小组

<br/>

### 1.3 预期的读者和阅读建议
- （1）项目经理：项目经理可以根据该文档了解产品的功能，并据此进行系统设计、项目管理。
- （2）设计员：对需求进行分析，并设计出系统，包括数据库的设计。
- （3）程序员：了解系统功能，编写《用户手册》。
- （4）测试员：根据本文档编写测试用例，并对软件产品进行功能性和非功能性测试。
- （5）用户：了解预期产品的功能和性能，并与分析人员一起对整个需求进行讨论和协商。
在阅读本文档时，首先要了解产品的功能概貌，然后可以根据自身的需要对每一功能进行适当的了解。


### 1.4 项目范围

&emsp; &emsp;本次待开发的软件为学士之路，该软件为模拟大学生活的养成类游戏。对于即将上大学的新生，可以提前体验真正的大学生活是什么样的，并从中了解面对部门工作和学习的冲突时该如何处理较为妥当，以及自己的大学生活怎么过才能更有意义有一个提前的思考。对于老生则是通过这款游戏可以回忆起自己大学生活的点点滴滴。

### 1.5参考文献

[1]GB-T8567-2006, 《计算机软件文档编制规范》[S]

<br/>



## 2. 项目概述
-------------------------------------------------------------

<br/>

### 2.1产品描述
&emsp; &emsp;“学士之路”是基于Android平台的一款app养成类游戏，应用了unity 3D游戏引擎。游戏内容是模拟大学四年的学习生活，玩家可以通过游戏来了解大学的学习生活，并学习去做好自己今后大学生活的规化。

<br/>

### 2.2产品功能
&emsp; &emsp;“学士之路是一款养成类游戏。在游戏里，玩家可以自由分配自己的时间，是上课、学习、参加部门活动、娱乐、乃至吃饭睡觉都由自己去安排，但是不同的选择会让角色有不同的成长。而不同种类的成长值会作用在一学期的评定从而影响下学期的安排。玩家通过自己一系列的选择，构成了大学四年的生活，系统最后会依据玩家所获得的学分及奖学金来评定玩家大学四年的成就。玩家就可以通过这款游戏看看这样的大学生活是否是自己想要的。

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>







### 2.3用例图
<center>
<img>![Alt text](./用例图.jpg)
</center>


<br/>

<br/>













### 2.4用户场景
<br/>

<br/>

**典型用户：** 中等新生小刘

<br/>

<br/>


**用户的需求：**
- a、新晋大学生，对大学充满了期待，但是感到迷茫，不知道如何去安排自己的大学生活；
- b、首次加入部门，待如何处理部门和学习的关系。

<br/>

<br/>


**假设：**
- a、成功安装app到手机上，而且运行流畅；
- b、小刘已经渡过了新手引导期，初步知道这个游戏的玩法，且成功的加入了部门中；
- c、新的一周开始，小刘人物活力值已经恢复满值，功课表和部门活动也都更新了。


<br/>

<br/>

**关于这个场景的描述：**

<br/>

  &emsp; &emsp;当游戏右上角的时间跳到周一6;00时，小刘的人物在宿舍醒来了，于是新的一周开始了。
  &emsp; &emsp;新的一周功课表更新了，他还不知道这一周的功课安排，他走出宿舍楼，移到教学楼，点击教学楼，出现了一张本周的功课表。看着功课表的安排，今天周一只有下午半天有课，嗯。。，为了能在期末获得较高的学分，上午半天空闲时间不能浪费，所以到素拓看看有没有可以参加的部门活动。
  &emsp; &emsp;移动到素拓楼，点击素拓楼，查看部门活动列表，今天上午有一个易班值班活动，点击报名参加；移动到易班门口，点击进入，开始执行部门活动。消耗了一些活力值后，右上角的时间推进到周一12:00，同时获得了一些学分。
   &emsp; &emsp;查看下午还有一个电脑维修培训活动，但是下午也还有课，要怎么选择呢？两者的学分都差不多，但是逃课的话会被扣学分，而且听说上课回答问题会加分，于是小刘决定下午还是去上课。
   &emsp; &emsp;剩下时间不够做别的了，要去上下午的课了，移动到教学楼，点击出现课程表，点击上面的课程《高级程序设计语言》，进入教室，上面是一个视频，播放着老师写一个输出”Hello world“的C程序，底下是选择认真听课，还是跳过。小刘觉得这门课很有意思，于是选择认真听课，视频播放结束后，跳出一个问答题，由于小刘有认真听，所以知道答案，答对了，获得双倍学分。


<br/>

<br/>





### 2.5用户特点
&emsp; &emsp;本产品的用户以大一新生为主，他们刚进入大学，对大学的一切还很迷茫，不知道如何去规划自己的大学生活。大学生目前都人手一只智能手机，大部分都喜欢玩游戏。相较于用讲座、文档甚至是一条条的条例等方式来帮助学生规划，显然游戏的方式，无疑是吸引大学生的最好载体，让大学生自己去安排，去体会，无疑是帮助他们的最好的方式。


<br/>

<br/>

### 2.6一般约束
（1） 至项目结束只有两个多月的时间， 开发周期短，需要合理规划时间，合理安排任务多线进行。
（2）都是第一次接触unity编程，技术不够娴熟，需要花费很多时间去学习。
（3） 队员都是第一次上手手游开发设计，也缺少强有力的指导，经验上不足。

<br/>

<br/>

###2.7 假设与依据
本项目是否能够成功实施，主要取决于以下的条件：
（1）团队成员的积极合作配合，为了项目的开发和实施，对个人时间进行合理规划同时为团队做出合理牺牲，配合队友完成任务。
（2）开发前期，做好需求分析部分；开发中间，队员间做好交流，不发生偏差。
（3）团队掌握先进的能够适用于该项目的技术，这是系统的性能是否优化和项目能否成功的保证。


<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>


## 3.具体描述
-------------------------------------------------------------
<br/>
#### 引入类图具体说明用户可以发生的交互及联系

<center>
<img>![类图](http://7xtpgk.com1.z0.glb.clouddn.com/finnalpng.png)
</center>

<br/>

<br/>

<br/>

<br/>


### 3.1.功能需求

<br/>

#### 3.1.1 用户类

<br/>

**登录界面**
*	用户输入姓名和学号，选择头像并通过下拉框选择班级，登录游戏app，开启你的学士之路。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019185445115-611864335.png)
</center>



<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>





**主页面**
*	左上方人物头像以及相关的活力值和学习值，右上方为当前虚拟时间以及综测值，目前背景有教学楼，生活区以及素拓三个模块，点击教学楼可出现课程安排I页面，点击生活区可出现宿舍安排界面，点击素拓可出现相应部门活动安排I界面。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019204927474-786772899.png)
</center>


<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

**课程安排I**
*	显示当前周的课程，点击当前时间对应的课程便可进入课程教学，弹出相应课堂学习页面。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019204939084-1821111195.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

**课堂学习**
*	模拟相应课程的学习（比如播放相应视频，以后改进），右上方点击便可离开课堂，返回课程安排II界面。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019185839974-1273114990.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

**课程安排II**
*	学习过的课程变为灰色（不可选），并扣除相应的活力值，增加学习值以及时间活力的相应改变。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019204947959-1042338585.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>




**部门活动安排I**
*	显示加入的部门对应的活动内容时间以及地点，点击对应的活动，进入相关活动进行页面，增加综测值以及时间活力的相应改变。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019205059256-1026263959.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>


**部门活动进行页面**
*	表示当前正在进行的部门活动，后期可能添加相应图片或者视频描述。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019205104412-1351152649.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

**部门活动安排II**
*	显示当前已完成的部门活动，并且时间也会相应的改变，减少活力值并且增加相应的属性值。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019205113287-504316483.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

**宿舍安排**
*	左边有出门的按键，点击可回到主页面进行相关的安排；上面有睡觉按键，可恢复活力值，并且时间会进行相应的改变；下方有玩游戏的按键。
<center>
<img>![](http://images2017.cnblogs.com/blog/887378/201710/887378-20171019185957974-1679213145.png)
</center>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>


### 3.2外部接口需求

#### 3.2.1用户接口

*	无特殊需求

#### 3.2.2硬件接口

*	无特殊需求

#### 3.2.3软件接口

  - 操作系统：Android4.0及以上
  - 数据库：SQLite
  - 开发工具：Unity 3D

#### 3.2.4通信接口

*	无

<br/>

### 3.3属性


#### 3.3.1可用性

<br/>
  - （1）游戏容易操作，游戏逻辑易理解。界面偏Q版风格。
  - （2）稳定性：不断修复bug，使游戏更加稳定。
  - （3）容错能力：系统具有一定的容错和抗干扰能力，在非硬件故障时，游戏能够保证正常运行。
  - （4）有较大影响的游戏操作有统一规范的提示信息

#### 3.3.2安全性

<br/>
  - （1）重要数据加密：对一些重要的数据利用可靠的加密技术进行加密
  - （2）记录日志：系统能够记录游戏运行时发生的错误。这些错误记录便于查找错误的原因。
  - （3）故障处理：正常运行时不应出错，若运行时出现不可恢复的系统错误，也必须保证数据库完好。

#### 3.3.3可维护性

<br/>

  - （1）保留游戏对应版本的源代码。
  - （2）代码一定要有注释，要有清晰的描述。
  - （3）清晰的系统结构和命名规范，界面规范，提示和帮助信息规范，友好的错误提示信息。
  - （4）完善的游戏配置管理，在项目开始之后，就需要进行，直到项目结束之后，维护工作中，仍然需要不断更新游戏配置信息。按模块对游戏进行配置项的划分，对每次维护工作，都进行记录，留待将来检查。

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

## 4.验证验收标准
-------------------------------------------------------------

<br/>

### 4.1 文档验收标准

<br/>

-	（1） 图文并茂，层次分明，文档可读性高
-	（2） 参考规范文本，文档的图表、文字、样式统一且符合规范

### 4.2 软件验收标准

<br/>

- （1）可安装运行的安卓APP
- （2）使用Android Studio开发
- （3）游戏具有一定的可玩性

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

### 4.3 界面验收标准

<br/>

| 序号 | 界面名称 | 界面描述 | 是否完成 |
|:------:|:------:|:------:|-------|
| 1 | 登入界面 | 顶部标题显示“学士之路”，底部按钮显示“开启学士之路”。第一次登入显示一些必要初始信息输入框，如姓名（昵称），还有选择头像的操作。|  |
| 2 | 中心界面 | 以地图为背景，有教学楼，部门活动中心，宿舍区等地点，还有头像，相关属性值等其它信息。 | |
| 3 | 学习界面 | 有类似课程表的视图，供玩家选择课程来进行学习活动。 | |
| 4 | 部门界面 | 有当前可参加的部门活动列表，供玩家选择参与。 | |
| 5 | 宿舍界面 | Q版形式的宿舍内部图，有睡觉，玩游戏等图标或反馈可选。 | |


<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

### 4.4 功能验收标准
| 序号 | 功能名称 | 详细操作 | 是否完成 |
|:----:|:----:|----|----|
| 1 | 登入 | 玩家第一次进入游戏设置好必要信息后，可以正确的保存，下次进入游戏时直接装载。| |
| 2 | 学习课程 | 在中心界面点击教学楼图标进入学习界面，在学习界面点击课程会有课程相关的学习活动，需要消耗一定属性值，如课程视频或是一些文案，最后再做点小测验完成课程，才能获得相应的奖励。| |
| 3 | 参与活动 | 在中心界面点击部门活动中心进入部门界面，有当前可参与的活动供玩家选择并耗费一定属性值完成，然后才能得到有关奖励。| |
| 4 | 宿舍活动 | 在中心界面点击宿舍区图标回到宿舍，点击电脑开始玩游戏，点击床位睡觉恢复属性值之类。| |

### 4.5 其他验收标准
- （1）游戏美工较为精美
- （2）游戏属性值，完成奖励等数值设置合理
- （3）游戏核心的课程学习部分有自己特色，不易被人模仿

### 4.6 初期版本最核心完成内容
-	（1）游戏策划的整体框架（包括初期版本的实现内容，和未来规划，合理性）
-	（2）游戏的整体美工（具体到每一个部分的UI）
-	（3）Android Studio与Java的学习

## 5.计划安排
-------------------------------------------------------------
### PS设计部分
| 截止时间时间 | 任务 |
|:----:|:----:|
| 2017.10.26 | 登录界面设计 |
| 2017.10.28 | 主页面（福大地图）（主页面图标，活力值，学习值，综测值，时间） |  
| 2017.10.29 |课程边框，按钮  | 
| 2017.10.29 | 课堂界面（实地拍照动画处理） |  
| 2017.10.30 | 部门工作界面|
| 2017.10.30 |宿舍界面（一张床一张桌）|

### Android Studio计划
* 在冲刺阶段前，完成几个基本的n内容
  * 1. Android Studio的环境搭建与调试
  * 2. 布局设计排版及界面切换
  * 3. 熟悉Android Studio的基本排版
  * 4. 完成一个基本的框架设计
  * 5. 可以完成一些与数据库的基本对接


### 数据库
* 在冲刺阶段前，完成的内容
  * 1. 数据的设计
  * 2. 数据库的基本建表
  * 3. 数据库的SQLite基本操作