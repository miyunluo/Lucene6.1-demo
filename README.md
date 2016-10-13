# Lucene6.1-demo

## 功能简介

将用web爬虫爬取的文件，以年月日形式组织放于本地，程序交互界面为一个简单的GUI界面，用户在输入要查询的内容后选取时间跨度，点击"search"按钮即可返回结果。初始index需要一些时间，与d等待索引的文件大小o有关。

## 文件组织

除了src文件夹，根目录下还需index文件夹以存放索引文件，documents文件夹用来存放待索引的文件

其中documents文件夹下的文件组织格式是：年（如2016）-月（01到12）-日（1到31）<br>
documents文件夹的组织需遵守上述规定，以保证程序按照限定的时间跨度进行检索可以正常进行

## 环境要求

使用Lucene版本为 6.1.0<br>
使用java版本为 1.8.0_91

## 结果展示

见[博客](http://miyunluo.com/2016/10/12/Lucene/)

## Introduction

Save the files catched by web crawler in your local computer with the form Year-Month-Day. Then user can use an easy GUI to input what you want to search and select the time span. Finally you click the "search" button and get the result. Notation: it costs sometime to index your files, so be patient if you have a large amount of files.

## File organization

Apart from "src" file, you needd to creat an "index" file under the root, and a "documents" file to save the files needed to be indexed.

File in "documents" should have this format: Year number(eg. 2016)->month(01 to 12)->day(1 to 31)<br>
You should obey this run so that the program can run well.

## Environment
Lucene 6.1.0<br>
java 1.8.0_91

## Result
See [blog](http://miyunluo.com/2016/10/12/Lucene/)
