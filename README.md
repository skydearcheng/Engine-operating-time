# Engine-operating-time

This group of numbers is from a presentation Jeff Dean gave at a Engineering All-Hands Meeting at Google.

L1 cache reference 0.5 ns//一级缓存操作 0.5ns

Branch mispredict 5 ns//分支预测失误 5ns

L2 cache reference 7 ns//二级缓存操作 7ns

Mutex lock/unlock 100 ns//互斥锁加锁/解锁 100ns

Main memory reference 100 ns//主内存操作 100ns

Compress 1K bytes with Zippy 10,000 ns//通过 zippy 压缩 1k 字节 10,000ns 即 10us

Send 2K bytes over 1 Gbps network 20,000 ns//通过 1Gbps 网络发送 2k 字节 20,000ns 即 20us

Read 1 MB sequentially from memory 250,000 ns//从内存中顺序读取 1MB 数据 250,000ns 即 250us

Round trip within same datacenter 500,000 ns//同一数据中心内往返 500,000ns 即 500us

Disk seek 10,000,000 ns//磁盘搜索 10,000,000ns 即 10ms

Read 1 MB sequentially from network 10,000,000 ns//从网络顺序读取 1MB 数据 10,000,000ns 即 10ms

Read 1 MB sequentially from disk 30,000,000 ns//从磁盘顺序读取 1MB 数据 30,000,000ns 即 30ms

Send packet CA->Netherlands->CA 150,000,000 ns//发送数据包从 CA->Netherlands->CA 150,000,000ns 即 150ms
