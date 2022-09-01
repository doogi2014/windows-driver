参考：
http://www.coderjie.com/blog/0e045082ec5011e6841d00163e0c0e36
VS2013 WDK8.1驱动开发2（最简单的WDM驱动）

问题：
1 编译不过，需要修改MyDriver1.inf文件中的内容三处
a)
[DriverFilesName]                                   
MyDriver1.sys 
b)
[SourceDisksFiles]
MyDriver1.sys =1
c)
[SysAddService] 
ServiceBinary = %12%\MyDriver1.sys   