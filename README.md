mmap面向行，只读的查询引擎，并且使用lrucache来缓存。

==== 修改 ===

索引包含两部分 ： 文件的偏移量 和 本行的长度 

增加分布式建立索引脚本 index.sh

增加index_checker 做索引diff
