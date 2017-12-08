# 源码自动生成模板 java-demo

### 概述

* 模板: java-demo
* 模板使用时间: 2017-12-07 14:12:30

### Docker
* Image: registry.cn-beijing.aliyuncs.com/codebase/java-demo
* Tag: 1.14
* SHA256: 600b5b6783ff0a0e4b7dac2cd58bfb2cefe867cf03cd5008c61d252e77ecbb3e

### 用户输入参数
* repoUrl: "git@code.aliyun.com:16760-xiazc_project/test01.git" 
* appName: "test01" 
* operator: "aliyun_494151" 
* appReleaseContent: "# 
* 请参考: 请参考 
* https://help.aliyun.com/document_detail/59293.html: https://help.aliyun.com/document_detail/59293.html 
* 了解更多关于release文件的编写方式: 了解更多关于release文件的编写方式 
* [NEWLINE][NEWLINE]#: [NEWLINE][NEWLINE]# 
* 构建源码语言类型[NEWLINE]code.language: oracle-jdk1.7[NEWLINE][NEWLINE]# 
* 构建打包使用的打包文件[NEWLINE]build.output: target/test01.war[NEWLINE][NEWLINE]# 
* 应用部署脚本[NEWLINE]deploy.appctl.path: deploy.sh" 

### 上下文参数
* appName: test01
* operator: aliyun_494151
* gitUrl: git@code.aliyun.com:16760-xiazc_project/test01.git
* branch: master


### 命令行
	sudo docker run --rm -v `pwd`:/workspace -e repoUrl="git@code.aliyun.com:16760-xiazc_project/test01.git" -e appName="test01" -e operator="aliyun_494151" -e appReleaseContent="# 请参考 https://help.aliyun.com/document_detail/59293.html 了解更多关于release文件的编写方式 [NEWLINE][NEWLINE]# 构建源码语言类型[NEWLINE]code.language=oracle-jdk1.7[NEWLINE][NEWLINE]# 构建打包使用的打包文件[NEWLINE]build.output=target/test01.war[NEWLINE][NEWLINE]# 应用部署脚本[NEWLINE]deploy.appctl.path=deploy.sh"  registry.cn-beijing.aliyuncs.com/codebase/java-demo:1.14

