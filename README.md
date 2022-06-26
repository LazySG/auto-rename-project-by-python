# auto-rename-project-by-python

自动重命名，python实现，作者申懒腰，还有很多不足的地方，懒得改了，开源给大家，平时办公用用还是很方便的



### 1.环境配置

1. 安装python3.6 以上版本, 并配置环境变量

教程：https://www.runoob.com/python3/python3-install.html

​    

2. 安装依赖包

方法：在cmd中（win+R 输入cmd 回车）输入

pip install xlrd 回车

pip install xlwt 回车

​    

3. 打开文件，会看到名为main 的文件夹，打开后有一个main.py ,该文件为程序入口，运行即可进入程序

 

4. 程序进入后会看到两个选项，一个是一键获取文件名，另一个是自定义重命名。右下角是退出，点击退出会终止程序，点击另外两个选项会跳转到另一个页面。

 

5. 一键获取文件名：点击后会看到一个新页面，其中有两个文本框，一个是需要获取的文件夹路径，另一个是生成的文件路径，填写第一个会把该路径下的所有文件名去掉后缀并放入一个名为 Message.xls 的excel表中，生成的文件路径即为Message.xls的保存路径，填写后会在该路径文件夹下生成名为Message.xls的文件，Message.xls文件中存放的就是需要获取的文件夹路径中的所有文件去除后缀的名字。下方的刷新会清空路径内容，一键生成则会执行操作生成Message.xls文件，如果路径为空会抛出异常和错误提示，如果成功也会有提示。左下角的返回会回到上一个页面，退出就终止程序。

 

6. 自定义重命名：点击会看到分隔符，文件后缀名，文件夹路径和xls路径。其中命名规则是用分隔符把excel表某行对应的列的全部内容用分隔符连接在一起，再加上文件后缀，如果填默认为空字符串。文件夹路径为需要改名的所有文件所在的文件夹。文件xls路径为存放提前命名好名字的excel文件，点击一键重命名即可执行。
