![1601363873853](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601363873853.png)

## 版本控制：

![1601341902846](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601341902846.png)

![1601342039961](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601342039961.png)

在git中的绝大多数操作都是只需要访问本地文件和资源，一般不需要来自网络上其他计算机的信息。

### 特性：

1. 短啊往后依旧可以在本地对项目就行项目版本管理
2. 联网后，把本地修改的几率同步到云端服务器即可。

**git三个区域：**

1. 工作区
2. 暂存区
3. git仓库

![1601343847961](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601343847961.png)

![1601345323929](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601345323929.png)

![1601345637971](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601345637971.png)

![1601346362087](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601346362087.png)

![1601346770229](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601346770229.png)

## 获取git仓库的两种方式：

以下两种方式都能够在自己的电脑上得到一个可用的git仓库

1. 将本地文件转换为git仓库
2. 从其他服务器克隆一个已存在的git仓库

初始化仓库 ：  `git  init`    创建一个隐藏的.git 文件夹

### 工作区中文件的4种状态：

![1601347772191](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601347772191.png)

**git status  检查目录文件状态**

**git status -s  已精简方式显示状态**

**git add 开始跟踪一个文件并添加到暂存区    git add  后面加文件名**

clear 快速清空终端

git commit 提交更新   git commit -m "提交的更新说明"

![1601351014933](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601351014933.png)

撤销对文件的修改： git checkout  -- 文件名

![1601359401717](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601359401717.png)

`git add .` 向暂存区中一次性添加多个文件

`git reset HEAD` 要移除的文件名     从暂存区中移除对应的文件

#### 跳过使用暂存区：`git commit -a -m`

![1601361648281](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601361648281.png)

#### 移除文件：

1. 从git暂存区中同时移除对应的文件  `git rm -f`  加文件名
2. 只从git暂存区中移除指定的文件   `git rm --cached`   加文件名

## 忽略文件：

![1601364234087](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601364234087.png)

![1601363774920](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601363774920.png)

#### 查看历史：`git log`

![1601366859312](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601366859312.png)

## 回退到指定版本：

![1601367598064](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601367598064.png)

 

![1601368394508](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1601368394508.png)

