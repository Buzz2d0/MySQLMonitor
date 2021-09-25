#  MySQLMonitor
> 监控 MySQL 实时打印执行语句（审计的好帮手

https://www.bilibili.com/video/BV1f44y1b7hW

![](https://user-images.githubusercontent.com/26270009/134752869-6d994043-11ba-4c7b-a24c-e1f540da2931.jpg)

- 监听 `general_log_file` 日志文件（效率高，结果准确，不会遗漏执行语句） 🚀
- 结束时会关闭 general_log 并且清空日志文件 🙈
- 执行正确以及错误的SQL语句都会被打印（mysql8.0以及高版本自动开启log_raw=1 
