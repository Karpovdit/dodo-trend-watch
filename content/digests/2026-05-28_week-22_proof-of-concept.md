# Trend Watch Дайджест — Неделя 22 (24–28 мая 2026)

> ⚠️ **Proof-of-concept**, не для рассылки. Сделан только из лично-верифицированных источников (5 из 37 Tier 1). Большая часть CN-half недоступна с моего узла (Luckin/Haidilao geo-block, см. [verified-sources-cn-jp.md](../verified-sources-cn-jp.md)).
>
> **Жанр**: показать **формат** + **подтвердить что метод работает** на 1-2 живых источниках.

## TL;DR

1. **Adi @hpn571 (note.com)** работает как обещано — ежедневный JP-дайджест food×AI выдаёт 5 концентрированных insights в день, **прямо применимых к Dodo доменам Accounting/Учёт и AI Agents**.
2. **Sushiro/Food & Life IR (EN)** — есть свежий Q2 FY26 (8 мая 2026) + Mid-term plan (март 2026). Контент надо листать по PDF — заголовки явно tech-related, но без открытия документа не подтвердить.
3. CN-сторона недоступна без VPN или прокси — Luckin / Haidilao / Foovo не отвечают. Текущий дайджест **JP-доминирован**, что само по себе ценный сигнал: JP-операторы в 2026 публично документируют то, что US/CN пока в trade-secret.

---

## 🔥 Высокий сигнал — есть что обсудить с Tribe

### Accounting / Учёт

**🇯🇵 Global Food Solution запустил RACS — DX-платформа управления food cost'ом с yen-level точностью**

