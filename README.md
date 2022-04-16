# Домашнее задание к занятию "5.2.


## Обязательная задача 1

Основополагающим принципом IaaC является идемпотентность.
Преимущества это - применении одного и того же кода, тогда мы получим одну и тужу конфигурацию, так же легко прочитать и понять что из себя представляет вся инфраструктура. Также хорошая прослеживаемость изменения конфигурации.


## Обязательная задача 2

Для Ansible не требуется установки дополнительного пакета в виртуальной машине. Windows - WinRM, Linux - ssh.
Всю работу можно организовать с одного места.

Push более предпочтителен, так как запуск сценариев происходит с одного места, консоли управления. Этот метод более прозрачен чем Pull, в больших организациях, при неграмотном выбранной системе версионирования.


## Обязательная задача 3

ansible 2.7.7
     config file = /etc/ansible/ansible.cfg
     configured module search path = ['/root/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
     ansible python module location = /usr/lib/python3/dist-packages/ansible
     executable location = /usr/bin/ansible
     python version = 3.5.3 (default, Apr 26 2021, 11:58:09) [GCC 6.3.0 20170516]
 
 Vagrant 2.0.2
 
 Oracle VM VirtualBox VM Selector v6.1.28
(C) 2005-2021 Oracle Corporation
All rights reserved.
No special options.



