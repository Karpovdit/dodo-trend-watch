# Apify v2.2 Filter Summary — 230 items из 290

> Сводка после фильтр v2.2. Данные: Apify preset-weekly (7 keyword searches), 28 апреля – 28 мая 2026 окно. Cost: $0.30. Источник: `digests/raw/2026-05-29_apify-filtered-v22.md`.

## TL;DR

3 главных сюжета в LinkedIn discourse за последнюю неделю:
1. **allO $14M Series A** усиленно обсуждается в EU foodtech community — minimum 5 voices repost/анализируют, включая Munich M&A scouts
2. **Pizza Hut / Starbucks AI failures как twin alarm bell** — operator backlash формируется в реальный narrative
3. **«AI должен меньше hype, больше honesty»** — emerging operator-side тезис от опытных hospitality consultants

## 🥇 Key new signals из T1 (Person-driven)

### Pizza Hut Dragontail — detailed teardown (Brian Deck, Chair & CEO Smooth Commerce)

Полный историко-стратегический разбор:
- Yum! acquired **Dragontail Systems за $72M в сентябре 2021**
- Promise was «super manager» алгоритм оптимизирующий kitchen flow
- Chaac Pizza Northeast иск **не за malfunction** — система работала **как спроектирована**
- **Это и есть пугающая часть** — Dragontail заглядывал в kitchen queues и переводил DoorDash courier'ам visibility

→ Это **уже не дальняя угроза «AI may fail»** — это «AI works as designed and that's the problem». Прямо применимо к нашему Smart Tracking dispatch rollout reasoning.

### «AI failure twin» framing (Anandhi Dhukaram, Chief AI Officer)

> "AI is no longer failing in experiments. It's failing inside live business systems."

Цитирует Starbucks inventory + Pizza Hut Dragontail + healthcare AI inside одной недели → формирующийся narrative «AI no longer experimental, real production failures».

→ **Argumentation для quarterly review** rollout decisions.

### Marcos Georgiou — «AI needs less hype, more operational honesty»

Опытный hospitality turnaround leader сформулировал то что я бы хотел сказать но не смог:

> "The real question is not 'Should we use AI?' The better question is 'Where is the operation losing time, clarity, consistency, or margin?' That is where AI becomes useful... Not as a replacement for hospitality. Not as a shortcut for weak standards. Not as another dashboard nobody uses."

→ **Strategic framing для AI Hub direction conversations.** Worth quoting in Dodo Buildin.

### Manish Tahiliyani — «modern outside, 10-15yr-old behind counter»

> "A lot of QSR brands look modern from the outside. Self-order kiosks. Mobile apps. Delivery integrations. Loyalty programs. But behind the counter, many are still running on technology built 10-15 years ago. And that creates operational cracks most customers never see."

→ Direct релевантно к Dodo IS architectural debates. **Pattern для discussions про legacy migration**.

### Andreas Donner — «Shadow AI» в hospitality

Front office уже использует AI прежде чем management утвердило strategy:
- Reservation team драфтит guest replies AI
- Sales manager prepare offer text via AI
- Translation tools

→ Релевантно для AI Hub governance — **Shadow AI = real pattern уже сейчас**, не теория.

### Christian Leyk + Wahid Rahim — allO context

Munich M&A scout (Wahid Rahim) + AI company builder (Christian Leyk) **независимо** разобрали allO Series A. Оба подтверждают:
- 1000+ active restaurant locations Germany
- Revenue tripled с seed 2024
- 6× location growth YoY
- Zigg Capital lead (как для consumer-tech-veteran VC заход в restaurant ops)
- «AI agents handle bookings, orders, inventory, menu updates»

→ Подтверждает мой [scout](../scouts/2026-05-29_allo-deepdive.md) — это **не overhyped startup**, это **EU foodtech consolidation event** недели.

### Andrew Christ — Eatch Technologies (Dutch robotic kitchen)

Imad Qutob (Fintech, met them recently):
> "A Dutch startup building a robotic kitchen piece by piece, capable of cooking thousands of personalized meals 24/7."

→ NEW vendor для нашего стэка — европейский конкурент Picnic Works (US который shut down) и Wonder.

### Computer vision restaurants — Justin Comeau (Solink case)

Cody Hendricks (**Jack in the Box operator**) использует **существующие camera infrastructure** + Solink → operational visibility без замены hardware. «We thought upgrading meant replacing everything» pattern.

→ **Same as PreciTaste angle**: vendor positioning «existing cameras, no new install» — это эмерджентная category. Дополняет наш scout PreciTaste.

### Brandon Dennis — three-star reviews insight

Restaurant CEO от которого: реад только **3-star reviews** (не 5, не 1):
- 5-star → ничего fixable
- 1-star → одна плохая ночь, не паттерн
- 3-star → «гость почти вернулся бы — и не вернулся». Best signal для improvement.

