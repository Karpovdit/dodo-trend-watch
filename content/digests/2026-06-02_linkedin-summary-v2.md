# LinkedIn Pipeline Summary v2 — week 2026-06-02 (44 keywords)

> Прогон с расширенным конфигом — 44 keywords vs 18 до этого. Новые блоки: shift planning, motivation/gamification, competitors by vertical.

---

## Сводка по прогону

| Метрика | Значение | Δ vs прошлый прогон |
|---|---|---|
| harvestapi posts | **858** | +539 |
| supreme_coder posts | **2** | **−143 (полностью сломан)** ⚠️ |
| Всего собрано | 860 | +396 |
| После v2.3 фильтра | 667 (78 %) | +327 |
| T1 | 0 | −1 |
| T2 | 496 | +255 |
| T3 | 171 | +73 |
| Dropped как noise | 193 (22 %) | +69 |

**⚠️ supreme_coder теперь сломан полностью.** В первом прогоне был broken только для search URLs (29 author URLs работали — отдали 145 постов). Сейчас та же cookie-ошибка на всех 29 author URLs. Нужно мигрировать author-tracking на harvestapi (он поддерживает `authorUrls`, но max 10 per call — нужны 3 батча).

---

## 🔥 Главный находка прогона — Ryan Hammer's sevenshifts-mcp

