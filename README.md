LabVIEW X-Controls
========================================

使用说明
-----------------

1.	部分XControl 依赖OpenG
2.	开发环境 LabVIEW 2014，高版本可以直接拷贝至开发目录使用。

列表
-----------------

 1. [XIconBtn](https://github.com/nevstop/LabVIEW-UI-XCtl/#xiconbtn)
 ：自定义图案按钮,可在编辑时右键中选择载入的按钮图案，可设置Label 文字和字体。
 2. [XLEDDisplay](https://github.com/nevstop/LabVIEW-UI-XCtl/#xleddisplay)
 ：LED 字符滚动显示控件
 3. [XpnlTab](https://github.com/nevstop/LabVIEW-UI-XCtl/#xpnltab)
 ：带Tab的Subpanel控件
 4. [XpnlWizard](https://github.com/nevstop/LabVIEW-UI-XCtl/#xpnlwizard)
 ：功能Btn，可调用 VI或触发 CommandLine 命令
 5. [XTwoColSelector](https://github.com/nevstop/LabVIEW-UI-XCtl/#xtwocolselector)
 ：双列List，用于列表项选择
 6. [XAdvanceList](https://github.com/nevstop/LabVIEW-UI-XCtl/#xadvancelist)
 ：增强LabVIEW String List
 7. [NEVSTOP_ProgressDlg](https://github.com/nevstop/LabVIEW-UI-XCtl/#nevstop_progressdlg)
 ：基于消息机制的进度条/忙碌窗口
 8. [saphir: VIBOX - XCONTROLS](http://www.saphir.fr/en/produits/vibox---xcontrols-9.html)
 : saphir's XControls  
  - XTab：支持动态调用的 XControl Tab，可作为程序的基本框架使用。   
  - PlaceHolderString: 提示用户输入的String控件。

功能说明
-----------------

### XIconBtn
自定义图案按钮,可在编辑时右键中选择载入的按钮图案，可设置Label 文字和字体。  
![2017-12-06_144736](https://user-images.githubusercontent.com/8196752/33648392-9075d896-da94-11e7-88df-92310c5ff7a2.png)

### XLEDDisplay
LED 字符滚动显示控件，字符可预设或运行时修改。

### XpnlTab
带Tab的Subpanel控件，可设置 tab 位置。  
![image](https://user-images.githubusercontent.com/8196752/33648427-c9e9a1e8-da94-11e7-851c-ec7da36d1d0c.png)

### XpnlWizard
来源于 LabVIEW DSC 中的按钮XControl，移除不必要的dsc 相关界面内容。可以在按钮右键菜单中选择  
 1. 触发 CommandLine 命令
 2. 调用 VI  

![image](https://user-images.githubusercontent.com/8196752/33648449-e2c086e6-da94-11e7-8717-c3b9b7c1ae35.png)
 
### XTwoColSelector
双列List，用于列表项选择  
![image](https://user-images.githubusercontent.com/8196752/33648464-f3ed8aae-da94-11e7-96c5-164b5cd66b6a.png)

### XAdvanceList
增强LabVIEW String List 功能  
![image](https://user-images.githubusercontent.com/8196752/33648476-09586b34-da95-11e7-807c-bc4f1da382a1.png)

### NEVSTOP_ProgressDlg
基于消息机制的进度条/忙碌窗口。
 1. 调用Initialize 自动配置显示进度窗口；
 2. 调用Set Information VI 更新进度信息；
 3. 使用Release 隐藏窗口。  

![image](https://user-images.githubusercontent.com/8196752/33648492-1c23e3ba-da95-11e7-8a71-b4b2e0aabbf7.png)  
![image](https://user-images.githubusercontent.com/8196752/33648496-22d37bbc-da95-11e7-99a9-887facf42366.png)

### saphir: VIBOX - XCONTROLS

动态Tab框架  
![image](https://user-images.githubusercontent.com/8196752/33918323-a5bb1244-dfed-11e7-9d9a-2c2eeaa403ff.png)

提示用户输入的String控件  
![image](https://user-images.githubusercontent.com/8196752/33918363-d37593d0-dfed-11e7-9d8d-34638d73d3c2.png)
