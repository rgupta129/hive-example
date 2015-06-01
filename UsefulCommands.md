
### show functions;
```
...
upper
var_pop
...
```

### describe function upper;
```
upper(str) - Returns str with all characters changed to uppercase
```

### show databases;
```
default
xademo
```

### describe database xademo;
```
xademo		hdfs://sandbox.hortonworks.com:8020/apps/hive/warehouse/xademo.db	hive	USER
```

### dfs -ls /apps/hive/warehouse/xademo.db;
```
drwxr-xr-x   - hive hdfs          0 2015-04-14 05:58 /apps/hive/warehouse/xademo.db/call_detail_records
drwxr-xr-x   - hive hdfs          0 2015-04-14 05:58 /apps/hive/warehouse/xademo.db/customer_details
drwxr-xr-x   - hive hdfs          0 2015-04-14 05:58 /apps/hive/warehouse/xademo.db/recharge_details
```

### use xademo;

### show tables;
```
call_detail_records
customer_details
recharge_details
```

### describe call_detail_records;
```
phone_number        	string              	                    
phone_type          	string              	                    
in_out              	string              	                    
local               	string              	                    
duration            	string              	                    
date                	string              	                    
time                	string              	                    
roaming             	string              	                    
amount              	string              	                    
in_network          	string              	                    
is_promo            	string              	                    
toll_free           	string              	                    
bytes               	string              	                    
type                	string
```
