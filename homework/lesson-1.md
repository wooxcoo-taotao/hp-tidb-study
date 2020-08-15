# 第一期作业
## 题目描述：
### 本地下载TiDB，TiKV，PD源代码，改写源代码并编译部署以下环境：
* 1. 1 TiDB
* 2. 1 PD
* 3. 3 TiKV

### 改写后
* 使得TiDB启动事务时， 会打印一个“hello transaction”的日志

## 资源：
  ###公司虚拟机
   * liuping@env-01.dev:/data/tidb [TESTING]$ uname -a
   *    Linux env-01 4.15.0-29-generic #31-Ubuntu SMP Tue Jul 17 15:39:52 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
   * cpu
   liuping@env-01.dev:/data/tidb [TESTING]$ cat /proc/cpuinfo | grep "processor" | wc -l
96
   * mem
   liuping@env-01.dev:/data/tidb [TESTING]$ free -h
              total        used        free      shared  buff/cache   available
Mem:           187G         21G        128G         20M         38G        164G
Swap:          952M         15M        937M

