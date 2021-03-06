![easymodbus4j运行效果图截屏](https://github.com/zengfr/easymodbus4j/blob/master/easymodbus4j-example/src/main/resources/capture.PNG?raw=true)
# easymodbus4j
easymodbus4j
A high-performance and ease-of-use implementation of the Modbus protocol written in Java netty support for modbus 4 mode client/server.
<pre>
easymodbus4j 特点:
1、Netty NIO high performance高性能.
2、Modbus Function sync/aync 同步/异步非阻塞。
3、完全支持4种部署模式: 服务器master,客户端slave,服务器slave,客户端master。
4、友好的调试以及日志支持bit\bitset\byte\short\int\float\double。
5、Supports Function Codes:
Read Coils (FC1)
Read Discrete Inputs (FC2)
Read Holding Registers (FC3)
Read Input Registers (FC4)
Write Single Coil (FC5)
Write Single Register (FC6)
Write Multiple Coils (FC15)
Write Multiple Registers (FC16)
Read/Write Multiple Registers (FC23)
</pre>
#Example Code in https://github.com/zengfr/easymodbus4j

[Repositories Central Sonatype Mvnrepository easymodbus4j](https://mvnrepository.com/artifact/com.github.zengfr/easymodbus4j)
``` 
maven:
<dependency>
<groupId>com.github.zengfr</groupId>
<artifactId>easymodbus4j</artifactId>
<version>0.0.1</version>
</dependency>
``` 
<pre>
Example run startup:
1、unzip file easymodbus4j-release.zip.
2、for modbus master mode:open autosend.txt file in dir or autosend.txt rsourcefile in easymodbus4j.jar 
3、for modbus master mode:edit autosend.txt file
4、start startup.bat.
5、you also can edit *.bat for modbus master/salve mode: .
说明:
1、解压缩zip文件到文件夹
2、java程序 运行不了 则安装jdk8.
3、解压后4个bat文件  对应 服务器master,客户端slave,服务器slave,客户端master 4种模式.
4、Master模式 可以设置autosend.txt文件，定时发送读写请求。
5、记事本打开bat文件可以编辑相关参数，如定时延时发送时间以及详细日志开关。
</pre>
![easymodbus4j运行效果图截屏](https://github.com/zengfr/easymodbus4j/blob/master/easymodbus4j-example/src/main/resources/capture.PNG?raw=true)

