# goSqlT
mongo(json)  to mysql or oracle auto


将mognodb下的数据迁移到MySQ，oracle等关系型数据库

语言：go（跨平台）

思路：

1.mogodbexport  可以导出生成json文件 ,提供数据源
2.很多数据格式基本相通
3.进过数据过滤和转换，转存容易提取共同点

