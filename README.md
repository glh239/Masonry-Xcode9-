
Masonry用Xcode9创建,运行崩溃问题,Terminating app due to uncaught exception 'NSInvalidArgumentException'解决办法
Xcode9创建项目 使用Masonry运行崩溃问题解决办法
我的报错Terminating app due to uncaught exception 'NSInvalidArgumentException', 
reason: '-[UIView mas_makeConstraints:]: unrecognized selector sent to instance 0x14550b6f0'



解决办法是点击项目 ->Build Phases ->Compile Sources 把Masonry的所有.m文件加进去就行

