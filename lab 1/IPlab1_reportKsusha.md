University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [IP Telephony](https://github.com/itmo-ict-faculty/ip-telephony)

Year: 2022/2023

Group: K34202

Author: Anisimova Ksenia Alekseevna

Lab: Lab1

Date of create: 19.03.2023

Date of finished: 19.03.2023


## Цель работы: 
Изучить рабочую среду Cisco Packet Tracer, ознакомиться с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer.

### I часть

Схема изучена и собрана в Cisko Packet (рисунок 1).

![1KS](https://user-images.githubusercontent.com/56114211/226305553-ff4f39c7-722a-4780-8d85-e15f2a2f2022.png)

Рисунок 1 - созданная схема

Компьютерам назначены адреса в сети от 192.169.0.1 для PC0 до 192.169.0.7 PC6. На рисунке 2 показан терминал PC0 и назначенный ему IP адресс.

![2](https://user-images.githubusercontent.com/56114211/226305655-8aa5f8e4-9d21-445c-9e32-952d44367ca9.png)

Рисунок 2 - настройка PC0

После настройки всех IP-адресов, выполнена проверка работоспособности сети (рисунок 3).

![3KS](https://user-images.githubusercontent.com/56114211/226305739-e3f0cb52-2621-404c-af4a-22be5b3b2a74.png)

Рисунок 3 - проверка связности компьютеров

### II часть

Собрана новая схема сети. В ней изменено название для роутера на CMERouter (рисунок 4).

![4KS](https://user-images.githubusercontent.com/56114211/226305763-a16a4556-e87e-4078-ba37-d977eb498454.png)

Рисунок 4 - Схема сети 

Перед настройкой CMERouter следует включить питание в подключенных телефонах (рисунок 5).

![5](https://user-images.githubusercontent.com/56114211/226305795-175140fe-8e4d-40ac-8056-7f54bc79dcba.png)

Рисунок 5 - включение телефонов

Открыт терминал настройки CMERouter'а. В нем выполнена следующая настройка:
- IP-адрес для порта f0/0 (рисунок 6), 
- DHCP-сервер для передачи голоса и данных на маршрутизаторе (рисунок 6)
- Параметры VoIP (рисунок 7).

![6](https://user-images.githubusercontent.com/56114211/226305817-d56174eb-4a15-4110-b65f-e99a3e824524.png)

Рисунок 6 - настройка IP и DHCP

![7](https://user-images.githubusercontent.com/56114211/226305829-d46fccbd-31c5-4dca-acab-008f56437cd1.png)

Рисунок 7 - настройка параметров VoIP

Также настроен vlan у коммутатора для работы с VoIP (рисунок 8).

![8](https://user-images.githubusercontent.com/56114211/226305857-9a890ea0-defa-4116-8148-f20807b0d517.png)

Рисунок 8 - настройка vlan для работы с VoIP

В конце, для корректной работы заданы номера для подключенных телефонов (рисунок 9)

![9KS](https://user-images.githubusercontent.com/56114211/226305883-b6e3bbd1-7b6f-447e-b52f-47b1ea9538f9.png)

Рисунок 9 - команды для задания телефонных номеров

Для проверки выполнен прозвон с одного телефона на другой.

![10KS](https://user-images.githubusercontent.com/56114211/226305898-f38fcb2f-8903-4a11-b835-47309cb0d58d.png)

Рисунок 10 - прозвон с телефона 01 на 02

![11](https://user-images.githubusercontent.com/56114211/226305924-c61c2e02-b96c-47ce-9dbf-d2a0842117dd.png)

Рисунок 11 - прозвон с телефона 02 на 01

## Вывод
В результате выполнения лабораторной работы смоделировано несколько сетей в Cisco Packet Tracer, а также изучен принцип работы сетей VoIP.


