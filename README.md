# Csharp---PLC
C#编写的PLC控制软件，整套物流传输系统只完成了单节点控制

上位机PC程序：将命令注写SQL

下位AGV小车程序，使用局域网读取SQL内命令，然后通过RS485控制PLC


PLC IO口：使用RS485连接发送命令控制辊链PLC


传感器读取：读取PLC返回命令，解析传感器状态


扫码器读取：常规串口返回


本人第一行代码，相当不规范
