# Audition CC

## 准备工作

- 独立声卡
- 麦克风

## 基本配置

- 编辑——首选项——音频硬件

设备类型：有独立声卡选择ASIO，没有就用MME

- 编辑——编辑快捷键

根据自己的习惯自定义

## 录音技巧

录音前要先确认麦克风是否可用，录音时请使用耳机，不要开音响

#### 简单的录音方式（不实用）

![image-20200501210530026](assets/image-20200501210530026.png)

根据声卡级别选择采样率，主控单声道和立体声根据需求选择

![image-20200501210616072](assets/image-20200501210616072.png)

![image-20200501210738817](assets/image-20200501210738817.png)

点击录制按钮，录完后可以播放

![image-20200501210828951](assets/image-20200501210828951.png)

#### 实用的录音方式

![image-20200501204514385](assets/image-20200501204310307.png)

根据声卡级别选择采样率，主控单声道和立体声根据需求选择

![image-20200501204753673](assets/image-20200501204753673.png)

![image-20200501205002913](assets/image-20200501205002913.png)

先点击轨道又上方的R按钮，再开始录音

![image-20200501211635295](assets/image-20200501211635295.png)

![image-20200501213123579](assets/image-20200501213123579.png)

多轨道的使用可以支持多个音频输入设备（男女混合演唱，一人一个话筒）

## 工程管理及混缩

#### 导入音频文件至多轨混音项目

- 文件窗口——导入——选择要导入的音频文件   

- 右键点击音频文件——插入多多轨混音中

#### 导出音频文件

文件——导出——多轨混音

## 常用音频编辑技巧

#### 时间指针定位

- 直接拉动指针
- 在时间上滚动
- 精准定位：直接编辑时间

![image-20200503114519427](assets/image-20200503114519427.png)

#### 轨道缩放功能

- 横向缩放

  ![image-20200503115324955](assets/image-20200503115324955.png)

- 纵向缩放

![image-20200503115514510](assets/image-20200503115514510.png)

#### 拆分

选中节点，点击右键——选择拆分

#### 复制

按住alt键+左键拖动某一段音频

#### 合并

选中多个音频剪辑，点击右键——合并剪辑

#### 控制声音大小

注意这两种方法是完全独立的

![image-20200503121040973](assets/image-20200503121040973.png)

#### 控制左右声道

注意这两种方法是完全独立的

![image-20200503121230640](assets/image-20200503121230640.png)

#### 淡入淡出

![image-20200503121731320](assets/image-20200503121731320.png)

![image-20200503121849223](assets/image-20200503121849223.png)

## 轨道效果功能

建议不要切换到单轨上加效果，因为是直接处理声音，不能还原。下面的方法都是多轨加效果。

#### 预设效果

![image-20200503130409197](assets/image-20200503130409197.png)

#### 自定义效果

![image-20200503130714731](assets/image-20200503130714731.png)

#### VST增效

需要先下载VST相关的扩展包

然后点击效果——音频增效工具管理器

![image-20200503130920479](assets/image-20200503130920479.png)

## 去噪

建议不要切换到单轨上去噪，因为是直接处理声音，不能还原。下面的方法是多轨去噪。

![image-20200503133549951](assets/image-20200503133549951.png)

![image-20200503133346889](assets/image-20200503133346889.png)

## 音量增幅

前面“常用音频编辑技巧”——“控制声音大小”可以调节音量增幅，但是使用增幅效果器会更好。

- 增幅效果器

![image-20200503134545597](assets/image-20200503134545597.png)

![image-20200503134651969](assets/image-20200503134651969.png)

## 去除齿音

![image-20200503135527540](assets/image-20200503135527540.png)

![image-20200503135634953](assets/image-20200503135634953.png)

## 科学滤波器

![image-20200620143930516](assets\image-20200620143930516.png)

选择科学滤波器

![image-20200620144110946](assets\image-20200620144110946.png)

## 均衡器

![image-20200620141812310](assets\image-20200620141812310.png)

均衡器段数越高，可调节的更细致

![image-20200620142051134](assets\image-20200620142051134.png)

## 参数均衡器

![image-20200620143526125](assets\image-20200620143526125.png)

![image-20200620143815034](assets\image-20200620143815034.png)

## 压缩效果器

#### 单频段压缩器

![image-20200620150421287](assets\image-20200620150421287.png)

![image-20200620150447633](assets\image-20200620150447633.png)

#### 电子管建模压缩器

效果最好的压缩器

![image-20200801101053141](assets\image-20200801101053141.png)

![image-20200801101229422](assets\image-20200801101229422.png)



#### 动态处理

调节比较自由的压缩器，不适合新手用。唯一可以调节声音硬度的压缩器。

![image-20200801101750288](assets\image-20200801101750288.png)

![image-20200801101815645](assets\image-20200801101815645.png)

#### 限制器

限制器一般加在主线轨道上；可以把大的声音变小，小的声音变大。

![image-20200801103111468](assets\image-20200801103111468.png)

![image-20200801103227983](assets\image-20200801103227983.png)

#### 多频段压缩器

相当于在不同频率段上加4个电子管建模压缩器

![image-20200801110955527](assets\image-20200801110955527.png)

![image-20200801111419676](assets\image-20200801111419676.png)

## 混音效果器

#### 混响

![image-20200801112737345](assets\image-20200801112737345.png)

![image-20200801112800655](assets\image-20200801112800655.png)

#### 室内混响

混响->室内混响

![image-20200801121827081](assets\image-20200801121827081.png)

#### 卷积混响

混响->卷积混响

![image-20200801121938081](assets\image-20200801121938081.png)

#### 完全混响

最好的混响效果器

混响->完全混响

![image-20200801122044421](assets\image-20200801122044421.png)

![image-20200801122101430](assets\image-20200801122101430.png)

## 消除人声制作伴奏

![image-20200801123533922](assets\image-20200801123533922.png)

![image-20200801123601842](assets\image-20200801123601842.png)

## 调音台

![image-20200801132616897](assets\image-20200801132616897.png)