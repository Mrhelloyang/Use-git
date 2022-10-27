# Use-git

### 1git的初始化
git  config --global user.name Mrhelloyang命名<br>
git  config --global user.email 2131424889@qq.com选择邮箱<br>


### 2下载github文件<br>
git clone+（文件的GitHub链接）<br>


### 3创建管理文件.git文件<br>
git init<br>


### 4提交项目<br>
全部项目<br>
git add .["."是指当前文件夹（准备提交，暂存区）]<br>
git commit -m"备注"#备注一定要写（仓库）<br>
查看<br>
git log<br>

提交单个文件<br>
git add 文件名<br>
git commit -m "备注"<br>


### 5删除一个文件<br>
必须在里面有个“.git"文件<br>
rm 文件名<br>
