University: ITMO University 
Faculty: FICT 
Course: IP-telephony 
Year: 2022/2023 
Group: K34202 
Author: Anisimova Ksenia 
Lab: Lab1 
Date of create: 14.04.2023 
Date of finished: 15.04.2023 
# Лабораторная работа №2 "Конфигурация voip в среде Сisco packet tracer"
## Описание

Для выполнения данной лабораторной работы собирается схема соединения. Необходимо проверить, правильно ли подключены все узлы устройств. Предварительно удалить все преды- дущие конфигурационные файлы на маршрутизаторах Cisco 2811, на коммутаторе Cisco catalyst 3560.

## Цель работы:
Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

## Ход работы:

В процессе выполнения лабораторной работы были выпонены следующие шаги:
1. Построена топология сети, которая включает компьютеры, коммутаторы и роутер.

![226111767-13fcd8f0-4ae9-45b7-9f0d-ce620fa445f0](https://user-images.githubusercontent.com/56114211/232223006-981d76d4-1720-4193-9525-df54111554e9.png)


2. В конфигурационном режиме изменено название маршрутизатора на CMERouter.
Отключен синтаксис ввода слов от DNS серверов с помощью команды no ip domain-lookup.


3. Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.

![226111876-2e98ef9b-1d33-4b35-a9b4-71de7e35d273-2](https://user-images.githubusercontent.com/56114211/232223113-3ce041fc-6e82-4633-8435-b510c781e60a.png)


4. Настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).

![226110660-4c0bd2d8-dc6e-4360-84ab-d5d4ba4e46d6](https://user-images.githubusercontent.com/56114211/232223144-ad5d6f42-fdf6-4e60-8212-c252aa9a18ec.png)


5. Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе Cisco 2811. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.

![226110760-1848636d-4066-4f96-b4d1-c6d36c9e577a](https://user-images.githubusercontent.com/56114211/232223188-04cfc747-2877-4a4e-8818-f448d81ee7a0.png)

![226110963-ac032ecb-2eb1-4d25-b142-7a37ff90a92d](https://user-images.githubusercontent.com/56114211/232223587-eb57aa51-8b40-408f-9815-54ede7f30371.png)


6. Созданы VLAN порты на коммутаторе Cisco Catalyst 3560 для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны. Настроены IP-телефоны и соединены с коммутатором Cisco Catalyst 3560.

![226111051-fa558b74-6938-4e65-a42f-de6a004c9606](https://user-images.githubusercontent.com/56114211/232223633-c332af17-8320-47c4-a25f-a70e304820bc.png)


![226111163-67bb291a-5a50-4aab-a0a8-182e8c9be021](https://user-images.githubusercontent.com/56114211/232223233-4e5df4ea-4e85-4497-98db-de232c9d614d.png)


7. Проверены звонки между телефонами.

![226111592-be6208b4-a036-4423-818b-3ec6a4d518f2](https://user-images.githubusercontent.com/56114211/232223274-7ee5a0f0-67db-4cb5-8dd5-852492fe90b0.png)

8. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.

![226112168-19b2d981-4f2b-4a2a-8872-066dd844beb0](https://user-images.githubusercontent.com/56114211/232223356-61a7a603-1e9e-498f-a12c-d2b95dca04f7.png)

![226112832-49a38080-74d2-4382-9445-3e813b6b65f8](https://user-images.githubusercontent.com/56114211/232223684-c6f5a588-74ef-4ced-bfb7-1f1d580ac22d.png)


9. Задан маршрут по умолчанию командой  ip default-gateway.

10. Настроен порт как канал типа trunk.

![226112598-75ce35b5-f08c-4c6b-8f40-a748ca83aabf](https://user-images.githubusercontent.com/56114211/232223387-1113fca2-c82d-40ba-ad70-16cb036a9e0b.png)

![226112675-8ec3e3ec-cfd8-4964-8c74-7450456f4d0f](https://user-images.githubusercontent.com/56114211/232223743-beec4889-cdb2-4c1a-9121-2fb6dbbe9919.png)


11. Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе Cisco 2811. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе. Настроены IP-телефоны и соединены с коммутатором. Подключены конечные узлы устройств.

![226112906-b977ef34-fcde-4bee-998c-33581fd1fada](https://user-images.githubusercontent.com/56114211/232223806-6254b724-4ef5-4bac-bd0e-be3d3ad95634.png)


![226112948-3a83d206-fb2b-4e05-a39b-703e1d18853e](https://user-images.githubusercontent.com/56114211/232223415-7ec11f97-d843-47bf-8f4c-22f8110dc591.png)

![226121120-9b091b54-1d92-44fc-bc56-c0fe8089467e](https://user-images.githubusercontent.com/56114211/232223422-3a8e147e-5e8e-461c-84f3-6aa4b2af58c4.png)


12. Проверены звонки между телефонами

![226121168-eead5dc4-1a2b-4818-8ab7-a731ca25aad1](https://user-images.githubusercontent.com/56114211/232223446-de168731-c7a7-45ef-9436-190f51f54abd.png)

![226122219-9d833d2e-6389-4a9a-9af6-c28df6e6cecf](https://user-images.githubusercontent.com/56114211/232223452-7301b593-1b6f-4421-bd85-76515d207bf9.png)


## Выводы
Таким образом, была изучена схема настройки IP-телефонии с помощью CallManager Express.