→ Может перевестись на product review heuristic для Dodo customer experience.

### Kevin Tatgenhorst — KDS labor efficiency

VP BD NX Restaurant репостит article «implementing KDS significantly improves kitchen labor efficiency and overall restaurant operations» — single-line endorsement.

→ Direct релевантно к tracker frontend work. Низкий signal но valid.

## 🆕 Vendors newly identified

| Vendor | Domain | Signal |
|---|---|---|
| **Solink** | Computer vision restaurant ops (на existing cameras) | Jack in the Box operator endorsement |
| **Eatch Technologies** | Robotic kitchen Dutch | Eatch — EU peer для Wonder / Picnic |
| **Otto AI** | Restaurant AI (Scott Fox = CAO) | POS ecosystem AI orchestration pitch |
| **Smooth Commerce** | Restaurant tech (Brian Deck CEO) | Source of Pizza Hut Dragontail teardown |
| **Hermetic AI** | AI for Hospitality Revenue Ops (Brandon Dennis Co-Founder) | Already в follow-list |
| **Insovision** (Shenzhen) | OEM self-service kiosk | Manufacturer signal — not customer-facing |
| **Peak Care AI** | AI for Hospitality Advisor (Andreas Donner) | German consultant — relevant для Dodo DE ops |
| **NX Restaurant** | Restaurant tech (Kevin Tatgenhorst VP BD) | KDS endorsement context |

## 🎯 Cross-cutting themes я не ожидал

1. **«Behind the counter» legacy debt** — Manish Tahiliyani's frame появился у нескольких авторов независимо
2. **Operators trying to "fix AI strategy reactively"** — many T1 posts признают что Shadow AI/уже-внедрённый AI обогнал official strategy
3. **CV-on-existing-cameras pattern** — Solink, PreciTaste similar positioning — становится recognized category, не isolated
4. **AI evaluation framework** — Marcos Georgiou's «start with operational pain points, not AI capability» — operator-side resistance to vendor-push patterns

## 👀 Skip patterns (False positives v2.2 пропустил)

Filter ещё пропускает несколько noise patterns которые стоит добавить в drop:

1. **Market research promos** — Pallavi Gohad / Chokrayath Sanjana / Co Star Tech / HTF Market Intelligence — все 「Market Size to Reach $X by 203Y» posts с тегами. Похожи на analytical content но pure промо.
   → Добавить regex: `Market Size to Reach|CAGR|Sample Report|Unlock Latest Market Insights`

2. **Vendor self-promo с industry headline** — Sandra VanBuren («Financing Simplified for Foodservice»), Seth Surio («AI Automation Consultant»), Zahid Nawaz («Hot Mealz N Dealz partner») — формально industry headline но контент чисто sales.
   → Добавить text pattern: `partner.*restaurants|our.*serves restaurants|book a (free )?consultation`

3. **Dups** — Joseph Tripodi, Pallavi Gohad имеют дубли в окне. v2.2 не dedupes.
   → Добавить `unique_by(.text[0:200])` step после filter.

→ В v2.3 filter добавим эти corrections.

## 📅 Calendar — что обсуждается прямо сейчас

| Topic | Why hot | Action |
|---|---|---|
| Pizza Hut Dragontail aftermath | $100M lawsuit + Yum! original Dragontail acquisition ($72M 2021) теперь видится по-другому | Long-form read в Restaurant Dive + Brian Deck thread |
| allO $14M Series A | EU consolidation event недели | [Scout already done](../scouts/2026-05-29_allo-deepdive.md) — DE country lead handoff |
| Starbucks AI inventory withdrawal | Twin to Pizza Hut в operator-narrative | Find root cause article (PYMNTS preview) |
| NRA Show 2026 echo | Multiple posts still recap'ят MURTEC findings | Joseph Tripodi tracking «menu trends + kitchen tech» |

## 🚀 Next steps что предложу

1. **Add 2-3 new vendor LinkedIn pages** для weekly preset:
   - Solink (existing-camera CV)
   - Eatch Technologies (EU robotic kitchen)
   - Otto AI (Scott Fox)
2. **Filter v2.3** — add market-research promo drop + dedupe
3. **Promote 3-4 T1 quotes** для AI Hub direction discussions:
   - Marcos Georgiou «less hype, more operational honesty»
   - Anandhi Dhukaram «AI failing inside live business systems»
   - Manish Tahiliyani «modern outside, 10-15yr behind counter»
   - Andreas Donner «Shadow AI hospitality»
4. **One-pager «Pizza Hut Dragontail teardown»** для Smart Tracking — combine Brian Deck timeline + Anandhi framing + our prior digest summary
