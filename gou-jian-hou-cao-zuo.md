构建后使用Deploy to container插件：

![](/assets/goujianhou.png)需要在tomca-user.xml下设置tomcat-user

在配置文件&lt;tomcat-users&gt;节点下添加如下xml

&lt;role rolename="admin-gui"/&gt;

&lt;role rolename="manager-script"/&gt;

&lt;user username="admin" password="admin" roles="admin-gui,manager-script"/&gt;即可

