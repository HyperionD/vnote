# oracle操作

1. 新建同样表结构的表

```
create table new_table as select * from old_table where 1=0;
```
