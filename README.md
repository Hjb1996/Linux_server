# Linux_server
A linux_server program

#开发环境 ubuntu18.04
           gcc 7.5.0
           cmake
#项目路径 
bin -- 二进制
build -- 中间文件路径
cmake --cmake函数文件夹
CMakeLists.txt -- cmake的定义文件
lib -- 库的输入路径
Makefile -- 方便使用
sylar -- 源代码路径
test -- 测试代码路径


## 服务器框架

##1：
## 日志系统，基于协程进行开发

  Log4J
  Logger（定义日志类别） 每个log
     |
          Formatter（日志格式）
     |
  Appender（日志输出的地方）
  
## 协程库封装

## socket函数库

## http协议开发（请求web）

## 分布协议 （高性能服务器有内部共享请求，逻辑业务抽象成插件，实现服务器之间的交互，业务功能系统功能拆分）

## 推荐系统 


