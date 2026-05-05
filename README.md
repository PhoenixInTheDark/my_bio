```
██████╗ ██╗  ██╗ ██████╗ ███████╗███╗   ██╗██╗██╗  ██╗
██╔══██╗██║  ██║██╔═══██╗██╔════╝████╗  ██║██║╚██╗██╔╝
██████╔╝███████║██║   ██║█████╗  ██╔██╗ ██║██║ ╚███╔╝ 
██╔═══╝ ██╔══██║██║   ██║██╔══╝  ██║╚██╗██║██║ ██╔██╗ 
██║     ██║  ██║╚██████╔╝███████╗██║ ╚████║██║██╔╝ ██╗
╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝╚═╝╚═╝  ╚═╝
                                              profile page
```

<div align="center">

![version](https://img.shields.io/badge/version-1.0.0-00ff41?style=for-the-badge&labelColor=030712)
![html](https://img.shields.io/badge/HTML5-pure-00ff41?style=for-the-badge&logo=html5&logoColor=00ff41&labelColor=030712)
![css](https://img.shields.io/badge/CSS3-tailwind-00ff41?style=for-the-badge&logo=tailwindcss&logoColor=00ff41&labelColor=030712)
![js](https://img.shields.io/badge/JavaScript-vanilla-00ff41?style=for-the-badge&logo=javascript&logoColor=00ff41&labelColor=030712)

*`root@system:~$ cat README.md`*

</div>

---

## EN — English

### What is this?

A hacker-aesthetic personal profile / link-in-bio page built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools — just one file you can open in any browser or drop on any static host.

### Features

| Feature | Details |
|---|---|
| **Matrix rain** | Animated katakana + hex characters fall in the background via `<canvas>` |
| **Glitch effect** | CSS pseudo-elements create a cyan/magenta glitch on the username |
| **Scanlines** | Subtle CRT scanline overlay on the whole page |
| **Pulsing avatar ring** | Green glow ring around the profile photo, animated |
| **Terminal UI** | macOS-style traffic lights, monospace font (JetBrains Mono), blinking cursor |
| **Social buttons** | Hover sweep animation + slide-in arrow on each link |
| **Live clock** | Real-time HH:MM:SS in the bottom status bar |
| **Fully responsive** | Works on any screen size |

### Tech stack

- **HTML5** — single `index.html`, zero dependencies
- **Tailwind CSS** — loaded via CDN for utility classes
- **JetBrains Mono** — monospace font from Google Fonts
- **Vanilla JS** — canvas matrix rain + clock, ~40 lines

### Quick start

```bash
# Clone
git clone https://github.com/PhoenixInTheDark/websiteHack.git
cd websiteHack

# Just open in browser — no build step needed
open index.html
```

### Customization

1. **Avatar** — replace `pfp.jpg` with your photo (keep the same filename or update the `src` in `index.html`)
2. **Name / role** — edit the `PHOENIX` and `[ FULL STACK DEV, SYS ADMIN ]` strings
3. **Bio lines** — change the two comment lines inside the card
4. **Social links** — update the `href`, label, and `@handle` for each `.social-btn`
5. **Colors** — the accent color is `#00ff41` (matrix green), change it globally with find & replace

### Deploy

Any static host works — GitHub Pages, Vercel, Netlify, Cloudflare Pages. No server required.

```bash
# Example: GitHub Pages
# Push to main and enable Pages in repo settings → done.
```

### Social

| Platform | Link |
|---|---|
| Telegram | [@nothacked](https://t.me/nothacked) |
| Telegram Channel | [@ph0en1xd14ry](https://t.me/ph0en1xd14ry) |
| GitHub | [@PhoenixInTheDark](https://github.com/PhoenixInTheDark/) |
| YouTube | [@phoenix33256](https://www.youtube.com/@phoenix33256) |

---

## RU — Русский

### Что это?

Персональная страница-визитка / link-in-bio в хакерской эстетике. Написана на чистом HTML, CSS и ванильном JavaScript — никаких фреймворков, никаких сборщиков. Достаточно одного файла, который откроется в любом браузере или развернётся на любом статическом хостинге.

### Возможности

| Фича | Описание |
|---|---|
| **Дождь из матрицы** | Анимированные катакана и hex-символы падают на фоне через `<canvas>` |
| **Глитч-эффект** | CSS псевдоэлементы создают циан/маджента-глитч на нике |
| **Сканлайны** | Тонкая накладка в стиле ЭЛТ-монитора поверх всей страницы |
| **Пульсирующее кольцо аватара** | Зелёное свечение вокруг фото профиля с анимацией |
| **Терминальный интерфейс** | «Светофор» в macOS-стиле, моноширинный шрифт, мигающий курсор |
| **Кнопки соцсетей** | Анимация свипа при наведении и стрелка-→ |
| **Живые часы** | Реальное время ЧЧ:ММ:СС в нижней строке статуса |
| **Полная адаптивность** | Работает на любом размере экрана |

### Стек

- **HTML5** — один файл `index.html`, ноль зависимостей
- **Tailwind CSS** — подключён через CDN для утилитарных классов
- **JetBrains Mono** — моноширинный шрифт с Google Fonts
- **Vanilla JS** — canvas-матрица и часы, ~40 строк

### Быстрый старт

```bash
# Клонировать
git clone https://github.com/PhoenixInTheDark/websiteHack.git
cd websiteHack

# Просто открыть в браузере — сборка не нужна
open index.html
```

### Кастомизация

1. **Аватар** — замените `pfp.jpg` своим фото (сохраните имя файла или измените `src` в `index.html`)
2. **Имя / роль** — отредактируйте строки `PHOENIX` и `[ FULL STACK DEV, SYS ADMIN ]`
3. **Строки биографии** — поменяйте два комментария внутри карточки
4. **Ссылки** — обновите `href`, подпись и `@handle` у каждой `.social-btn`
5. **Цвета** — акцентный цвет `#00ff41` (матричный зелёный), меняется глобальным поиском и заменой

### Деплой

Подойдёт любой статический хостинг — GitHub Pages, Vercel, Netlify, Cloudflare Pages. Сервер не нужен.

```bash
# Пример: GitHub Pages
# Запушьте в main и включите Pages в настройках репозитория → готово.
```

### Соцсети

| Платформа | Ссылка |
|---|---|
| Telegram | [@nothacked](https://t.me/nothacked) |
| Telegram-канал | [@ph0en1xd14ry](https://t.me/ph0en1xd14ry) |
| GitHub | [@PhoenixInTheDark](https://github.com/PhoenixInTheDark/) |
| YouTube | [@phoenix33256](https://www.youtube.com/@phoenix33256) |

---

<div align="center">

```
$ echo "made with ❤ & nano"
```

`v1.0.0` · `64-bit` · `© PHOENIX`

</div>
