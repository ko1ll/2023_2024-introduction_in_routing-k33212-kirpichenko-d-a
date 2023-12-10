University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction in routing](https://github.com/itmo-ict-faculty/introduction-in-routing)  
Year: 2023/2024  
Group: K33212  
Author: Kirpichenko Daniil Aleksandrovich
Lab: Lab4
Date of create: 10.12.2023  
Date of finished: 11.12.2023  


# Лабораторная работ №3 "Эмуляция распределенной корпоративной сети связи, настройка iBGP, организация L3VPN, VPLS"

### Цель работы
Изучить протоколы BGP, MPLS и правила организации L3VPN и VPLS.

### Ход работы
- Вам необходимо сделать IP/MPLS сеть связи для "RogaIKopita Games" изображенную на рисунке 1 в ContainerLab. Необходимо создать все устройства указанные на схеме и соединения между ними.- Настроить OSPF и MPLS.
- Помимо этого вам необходимо настроить IP адреса на интерфейсах.
- Настроить OSPF и MPLS.
- Настроить iBGP с route reflector кластером

#### Первая часть:

- Настроить iBGP RR Cluster.
- Настроить VRF на 3 роутерах.
- Настроить RD и RT на 3 роутерах.
- Настроить IP адреса в VRF.
- Проверить связность между VRF
- Настроить имена устройств, сменить логины и пароли.

#### Вторая часть:

- Разобрать VRF на 3 роутерах (или отвязать их от интерфейсов).
- Настроить VPLS на 3 роутерах.
- Настроить IP адресацию на PC1,2,3 в одной сети.
- Проверить связность.


## Yaml файл с настройкой сети

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/52.jpg)

## Схема сети

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/51.jpg)

## Настройка NY

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/42.jpg)


## Настройка SPB

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/43.jpg)


## Настройка SVL

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/44.jpg)


## Настройка HKI

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/45.jpg)

## Настройка LND

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/46.jpg)


## Настройка LBN

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/47.jpg)


## Настройка PC1 (вторая часть)

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/34.jpg)

## Настройка PC2 (вторая часть)

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/35.jpg)

## Настройка PC3 (вторая часть)

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/33.jpg)

## Настройка SVL (вторая часть)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/36.jpg)
## Настройка NY  (вторая часть)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/37.jpg)
## Настройка SPB (вторая часть)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/38.jpg)



## Проверка сети (первая часть)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/48.jpg)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/49.jpg)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/50.jpg)

## Проверка сети (вторая часть)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/39.jpg)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/40.jpg)
![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/41.jpg)


