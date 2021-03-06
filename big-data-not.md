# 数据可视化部分

## html

## css

主要给div定义高宽

## javaScript（重点）

主要是获取后台flask的数据

1. 基本语法
   - 从后台拿到数据映射到echarts的方法中
2. 请求接口
   - js自带请求数据api(fetch)

## nodeJs

## webpack

vue-cli用到 涉及到项目构建

## vue（重点）

1. 基本使用
2. vue-cli
   - 配置跨域（cors)
3. vue-router

## ecahrts（重点）

根据官方提供的文档进行使用 后期要记住常用属性

1. 基本配置
2. 饼图， 线图， 柱状图
3. 常用组件

## python

主要用到flask搭建web服务器开放api让前端进行获取

1. flask（重点）
   - 基本使用
   - [flask-sqlalchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
   - flask-restful
2. pymysql

## 学习路线

基本分为两部分 前端 后端 可同时进行学习（后端部分要先会写接口 才可供前端使用）

### 后端

1. python基础
2. flask基本使用
3. flask配合sqlalchemy
4. flask配合restful

### 前端

1. html css js
   - js需要重点学习
2. vue基础 vue-cli vue-router
3. echarts使用 ajax数据请求

# 数据处理部分

## scala

1. 熟练其基本语法
2. 熟练使用scala中的数据结构
3. 熟练使用scala中的函数式编程

## Spark

 1.熟练使用spark中各种算子的运用

2.熟练sparkSql（dataframe与dataset）的各种操作（如连接 ，保存， 临时表与全局表等知识）（重点）

## Maven

基本了解

## Mysql

1.熟练sql语句（增删改查）

2.熟练使用mysq中的一些函数（sum， avg， max， min， count）

3.在spark会用到数据库的知识，所以数据库基础要扎实。

## mongodb

1.了解一下， 比如如何从里面读取数据，spark会读取其中的数据，进行数据分析。（建议完整的学习mogodb）

## linux

2.熟练使用linux（比赛都是在ubuntu上进行的）

## 学习路线

个人建议：

linux ----->> mysql（次重点）----->> mogodb（了解）----->> scala（底层是java，java基础要扎实，面向对象， jdbc，反射，数据结构）----->> spark(重点学习)

最后一个小建议：
平台的搭建最好也会（选修）

# 平台的搭建

## 平台组件配置（linux shell）

1. 首先熟悉Linux系统的基本使用，能够熟练操作Linux系统，为平台搭建打好基础

2. hadoop平台的搭建（完全分布式 ）
3. spark的安装配置、节点配置文件修改、spark集群的启动
4. mongodb安装配置、数据文件配置、日志文件配置、环境变量的配置,启动mongodb
5. mongodb还可能用到的可视化软件是Robo 3T，学会简单使用（使用Robo 3T对表的增删改查）
6. maven基本使用

## 个人建议学习路线

Linux ---->> hadoop平台的搭建（完全分布式） ---->> spark的安装配置 ---->> mongodb基础的增删改查

