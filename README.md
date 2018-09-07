# Mac-workflow-alfred

Mac勿扰模式没有定时关闭的功能对于我来说一直是个痛点，本workflow给勿扰模式加入了定时关闭功能和番茄钟工作法的模式（需要系统热键配置）

本workflow配合Alfred使用，触发hotkey为nd（not disturb之意）

![open](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/open.png)


## 配置指南

1. 给勿扰模式添加全局系统热键 cmd + option + control + D，在设置-键盘-快捷键-调度中心可以找到配置勿扰模式的tab

   ![settings](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/settings.png)

2. 下载Alfred并且点击workflow就可以直接使用





## 使用指南

### 普通模式：勿扰模式定时关闭

![setFocusTime](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/setFocusTime.png)

这是开始界面，输入时间以后按回车即可，整个流程非常高效。

在开始和结束时都会在右上角有弹窗提醒





### 番茄工作法模式：在一定的时间内循环番茄钟

![setRestTime](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/setRestTime.png)

如果选择了“番茄工作法”，这里会要求输入休息时间，我设置默认为十分钟

（可以在AppleScript里面自定义）

![setTotalTime](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/setTotalTime.png)

接下来输入总学习时间，接下来系统会在这个时间之内不断的循环番茄钟（fucus+休息）

默认为：一直循环番茄钟到晚上23:15分，这是我自己的习惯，用户可以在Applescript里面自定义。





### 如何自定义

![customize1](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/customize1.png)

点最右边run script那个小块，展开AppleScript代码

![customize2](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/customize2.png)

此处可以自己调整番茄钟模式的默认总时长：此处我设置为23:15分之前，可以根据逻辑自己更改

![customize3](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/customize3.png)

此处可以更改默认的休息时间：default answer后数字





### 右上角通知的类型

![notification1](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/notification1.png)

![notification2](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/notification2.png)

![notification3](https://github.com/max-yeah/Mac-workflow-alfred/blob/master/picture/notification3.png)

通知的数字是根据用户输入的数字而定的
