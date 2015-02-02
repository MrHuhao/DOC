# DOC
##How To Get Started
---------------------------------------


ASZimOrm library for iOS and Mac OS X. It's built on top of the sqlite3.0
Choose ASZimOrm for your next project, or migrate over your existing projects—you'll be happy you did!

##Communication
---------------------------------------
TODO..
##Requirements
---------------------------------------
libsqlite3.dylib
##Architecture
---------------------------------------

| 类        | 描述           | Cool  |
| ----------------------- |:-------------:| -----:|
| ORMSqliteFramework | | .. |
| ObjectRuntime        | 这个类主要是耦合orm框架和实体类    |  ..  |
| FBDMManager           | 这个类主要是对fmdb进行了简单的封装      |   ..  |
| ZIMORMManagerImp |这里的类主要实现是curd操作，也是核心类     |   ..  |


##How To Get Started
---------------------------------------
* 找到这个文件 cn.com.yitong.db ，如果你想使用，写入xml，这里是你要建立的表名和字段

*  查询语句  : `NSArray *aryOfData = QUERY_SQL(@"T_CACHE_BUSI_TRANS", @"TRANS_ID", dataSource[@"TRANS_ID”]);`
*  保存语句  : `  SAVE_SQL(@"T_CACHE_BUSI_COMMON", @[muDataSource]);`
*  删除语句语句  : `DELETE_SQL….`

---------------------------------------
####Created by huhao on 14-8-1.
