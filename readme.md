# 安装
### 安装node.js
### 安装Python2
看好自己是32位还是64位
### 安装jdk
看好自己是32位还是64位
### 下载adt-eclipse
打开命令窗口
验证

    node -v
	
	python -V

# 修改环境的变量
### 1. java环境的搭建
    (1)JDK的安装
	
    (2)JAVA_HOME 环境变量的设置
	
    (3)修改环境变量path  环境变量

       %JAVA_HOME%/bin;
	   
    (4)修改环境变量classpath
       %JAVA_HOME%/lib/dt.jar;%JAVA_HOME%/lib/tools.jar
      ```
      验证
      java -version
	  javac
      ```
   2. android环境的搭建
   
    (1)sdk的安装
    (2)eclipse
	
    (3)ANDROID_HOME 环境变量的设置
	
    (4)修改环境变量path  环境变量
    ;%ANDROID_HOME%/tools;%ANDROID_HOME%/platform-tools;

    ```
    验证
    android
    ```
    如果显示 不是内部命   
    重新打开 命令行工具  运行
    不是内部命令消失
    
# 安装命令

    npm install -g react-native-cli
    
# 进入项目目录下
    1.react-native init test
	
	2.cd test
	
	3.连接设备
	尽量选择真机
	 
	4.react-native run-android
	
# react-native run-android报错
    
1.
    You have not accepted the licenseagreements of the following SDK components:

    答案：拷贝  licenses 到 android\sdk
     
2.   
    Error while uploading app-debug.apk :Unknown failure ([CDS]close[0])
 
	答案：https://stackoverflow.com/questions/39518928/gradle-error-while-uploading-app-local-debug-apk-unknown-failure-cdsclose
     
3.  如果报错找不到android-23

    答案：在运行android的时候会弹出窗口，在窗口里找到android 6.0(API 23) 安装就好了

4.   A problem occurred configuring project            ':app'. > SDK location not found
    
    推荐博客[推荐博客](http://blog.csdn.net/wojiong132/article/details/69855729)
    
这就是我搭react-native环境的步骤以及所报的错！

这是软件需要的解压包链接以及密码

{
		http://pan.baidu.com/s/1bp2aaU7
		
		tsut
}

{
		http://pan.baidu.com/s/1jIvahUm
		
		wtc8
}

{
		http://pan.baidu.com/s/1hsMi6Wk
		
		kafr
}

{
		http://pan.baidu.com/s/1kUYD0pT
		
		rium
}

{
		http://pan.baidu.com/s/1eSkYQyQ
		
		70oq
}

{
		http://pan.baidu.com/s/1kUYD0qF
		
		9fpr
}

{
		http://pan.baidu.com/s/1bpjdfeJ
		
		z8sd
}
