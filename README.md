# Привет, я ninelegsdog 👋

**AI Automation Engineer** | Agentic harness & context engineering | Quality gates & verification | 9 Telegram bots in production

Экосистема **BotKit** — production-ready Telegram-боты, общие библиотеки и инструменты для агентной разработки с выстроенными гейтами качества.

## Экосистема BotKit

### Ядро
- **[botkit-core](https://github.com/ninelegsdog/botkit-core)** — Общее ядро для всех ботов: платежи, метрики, логирование, вебхук, ошибки, трейсинг. Side-effect-free, инжекция зависимостей.

### Боты в продакшене (9 штук)
- **[botkit-bookingbot](https://github.com/ninelegsdog/botkit-bookingbot)** — Бронирование и запись с оплатой YooKassa
- **[botkit-store](https://github.com/ninelegsdog/botkit-store)** — Каталог, корзина, оформление заказа
- **[botkit-leadgen](https://github.com/ninelegsdog/botkit-leadgen)** — Квалификация и сбор лидов
- **[botkit-support](https://github.com/ninelegsdog/botkit-support)** — Тикеты, FAQ, SLA с рабочими часами
- **[botkit-membership](https://github.com/ninelegsdog/botkit-membership)** — Подписки, доступ по ролям, оплата
- **[botkit-reminder](https://github.com/ninelegsdog/botkit-reminder)** — Напоминания и сегментированные рассылки
- **[botkit-docuflow](https://github.com/ninelegsdog/botkit-docuflow)** — Документооборот, генерация PDF
- **[botkit-pricesentry](https://github.com/ninelegsdog/botkit-pricesentry)** — Мониторинг цен и алерты
- **[botkit-delivery](https://github.com/ninelegsdog/botkit-delivery)** — Отслеживание доставки с вебхуками

### Инфраструктура и тестирование
- **[botkit-monitoring](https://github.com/ninelegsdog/botkit-monitoring)** — Observability стек: Prometheus, Grafana, Loki, Tempo, Alertmanager, OTel, MinIO
- **[botkit-farm](https://github.com/ninelegsdog/botkit-farm)** — Тестирование настоящего кода бота без Telegram. Прогон хендлеров, кадры диалога, баг-репорты
- **[cookiecutter-botkit-bot](https://github.com/ninelegsdog/cookiecutter-botkit-bot)** — Шаблон для быстрого старта нового бота

### Инструменты качества и методология
- **[qualityforge](https://github.com/ninelegsdog/qualityforge)** — Evidence-first browser quality automation с read-only MCP сервером
- **[qualityforge-template](https://github.com/ninelegsdog/qualityforge-template)** — Готовый шаблон с quality gates из коробки
- **[agentic-development-playbook](https://github.com/ninelegsdog/agentic-development-playbook)** — Методология работы с AI-агентами: harness, context engineering, гейты, ревью, handoff

## Принципы

- **Harness-driven** — Качество агента определяется не моделью, а harness + acceptance criteria + гейтами
- **Verification-first** — Тест обязан уметь падать. «Зелёный CI» ≠ рабочий продукт
- **Evidence-first** — Артефакты падения, трассировки, проверки перед коммитом
- **Production-minded** — Docker security hardening, наблюдаемость, бэкапы, гейты

## Стек

`Python 3.12` · `aiogram 3` · `SQLAlchemy 2 (async)` · `Redis` · `Postgres/SQLite` · `Docker` · `Prometheus/Grafana/Loki/Tempo` · `pytest/ruff/mypy` · `Playwright` · `OpenTelemetry`

## Контакты

- **Telegram:** [@ninelegsdog](https://t.me/ninelegsdog)
- **Канал:** [@BotogradPress](https://t.me/BotogradPress)
- **GitHub:** [github.com/ninelegsdog](https://github.com/ninelegsdog)
