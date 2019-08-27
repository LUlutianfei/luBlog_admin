# ***服装后台管理系统*** #
# 一、运行 #
1. 需要node环境
2. npm start运行项目
3. 本地网址127.0.0.1:3001
# 二、MySQL数据库格式 #
    
> 首先手动建立数据库及基本表

- create database lulublog character set utf8;<br/>
- 数据库名称：lulublog<br/>
- 表的定义 

----------

    /*新闻表 编号 标题 发布时间 简介 具体内容*/
    create table New(
    	Id varchar(20) primary key,
    	Title varchar(255) not null,
		Time varchar(100) not null,
		Intro varchar(255),
		Detail MEDIUMTEXT
    );
   
# 三、功能实现 #
# 四、过程 #
8/27/2019 8:49:30 PM 
> 基本框架建立