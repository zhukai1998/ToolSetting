第一行 现在运行时间
机器启动时间
在线用户
系统负载 / 核心数，> 5 则高负载

第二行
总进程
运行中 
睡眠中
停止的
僵尸的

第三行
用户占用
内核占用
改变优先级的
空余的
等待输入输出的
硬中断
软中断

第四行
总内存，空余的，易用的，缓存
第五行
交换去，用于下一个进程分配的


top -b 批处理
-c 完整inkling
-d 刷新间隔时间
-u 指定用户
-p 指定进程
-n 循环几次退出

1 显示cpu详细
h 帮助界面
n 指定行数，0 指无限制
q 退出

l 显示/隐藏第一行负载信息
t 显示/隐藏第二三行CPU信息（按三次全部隐藏）
m 显示/隐藏第四五行内存信息（按三次全部隐藏）

M 内存排序
P cpu排序
T 进程时间排序
