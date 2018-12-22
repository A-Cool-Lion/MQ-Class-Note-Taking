### git

`git init` 将当前文件夹初始化为本地git仓库, 初始化成功后, 在该文件夹下的所有文件. 如果出现变更, 都会被git发现: `1 file changed, 0 insertions(+), 0 deletions(-)`

`git status` 查看当前状态

- 出现红色文件: 表示该文件为新增文件, 还没有被git所管理(未添加到暂存区)
- new file, 绿色: 该文件为新增到暂存区的文件
- modifile, 红色: 代表该文件有修改
- modifile, 绿色: 修改的文件添加到了暂存区

`git add 'file_path'` 把文件添加到暂存区

`git add .` 把所有文件添加到暂存区

`git commit -m '备注'` 将暂存区的所有文件都提交到本地仓库

`git log` 显示详细的提交历史 `q` 退出

`git reflog` 显示比较简洁的提交历史及变更历史

### 修改user

`git config --global user.name "runoob"`
`git config --global user.email test@runoob.com`

### 时光机

1. `git reflog` 在本地git仓库文件夹下
2. `git reset --hard 4edf568(ID)` 回到相应ID的版本

### 绑定一个远程仓库

1. `git remote add origin https://github.com/jomplte/gitlearn.git` 将本地仓库绑定一个远程仓库

2. - `git push -u origin master` 第一次推送

![image](https://ws4.sinaimg.cn/large/006tKfTcly1fss1l46cm2j30cz04rt98.jpg) 
   - `git push` 本地仓库推送到远程仓库

### 从远程仓库把代码克隆到本地

`git clone https://github.com/jomplte/gitlearn.git`

### 团队协作
`git pull origin master` 拉取