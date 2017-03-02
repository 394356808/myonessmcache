这个项目是我看黑马的视频自己实现的，如果侵犯了谁的版权和我说下我马上删除，用户名就是我的QQ号
这个是我练习二级缓存的项目以我以前的ssm例子改的
   用到了springmvc mybatis，ehcache缓存 jq css
数据库我没弄上来了，如果要用的话直接按po里面的类建一下就好了用的mysql数据库，除了主键自增没加其他的了
增，删，改，查四个功能都实现了
采用的是配置文件的方式实现的，具体的在程序里面都有注释的 我电脑里面没有办公软件，文本文档一个个敲实在有点费劲
因为我用的以前的项目改造成的maven，ssm二级缓存项目所以有的包我没从maven仓库下了直接用的lib里面的了
我只提一下把，这个项目中把cache加入配置文件后默认是开启缓存的如果想要不开启缓存在标签中加入useCache="false"
就行了例如<select id="findItemsList" parameterType="cn.ssm.po.ItemsQueryVo" resultType="cn.ssm.po.ItemsCustom" useCache="false">