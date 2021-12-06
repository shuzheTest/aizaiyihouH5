# 欢迎来到我的网站
## 数据库第一章笔记
1.创建数据库：CREATE DATABASE  [IF NOT EXISTS] 数据库名；    
2.显示数据库：SHOW DATABASES;
3.打开指定数据库：USE 数据库名；
4.查看字符集和校验规则：SHOW CHARACTER SET;字符集默认为gb2312(国标2312),校对规则为gb2312_chinese_ci
5.创建数据库并设置字符集和校验规则：CREATE DATABASE 数据库名[DEFAULT] CHARACTER SET 字符集   [default] COLLATE 校对规则；
6.更改数据库字符集和校验规则：ALTER DATABASE 更改的数据库 [DEFAULT] CHARACTER SET 更改的字符集  [DEFAULT] COLLATE 更改的校验规则；
7.删除数据库：DROP DATABASE [IF EXISTS] 数据库名;
# 我是沭辙
