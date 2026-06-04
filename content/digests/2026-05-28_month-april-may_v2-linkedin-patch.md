# V2 Patch — LinkedIn Apify дополнение к monthly digest

> Дополнение к [2026-05-28_month-april-may.md](2026-05-28_month-april-may.md), сгенерировано из Apify LinkedIn keyword search (290 постов, ~$0.30, см. [linkedin-search-options.md](../linkedin-search-options.md)).
>
> **5 high-signal items**, которые наш monthly digest пропустил.

## TL;DR

LinkedIn keyword-search через Apify supreme_coder/linkedin-post подтвердил **method-validity** и принёс **5 новых сигналов**:

1. 🔥 **allO — $14M Series A (Munich-based AI restaurant OS, 1000+ stores DE)** — самая важная пропущенная новость
2. 🔥 **PreciTaste — Vision AI in kitchen** — новый CV vendor для kitchen ops
3. 🔧 **iFixAi — open-source diagnostic для AI agents** — связан с Pizza Hut Dragontail case
4. 📋 **Crunchtime Voice-Based Inventory operational detail** — операторская перспектива продукта который у нас был только в PR-форме
5. 👤 **Sergio Osona Yuste (Deliverect Southern Europe GM)** — добавляю в thought-leader watchlist

---

## 🔥 Новые critical signals (Apify discovery)

### 1. allO — $14M Series A для AI Restaurant Operating System (Германия)

