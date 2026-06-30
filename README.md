### Anton · Full-stack developer

Разрабатываю и вывожу в продакшен свои продукты: от интерфейса и API до деплоя и поддержки. Основной фокус — **веб и Telegram**, плюс SEO-лендинги и статика без фреймворков.

Работаю как **вайбкодер / AI-assisted developer** (Cursor, LLM): быстрые итерации, но с тестами и нормальной структурой репозитория.

---

## Основные навыки

### Frontend
- **React 18**, **TypeScript**, **Vite**, Tailwind CSS
- SPA и **PWA** (офлайн-паттерны, mobile-first, safe area, Media Session)
- **Telegram Mini Apps** (WebApp SDK, `initData`, тема, deep links)
- Ванильный **HTML / CSS / JavaScript** — лендинги без сборщика, conversion UI
- Адаптивная вёрстка, производительность (LCP, кэш ассетов, lazy load)

### Backend
- **Python 3**, **FastAPI**, asyncio
- **REST API**, OpenAPI / Swagger (`/docs`)
- Авторизация: Telegram WebApp (`tma`), OAuth/PKCE, JWT-сессии
- **SQLite** (аналитика, агрегаты), **Redis** (кэш поиска и метаданных)
- Интеграции с внешними API (Telegram Bot API, SoundCloud и др.)
- Rate limiting, фоновые задачи, webhook-обработка
- Генерация и отдача медиа (изображения, аудио)

### Админка и данные
- Веб-интерфейс администратора на **React** (`AdminStatsApp`)
- Защищённые эндпоинты `/api/admin/*` (метрики, лимиты, кэш, таймлайны)
- Событийная аналитика, фильтры, агрегаты по пользователям
- Персональные рекомендации, ранжирование, исключения (дизлайки, штрафы)

### SEO и лендинги
- Семантическая разметка, **canonical**, **hreflang**, Open Graph
- **JSON-LD** (`@graph`: WebSite, WebPage, ItemList, FAQ и др.)
- `robots.txt`, `sitemap.xml`, affiliate-трекинг (`data-offer`, UTM, `sub1`)
- Статический деплой, Apache `.htaccess` (HTTPS, gzip, cache headers)
- Мультистраничные лендинги под разные GEO (es-CL, es-AR)

### DevOps и качество
- Деплой на **VPS** (nginx, systemd, rsync)
- `README`, `.env.example`, без секретов в git
- **pytest**, **Vitest**, ESLint
- Git, понятная история коммитов, открытые репозитории как витрина

### AI / процесс
- Vibe coding с **Cursor** и LLM: прототип → прод
- Рефакторинг, тесты, документация в том же цикле
- Умею разбираться в новом SDK/API по доке и быстро встраивать в существующий бэкенд

---

## Главный проект — TGPlay

**[tgplay.fun](https://tgplay.fun)** · бот [@tgplayxbot](https://t.me/tgplayxbot)  
Код: [tgplay-telegram-music-miniapp](https://github.com/dirtyworker666x/tgplay-telegram-music-miniapp)

Музыкальный **Telegram Mini App** и **PWA**: поиск треков, плейлисты, фоновый плеер, шеринг в чат и Stories.

| Слой | Что сделано |
|------|-------------|
| Клиент | React, TypeScript, HLS.js, очередь воспроизведения, полноэкранный плеер |
| API | FastAPI, resolve/streaming, плейлисты, рекомендации, story-cards |
| Auth | Mini App + веб-логин через Telegram |
| Данные | SQLite-аналитика, JSON-плейлисты пользователей, Redis |
| Админка | React UI + API метрик и операционных действий |
| Прод | Живые пользователи, домен, бот, кэширование, лимиты |

Локально: `npm run dev` + `python3 backend/server_lite.py` → API docs на `/docs`.

---

## Другие открытые репозитории

| Репозиторий | Суть | Демо |
|-------------|------|------|
| [igaming-seo-juegachile](https://github.com/dirtyworker666x/igaming-seo-juegachile) | iGaming SEO-лендинг, Чили · JSON-LD, affiliate JS, калькулятор бонуса | [открыть](https://dirtyworker666x.github.io/igaming-seo-juegachile/) |
| [igaming-seo-jugarey](https://github.com/dirtyworker666x/igaming-seo-jugarey) | iGaming SEO-лендинг, Аргентина · structured data, responsive hero | [открыть](https://dirtyworker666x.github.io/igaming-seo-jugarey/) |
| [streetwear-landing-altered-state](https://github.com/dirtyworker666x/streetwear-landing-altered-state) | Лендинг бренда одежды · glitch UI, каталог, заказ через Telegram | [открыть](https://dirtyworker666x.github.io/streetwear-landing-altered-state/) |

Лендинги — статика на **GitHub Pages** (ссылки выше). TGPlay — живой продукт на [tgplay.fun](https://tgplay.fun).

---

## Стек (кратко)

`React` · `TypeScript` · `Vite` · `Tailwind` · `Python` · `FastAPI` · `SQLite` · `Redis` · `Telegram Bot API` · `Mini Apps` · `PWA` · `HTML/CSS/JS` · `SEO` · `JSON-LD` · `nginx` · `pytest` · `Vitest`

---

Часть коммерческой работы остаётся в приватных репозиториях. Здесь — проекты, которые можно посмотреть в коде и в проде.

**Живой продукт:** [tgplay.fun](https://tgplay.fun)
