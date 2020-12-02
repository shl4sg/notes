#### vfs

虚拟文件系统(VFS) 位于文件系统的最上层，管理各种逻辑文件系统，并可以屏蔽各种逻辑文件系统之间的差异，提供统一文件和设备的访问接口。

#### 设置自启动

“/etc/rc.local”，把启动程序的shell命令输入进去即可

#### 设置定时任务

cron，设置cron_tab



#### Linux命令

linux查看tcp的状态命令：
1) netstat -nat 查看TCP各个状态的数量
2)lsof -i:port 可以检测到打开套接字的状况
3) sar -n SOCK 查看tcp创建的连接数
4) tcpdump -iany tcp port 9000 对tcp端口为9000的进行抓包

##### 查找文件命令

find [path] [option] [commond]

**复制** cp

**重命名** mv

**批量重命名** rename

**移动** mv

##### 删除

rm

##### 从文件中找字符串

grep [str] [filename]

##### vim打开文件

vim

##### 查看文件内容

cat

##### 查看网络接口状态

ifconfig

##### 查看linux手册

man

##### 查看文件和文件夹

ls ll

##### 切换工作目录

cd

##### 按资源占有率从大到小显示进程

top

##### 创建文件夹

makedir

##### 创建空文件或修改时间戳

touch

##### 查看磁盘使用情况

df