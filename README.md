# unisecurity-ranger
背景：
   用户使用Ranger管理Hadoop各个组件的用户权限。

使用前提:
   用户已经搭建好Ranger与Hadoop的环境，而且可以通过Ranger UI来配置用户在Hadoop各个组件中的权限

使用说明：
   配置ranger-site.xml中的各个参数，这其中包含：ranger地址，管理用户名、密码，以及各个组件的仓库名称。
   具体执行，可以参考com.idatrix.unisecurity.ranger.main中的TestMain.java
