### Mac快捷键

`command + c&v&z` 复制粘贴撤销

`command + l` 定位到网址栏

`command + r` 刷新网页

`command + shift + 4` 自由截图

`command + shift + 3` 全屏截图

### 常用shell命令

`open .` 打开当前所在文件夹子目录

`pwd` 查看当前目录

`mkdir` 新建文件夹

`touch` 新建文件

`ls` 查看当前目录文件夹及文件不包括隐藏文件

`ls -a` 查看当前目录文件夹及文件包括隐藏文件

`ls -l` 查看==详细信息==(drwxr-xr-x)rwx分别为:读写执行

`cd` 进入下层目录

`cd ..` 进入上层目录

`cd /Users/dllo/Desktop`
`cd ~/Desktop` 进入桌面绝对路径

`rm -rf Lesson` 递归直接删除(慎用)

`mv` 移动&重命名

`mv A.txt ../Desktop` (移动)

`mv A.txt ./B.txt` (重命名)

`cp` 复制

`./` 当前路径

`clear` 清屏

`pwd > A.txt` `ls -al > A.txt` 将内容写入文本文档A

`ls -a ~/ | grep git` 查看个人目录下关于git的文件

`netstat -ano` 
查看占用的端口号

### vi三种模式:

1. 命令模式 (vi)
	
- N dd : 删除N行内容
- hjkl : 移动光标
- x : 删除光标位置的字符
- X : 删除光标位置前的字符
- 0 (零): 光标移动到所在行首
- $ : 光标移动到所在行尾	
- gg : 光标移动到首行行首
- G: 光标移动到尾行行首
- u : 撤销

2. 插入模式

- i : 光标所在位置插入
- o : 另起一行插入 
- a : 光标后一位位置插入
- Esc : 从插入模式进入命令模式

3. 底行命令模式(:)
 
- set nu : 显示文档行号
- w : 保存文档
- q : 退出vi状态.(要先保存)
- q! 强制退出
