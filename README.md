#牛腩代码生成器
 写的代码生成器，生成最基本的实体类和DAL增删查改方法，用于自己的项目和公司的项目
 
 2017年10月03日
  加入mssql数据库下的layui版本的选择和mvc_add页面布局div和table的选择
  加了一个按钮，把后台框架页的生成弄进去了，生成的代码不能直接复制，得用记事本打开了有选择的复制，登录页用vivaldi的登录页，后台首页用layui案例里的后台界面

 2017年09月14日加入生成每个表的insert语句，每个表按主键降序排列取10条记录，用于把别人的老旧数据库考过来，如果别人的数据库有几千万条数据，备份成BAK会有好几G好大的，我只是想要些测试数据，网上找不到现成的工具，只能自己写个，只是写了sql server数据库的...

 2016年08月12日新增了前台页面的关键代码的生成，不过还没有经过测试！！！
 
 ![](http://ohpxbzczu.bkt.clouddn.com/niunan_gencode.png)
 
#注意事项
 数据库创建的时候每张表的主键必须叫id,必须是自增，建表的时候最好每个字段都加上说明，字段类型非字符型则需要设置非空和默认值，这样才能生成比较正确的粘贴到VS中不报错的代码
 
 使用视频：
 [http://www.bilibili.com/video/av11713045/]
 
 注：设计数据库的时候需要每个表的主键为id，自增类型