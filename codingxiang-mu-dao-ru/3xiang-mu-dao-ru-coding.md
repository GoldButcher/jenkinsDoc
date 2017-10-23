![](/assets/coding.png)

点击复制SSH地址,在IDEA 中将项目初始化为git仓库

![](/assets/coding2.png)

如上图然后选择本项目的目录。

接下去 windows用户请下载GitBash命令行工具, Linux & Unix用户跳过本步骤 ,进入项目目录,分别使用命令

1. git remote add origin [http://git.coding.net/\*\*\*/\*\*\*.git](http://git.coding.net/***/***.git)  给项目设置远程远程仓库 \#  
2. git pull origin master    抓取远程仓库数据，并自动合并远程分支 \#

3. git pull origin master  更新本地数据到Git@Coding \#

4. git add . \(此处有一个.的意思是该文件夹下全部文件\) 添加项目文件

5. git commit -m "commit信息"

6. git branch --set-upstream master origin/master

即可同步到coding

### 



