# shadowrocket-proxy-configuration

Конфигурации и списки правил для приложения Shadowrocket, предназначенные для оптимизации работы прокси, блокировки рекламы и трекинга, а также обхода блокировок в Рунете.

## Описание

В репозитории представлены готовые конфигурационные файлы и списки правил для Shadowrocket:

### Конфигурационные файлы
- **shadowrocket_cellular.conf** — конфигурация для мобильной сети (через прокси YouTube и заблокированные ресурсы, реклама блокируется).
- **shadowrocket_wifi.conf** — конфигурация для Wi-Fi (YouTube напрямую, заблокированные ресурсы через прокси, реклама блокируется).

### Списки правил
- **shadowrocket_ad.list** — список блокировки рекламы и трекинга.
- **shadowrocket_ru_only.list** — правила для прямого доступа к российским сайтам и госуслугам.
- **shadowrocket_unblock.list** — список заблокированных ресурсов, доступных через прокси.

## Использование

Скопируйте нужные конфигурационные файлы и списки правил в Shadowrocket.


## Пример подключения конфигурации в Shadowrocket

```ini
https://raw.githubusercontent.com/milbrianler/shadowrocket-proxy-configuration/main/shadowrocket_wifi.conf
https://raw.githubusercontent.com/milbrianler/shadowrocket-proxy-configuration/main/shadowrocket_cellular.conf
```