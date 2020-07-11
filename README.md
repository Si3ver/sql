# sql

## env

```s
# macos
$ mysql
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 7
Server version: 8.0.16 MySQL Community Server - GPL
...
> show databases
> use [db name]
> show tables
> desc [table name]
> SELECT * FROM [table name]
```

## 数据过滤

+ 比较运算符
  - `> < >= != !>`
  - BETWEEN
  - IS NULL
+ 逻辑运算符
  - AND OR IN NOT
+ 通配符
  - LIKE % *

## SQL函数

+ 算术函数
  - ABS MOD ROUND
+ 字符串函数
  - CONCAT LENGTH CHAR_LENGTH LOWER UPPER REPLACE SUBSTRING
+ 日期函数
  - CURRENT_DATE CURRENT_TIME CURRENT_TIMESTAMP EXTRACT DATE YEAR MONTH DAY HOUR MINUTE SECOND
+ 转换函数
  - CAST COALESCE
+ 聚集函数
  - COUNT MAX MIN SUM AVG
