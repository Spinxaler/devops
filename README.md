Ответы к заданию 3.7

1.

![изображение](https://user-images.githubusercontent.com/16610642/153714764-89a393fb-dbe0-45d4-bf17-8768063abdb6.png)
![изображение](https://user-images.githubusercontent.com/16610642/153714792-a2d7aabe-c934-4294-a7c7-68641836d574.png)


2.

Link Layer Discovery Protocol (LLDP) - протокол.
lldpd - пакет

![изображение](https://user-images.githubusercontent.com/16610642/153715317-6fb18579-5b94-49a6-ac61-4c13dd928d3d.png)


3.

Технология VLAN (Virtual Local Area Network). 
Vlan - пакет.  Настройка или через конфиг файлы интерфейсов, если без сохранения после перезагрузки то через команду vconfig.

![изображение](https://user-images.githubusercontent.com/16610642/153715858-be62f58d-6fa2-472f-815c-ae63c18e7a22.png)


4.

0 (balance-rr), 1 (active-backup), 2 (balance-xor), 3 (broadcast), 4 (802.3ad), 5 (balance-tlb), 6 (balance-alb).

        auto bond0 eth0 eth1

        iface bond0 inet static

        address 192.168.0.120
        
        netmask 255.255.255.0
        
        gateway 192.168.0.254
        
        bond-slaves eth0 eth1
        
        bond-mode balance-alb
        
        bond-miimon 100
        
        bond-downdelay 200
        
        bond-updelay 200

5.

Сколько IP адресов в сети с маской /29  - 8 адресов. Сколько /29 подсетей можно получить из сети с маской /24 - 32 сети.  Приведите несколько примеров /29 подсетей внутри сети 10.10.10.0/24 - 10.10.10.32/29   10.10.10.40/29

6.

192.0.2.0/26

7.
![изображение](https://user-images.githubusercontent.com/16610642/153751761-34056b71-acb8-4756-98c2-f0766500090f.png)

![изображение](https://user-images.githubusercontent.com/16610642/153751787-82eee9ac-661a-42d2-b60e-ca97c81ebc13.png)


ip neigh flush 192.168.0.211 удалить МАС от определённого IP. 

ip neigh flush ALL  - удалить все записи.









