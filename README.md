
Android-Crack-Tool For Mac
================

![](https://img.shields.io/badge/platform-macOS-red.svg) ![](https://img.shields.io/badge/language-Objective--C-orange.svg) ![](https://img.shields.io/badge/version-2.5.1-red.svg)

[中文](https://github.com/Jermic/Android-Crack-Tool/blob/master/README.md)  [English](https://github.com/Jermic/Android-Crack-Tool/blob/master/README-EN.md)

## 简介
本软件集成了Android开发中常见的一些编译/反编译工具,方便用户对Apk进行逆向分析,提供Apk信息查看功能.目前主要功能包括(详细使用方法见使用说明):

- 反编译APK
- 重建APK
- 签名APK
- 优化APK
- DEX2JAR（APK2JAR）
- JDGUI
- 提取DEX
- 提取XML
- Class to smail
- Apk信息查看
- Unicode转换

## 下载 
[Git下载](https://github.com/Jermic/Android-Crack-Tool/releases)

[网盘下载(网盘分享总被和谐，不定期更新)](https://pan.baidu.com/s/1dPtuMqW1GQbgX3LA12xt4Q) 密码: vq44


## 无法打开提示损坏
打开终端执行
```shell
sudo spctl --master-disable
```
在系统设置中修改权限
go to System Preferences > Security & Privacy > General > check Allow Anywhere


## 截图
![](https://raw.githubusercontent.com/Jermic/Android-Crack-Tool/master/g1.gif)
![](https://raw.githubusercontent.com/Jermic/Android-Crack-Tool/master/g2.gif)
![](https://raw.githubusercontent.com/Jermic/Android-Crack-Tool/master/9.png)


## 版本更新:

### V2.5
```
1.提供英文版本
```
### V2.3.2
```
1.解决部分BUG
2.更新内部工具版本
```
### V2.2
```
1.添加Class转Smail功能
2.解决部分BUG
```
### V2.0
```
1.修改主界面布局,添加新功能项
	提取DEX、提取XML、ApkInfo、Unicode
2.日志添加Start&End标识
3.提取DEX
	从APK文件中提取DEX文件
4.提取XML
	从APK文件中提取并解析XML文件
5.ApkInfo
	扫描APK基本信息
6.Unicode
	Unicode的加解转换
7.解决部分BUG
```
### V1.0
```
主要功能:
1.集成常用反编译破解工具
2.反编译APK
	默认使用ShakaApkTool（设置页面可切换为ApkTool）
	对apk文件进行反编译
3.重建APK
	根据apk文件反编译得到的目录重新生成apk
3.签名APK
	使用SignApk对apk文件进行签名
4.优化APK
	使用Zipalign对apk文件进行优化对齐
5.DEX2JAR（APK2JAR）
	将apk文件中的dex文件转为jar格式文件,支持选择格式apk、dex
6.JDGUI
	使用JDGUI打开Jar文件
```
### 插件:
```
1.ShakaApkTool
2.Apktool
3.Dex2Jar
4.Zipalign
5.SignApk
6.JDGUI
```
### 环境:
```
1.MAC OSX
	测试了10.11.2版本系统，其它版本系统未测试，如果出现问题邮件反馈一下
2.JDK
测试了JDK8，其它版本系统未测试，如果出现问题邮件反馈一下
```
### 使用说明:
```
1.点击浏览打开选择相应功能文件，如果格式错误将无法选中
2.支持拖拽文件到路径，支持手动修改文件到路径（没有做详细判断，所以不要挑战程序健壮性了，正常用就好）
3.添加源文件路径后，若于对应功能吻合将自动生成输出路径，后面会添加功能标识
	O	out        反编译标识
	R	rebuild    重建标识
	S	sign      签名标识
	Z	zipalign  优化标识
	d2j	dex2Jar    转Jar标识
	dex	dex	  提取DEX
	smali	CS2SM	  转Smail标识
4.选中相应功能，点击执行按钮（没有做功能过渡动画，根据LOG自行判断完成是否执行完毕，后续版本功能）
5.点击打开可打开到对应输出目录文件
6.点击交换按钮和互换输入输出路径
7.支持日志导出
8.检测插件版本（后续版本功能）
9.设置面板可更换默认apktool工具i
10.最重要的一点是，请注意使用部分功能时，输出文件如果存在会覆盖掉并不会做提示
```
### 历史版本:
```
2016年08月22日    AndroidCrackTool 2.5 (For MAC)
2016年08月02日    AndroidCrackTool 2.4 (For MAC)
2016年05月09日    AndroidCrackTool 2.3.2 (For MAC)
2016年01月26日    AndroidCrackTool 2.2 (For MAC)
2016年01月13日    AndroidCrackTool 2.0 (For MAC)
2015年12月31日    AndroidCrackTool 1.0 (For MAC)
```

### 联系方式
```
感谢以上插件作者
如遇到问题欢迎私信或邮件反馈
有更好的建议欢迎提出来，尽快改进
By Jermic

Email:Jermic@qq.com
QQ 群:151381462
```
![](https://raw.githubusercontent.com/Jermic/Android-Crack-Tool/master/qqun.png)
