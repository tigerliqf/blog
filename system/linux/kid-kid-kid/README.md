## 孤儿进程 僵尸进程 守护进程

- 孤儿进程 ： 子进程尚未结束，父进程退出，子进程将托付给init进程

- 僵尸进程 子进程结束，发出结束信号给父进程，但是父进程没有接收到，子进程就变成了僵尸进程。并且会消耗一定的资源

- 守护进程，守护进程就是在后台运行,不跟任何终端关联的进程。
