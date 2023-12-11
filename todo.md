### 进程启动
Fork()创建一个新的子进程    exec1()    执行代码   退出进程 exit_group   等待子进程回收 wait4()
1. 实现守护进程demo


### suid && sgid
/etc/shadow 超级用户可以查看
https://www.cnblogs.com/fhefh/archive/2011/09/20/2182155.html
https://www.runoob.com/linux/linux-comm-ls.html
1. 实现suid sgid demo


### signal
https://gityuan.com/2015/12/20/signal/
1. 实现系统中断demo
2. 实现信号屏蔽demo
3. 实现信号处理函数demo

### systemd
https://zhuanlan.zhihu.com/p/419372683


### tty 终端  pty  pts 模拟终端
https://zhuanlan.zhihu.com/p/42771810

### 进程间通信
1.  匿名管道
2.  具名管道
3.  共享内存
4.  信号量 （加锁的 mutex 条件变量 cond）
5.  消息队列  数据存储在内核中
6.  套接字 unix socket
7.  信号

### 网络进程间通信
1.  socket
