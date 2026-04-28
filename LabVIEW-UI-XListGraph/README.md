LabVIEW-UI-XListGraph
===========================

ListGraph 控件。曲线可高亮显示、隐藏。

![范例截图](https://images.gitee.com/uploads/images/2018/0904/101628_418b970e_136753.png "屏幕截图.png")

### 使用到的 Waveform Attributes

 - NI_ChannelName : 通道名称
 - NI_ChannelUnit : 通道单位

### User Event

 - Selected Item Changed : 选择的曲线发生变化
 - Visible Item Changed ： 可见的曲线发生变化

## 开发环境  
LabVIEW 2014

## 依赖项  
 - OpenG Library
 - JKI State Machine
 
## 修改记录  

 - v1.0 创建 XControl
 - v2.0 增加 User Event，以及配套的Property/Method，可实现对用户操作的感知，实现与其他模块的互动。
 
