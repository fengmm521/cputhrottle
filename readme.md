#mac下限制CPU使用率
因为有时间在笔记本上运行一个游戏，太耗CPU所以电脑风扇会一直响，如果不是很急的活，我们可以让CPU慢慢处理。
##编译：
cd到当前目录，运行
make
会生成一个可执行文件cputhrottle
用法
./cputhrottle 进程PID CPU限制使用率(0~100)
代码来源:
http://www.willnolan.com/cputhrottle/cputhrottle.html