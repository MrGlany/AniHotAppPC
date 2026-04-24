# AniHotAppWindows

Приложение с удобным интерфейсом для просмотра аниме-сериалов.

## Тестирование

Приложение проверялось на:

- Linux Mint
- Arch Linux (KDE Plasma)

## Установка на Linux

На Arch Linux приложение можно установить командой:

`yay -S anihot-app`

## Linux: обязательная зависимость

Если `SQLite` ещё не установлен в системе, установите пакет для вашего дистрибутива:

- Ubuntu/Debian: `sudo apt install libsqlite3-0`
- Arch Linux: `sudo pacman -S sqlite`
- Fedora: `sudo dnf install sqlite-libs`
