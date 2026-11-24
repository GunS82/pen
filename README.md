# Статус VPN-ключей

**Последняя проверка: 25.11.2026 00:32 МСК** · работает 4 из 9 · проверка с ноутбука SIN6 (прямой IP 5.187.86.30), заняла 232 с

| Ключ | Протокол | Сервер | Статус | Выход (IP, страна) | Задержка | Ошибка |
|---|---|---|---|---|---|---|
| VPNTYPE 🇮🇹 Milan | Shadowsocks | in-ru006.vpntype.dev:8388 | ✅ работает | 212.2.35.145 (DE) | 391 мс |  |
| 🇩🇪 Франкфурт 3 | VLESS Reality | fra3.vpntype.dev:8443 | ❌ не работает | — | — | сервер не принимает подключения на порт 8443 (таймаут) |
| 🇺🇸 Чикаго | VLESS Reality | chi1.vpntype.dev:8443 | ✅ работает | 88.216.68.162 (US) | 880 мс |  |
| 🇦🇪 Дубай 2 | VLESS Reality | dub2.vpntype.dev:8443 | ❌ не работает | — | — | сервер не принимает подключения на порт 8443 (таймаут) |
| AmneziaWG Амстердам 5 | WireGuard | ams5.vpntype.dev:2500 | ❌ не работает | — | — | [31mERROR[0m[0002] [[38;5;104m1372783704[0m 0ms] connection: open connection to cloudflare.com:443 using outbound/wireguard[out]: WireGuard is not ready yet |
| AmneziaWG in-ru001 | WireGuard | in-ru001.vpntype.dev:2000 | ❌ не работает | — | — | нет ответа через туннель |
| OpenVPN in-ru001:1021 | OpenVPN UDP | in-ru001.vpntype.dev:1021 | ✅ работает | 88.216.68.162 (US) | 762 мс |  |
| OpenVPN in-ru006 (Milan) | OpenVPN UDP | in-ru006.vpntype.dev:1194 | ✅ работает | 147.45.60.38 (US) | 985 мс |  |
| OpenVPN mos5 | OpenVPN UDP | mos5.vpntype.dev:1194 | ❌ не работает | — | — | error: tunnel: openvpn handshake error: context deadline exceeded |

Обновляется каждые 15 минут (задача «VPN Status Dashboard» на DESKTOP-SIN6RQ6). Хранится только последний результат, истории нет.
«Работает» = через ключ удалось выйти в интернет и внешний IP отличается от прямого. Задержка = время запроса к cloudflare.com/cdn-cgi/trace через туннель.
