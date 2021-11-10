# account-checking
find differences and similarity  between two account
作用：
查找两个账务（excel）记录表中的相同记录，并保持到1个excel文件中，剩下的部分分别保持到两个文件中。
相同记录判别规则：
同时满足1 和2条件（2.1或2.2）。
1.   金额相同
2.1  文件1的备注项全部内容在文件2中可以找到，
2.2  文件1的备注项指定字段在文件2中指定位置可以找到
