### phper技术栈整理
- php
 - 基础语法
   * [运算符](grammar.md#运算符) 
 - 数组操作
 - 文件操作管理
 - 图片操作管理
 - 字符串操作
 - [面向对象](oop.md)
   - 魔术方法 
   - [对象引用](oop.md#对象引用)
   - [访问控制](oop.md#访问控制private)
   - [访问控制之继承](oop.md#访问控制之继承)
   - [对象遍历](oop.md#对象遍历)
 - [设计模式](DesignPatterns)
   - 单例模式
   - 观察者模式
   - 简单工厂模式
   - 建造者模式
   - 策略模式
 - mvc
  - 框架
    - thinkphp
    - yaf
    - phalcon
  - [swoole](https://github.com/lisiqiong/swoole-demo)
    - [tcp]
    - [udp]
    - [websocket]
    - 协程corutine
    - [process]
    - memory
      - table
    - timer
  - [常用算法](arithmetic.md)
    * 排序
      * [冒泡排序](arithmetic.md#冒泡排序)
      * [快速排序](arithmetic.md#快速排序)
      * [选择排序](arithmetic.md#选择排序)
    * 查找
      * [二分法查找](arithmetic.md#二分法查找)
      * [递归](arithmetic.md#递归)
      * [顺序查找](arithmetic.md#顺序查找)
    * 其它
      * [乘法口诀](arithmetic.md#乘法口诀)
      * [寻最小的n个数](arithmetic.md#寻最小的n个数)
      * [寻相同元素](arithmetic.md#寻相同元素)
      * [抽奖](arithmetic.md#抽奖)
      * [数组反转](arithmetic.md#数组反转)
      * [随机打乱数组](arithmetic.md#随机打乱数组)
      * [寻找最小元素](arithmetic.md#寻找最小元素)
- mysql
  - 基础知识    
    - 普通查询语句
    - join
    - 子查询
    - union
    - union all
    - [触发器](mysql.md#触发器)
    - 存储过程
  - 数据库优化
    - 应用系统sql优化
      - 分表策略
      - 分库策略
      - 索引
	  - 普通索引，联合索引
	  - 如何选择字段创建索引
	  - 索引失效原因 
      - 查询缓存
    - mysql服务器优化
      - 开启慢查询定位问题
      - mysql连接数
    - 操作系统与硬件优化
    - 系统架构整体优化
      - 负载均衡
      - 缓存
      - 分布式优化
  - 数据管理与维护
    - 数据备份
	- mysqldump备份数据库
	- mysldump备份数据表
	- mysqldump备份数据表结构
    - 数据恢复
    - mysql日志
    - mysql监控
    - mysql常用工具
- [nginx](nginx.md)
  - nginx简单介绍以及安装
  - [nginx信号量](nginx.md#nginx信号量)
  - nginx虚拟主机的配置
  - location
  - rewrite重写
  - nginx结合php
  - nginx防盗链
  - expires缓存提升网站负载
  - nginx反向代理
  - nginx实现负载均衡
  - 大访问量的处理优化思路
  - nginx服务器集群搭建
- redis
  - 事务
  - redis数据开发设计
  - 主从复制
  - 集群分片
  - 数据备份策略
  - 常见reds错误分析
  - 监控redis的服务状态
  - 可视化管理工具
  - [redis防止商品超发](redis.md#redis防止商品超发) 
  - redis持久化
- linux
 - 待续

