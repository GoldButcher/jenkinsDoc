首页点击新建即可看到：

![](/assets/goujian.png)这里选择构建maven项目输入项目名字确定即可

##### 构建时的必要选项

1.保留以及丢弃旧版本：

![](/assets/goujian2.png)按照需要填写保留的天数以及保留的版本数量如都填写3则说明旧的版本最对保留3天并且最多保留3个版本的代码。

2.版本库设置:![](/assets/goujian3.png)填写git仓库地址，然后添加账号密码即可

3.构建触发器：

![](/assets/goujian4.png)这里有2种不同的方式，一种是Build periodically 此方式会规定时间打包项目不管版本库种代码是否有更新都会重新打包一份他有5个参数分别是 MINUTE HOUR DOM MONTH WEEK,比如：0 2 \* \* \* 意思是每天2:00会自动构建一次，还有一种是Poll SCM,此方式会在一个规定时间查看一次版本库代码是否有更新，如果有则打包一次他的参数同上,比如:\*/3 \* \* \* \*   注意如果使用\*/，如例子则表示每3分钟一次循环查看一次版本库版本。

