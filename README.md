# Сеть
adm- 10.0.0.2
     255.255.255.0
     10.0.0.3

open 10.0.0.3
     255.255.255.0
     10.0.0.2
     
oper 10.0.0.4
     255.255.255.0
     10.0.0.1

client 192.168.100.2
       255.255.255.192
       192.168.100.1
coord 1-
eth0
172.16.0.1
255.255.255.224
eth 1 
10.0.0.1
255.255.255.0
Ip-172.16.0.2
coord 2-
eth0
172.16.0.2
255.255.255.224
eth1
192.168.100.1
255.255.255.192
Ip 172.16.0.1
pass-xxXX1234

## Роли компонентов
Coor1,2 Coordinator HV-VA
OperCa Busnise mail, Vipnet Client, Registration Point
## филтры
Ист 10.0.0.3
Назначение мой узел
Порты 9000-9900
+ new уч admindb
+ ![image](https://github.com/Tanonagod/-VipNet-/assets/171233356/a41ee1b6-8d32-4544-9f73-0e406ad8a016)
+ 
