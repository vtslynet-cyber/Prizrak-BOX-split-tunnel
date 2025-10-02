# Ультимативный конфиг Mihomo для Prizrak-BOX 

Конфиг предназначен для использования внутри России и предоставляет расширенные правила маршрутизации трафика через прокси. Подходит для тестирования, примеров и персональной настройки. 

- Купить VPN ключ: [https://t.me/VTSLYVPN_bot](https://t.me/VTSLYVPN_bot)  
- Ссылка на Prizrak-BOX: [https://github.com/legiz-ru/Prizrak-Box/releases/tag/v1.0.19](https://github.com/legiz-ru/Prizrak-Box/releases/tag/v1.0.19)
-  Ссылка на Prizrak-BOX v1.0.20-alpha19: [v1.0.20-alpha19](https://github.com/legiz-ru/Prizrak-Box/releases/tag/v1.0.20-alpha1)
- В таком формате импорт профиля/ключа: `prizrak-box://install-config?url=(ключ)`

## Скриншоты

![Интерфейс](https://github.com/vtslynet-cyber/Prizrak-BOX-split-tunnel/blob/main/1.png)  
![Интерфейс](https://github.com/vtslynet-cyber/Prizrak-BOX-split-tunnel/blob/main/2.png)

## Возможности

- Разделение трафика по прокси-группам:
  - 🚫 Недоступные сайты
  - ▶️ YouTube
  - 💬 Discord
  - ➤ Telegram
  - 🟠 Cloudflare
  - ⚪🔵🔴 RU сайты
  - 🎮 Игры
  - 🔗 Торренты
  - 🌍 Остальные сайты
- Автоматический выбор прокси внутри группы «Любой доступный сервер»
- DIRECT для российских сайтов и приложений
- Поддержка IPv4 (IPv6 можно включить)
- Sniffer для HTTP/TLS трафика, автоматическое перенаправление
- Блокировка рекламы и нежелательных сайтов через списки OISD, ReFilter, ru-inline-banned и др.
- Поддержка популярных приложений и сервисов (Steam, Epic Games, Origin, Discord, Telegram, YouTube, Cloudflare и др.)
- Возможность исключений по процессам (например, для VPN, AnyDesk, RustDesk)

---

## Настройка

1. Скачайте Ссылка на Prizrak-BOX: [https://github.com/legiz-ru/Prizrak-Box/releases/tag/v1.0.19](https://github.com/legiz-ru/Prizrak-Box/releases/tag/v1.0.19)  
2. Откройте приложение , от имени Администратора. 

**Настройка через приложение Prizrak-BOX:**

1. Откройте приложение Prizrak-BOX.  
2. Перейдите во вкладку **Правило**.  
3. Выберите **Единое правило**.  
4. Скопируйте всё содержимое файла `split-tunnel.json` и вставьте в приложение.  
5. Включите ползунок и сохраните изменения.  
6. В приложении **выключите прокси** и выберите режим **Tun**.

---

## Источники правил

- Legiz  
- PentiumB  
- itdog  
- MetaCubeX / geosite / geoip  

---

## Важные замечания

- Используйте конфиг **только для тестирования** и как пример.  
- Возможны ошибки или перегрузка правил.  
- Внимательно изучите комментарии и документацию Mihomo: [https://wiki.metacubex.one/ru/config/](https://wiki.metacubex.one/ru/config/)  

---

