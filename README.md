<div align="center">

# AniHot App

**Твои любимые истории — на большом экране.**

Десктопное приложение для просмотра аниме на **Windows и Linux**. Удобный поиск, личная библиотека, нативный плеер и общение с друзьями. Без рекламных баннеров.

[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MrGlany/AniHotAppPC/releases/latest)
[![Linux](https://img.shields.io/badge/Linux-supported-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/MrGlany/AniHotAppPC/releases/latest)
[![Latest release](https://img.shields.io/github/v/release/MrGlany/AniHotAppPC?style=for-the-badge&label=Release&color=7C3AED)](https://github.com/MrGlany/AniHotAppPC/releases/latest)

<br>

[![Скачать для Windows и Linux](https://img.shields.io/badge/%E2%AC%87%20%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C-Windows%20%7C%20Linux-C52B87?style=for-the-badge)](https://github.com/MrGlany/AniHotAppPC/releases/latest)

**[Сайт](https://anihot.app)** · **[Новости в Telegram](https://t.me/anihot_news)** · **[Поддержка](https://t.me/Enagie)**

<sub>Официальный репозиторий десктопных релизов AniHot App от Glany Studio.</sub>

</div>

---

## ✨ AniHot App на компьютере

| | Возможность |
|:---:|---|
| 🖥️ | **Интерфейс для ПК.** Боковая навигация, сетки постеров, адаптация под размер окна, поиск по `Ctrl + K`. |
| 🎞️ | **Каталог аниме.** Поиск, фильтры, последние обновления, онгоинги, подборки и страница тайтла. |
| ▶️ | **Нативный плеер.** Выбор источника, озвучки и серии, прогресс просмотра, полноэкранный режим. |
| ✨ | **Anime4K.** Дополнительные шейдеры обработки видео, если оборудование их поддерживает. |
| 💗 | **Личная библиотека.** Избранное, категории, коллекции, история, импорт и синхронизация с аккаунтом. |
| 📥 | **Загрузки.** Управление загруженными сериями и очередью скачивания. |
| 👥 | **Совместный просмотр.** Комнаты с синхронизацией воспроизведения, текстовым чатом и голосовой связью. |
| 💬 | **Сообщество.** Друзья, профили, переписка, комментарии, оценки и рецензии. |

### 🎥 Плеер для большого экрана

В AniHot App используется **DirectMPV** — встроенный плеер для комфортного просмотра:

- Выбор источника, озвучки и серии.
- Продолжение с места остановки и работа с потоковым видео.
- Постоянный сетевой кэш для воспроизведения (не заменяет полноценные офлайн-загрузки).
- Мини-плеер и режим «картинка в картинке» с учётом возможностей оконной системы.

> [!NOTE]
> Возможности видеовывода, PiP и Anime4K зависят от графического окружения, драйверов, оборудования и формата источника.

---

## ⬇️ Скачать AniHot App

<div align="center">

### [🚀 Открыть последний релиз для Windows и Linux](https://github.com/MrGlany/AniHotAppPC/releases/latest)

</div>

| Платформа | Формат релиза | Установка |
|---|---|---|
| **Windows 10 / 11** | `*-windows.zip` | Скачай архив из **Assets**, распакуй его и запусти приложение из распакованной папки. |
| **Linux** | `*-linux.zip` | Скачай архив из **Assets**, распакуй и запусти сборку согласно содержимому пакета. |
| **Arch Linux / AUR** | `anihot-app` | Можно установить через AUR — команда ниже. |

### 🪟 Windows

1. Перейди в [Releases](https://github.com/MrGlany/AniHotAppPC/releases/latest).
2. Скачай архив с суффиксом **`-windows.zip`**.
3. Распакуй архив в отдельную папку и запускай приложение оттуда.

**Важно:** не запускай отдельный EXE прямо из ZIP — для работы приложения могут требоваться соседние файлы и библиотеки.

### 🐧 Linux

**Arch Linux (AUR):**

~~~bash
yay -S anihot-app
~~~

**Остальные дистрибутивы:** скачай архив **`-linux.zip`** из [Releases](https://github.com/MrGlany/AniHotAppPC/releases/latest).

Если приложение не запускается, проверь наличие необходимых системных пакетов. Часть компонентов уже может входить в архив приложения.

<details>
<summary><b>Команды установки системных библиотек</b></summary>

<br>

**Ubuntu / Debian**

~~~bash
sudo apt install libsqlite3-0 mpv
~~~

**Arch Linux**

~~~bash
sudo pacman -S sqlite mpv
~~~

**Fedora**

~~~bash
sudo dnf install sqlite-libs mpv
~~~

</details>

**Проверенные в проекте окружения:** Windows 10/11, Linux Mint и Arch Linux (KDE Plasma). Работа на других дистрибутивах и конфигурациях может отличаться.

> [!TIP]
> Новые версии и список изменений публикуются в [истории релизов](https://github.com/MrGlany/AniHotAppPC/releases). После скачивания обновления не удаляй пользовательские данные приложения вручную.

---

## 💜 Больше, чем просто плеер

<details>
<summary><b>Персональная библиотека</b></summary>

<br>

Сохраняй аниме в избранное, распределяй по своим категориям, отслеживай историю, составляй коллекции и управляй загрузками. Предусмотрен импорт библиотеки из Anixart и Shikimori.

</details>

<details>
<summary><b>Совместный просмотр и общение</b></summary>

<br>

Смотри серии вместе с друзьями в комнатах, общайся во время просмотра через текстовый чат или голосовую связь. Также доступны личные сообщения и социальные функции.

</details>

<details>
<summary><b>Отзывы, достижения и профиль</b></summary>

<br>

Оценивай просмотренное, пиши рецензии, получай достижения, настраивай профиль и находи друзей. Некоторые дополнительные функции зависят от статуса аккаунта.

</details>

---

## ❔ Частые вопросы

**Есть ли версия для Android?**  
Да — APK выпускается в отдельном [репозитории AniHotAppAndroid](https://github.com/MrGlany/AniHotAppAndroid).

**Нужен ли интернет?**  
Для каталога, аккаунта и потокового просмотра требуется подключение к сети. Некоторые ранее загруженные файлы могут быть доступны локально.

**Почему нет установщика?**  
В текущих GitHub-релизах для Windows и Linux опубликованы ZIP-архивы. Актуальный состав поставки всегда смотри в **Assets** конкретного релиза.

**Где исходный код?**  
Этот репозиторий предназначен для готовых сборок и файлов обновления. Исходный код не опубликован здесь.

---

## 💬 Ссылки и поддержка

| Ресурс | Ссылка |
|---|---|
| 🌐 Официальный сайт | [anihot.app](https://anihot.app) |
| 📢 Новости и анонсы | [Telegram · AniHot News](https://t.me/anihot_news) |
| 🛠 Вопросы и помощь | [Telegram · @Enagie](https://t.me/Enagie) |
| 📱 Android-версия | [AniHotAppAndroid](https://github.com/MrGlany/AniHotAppAndroid) |
| 📋 Условия распространения | [Лицензия](LICENSE_RU.md) |

---

## ⭐ История звёзд

<div align="center">

<a href="https://www.star-history.com/?repos=MrGlany%2FAniHotAppPC&type=date&legend=bottom-right">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=MrGlany/AniHotAppPC&type=date&legend=bottom-right&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=MrGlany/AniHotAppPC&type=date&legend=bottom-right" />
    <img alt="История звёзд AniHotAppPC" src="https://api.star-history.com/chart?repos=MrGlany/AniHotAppPC&type=date&legend=bottom-right" width="800" />
  </picture>
</a>

<sub>Нажми на график, чтобы открыть интерактивную статистику.</sub>

</div>

---

<div align="center">

**Аниме — там, где тебе удобно.**

Сделано с 💜 в **Glany Studio**

[Релизы](https://github.com/MrGlany/AniHotAppPC/releases) · [Лицензия](LICENSE_RU.md) · [Новости](https://t.me/anihot_news)

<sub>AniHot App · Проект Glany Studio. Условия распространения указаны в лицензии.</sub>

</div>
