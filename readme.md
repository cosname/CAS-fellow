# 2000-2021年中科院院士增选数据分析

## 概览


我们整理了2000-2021年共11次中科院院士增选信息以及相关单位地址和类型，
从人数、学部、单位、双一流大学、区域、单位类型、年龄等多个角度进行统计、可视化和比较分析。
最终形成了一份[交互式分析报告](https://costudy.gitee.io/cas-fellow/)，以满足自己和读者的好奇心。


## 数据和程序说明

院士增选数据来自于[中科院官网](http://casad.cas.cn/yszx2017/jj/201504/t20150429_4683835.html)，
我们整理了原始数据，经过初步的人工审核，存放在`CAS-Fellow-2001-2021.csv`文件中。
为了分析单位所在的省、市和类型，建立了入选单位的省、市和类型对照数据表，存放在`Empl_location.csv`文件中。
本报告用rmarkdown撰写，相关图表自动生成，得到的HTML文档中的表格支持搜索和交互查询。

还需要特别说明的几点是：

- 同一个单位在不同年份叫法并不统一（比如中科院X所，中国科学院X所），我们对这些单位名称进行了归一
- 生命科学和医学学部之前被称为生物学部，统一为现在的名称：生命科学和医学学部
- 大学的附属医院、国企的下属研究院往上进行了合并，比如复旦大学附属中山医院，合并入复旦大学
- 部分单位在多个地方有分布，在填写所在地的时候，一般以总部为主，比如北京
- 少数院士有两个单位，我们在计算的时候只要单位都在国内，都各算1个
- 部分单位在历史中，发生过组织上的合并和撤销，对这方面不作处理


## 项目地址和版权协议

本文所有的数据、代码都完全公布，报告基于rmarkdown和Git的可重复框架。
读者运行rmd文件即可得到同样的报告，欢迎更多吃瓜群众围观、挑错和协作改进！

本项目相关地址如下，欢迎star、fork、pr三连：

- 动态报告：[https://costudy.gitee.io/cas-fellow/](https://costudy.gitee.io/cas-fellow/)
- 项目地址（Github）：[https://github.com/cosname/CAS-fellow/](https://github.com/cosname/CAS-fellow/)
- 项目地址（Gitee）：[https://gitee.com/costudy/CAS-fellow/](https://gitee.com/costudy/CAS-fellow/)

本项目版权协议使用[木兰宽松许可证第二版](http://license.coscl.org.cn/MulanPSL2)，请遵守相关规定。

引用格式：

> 六边形吃瓜群众，**数说风云：2000-2021年中科院院士增选数据分析**，统计之都，2021，URL：https://cosname.github.io/CAS-fellow/


## 关于数说风云

【数说风云】是由统计之都发起，针对热点或重大话题，开放式约稿，
以共享数据、传播技术、促进交流、启发思考。
欢迎讨论、欢迎参与、欢迎投稿！
联系邮箱：editor@cosx.org
