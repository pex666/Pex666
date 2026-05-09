# Павел Фурсов — Product / Data Analyst

**Москва, Россия** • [Telegram](https://t.me/pex666) • [Gmail](mailto:pav.fursov@gmail.com) • [HH](https://hh.ru/resume/235136b3ff0c5077d10039ed1f584c72323246)

---

## О себе

Product / Data Analyst, работаю с мобильными приложениями. Строил с нуля внутреннюю систему аналитики: таксономия событий, модель данных в ClickHouse, агрегаты, BI-дашборды, A/B-тестирование.

Работал с мобильной монетизацией (подписки, paywalls, ads), retention, attribution, когортным анализом и автоматизацией рутинных отчётов.

---

## Стек

### SQL / БД
- **ClickHouse** — целевая аналитическая БД, слои `fact_` / `dim_` / `agg_`
- **PostgreSQL** — продуктовая БД
- **Apache Superset** — BI и self-service дашборды

### Python
- pandas, numpy, scipy, statsmodels — анализ и статистические тесты
- matplotlib, plotly, seaborn — визуализация
- requests, gspread, google-api-python-client — пайплайны и автоматизация
- Playwright — скрейпинг и парсинг конкурентов

### Mobile analytics
- **Amplitude** — event analytics, retention, funnels; Export API, Chart API
- **AppsFlyer** — attribution, install / cohort APIs
- **Adapty** — subscription analytics
- **Sensor Tower** — market intelligence
- **Firebase** — A/B testing, Remote Config

### A/B-тестирование
- Полный цикл: гипотеза → расчёт sample size → тест → статзначимость → вывод
- t-test / Welch, Mann-Whitney U, z-test, bootstrap, доверительные интервалы
- Bonferroni correction для множественных сравнений
- Когортный и сегментный анализ

### Автоматизация и среда
- Google Sheets API + Apps Script — task tracker, отчёты, расшаренные данные
- Git / GitHub, Linux (Ubuntu), VPS, Jupyter, DBeaver

---

## Опыт

- **Event taxonomy** — единая схема событий по 9 экранам мобильного приложения, ~90 событий, передана клиентской Flutter-команде.
- **Каталог метрик** — 87 чартов из 8 Amplitude-дашбордов разобрал на формулы; 91% воспроизводимо в ClickHouse напрямую.
- **A/B-testing** — внедрение Firebase A/B как Stage 1, далее интеграция с ClickHouse.
- **Retention sources of truth** — выровнял расчёты между Amplitude / AppsFlyer / Adapty.
- **Продуктовая аналитика** — funnels, paywall-конверсии, content engagement, когортный анализ; диагностика падений метрик и расхождений между источниками данных.
- **Market data automation** — ежемесячный пайплайн Sensor Tower → Google Sheets для конкурентного анализа.

---

## Pet / portfolio

- [Анализ рынка жилой недвижимости Санкт-Петербурга и Ленинградской области](https://github.com/pex666/portfolio/tree/main/real-estate)
- [Анализ исторических данных по сделкам M&A в стартап-сегменте](https://github.com/pex666/portfolio/tree/main/EDA)
- [Исследование результатов A/B-теста и поиск инсайтов](https://github.com/pex666/portfolio/tree/main/AB-results)

---

## Контакты

- Telegram: [@pex666](https://t.me/pex666)
- Email: pav.fursov@gmail.com
- HeadHunter: [Павел Фурсов](https://hh.ru/resume/235136b3ff0c5077d10039ed1f584c72323246)
