数据库已经使用Navicat导出为SQL文件。
测试环境为wamp3.0.4 64位，php5.6，mysql 5.7
IE浏览器显示可能部分会不正常，Chrome以及Firefox正常工作。
index.html为起始页。

管理员登录，并对数据库进行操作。
账户：admin 
密码：admin123
登录一次之后会记录session，浏览器地址栏直接访问可以访问到admin，退出此次会话之后，进行如此操作会重定向到login。

解决随机抽取试题，并且试题不能重复这个需求方面，采用了打乱数组数据排序进行处理，使用过的数据记录到数据库中，使用完一轮之后会清理记录的id。
故这样会导致出现一些异常，刷新一下页面即可重新开始。

界面没有过多美化，因为我不擅长美工......做的不是很好，还会继续努力。