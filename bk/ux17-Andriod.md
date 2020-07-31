# 安卓设计规范

知识点

- MD UI 
- 概况
- 导航
- 控件
- Typography
- 其他规范

## MD UI

结构

- Bottom App Bars
- Top App Bars
- Backdrop
- Banner
- Bottom Navigation
- Buttons
- FAB:Floating Action Buttons
- Cards
- Chips
- Dialogs
- Image Lists
- Lists
- Menus
- Navigation Drawers
- 进程指示符
- 选择控件
- Sheets
- Sliders
- Snack Bar
- 标签栏
- 文本域
- 

## 概况

将APP从IOS转换成Andriod时，需要考虑以下不同之处

|设计元素|IOS|Andriod|
|:---|----|----|
|最小点击尺寸|44*44pt|48*48dp|
||||
||||
||||
||||
||||
||||
||||
||||
||||

安卓开发单位是DP、SP



DP：安卓专用长度单位。

以160 DPI屏幕为标注，则1DP=1PX

计算公式：dp x dpi/160=px

例：以720x1280px （320dpi）为例， 1dp x 320 dpi/160=2px



SP：安卓专用字体单位。

以160 DPI屏幕为标注，则1SP=1PX

计算公式：sp x dpi/160=px

例：以720x1280px （320dpi）为例， 1sp x 320 dpi/160=2px




二、安卓设计尺寸：以1080x1920px作为设计稿标准尺寸



1.从中间尺寸向上、下适配，界面调整幅度最小，最方便适配。

2.大屏幕时代依然以小尺寸作为设计尺寸，会限制设计师的设计视角。

3.用主流尺寸来做设计稿尺寸，极大的提高了视觉还原和其他机型适配。




三、安卓图标尺寸

![](/Users/zj/ui-notes/bk/1.jpeg)






四、安卓字体



中文：思源黑体 / Noto Sans Han

英文：Roboto

大小：主题文字 36-34px    正文 28-26px     提示文字 24-22px

链接: https://pan.baidu.com/s/17cKM9co53TEN85gj4vy5dw 提取码: hd35




五、切图规范



1.切图尺寸必须为双数

2.单像素的图会出现边缘模糊的情况

一般情况下，我们只需要提供3套切图资源就可以满足安卓工程师的适配，分别是HDPI、XHDPI、 XXHDPI 3套切图资源。







## 导航栏

导航栏显示成什么样子，不同的平台有不同的标准。

- IOS：

  - 返回动作在左边
  - 主要动作在右边：动作是文本或图标
  - 标题开始在左，滑动时居中

- Andriod

  - 返回和标题在左
  - 主要动作在右：动作是图标
## 主导航：标签栏

标签栏是主导航区。

IOS(原生规范)

- 位置：屏幕底部
- 数量：3-5个标签
- 标签字号：10pt
- 标签标示视图名称：名词

IOS(第三方扩展规范)

- 动作标签居中（IOS：不鼓励将动作放在标签栏）
- 我的最后（IOS：没有我的这种设置相关的标签）
- 搜索第二：（IOS：放在最后）

Andriod

主导航区分布在四个位置

- 汉堡菜单按钮
- 搜索栏
- 顶部标签栏
- 浮动按钮

越来越多的使用底部标签栏。差异不明显

## 二级导航

IOS

- 位置：
  - 底部标签栏最后一个：more
  - 导航栏右侧：

Andriod

- 位置：汉堡菜单（IOS：不鼓励使用汉堡菜单，第三方用的多）

Obvious Always Wins https://www.lukew.com/ff/entry.asp?1945



## 后退模式



## 分辨率

1080*1920 13

720*1280 6.58

1080*2340 2.89

1080×2259  2.55

600×1024  2.45

1080×2265  2.42

720×1440  2.2

1080×2139  2.16

720×1360  1.99

1080×2137 1.68

1080×2208 1.67

720×1424  1.6



## 我的

- 1080×2160 ：2.68×5.36 = 6.8×13.6cm

- 5.99英寸

- 像素比：2.5

- 432*864
- PPI:403

1:403

5.99:2414

## 参考

https://tongji.baidu.com/research/app?source=index#screen