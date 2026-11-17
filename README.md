# Подготовка к собеседованию — Business Analyst, Plata (Мехико)

Nov 17, 2026 · @Pyatakov

## Цель

Отклик в январе 2027 на роли Business Analyst (бизнес-аналитик) в Banco Plata с релокацией в Мехико; запасной вариант — Product Analyst (продуктовый аналитик). До нового года — подготовка и доработка резюме.

| Вакансия | Уровень | Релокация |
| --- | --- | --- |
| [BA \[Delivery Platform\]](https://plata.careers/vacancy/details?id=5466778008) | Junior+/Middle | Мексика |
| [BA Middle \[Antifraud, Mexico\]](https://plata.careers/vacancy/details?id=4938329008) | Middle | Мексика |
| [BA Middle+ \[Customer Care for Antifraud\]](https://plata.careers/vacancy/details?id=4987196008) | Middle+ | Мексика |
| [Product Analyst \[Delivery\]](https://plata.careers/vacancy/details?id=5432577008) | Junior/Junior+ | Мексика |
| [Product Analyst (Mexican Teams)](https://plata.careers/vacancy/details?id=4889803008) | Junior–Middle | Мексика или Грузия |

**Этапы отбора (ожидаемые):** HR screening (скрининг с рекрутером) → test task (тестовое) → technical interview (техническое интервью с кейсом) → hiring manager (финал с руководителем) → offer → visa (2–3 месяца).

**Язык:** часть интервью может быть на русском, но английский B2 проверят — каждый пункт ниже готовим сразу на английском. **Зарплатные ожидания:** от 2 000 € до налогов. **Загранпаспорт:** оформить до отклика.

## Приоритет 0 — контекст собеседования

Этих пунктов нет в резюме, но на собеседовании они всплывут первыми.

- [ ] **Domain knowledge (знание предметной области).** Card lifecycle (жизненный цикл карты: выпуск → доставка → активация → перевыпуск), KYC (проверка клиента), AML (противодействие отмыванию), fraud (мошенничество), disputes / chargeback (оспаривание операций).
- [ ] **Agile / Scrum basics (основы гибкой разработки).** Sprint (спринт), stand-up (ежедневная встреча), retro (ретроспектива), roles (роли), SDLC (жизненный цикл разработки: идея → релиз).
- [ ] **Behavioral questions (поведенческие вопросы).** «Зачем фаундеру найм?», «Расскажи о провале», «Конфликт со стейкхолдером». Отвечать по STAR (Situation — ситуация, Task — задача, Action — действие, Result — результат).
- [ ] **Logic & math tasks (логика и математика).** Задачи на вероятность и estimation (оценка «на салфетке»), например «Сколько курьеров нужно Мехико?».
- [ ] **Product knowledge (знание продукта Plata).** Кредитные и дебетовые карты, кредиты, инвестиции; доставка карт через ambassadors (курьеров-амбассадоров).
- [ ] **Your questions (твои вопросы интервьюеру).** 3–4 вопроса: команда, задачи на первые 3 месяца, метрики успеха, оплата больничного, удалёнка на время визы.

## Приоритет 1 — проверят точно

Ядро работы BA: именно этим ты будешь заниматься каждый день. По каждому пункту — STAR-история из JobToo или Mevratek на английском.

- [ ] **Requirements elicitation (сбор и формализация требований).** Интервью со стейкхолдером, поиск настоящей проблемы, user story (пользовательская история), acceptance criteria (критерии приёмки), use case (сценарий использования), functional / non-functional requirements (функциональные / нефункциональные требования).
- [ ] **Process modeling in BPMN (моделирование процессов).** As-is / to-be (как есть / как будет), swimlane (дорожка роли), gateway (развилка), exceptions (исключения). UML и DFD (data flow — потоки данных) на базовом уровне.
- [ ] **Backlog & prioritization (бэклог и приоритизация).** Decomposition (декомпозиция), RICE и MoSCoW (методики приоритизации), trade-offs (компромиссы) — уметь объяснить выбор.
- [ ] **Root cause analysis (поиск корневой причины).** Главный кейс: «метрика упала — что делаешь?». 5 Whys (пять «почему»), hypothesis (гипотеза).
- [ ] **Stakeholder management (работа со стейкхолдерами).** Alignment (согласование), expectation setting (управление ожиданиями) — история про людей с разными интересами (пилот в Яндекс Лавке).

## Приоритет 2 — поднимает до Middle

- [ ] **SQL.** SELECT, JOIN, GROUP BY, aggregation (агрегации), window functions (оконные функции). Скорее всего будет живая задача (live coding).
- [ ] **Metrics & KPI (метрики).** Conversion (конверсия), funnel (воронка), unit economics (юнит-экономика), north star metric (главная метрика) — уметь выбрать метрику и объяснить, что она показывает.
- [ ] **SLA & process quality (качество процесса).** Resolution time (время решения), repeat contact rate (доля повторных обращений), escalation (эскалация). Прямо из вакансии BA \[Antifraud\].
- [ ] **CJM — customer journey map (карта пути клиента).** Touchpoints (точки контакта), pain points (точки боли).
- [ ] **Integrations & architecture (интеграции и архитектура).** REST API, endpoint (точка доступа), microservices (микросервисы), event streaming / message queue (очередь сообщений, Kafka) — на уровне понимания, не разработки.

## Приоритет 3 — достаточно базового уровня

- [ ] **UI design in Figma (проектирование интерфейсов).** User flow (пользовательский сценарий), wireframe (схема экрана), prototype (прототип) — набросать многоэкранный сценарий для внутреннего инструмента.
- [ ] **A/B testing (A/B-тесты).** Hypothesis (гипотеза), control group (контрольная группа), statistical significance (статистическая значимость), sample size (размер выборки).
- [ ] **BI dashboards (дашборды).** Metabase или Superset: собрать простой дашборд из SQL-запроса.
- [ ] **Cross-functional project management (управление проектами между командами).** Delivery (доведение до релиза), timeline (сроки), dependencies (зависимости).
- [ ] **Python (pandas).** Загрузить таблицу, отфильтровать, сгруппировать. Для BA спрашивают редко.
- [ ] **Tools (инструменты).** [Jira](https://www.atlassian.com/software/jira), [Confluence](https://www.atlassian.com/software/confluence), [Notion](https://www.notion.com), [Miro](https://miro.com) — знать, как в них ведут задачи и документацию. Для практики из России подойдут Яндекс Трекер, Kaiten, Яндекс Вики.
