# 在Windows上运行Appium

## 开始安准备

1. 安装[nodejs](http://nodejs.org/download/) 4.0版本及以上。

2. 安装android的sdk包，(http://developer.android.com/sdk/index.html), 运行依赖sdk中的'android'工具。
  并确保你安装了Level17或以上的版本api。
  设置`ANDROID_HOME`系统变量为你的Android SDK路径，并把tools platform-tools两个目录加入到系统的Path路径里。

3. 安装java的JDK，[下载地址](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)并设置`JAVA_HOME` 变量为你的JDK目录。

4. 安装[Git](http://git-scm.com/download/win). 确保你安装了windows下的Git，以便可以在github上clone项目。

## 开始安装

1 安装appium
```
npm install -g appium
```
2 run appium
```
appium
```
3 clone [测试例子](https://github.com/appium/sample-code.git)
```
 sample-code\sample-code\examples\node>npm install //安装依赖库
 ```
 4 安装mocha 
  ```
  npm install -g mocha
  ```
5 检查设备或模拟器
```
 adb devices
 ```
 6 运行测试

```
mocha android-simple

```