**31 мая, [пост Ryan Hammer](https://www.linkedin.com/posts/nobanksnearby_nobanks-overview-activity-7466878222417235969-I4OS):**

> «Shipped **sevenshifts-mcp at github.com/NoBanks**.
>
> Wraps **7shifts API v2** (150 000+ restaurant workers across North America, Europe, Middle East, Australia).
>
> **8 MCP tools:** get_company, list_locations, list_departments, list_users, get_user, list_shifts, create_shift, list_time_punches.
>
> Safety: defaults to read-only. Shift creation env-gated by SEVENSHIFTS_ALLOW_WRITE=true because shifts immediately appear on a real team member's schedule.
>
> **Why this matters:** restaurant scheduling is where AI agents can deliver immediate operator ROI by auto-generating shifts from POS demand, weather, PTO requests, sentiment data. An open-source MCP server is the install-ready path.»

**→ Огромный сигнал для Dodo:**

1. **Прямой паттерн для shiftmanager-frontend MCP.** У нас есть собственный shiftmanager — Ryan показал референс-архитектуру 8-tool MCP. Можно поднять `dodo-shiftmanager-mcp` за неделю по этой схеме.
2. **Safety model правильный** — read-only by default, write через ENV-flag. Это совпадает с практикой ai-hub.
3. **Это идеальная демо-история для PM AI-native workshop** ([project_pm_ai_native_workshop](C:\Users\rexep\.claude\projects\C--Users-rexep--claude\memory\project_pm_ai_native_workshop.md)) — параллель к flutter_drive dart_assistant MCP.
4. **Кейс для гильдии фронта** — paste paragraph + GitHub link + «вот так выглядит install-ready MCP wrapper для нашей домены».

GitHub: `github.com/NoBanks/sevenshifts-mcp` (тэгнут Jordan Boesch — CEO 7shifts).

---

## 🆕 Новые категории — что принесли

### 1. Shift planning (5 keywords)

Самая продуктивная новая категория. Топ-сигналы:

- **🔥 sevenshifts-mcp** (см. выше)
- **Restaurant Finance Advisors — «Tech Spotlight: 7shifts and the War on Labor Inefficiency»** (31 мая, [пост](https://www.linkedin.com/posts/restaurant-finance-advisors-inc_tech-spotlight-7shifts-and-the-war-on-labor-activity-7466927247527022592-66hy)) — long-form breakdown 7shifts ROI
- **Quantic Connect 2026 conference (10 июня, Miami Fontainebleau)** — restaurant tech conference от Quantic POS вендора (28 мая, [пост](https://www.linkedin.com/company/quantic-pos))
- **Preston Junger пост про Olo × 7shifts партнёрство** (1 июня) — индустриальная новость

**Keyword качество:**
- `7shifts` → 19/20 — 🟢 продуктивный
- `restaurant shift planning` → 20/20 — 🟢 OK
- `employee scheduling restaurant` → 20/20 — 🟢 OK
- `restaurant workforce scheduling AI` → 20/20 — 🟢 OK (уже был)
- **`Quinyx restaurant` → 2/20** — 🔴 dead, vendor-with-restaurant suffix не работает

**Рекомендация:** убрать `Quinyx restaurant`, попробовать просто `Quinyx`.

### 2. Motivation / Gamification (4 keywords)

🔴 **Слабый сигнал.** В основном HR-influencer self-promo посты и обобщённые LinkedIn-philosophy.

Что нашлось за прошедшие 7 дней:
- HOUSSAM AITELBIED — «management is about more than reports» — generic philosophy, не material
- NUMAN KHAN — «Employee Retention in Restaurant Industry» — generic HR
- Bhavik Doshi — «fastest way to kill a business» — operator opinion
- Dubai jobs / hiring posts

**Keyword качество:**
- `restaurant employee motivation` → 20/20, но 80 % noise
- `restaurant gamification` → 20/20, лучше — больше vendor-tech постов
- `restaurant staff incentives` → 20/20, mix
- `restaurant team performance` → 20/20, mix

**Рекомендация — заменить generic на vendor/category-specific:**
- ❌ `restaurant employee motivation` → ✅ `workforce gamification platform`
- ❌ `restaurant team performance` → ✅ `restaurant performance management`
- Добавить `restaurant KPI dashboard`, `kitchen advisor` (Dodo-style term), `restaurant pay-per-performance`

### 3. Competitors — Pizza vertical (4 keywords)

🟡 **Среднее качество — нужно дочистить.**

За прошедшие 7 дней самое интересное:

- **Papa Johns × Toy Story 5 partnership** (2 июня, Laura Glotzbach, [пост](https://www.linkedin.com/in/laura-glotzbach)) — «Papa Johns is in the mix with interesting partnership with the soon to launch Toy Story 5 movie. The pizza chain is opening up real experi[ences]...» — маркетинговая sit-com стратегия
- **Bicycle B Corp marketing campaign для Papa Johns** (2 июня) — agency-side anouncement

Остальное noise:
- Job postings (Papa Johns Kitchen Manager UK, Pizzaçılar Azerbaijan etc.)
- Real estate listings («near Papa Johns»)
- Generic listicles («Qdoba, Chipotle and Papa Johns»)

**Keyword качество — все по 20/20**, но процент noise высокий.

**Рекомендация:** для бренд-keywords попробовать harvestapi нативный параметр **`mentioningCompany`** вместо plain keyword search. Это даст «посты, в которых пост-автор tagged компанию», что отсекает 90 % noise (job/real-estate/listicles).

### 4. Competitors — Drinkit / Beverage (7 keywords)

🟡🔴 **Слабый сигнал — много noise.**

За прошедшие 7 дней:

- **Justine Padilla — переход в Dutch Bros** на роль Occupational Safety Compliance Manager (1 июня) — career signal, не корпоративная новость
- **Plot raised $10M seed** (2 июня, [пост](https://www.linkedin.com/company/plotworkspace)) — pure adjacent (social listening для marketing), но интересно для B2C
- Dutch Bros real estate listings (8 постов о продаваемой недвижимости у Dutch Bros) — noise

Остальное — Tropical Smoothie Cafe (не наш конкурент), Blair Church Consulting (welcome-aboard пост), donate-blood-get-free-Dutch promo.

**Keyword качество:**
- `Dutch Bros` → 20/20, но 80 % real estate / hiring noise
- `Starbucks` → 20/20, нужно проверить (могут быть food-blogger посты)
- `Blue Bottle Coffee` → 20/20
- `CHAGEE` / `Luckin Coffee` / `Mixue` → 20/20 каждый, но **дубликаты с supreme_coder authors** когда authors-pipeline починим
- `Joe & The Juice` → 20/20

**Рекомендация:** перейти на `mentioningCompany` для брендов (см. выше).

---

## Что снести / починить — план следующей итерации

### Срочное

1. **🚨 Мигрировать authors-list на harvestapi (`authorUrls` параметр)** — supreme_coder теперь сломан полностью. 29 URLs → 3 batch по 10 (harvestapi limit). Без этого теряем 145 постов/неделю от целевых аккаунтов.
2. **Сбросить Quinyx restaurant** → попробовать `Quinyx` alone.

### Тюнинг keywords

| Что убрать | Что поставить вместо |
|---|---|
| `restaurant employee motivation` | `workforce gamification platform` |
| `restaurant team performance` | `restaurant performance management` |
| `restaurant staff incentives` | оставить, чуть лучше |
| `Quinyx restaurant` | `Quinyx` |

### Архитектурный шаг

3. **Перейти на `mentioningCompany` параметр** для всех 11 brand-конкурент-keywords. Это нативная feature harvestapi — пост должен upbringing-tag/mention компанию, а не просто содержать слово. Должно отсечь 70-80 % noise.
4. **Добавить hard date cutoff `postedAt > now-7d`** в фильтр — сейчас у нас много постов с 2025 года в T2, которые «соответствуют», но не actionable для weekly.

---

## Pipeline status — наглядно

| Этап | Статус | Действие |
|---|---|---|
| supreme_coder (authors) | ❌ **Полностью сломан** | Мигрировать на harvestapi `authorUrls` (3 батча по 10) |
| harvestapi (keywords) | ✅ 858 posts из 44 keywords | Тюнинг — см. таблицу выше |
| v2.3 filter | ✅ 667/860 kept (78 %) | Добавить date cutoff |
| SEC EDGAR | ✅ 13 filings (state cache reset помог) | Добавить флаг `--force-rebuild` в скрипт |
| Web fallback | ✅ Готов как backup | Включить регулярно (DigitalFoodLab weekly) |

---

## Файлы

- **Полный prod-конфиг keywords:** [example-keywords-weekly.json](plugins/marketplaces/ai-hub/integrations/trend-watch-qsr/scripts/example-keywords-weekly.json) — 44 keywords в 10 секциях
- **Authors-list (заморожен пока):** [example-authors-weekly.json](plugins/marketplaces/ai-hub/integrations/trend-watch-qsr/scripts/example-authors-weekly.json)
- **Pipeline orchestrator:** [weekly-digest.sh](plugins/marketplaces/ai-hub/integrations/trend-watch-qsr/scripts/weekly-digest.sh)
- **Raw данные**: `cache/harvestapi-keywords-merged-2026-06-02.json` (overlay), `cache/apify-authors-2026-06-02.json` (содержит только error-объекты)
