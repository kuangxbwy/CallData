# CallData
## 项目名称：
 基于大数据技术的通话日志数据分析
         
## 技术栈：
         Hadoop+Kafka +Hbase +Flume+ Redis+SSM+MySQL
         
## 项目目标：
         通过对原始的通话数据进行收集、清洗、统计、分析最终得到每位用户的通话数据详情，可以清楚的查看每位用户在某个时间段内打过的电话次数及总时长。并通过通话的次数和时长来判断用户之间的亲密度。
         
## 项目主要模块：
           1）随机生成通话数据，使用Flume+Kafka的组合进行采集并存入Hbase之中，加入协处理器进行优化
           2）使用MapReduce读取Hbase中的数据，并分解计算之后得到最终的统计数据存入MySQL
           3）后端集成SSM框架，前端使用ECharts。读取数据并进行展示。
 ## 项目整体架构图：
 ![](https://imgchr.com/i/Nj2VQf)
 ## 详细架构图：
 ![](https://s1.ax1x.com/2020/07/03/Nj2VQf.md.png)
## 效果图1：
 ![](https://imgchr.com/i/Nj2ESP)
 ## 效果图2：
 ![](https://imgchr.com/i/Nj2kWt)
 
 
https://imgchr.com/i/Nj2VQf
https://imgchr.com/i/Nj2ESP
https://imgchr.com/i/Nj2kWt
https://imgchr.com/i/Nj2FJI
