
# 基于Doris搭建一个简单的实时数仓演示环境

包含：
doris，分析型数据库
mysql（模拟业务数据库），
superset（数据可视化），
flinkcdc（数据传输）

这只是一个简单的测试环境，不建议用于开发环境。
具体关于doris的使用和优化内容，建议餐卡官方文档
https://doris.apache.org/zh-CN/docs/gettingStarted/what-is-new/

Flinkcdc是对事务数据库实现实时数据抽取，具体使用请参考Flink官方文档
