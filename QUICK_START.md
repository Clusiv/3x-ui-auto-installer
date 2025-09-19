# 🚀 Быстрый старт - 3X-UI Автоустановщик

## Установка за 1 команду

```bash
sudo bash <(curl -Ls https://raw.githubusercontent.com/Tsuev/3x-ui-auto-installer/main/3xui-intaller.sh)
```

## Что получите после установки

- **URL**: `http://YOUR_SERVER_IP:2053/wayvpn`
- **Логин**: `admin`
- **Пароль**: `admin`

## ⚠️ Важно

- Запускайте с правами root (`sudo`)
- Убедитесь, что порт 2053 открыт в файрволе
- **Обязательно смените пароль после первого входа!**

## 🔧 Основные команды

```bash
# Статус службы
systemctl status x-ui

# Перезапуск
systemctl restart x-ui

# Логи
journalctl -u x-ui -f
```

## 🆘 Нужна помощь?

- 📖 **Полная документация**: [README.md](README.md)
- 🐛 **Сообщить об ошибке**: [Issues](https://github.com/Tsuev/3x-ui-auto-installer/issues)
- 🔗 **Репозиторий**: [GitHub](https://github.com/Tsuev/3x-ui-auto-installer)

---
💡 **Совет**: После установки настройте файрвол и смените пароль для безопасности!