- **Оригинал**: 「1円単位の原価をAIで可視化」 (Adi note.com №68, 25 мая 2026)
- **Что**: японский B2B вендор Global Food Solution запустил `RACS` — система калькуляции себестоимости блюд с точностью до **1 йены за единицу**, real-time profitability по меню, **автоматический guide на идеальный FL-ratio** (food cost + labor cost к выручке).
- **Dodo relevance**: команда **accounting (сервис учёта)** + **inventory (ревизия)**. У нас уже есть unit-cost тракинг на ингредиент-уровне, но идея «AI auto-guide к FL-ratio» — отдельный UX-слой поверх существующей аналитики. Можно сделать proof в один спринт.
- **Action**: ⚠️ открыть оригинал поста, найти ссылку на product page Global Food Solution / RACS → 1-pager в формате [feature-dev](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\reference_external_skills_library.md) для accounting Tribe.
- **Источник**: [note.com/hpn571 RSS — пост от 2026-05-25](https://note.com/hpn571/rss)

---

### Production R&D / B2B Pizza

**🇯🇵 Japan Food Research Holdings: receipt-data → AI-персоны → product dev time / 2**

- **Оригинал**: 「日本食研HDがレシートデータをAIペルソナ化、商品化期間が半減」 (Adi note.com №69, 26 мая 2026)
- **Что**: Japan Food Research Holdings прогоняет POS-receipt data через gen-AI чтобы сгенерить «AI personas» — модели потребительской психологии. Одна beverage-компания на их методике **сократила время вывода продукта в производство в 2 раза**.
- **Dodo relevance**: команда **B2B Pizza unit** (partnerships) + продуктовое R&D. Dodo сидит на огромном датасете POS-чеков (Databricks medallion) — фактический blueprint того что они описывают. Вопрос — кто owner, и есть ли уже такой эксперимент.
- **Action**: проверить с **product_analytics / core_data** ([reference_dodo_analytics_stack](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\reference_dodo_analytics_stack.md)) — не делают ли уже? Если нет — кейс достоин 5-минутного pitch'а.
- **Источник**: [note.com/hpn571 RSS — пост от 2026-05-26](https://note.com/hpn571/rss)

---

### AI Agents / Copilots

**🇺🇸+🇯🇵 AI-инвестиции операторов превращаются в маржу — Red Robin 14.8% (5-летний high) + Zensho ¥1.264T (+8.4% операционка)**

- **Оригинал**: 「★外食×AI｜週報10｜AI投資が『業績の数字』になり始めた週」 (Adi note.com weekly №10, 24 мая 2026)
- **Что**: недельный roundup от Adi фиксирует переход. **Red Robin** (US fast-casual) достиг **14.8% restaurant-level margin** — 5-летний максимум — частично через **развёртывание ChatGPT в операционке** (точные use-cases надо смотреть в их IR). **Zensho Holdings** (JP — Sukiya и др.) — выручка ¥1.264 трлн, операционная прибыль +8.4% YoY.
- **Dodo relevance**: argument для **AI Hub / Personal Leadership System** ([project_leadership_system](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\project_leadership_system.md)) и для всех PM/lead — публичные финансы операторов уже отражают AI investment ROI. Тема для квартального talking-point.
- **Action**: сохранить как пример «AI → measurable финансовый impact» для discussions с C-level / финансами.
- **Источник**: [note.com/hpn571 RSS — пост от 2026-05-24](https://note.com/hpn571/rss)

---

### Operator Macro (бенчмарк)

**🇯🇵 Same-store sales апрель 2026: разлёт между chains 2.9% vs -5.6%**

- **Оригинал**: 「4月既存店、丸亀製麺2.9%増・王将フード5.6%減で明暗」 (Adi note.com №71, 28 мая 2026)
- **Что**: апрельские LfL sales по 8 japanese udon/ramen/teishoku сетям. **Marugame Seimen** (Toridoll group) +2.9%, **Ohsho Food Service** -5.6%. Расхождение в один месяц = +8.5 п.п. между близкими по сегменту сетями.
- **Dodo relevance**: macro-бенчмарк формата «вот так выглядит дисперсия операторов в JP». Полезно для **бизнес-демо** про разнобой LfL-перформанса в сегменте — частая дискуссия в Dodo про устойчивость pizza-сегмента vs другие.
- **Action**: возможно для слайда в внутренних talks про operator landscape. Не срочно.
- **Источник**: [note.com/hpn571 RSS — пост от 2026-05-28](https://note.com/hpn571/rss)

---

## 📋 Средний сигнал — почитать на досуге

- **🇯🇵 Sushiro/Food & Life Companies — JV establishment + Q2 FY26 results** (8/27 мая 2026, [food-and-life.co.jp/en/investor](https://www.food-and-life.co.jp/en/investor)) — у головной компании Sushiro **создание совместного предприятия** (детали в IR-релизе) и **Q2 FY26 financial results** (видеопрезентация). Заголовки tech-нейтральные, но в Q2-decks традиционно есть updates на conveyor automation / RFID / AI dispatch. _Открыть IR-relations PDF когда будет 30 мин._
- **🇯🇵 Aomori префектура — gen-AI чатбот, OPEX -70%** (Adi note.com №70, 27 мая 2026) — государственный chatbot Aomori снизил эксплуатацию с ¥220k до ¥50k/мес после перехода на gen-AI. Не QSR, но **референс по unit economics LLM-внедрений** — applicable для нашей AI Hub spend-планирования.
- **🇨🇳 Meituan launches Qianniuhua Claw** (KrAsia, undated в свежей подсветке) — AI-solution для quick commerce merchants. **Adjacent** к restaurant tech, но фокус на ритейл-мерчанты. Watching.

---

## 👀 Watching — без action

- **🇯🇵 Sushiro Mid-term Management Plan март 2026** ([food-and-life.co.jp/en/investor](https://www.food-and-life.co.jp/en/investor)) — на 3-year strategic plan традиционно есть upd по KDS rollout / robot fleet / conveyor architecture. Полезно для квартального scout-режима, не для weekly.
- **🇯🇵 Sustainability Report 2025 Sushiro** (8 мая 2026) — в JP-сетях sustainability-репорты иногда содержат раскрытия по food waste tracking tech, traceability supply chain.

---

## Источники охвачены этой недели

| Источник | Регион | Verified | Items | Что нашлось |
|---|---|---|---|---|
| Adi @hpn571 (note.com RSS) | JP | ✅ HIGH | 5 | 4 high-signal item'а для Dodo, 1 macro-бенчмарк |
| Food & Life Companies IR (EN) | JP | ✅ MED | 5 IR docs | JV + Q2 results + Mid-term + Sustainability — нужно открывать PDF для деталей |
| KrAsia (homepage scan на 'restaurant') | CN/Global | ⚠️ LOW | 1 adjacent | Meituan Qianniuhua Claw (quick commerce, не QSR) |
| Kura Sushi IR | JP | ⚠️ PAGE-LOADS | 0 | Страница работает, но IR-doc list не отдалась через WebFetch — нужен другой подход (RSS-feed страницы?) |

---

## Источники пропущены (и почему)

| Источник | Почему |
|---|---|
| **Luckin Coffee IR** (LKNCY) | Timeout 15-19s с моего IP — вероятно geo-block. Запрошен у пользователя проверка из Dodo-сети. |
| **Haidilao IR** (en.haidilao-inc.com) | DNS/connection fail. Альтернатива: irasia.com fallback — не пробовал в этот заход. |
| **Foovo.jp** (JP food-tech daily) | ECONNREFUSED. Server не отвечает. |
| **36Kr search для `餐饮SaaS`** | JS-rendered, WebFetch не получает actual список статей. Нужен другой fetch path или manual через 36Kr публичные URL. |
| **Caixin Global** | Homepage загружен (verified), но search по теме не таргетировал — `caixinglobal.com/?s=restaurant` пропустил в этом заходе. |
| **Nikkei Asia** | Аналогично — homepage работает, search по QSR-теме не делал. |
| **HKEX Mixue/Haidilao prospectuses** | Search-page работает, но PDF prospectus не открывал — это **отдельная задача** на 30-60 мин. |
| **Tech Buzz China** | Recent posts не про QSR (humanoid robots / AI agents / instant retail) — снят из обоймы до подтверждения food-эпизодов. |

---

## Открытые вопросы для следующей итерации

1. **Action на Luckin geo-block**: попробовать из dev/корп-сети, либо через VPN. Это самый высокосигнальный CN-источник, нельзя терять.
2. **Sushiro Q2 FY26 results video + Mid-term plan PDF** — открыть, выписать конкретные tech-disclosures (conveyor automation %, robot fleet count, AI dispatch metrics). Если find'ы тяжёлые — отдельный scout.
3. **Найти Global Food Solution RACS product page** — посмотреть на маркет-позиционирование, цены, кейс-стади. JP-only сайт скорее всего.
4. **Поискать ChatGPT use cases в Red Robin** — через их IR / NRN / Restaurant Dive (US-сторона стэка которую я не верифицировал руками).
5. **Manual verification pass** оставшихся ~30 источников Tier 1 — для production-режима скилла обязательно (см. [verified-sources-cn-jp.md](../verified-sources-cn-jp.md) §«What to do next»).

---

## Calibration notes для скилла

**Что хорошо сработало:**
- **note.com RSS pattern** — даёт concentrated, on-topic, дату-структурированный контент. Идеальный default-источник для JP-стороны.
- **English IR pages** (Food & Life) — быстро дают список свежих disclosures, дальше можно targeted-pull нужных PDF.
- **Формат «Dodo relevance + Action»** — после написания 4 high-signal items понятно, что каждый item занимает ~80-120 слов с прямым call-to-action. Это **читабельная плотность** — не водянисто, не телеграфно.

**Что не сработало:**
- **`?s=restaurant` search-pages у медиа** — KrAsia/Caixin/Nikkei через простой search-URL не отдают targeted список через WebFetch. Нужен либо RSS, либо tag-page, либо manual.
- **JS-rendered страницы** (36Kr, Wechat2RSS) — WebFetch ловит только initial HTML, динамика теряется. Нужен либо API endpoint, либо curl + JSON parsing, либо headless-browser.
- **Geo-blocked sources** — без VPN / proxy / CN-узла reachability ~50% CN-стека.

**Калибровка rubric'а** на основе этого захода:
- Axis **Accessibility (0.10)** правильно weight'нут — для дайджеста реально живые-теперь источники в приоритете
- Axis **Verifiability (0.15)** надо поднять — каждый Adi-item сам ссылается на 5 первичных источников; это double signal
- Axis **B2B Operator-Relevance (0.20)** работает — 4 из 5 Adi-постов попали прямо в Dodo domains, 1 macro-бенчмарк

---

## Privacy disclaimer

Этот дайджест — **черновик в личной рабочей папке**. Если решишь шарить с Dodo Tribe — оформи как Buildin draft по workflow [feedback_draft_before_publish](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\feedback_draft_before_publish.md): черновик → подтверждение → публикация.

Adi-посты — публичные, переводы здесь — мои summaries, OK шарить с attribution на оригинал.
