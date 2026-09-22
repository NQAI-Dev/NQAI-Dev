<div align="center">

# ⚡ NQAI

**Open-source инженерия. Мониторинг. Инфраструктура.**

[![Telegram](https://img.shields.io/badge/Telegram-@nqai_dev-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/nqai_dev)
[![Email](https://img.shields.io/badge/Email-nqao--dev@mail.ru-D14836?style=flat&logo=gmail&logoColor=white)](mailto:nqao-dev@mail.ru)
[![Site](https://img.shields.io/Website-pulse.nqai.es-cloud.ru-blue?style=flat&logo=google-chrome&logoColor=white)](https://pulse.nqai.es-cloud.ru)

</div>

---

### 🚀 Проекты

#### 🌐 [NodePulse](https://github.com/NQAI-Dev/nodepulse)
Лёгкий распределённый мониторинг инфраструктуры на Go.
**~4 МБ RAM** у агента, авто-heal для Docker/systemd, публичные статус-страницы.
Standalone замена Prometheus + Grafana + Alertmanager.

#### 🤖 [NodePulse Bot](https://github.com/NQAI-Dev/nodepulse-bot)
Telegram-бот для NodePulse: HTTP/TCP/MC/Minecraft-пробы, cooldown, история проверок, `/start login` deep-link с HMAC-подписью.

#### ✉️ [NQAIMail](https://github.com/NQAI-Dev/nqai-mail)
Single-binary SMTP-сервер на Go. Maildir backend, STARTTLS, AUTH PLAIN, greylisting, DKIM.
SPF-проверка входящей почты, PBKDF2-хранилище пользователей и CLI для управления аккаунтами.
Standalone замена Stalwart / iRedMail / Mailcow.

#### 🐍 [Habr SDK](https://github.com/NQAI-Dev/habr-sdk)
Лёгкий Python-клиент для Habr API (v2 / kek API). Без внешних зависимостей.
Standalone замена `habr`/`habralib` для парсинга статей, хабов и пользователей.

#### 📋 [es-paste](https://github.com/NQAI-Dev/es-paste)
Минималистичный моноширинный pastebin и сервис анализа краш-логов.
Axum + SQLite + Zstandard, авто-TTL, EULA-детект, без внешних хранилищ.

#### ⛏️ [mc-log-analyzer](https://github.com/NQAI-Dev/mc-log-analyzer)
Регулярный диагностический парсер `latest.log` Minecraft-серверов.
Python 3.11+ stdlib, детектит EULA/порт/Java/OOM/плагины/чанки/sqlite, выдаёт root cause + fix hint.

#### 📊 [system-monitor](https://github.com/NQAI-Dev/system-monitor)
Однофайловый FastAPI-дашборд живых метрик Linux-хоста.
CPU, RAM, swap, диски, сеть, uptime/load, статус systemd. Авто-рефреш 3 секунды.

#### 🧠 [NQAI Atlas](https://github.com/NQAI-Dev/nqai-atlas)
Локальное append-only хранилище долговечных фактов, решений, целей и связей.
CLI + MCP-сервер, цепочки `supersedes`, weekly-review, health-checks, Git-snapshot-наблюдения.

---

### 🛠 Стек

**Backend:** Go · PHP · C#
**DevOps:** Linux · systemd · Docker · Angie · WireGuard · Tailscale
**Databases:** SQLite · PostgreSQL · Redis
**Observability:** NodePulse (свой) · Grafana · Loki

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NQAI-Dev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NQAI-Dev&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 🤝 Контакты

- 💬 Telegram: [@nqai_dev](https://t.me/nqai_dev)
- 📧 Email: [nqao-dev@mail.ru](mailto:nqao-dev@mail.ru)
- 🌐 Сайт: [pulse.nqai.es-cloud.ru](https://pulse.nqai.es-cloud.ru)

<div align="center">
  <sub>⚡ Автоматизация, надёжность, минимализм.</sub>
</div>
