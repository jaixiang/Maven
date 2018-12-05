 如何导入github上clone下来的Maven工程包
 
 1、（1）cmd-以管理员身份运行

    （2）net start mysql 启动MYSQL服务器

    （3）mysql -u root -p root 进入mysql

    （4）create database if not exists hill_db default charset utf8 collate utf8_general_ci; 建立一个hill数据库

    （5）show database 看数据库有没有建立成功


	
 2、（1）eclipse--File--Import--Existing Maven Projects--Browse 浏览将所需要的文件导入

    （2）将application.properties里面的用户名和密码改为自己的用户名和密码 root - root

    （3）将pom.xml里面的jdk版本改为自己的jdk版本

    （4）window -- 最后一项preferences--Maven--User settings--选择本地仓库--apply

    （5）选中项目--右键点击--Maven--Update Project--勾选Force Update
	