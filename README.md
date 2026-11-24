# Статус VPN-ключей

**Последняя проверка: 25.11.2026 00:41 МСК** · работает 4 из 9 · проверка с ноутбука SIN6 (прямой IP 5.187.86.30), заняла 240 с

| Ключ | Протокол | Сервер | Статус | Выход (IP, страна) | Задержка | Ошибка |
|---|---|---|---|---|---|---|
| VPNTYPE 🇮🇹 Milan | Shadowsocks | in-ru006.vpntype.dev:8388 | ✅ работает | 212.2.35.145 (DE) | 382 мс |  |
| 🇩🇪 Франкфурт 3 | VLESS Reality | fra3.vpntype.dev:8443 | ❌ не работает | — | — | сервер не принимает подключения на порт 8443 (таймаут) |
| 🇺🇸 Чикаго | VLESS Reality | chi1.vpntype.dev:8443 | ✅ работает | 88.216.68.162 (US) | 900 мс |  |
| 🇦🇪 Дубай 2 | VLESS Reality | dub2.vpntype.dev:8443 | ❌ не работает | — | — | сервер не принимает подключения на порт 8443 (таймаут) |
| AmneziaWG Амстердам 5 | AmneziaWG | ams5.vpntype.dev:2500 | ❌ не работает | — | — | сервер не принимает подключения на порт 2500 (таймаут) |
| AmneziaWG in-ru001 | AmneziaWG | in-ru001.vpntype.dev:2000 | ❌ не работает | — | — | сервер не принимает подключения на порт 2000 (ConnectionRefusedError) |
| OpenVPN in-ru001:1021 | OpenVPN UDP | in-ru001.vpntype.dev:1021 | ✅ работает | 88.216.68.162 (US) | 806 мс |  |
| OpenVPN in-ru006 (Milan) | OpenVPN UDP | in-ru006.vpntype.dev:1194 | ✅ работает | 147.45.60.38 (US) | 1032 мс |  |
| OpenVPN mos5 | OpenVPN UDP | mos5.vpntype.dev:1194 | ❌ не работает | — | — | error: tunnel: openvpn handshake error: context deadline exceeded |

Обновляется каждые 15 минут (задача «VPN Status Dashboard» на DESKTOP-SIN6RQ6). Хранится только последний результат, истории нет.
«Работает» = через ключ удалось выйти в интернет и внешний IP отличается от прямого. Задержка = время запроса к cloudflare.com/cdn-cgi/trace через туннель.