- **Что**: Munich-based стартап **allO** получил **$14M Series A** во главе с **Zigg Capital** (LifeX Ventures, Aperture, Wecken & Cie, 20VC, Keen Venture Partners as co-investors).
- **Traction**: 1000+ активных точек в Германии, **revenue tripled** с seed round 2024.
- **Product**: «Unified AI operating system for restaurants». AI agents автоматизируют bookings, orders, inventory, menu updates. **Founding insight** (per Tech Lens Media): «restaurant owners want the work done. They do not want to learn another piece of software.»
- **Когда**: report 26 мая 2026 (Tech Funding News). LinkedIn posts 27-28 мая.
- **Где упоминается**:
  - [Christian Leyk Neoley LinkedIn](https://www.linkedin.com/posts/christian-leyk-neoley_many-investors-assume-ai-agents-will-win-activity-7464975656301428736-kKmI)
  - [Tech Lens Media LinkedIn](https://www.linkedin.com/posts/tech-lens-media_techlensmedia-hosptech-restauranttech-activity-7465385742584795136-99Ww)
  - [VentureBurn LinkedIn](https://www.linkedin.com/posts/ventureburn_allo-secures-14m-to-advance-ai-restaurant-activity-7465024068505890816-vhgM)
- **Dodo relevance**: 🚨 **HIGH**.
  - Direct EU peer model. **Германия — Dodo operates там сейчас.** Возможно competitive overlap.
  - Concept "AI agents что выполняют работу за оператора" совпадает с обсуждениями про Dodo AI Hub direction
  - 1000+ stores с trip-revenue в год — sign что operator-AI category созревает быстрее ожидаемого
- **Action**: 
  1. ⚠️ Проверить Dodo Germany direct conflict — есть ли overlap с allO customer base?
  2. Глубокий dive — что именно allO automatизирует, как deal structure с operators (revenue share / SaaS / both?)
  3. Один-pager для AI Hub direction + Germany ops lead
- **Что важно проверить**: founders' background, exact product architecture, customer testimonials. На GitHub / Crunchbase / Pitchbook найти deeper context.

### 2. PreciTaste — Computer Vision AI для kitchen

- **Что**: vendor **PreciTaste** — CV-based AI для restaurant kitchen production management
- **Source**: ["Tech Spotlight: PreciTaste and the Power of Vision AI in the Kitchen"](https://www.linkedin.com/posts/restaurant-finance-advisors-inc_tech-spotlight-precitaste-and-the-power-activity-7465481691332161536-tQHh) — Restaurant Finance Advisors, 27 мая 2026
- **Цитата из поста**: «The traditional restaurant kitchen is a theater of controlled chaos where guesswork is often the lead actor.» Решение PreciTaste применяет vision AI к kitchen prep workflow.
- **Dodo relevance**: 
  - Direct overlap с Domain 2 (Quality Control / CV) и Domain 3 (Kitchen Experience / KDS)
  - Computer vision на kitchen line — то о чём думают на Kitchen Experience Tribe
- **Action**: 
  1. WebFetch precitaste.com — продуктовая страница, кейсы клиентов
  2. Если product page показывает применение к pizza chain — escalate в Kitchen Experience Tribe
  3. Добавить **PreciTaste** в LinkedIn vendor monitoring list

### 3. iFixAi — open-source diagnostic для AI agents (связан с Pizza Hut case)

- **Что**: open-source инструмент **iFixAi** — 32 inspections для **operational AI misalignment**. Тестирует: fabrication, manipulation, deception, unpredictability, opacity.
- **Связь с Pizza Hut**: pитч прямо позиционирует tool как ответ на Dragontail-кейс который попал в наш digest как TL;DR #1.
- **Source**: [TheAIEngineering LinkedIn](https://www.linkedin.com/posts/theaiengineering_your-ai-agent-just-got-a-report-card-for-activity-7465677363993792512-Wlcu)
- **Цитата**: «The Pizza Hut Dragontail lawsuit is a real example of what happens when that alignment layer breaks down... Drivers got visibility into kitchen queues and...»
- **Dodo relevance**: 
  - Если Dodo делает AI dispatch / cooking-time ML / capacity buckets / dyn_delivery — нужны **диагностические инструменты** для проверки model alignment перед rollout
  - **Pre/post comparison** какого-то типа уже наверняка есть, но iFixAi pattern достоин review
- **Action**: 
  1. Найти iFixAi GitHub — посмотреть какие именно 32 inspections
  2. Если pattern полезный — рассмотреть для УT validation pipeline

### 4. Crunchtime Voice-Based Inventory — operational детали

- **Что**: **Crunchtime May 2026 suite update** (мы уже видели как PR launch) — но Leap X пост раскрывает **операторскую перспективу**.
- **Detail (новый!)**: «Voice-Based Inventory — Managers count stock 3-4x faster using AI-powered speech-to-text. No clipboards. No fat-finger errors»
- **Source**: [Leap X LinkedIn](https://www.linkedin.com/posts/leap-x-40b7b0407_whats-new-in-the-crunchtime-suite-may-2026-activity-7465659778577530880-n9V3)
- **Dodo relevance**: 
  - Direct overlap с **inventory (ревизия) команда** + planшетный flow ([project_pos_admin_dev](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\project_pos_admin_dev.md))
  - "No clipboards / no fat-finger" — UX angle стоит проверить против текущего Dodo inventory flow
- **Action**: 1-pager для inventory team — сравнить Crunchtime voice UX vs нашего планшетного

### 5. Sergio Osona Yuste — Deliverect Southern Europe GM (LinkedIn watch)

- **Кто**: General Manager Southern Europe в Deliverect
- **Что**: 27 мая постит про partnership announcement Deliverect (детали в самом посте не раскрыты — нужен follow-up)
- **Источник**: [Sergio Osona Yuste LinkedIn](https://www.linkedin.com/posts/sergio-osona-yuste-60777460_partnershipannouncement-saas-foodtech-activity-7465407374749573120-bOPK)
- **Dodo relevance**: Deliverect — Tier 1 EU delivery integration vendor (уже в наших sources). Добавляю Sergio как **thought-leader watch** для regional EU intelligence.
- **Action**: Добавить `linkedin.com/in/sergio-osona-yuste-60777460` в LinkedIn thought-leader watchlist (вместе с Brita / Wolf / Carl / Hirotaka Tanaka).

---

## 📋 Дополнительные сигналы (medium)

- **Self-service kiosk uplift data**: «1 in 3 consumers prefer self-service kiosk over counter ordering, McDonald's customers spend +30% via kiosk» ([Mahdi Iraqi LinkedIn](https://www.linkedin.com/posts/mahdi-iraqi-1231aa169_self-service-kiosks-activity-7464343859775488001-Qvln))
- **Agentic Commerce $1T projection by 2030** — broader AI agent trend (US-focused) ([Keith Siedentop LinkedIn](https://www.linkedin.com/posts/keithsiedentop_us-agentic-commerce-revenue-forecast-to-reach-activity-7463952878802726912-xKjd))
- **Workday Sana expansion to IT/travel + Microsoft 365 Copilot** — HR-tech adjacency ([Rick Weijers LinkedIn](https://www.linkedin.com/posts/rickweijers_ai-agents-are-moving-into-your-employee-activity-7464922101209194496-OH1p))

---

## Calibration: что показал первый Apify run

### Метрика
| | Value |
|---|---|
| **Total посты получено** | 290 |
| **Unique авторы** | 277 |
| **Cost** | $0.29 |
| **Time** | ~2 мин на actor + 1-2 мин на анализ |
| **High-signal items** | 5 (1.7%) |
| **Medium signal** | ~10 |
| **Noise (self-promo / off-topic)** | ~270 (93%) |

### Что работает

- **Keyword search** через native LinkedIn URL — точно targeted
- **Multiple sources в одном run** — все 7 domain queries в одну посылку, $0.29 за full digest
- **Author metadata богатый** — позволяет фильтровать по `authorHeadline` (followers count, role)
- **Engagement metrics** включены — можно sortировать по traction

### Что нужно улучшить

- **Noise ratio 93%** — нужна фильтрация. Идеи:
  - Author followers threshold (e.g. `>500`) убирает мелкий self-promo
  - Текст-блок фильтр на mentions known vendors (PreciTaste, Toast, allO etc)
  - Engagement threshold (reactions > 10) убирает posts без traction
  - LLM-pass для тематической классификации (B2B-relevant / SMB-promo / off-topic)

- **Date range окно `past-week`** возвращает посты до 2 weeks назад в некоторых случаях — нужен post-filter на `postedAtISO`

### Suggested calibration для next run

```bash
# Past-month с большим limit для глубокого retrospective
./apify-linkedin-fetch.sh search "allO restaurant Germany" past-month 30
./apify-linkedin-fetch.sh search "PreciTaste vision AI kitchen" past-month 30
```

Cost: ~$0.06. Получим deeper context на 2 newly-discovered vendors.

---

## ROI verdict для Apify integration

✅ **Confirmed.** За $0.30 в одном run'е получили 5 high-signal items включая **критический пропущенный signal** (allO $14M в Германии).

**Production cost projection updated**:
- Weekly preset: $0.30 × 4 = **$1.20/мес**
- Plus ad-hoc deep-dives (~$1-2/мес)
- **Total: ~$3/мес**, в 1.7× ниже моего initial estimate $5

Free tier Apify ($5/мес credit) **полностью покрывает**.

→ Promotion в overlay ai-hub производственный режим: GO.
