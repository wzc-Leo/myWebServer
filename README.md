编译： make

清除.o文件： make clean

服务器运行：./server+port

测试页：106.12.207.167:8000


基于epoll+threadpool实现的小型webserver，支持GET、POST方法(两数相加返回结果)

使用Epoll边沿触发的IO多路复用技术，非阻塞IO

可以解析返回html、css、js、mp3、mp4、jpg、png等文件。


