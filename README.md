Util
====
Testjar 

通过IP获取MAC地址也可以用nbtstat命令，但是nbtstat获取不到ipad的mac地址，所以现在改用arp命令获取mac地址， 但通过arp命令获取地址只能是与服务器有过通信的才能查看，所以在代码中有一次ping一次对方IP的方法， 1、确保IP通信正常； 2、建立与对面IPAD的通信 详细见代码
