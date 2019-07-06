Git

### Git是什么?

​	Git是分布式版本控制系统

### 版本控制系统的作用

```markdown
1. 保存修改记录,更方便的恢复文件状态
2. 方便协同开发
```

### 分布式 Vs 集中式

​	集中式

![](E:\后期项目\补充知识\git\图片\2019-01-24_100407.png)

​	分布式

​			![](E:\后期项目\补充知识\git\图片\2019-01-24_100520.png)\

集中式版本控制系统的问题

```markdown
1. 网络原因导致工作时代码的上传下载速度限制
2. 服务器损坏或宕机时,无法正常进行工作
3. 本地条件下无法完成代码回退的需求
```

### Git的安装使用

```markdown
1. 从官方网站下载Git安装包
2. 傻瓜式安装
3.声明git的用户的名字和邮箱
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

### Git的常用指令

```markdown
1. $ git init 初始化版本库
2. $ git add XXX 将文件修改添加至暂存区
3. $ git commit | $ git commit -m "XXX" 将暂存区的所有内容提交至版本库
4. $ git status 查看版本库状态
			红色: 未添加
			绿色: 未提交
			cleaning: 已提交
```

### Git的版本回退

```markdown
1. $ git log 查看历史版本日志 展示详细的信息
	$ git log --pretty=oneline 展示精简版历史日志信息
2. $ git reset --hard 版本号 回溯某个版本 既可以向前 也可以向后
3. $ git reflog 查看所有版本日志信息 包括版本回溯的信息
```

### Git的工作区 | 版本库

![](E:\后期项目\补充知识\git\图片\2019-01-24_113105.png)

### Git的撤销修改

```markdown
1. git checkout XXX 撤销工作区的修改
2. git reset head XXX 撤销暂存区的修改
```

