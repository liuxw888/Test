# 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？ 
	创建一个新的仓库   导入  创建一个新的新的平台  创建一个新的组织  
# 2.如何能将仓库中的html文件直接解析成页面？  
	首先找到网页所在的仓库，点击该网页，然后找到setting，之后在GitHub Pages中点击sourse中选中branch master  
# 3.如何删除仓库  
	一种是 git rm --cached "文件路径"，不删除物理文件，仅将该文件从缓存中删除；  
    一种是 git rm --f "文件路径"，不仅将该文件从缓存中删除，还会将物理文件删除（不会回收到垃圾桶  
# 5.Bash是什么操作系统的命令  
	linux系统  
# 6.Pwd是什么命令  
	打印当前的工作目录  
# 7.Cd是什么命令  
	切换目录  
# 8.Echo是什么命令  
	打印当前目录输出  
# 9.配置git用户名的命令  
	git config user.name "用户名"    
# 10.配置邮箱的命令  
	git config user.email '邮箱名'  
# 11.命令行换行方式  
	空格 斜杠 回车 继续命令： 
# 12.命令行终结方式  
	ctrl c  
# 13.使用命令行比GUI方式有何优势  
	能做一些GUI不能做的事情，比如命令行可以进行多个文件的操作，用命令行方式，GUI方式只能进行一个库的操作。  
# 14.提交到本地仓库时为什么有暂存区  
	这个试验说明当执行 “git status” 命令扫描工作区改动的时候，先依据.git/index 文件中记录的（工作区跟踪文件的）时间戳、长度等信息判断工作区文件是否改变。如果工作区的文件时间戳改变，说明文件的内容 可能 被改变了，需要要打开文件，读取文件内容，和更改前的原始文件相比较，判断文件内容是否被更改。如果文件内容没有改变，则将该文件新的时间戳记录到.git/index 文件中。因为判断文件是否更改，使用时间戳、文件长度等信息进行比较要比通过文件内容比较要快的多，所以 Git 这样的实现方式可以让工作区状态扫描更快速的执行，这也是 Git 高效的因素之一。
# 15.新建代码仓库的命令  
	git init  
# 16.git clone [url] 这个命令的作用是  
	将github上的文件或者仓库克隆到本地  
# 17.添加指定文件到暂存区的命令  
	git add
# 18.删除工作区文件，并且将这次删除放入暂存区的命令  
	git rm
# 19.改名文件，并且将这个改名文件放入暂存区的命令  
	git mv  
# 20.提交暂存区到仓库的命令  
	git add  
# 21直接从工作区提交到仓库的命令  
	git commit -a -m ""  
# 22.显示变更信息的命令  
	git status  
 #23.查看历史信息的命令  
	git log  
# 24.Commit的意义是  
	提交不同版本的文件  
# 25.Pull的意义是  
	将github上的仓库拉到本地来  
# 26.Push的意义是  
	将本地的仓库和文件推送到github仓库上去  
