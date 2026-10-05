---
publish: true
title: "Starbucks · Smart Queue, ассистент бариста и свёрнутая AI-инвентаризация"
date: 2026-10-05
---

*Досье на технологический стек: функции, цифры, сроки, деньги и критика со ссылками на первоисточники — стенограммы звонков Starbucks с инвесторами, отчётность в SEC, пресс-центр компании, отраслевые медиа, LinkedIn и Telegram. Последняя сверка — 5 октября 2026.*

![Starbucks Investor Day 2026](/static/platforms/starbucks-tech.jpg)

## Коротко

**Технологический стек Starbucks при CEO Брайане Никколе** компания подаёт как «технологию, которая поддерживает бариста, а не заменяет человека». Ядро стека:

- **Smart Queue** — алгоритм, который выстраивает заказы из кафе, драйв-тру, мобильного приложения и доставки в одну очередь;
- **Green Dot Assist** — генеративный ассистент для бариста на iPad;
- **приложение** с мобильным заказом, заказом на время и перезапущенной программой лояльности;
- **новое оборудование**, а в разработке — собственные касса, учёт запасов и планирование смен.

**Главный провал — AI-инвентаризация на компьютерном зрении от стартапа NomadGo.** Её развернули в сентябре 2025 года больше чем на 11 000 кофейнях Северной Америки и выключили в мае 2026 года. Это редкий публично разобранный случай, когда AI-проект провалился на масштабе сети.

**Итог разворота — рост визитов.** Транзакции в США растут впервые за два года, но Starbucks прямо связывает это и с технологиями, и с \$500 млн, вложенными в персонал.

---

## Ключевые цифры

| Показатель | Значение | Период | Статус |
|---|---|---|---|
| Стандарт скорости | 4 минуты в кафе, 4 в драйв-тру, обещанное время мобильного заказа меньше 12 минут | 2026 | официально |
| Кофейни со временем в кафе 4 минуты или меньше | больше 80% собственных кофеен США | после запуска Smart Queue | официально |
| Пилот алгоритма очереди | минус 2 минуты на напиток в среднем | весна 2025 | СМИ, WSJ |
| Доля мобильного заказа в транзакциях | 31% → 33% | 2025 → III кв. 2026 финансового года | официально |
| Активных участников Starbucks Rewards в США | 35,8 млн | III кв. 2026 финансового года | официально |
| Доля трат участников Rewards | 58–59% | 2025–2026 | официально |
| Сопоставимые продажи в США | +7,9%, транзакции +4,2% | III кв. 2026 финансового года | официально |
| Визиты | +4,5% к прошлому году | лето 2026 | официально |
| Вложения в персонал | больше \$500 млн в часы, штат и смены | с 2024 года | официально |
| AI-инвентаризация NomadGo | больше 11 000 точек, выключена через девять месяцев | сентябрь 2025 – май 2026 | СМИ |
| Стоимость проекта NomadGo | возможно, больше \$10 млн за несколько лет | — | СМИ, Fast Company |
| Расходы на софт | около \$400 млн в год | июль 2026 | СМИ со слов CTO |
| Доступность еды в кофейнях | около 99%, на 10 п.п. лучше, чем год назад | III кв. 2026 финансового года | официально |

Источники: стенограммы звонков за [IV кв. 2025](https://s203.q4cdn.com/326826266/files/doc_financials/2025/q4/SBUX-Q4-2025-Earnings-Call-Corrected-Updated.pdf), [II кв. 2026](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q2/Q2-FY26-SBUX-Transcript.pdf) и [III кв. 2026](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q3/Q3-FY26-SBUX-Transcript.pdf) финансового года, [цифровая отчётность](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q3/Q3-FY26-Digital-IR-Dashboard.pdf), [отчётность в SEC](https://www.sec.gov/Archives/edgar/data/0000829224/000082922426000129/sbux-06282026xearningsrele.htm), [WSJ в пересказе NACS](https://www.convenience.org/stay-current/news/2025/april/30/6-starbucks-cuts-wait-time-by-two-minutes_fs), [Fast Company](https://www.fastcompany.com/91572019/starbucks-bet-big-ai-tool-national-scale-9-months-inventory-automated-counting-nomadgo), [Fortune](https://fortune.com/2026/07/09/starbucks-to-use-ai-to-replace-microsoft-ibm-software/).

---

## Smart Queue — очередь заказов

- **Что делает.** Собирает в один поток заказы из кафе, драйв-тру, мобильного приложения и доставки и задаёт бариста порядок приготовления вместо «первым пришёл — первым обслужен» ([Starbucks](https://about.starbucks.com/press/2026/supporting-the-moments-that-matter-with-artificial-intelligence/)). Раньше всё работало именно так, и это «создавало массу узких мест», говорит Никкол ([Fortune](https://fortune.com/2025/10/16/starbucks-ceo-brian-niccol-secret-ai-barista-green-dot)). Гость в кафе не должен ждать, пока готовят чужие мобильные заказы.
- **Приоритеты.** Кафе и драйв-тру в приоритете с целью 4 минуты, мобильный заказ и доставка — 12 минут ([Quartz](https://qz.com/starbucks-mobile-order-labor-barista-workflow-051926)).
- **Откуда взялся.** Starbucks лицензировала софт стартапа Empower Delivery и наняла шесть его инженеров. Основательница стартапа стала директором по развитию кофеен ([Restaurant Business](https://restaurantbusinessonline.com/operations/starbucks-taps-new-tech-help-order-timing)).
- **AI или правила.** WSJ в 2025 году писал, что алгоритм построен на правилах «если — то», а не на AI. С 2026 года Starbucks описывает его в разделе про AI.
- **Раскатка.** С августа 2025 года работает во всех собственных кофейнях США вместе с новым стандартом обслуживания Green Apron.
- **Заказ на время с мая 2026 года.** В приложении можно выбрать окно по 5 минут до часа вперёд, доступность слотов зависит от загрузки кофейни. Работает на Smart Queue ([NRN](https://www.nrn.com/restaurant-technology/starbucks-will-soon-let-you-plan-your-pickup-times)).

> «Гипотеза была, что в кофейнях не тот штат и заказы неправильно выстраиваются между драйв-тру, мобильным заказом и кафе… Понадобились и технология SmartQ, и больше персонала». — Брайан Никкол, CEO Starbucks

**Эффект Smart Queue отдельно от вложений в персонал не выделен.** Сам Никкол говорит о связке «алгоритм плюс люди».

---

## Green Dot Assist — ассистент бариста

- **Что делает.** Чат на iPad в кофейне: голосом или текстом бариста спрашивает рецепт, стандарт сервиса, способ починить оборудование и получает разговорный ответ. Помогает старшим смены распределять людей в пик ([Starbucks](https://about.starbucks.com/press/2025/meet-green-dot-assist-starbucks-generative-ai-powered-coffeehouse-companion/)).
- **Стек.** Microsoft Azure OpenAI, версия модели не названа ([CIO Dive](https://www.ciodive.com/news/starbucks-introduces-virtual-assistant-green-dot-assist-microsoft-azure/750500/)).
- **Охват.** Пилот в 35 кофейнях в июне 2025 года, по данным GeekWire — вся Северная Америка с ноября 2025 года. В мае 2026 года операционный директор всё ещё называл его пилотом. Официальных цифр охвата и эффекта нет.
- **Планы.** Автоматические заявки на ремонт оборудования, подбор замены при невыходе сотрудника, ранние сигналы о поломках.

### Что говорят бариста

По словам бариста в Business Insider, ассистент отвечает 10–20 секунд, иногда дольше, а в одной кофейне им никто не пользуется. После перестройки базы знаний под бота ответы стало сложнее найти самим, а ассистент «отбивает охоту» учить рецепты ([Business Insider](https://www.businessinsider.com/artificial-intelligence-digital-coworkers-restaurants-staff-starbucks-burger-king-chipotle-2026-5)).

---

## AI-инвентаризация NomadGo — что пошло не так

- **Что делала.** iPad Pro с камерой и лидаром сканировал полки подсобки — молоко, сиропы, кофе — и считал остатки прямо на устройстве с синхронизацией в учётную систему. Час ручного подсчёта должен был превратиться в 10–12 минут ([GeekWire](https://www.geekwire.com/2025/starbucks-rolls-out-automated-counting-tech-for-inventory-with-help-from-seattle-area-startup/)).
- **Зачем внедряли.** Хронический дефицит молока, выпечки и крышек, который Никкол называл причиной потерянных продаж.
- **Почему выключили** ([Fast Company](https://www.fastcompany.com/91572019/starbucks-bet-big-ai-tool-national-scale-9-months-inventory-automated-counting-nomadgo)):
  - блики в холодильниках удваивали счёт молока;
  - цельное молоко и молоко 2% распознавались как обезжиренное;
  - при обрыве Wi-Fi прогресс сканирования стирался;
  - переобучение под новую сезонную упаковку занимало 4–6 недель;
  - учётная система, куда шли данные, — IBM AS/400 из 1990-х;
  - из-за перезаказов одна кофейня выбросила еды почти на \$700 за день, бариста правили почти каждую строку вручную.
- **Как закрыли.** 3 апреля 2026 года Starbucks уведомила стартап, 18 мая сотрудникам объявили, что молоко снова считают вручную ([GeekWire](https://geekwire.com/2026/report-starbucks-scrapped-an-ai-inventory-tool-and-left-a-seattle-area-startup-blindsided)). Официальная формулировка — «стандартизировать подсчёт запасов во всех кофейнях» и перейти к более частым поставкам ([Reuters в пересказе KFGO](https://kfgo.com/2026/05/21/exclusive-starbucks-scraps-ai-inventory-tool-across-north-america/)).
- **Последствия для вендора.** У NomadGo было 30 сотрудников, большую часть уволили. «Это было полной неожиданностью. Ничего не поделаешь, когда меняются руководство и стратегия», — CEO стартапа.
- **Правка принципа.** После провала на AI-странице Starbucks формулировку «если нет — идём дальше» заменили на «если нет — дорабатываем».

> «Технология, которая экономит 20 минут и создаёт 30 минут проверок, исправлений и раздражения, — не автоматизация в каком-либо осмысленном смысле». — Restaurant Technology News ([RTN](https://restauranttechnologynews.com/2026/08/why-starbucks-was-right-to-pull-the-plug-on-its-ai-inventory-system/))

---

## Приложение, лояльность и оборудование

- **Мобильный заказ** — 33% транзакций собственных кофеен США. Кофейни формата «только самовывоз» закрывают: формат «слишком транзакционный и лишён тепла», считает Никкол ([Retail TouchPoints](https://www.retailtouchpoints.com/news/starbucks-to-complete-1000-store-uplifts-in-2026-plans-to-phase-out-pickup-only-locations/153497/)).
- **Приложение Starbucks в ChatGPT, бета с апреля 2026 года.** Гость описывает настроение или присылает фото и получает предложения напитков, но оплачивает в приложении Starbucks ([Starbucks](https://about.starbucks.com/stories/2026/meet-the-beta-starbucks-app-in-chatgpt-a-new-way-to-discover-your-next-favorite-drink/)). В приложении анонсирован AI-помощник, который собирает напиток по описанию вкуса, дата запуска не названа ([GeekWire](https://www.geekwire.com/2026/vibe-coffee-is-coming-starbucks-is-building-an-ai-powered-ordering-companion/)).
- **Starbucks Rewards перезапущен в марте 2026 года** с тремя уровнями, звёзды начисляются за траты, а не за способ оплаты ([Starbucks](https://investor.starbucks.com/news/financial-releases/news-details/2026/Starbucks-Unveils-Reimagined-Loyalty-Program-to-Deliver-More-Meaningful-Value-Personalization-and-Engagement-for-Members/default.aspx)). Число участников выросло вместо ожидаемой просадки. Дешёвая награда за 60 звёзд стала самой популярной — около трети погашений.

> «Программа лояльности не должна быть книжкой купонов… она про вовлечённость, персонализацию и признание». — Брайан Никкол

- **Оборудование.** Кофемашина Clover Vertica собственной разработки варит чашку за 30 секунд и стоит больше чем в 90% собственных кофеен США ([Starbucks](https://about.starbucks.com/stories/2026/freshly-brewed-coffee-on-demand-how-the-innovative-clover-vertica-is-changing-starbucks-coffeehouses/)). Новая эспрессо-машина сократит четыре шота с 70 до 30–35 секунд, запуск в 2027 году.

---

## Свой софт вместо вендоров

- **Starbucks тратит на софт около \$400 млн в год** и с помощью AI пишет собственные замены учётной системы Microsoft, инструмента обслуживания оборудования IBM и кассы Oracle. Первые решения — к концу 2027 года ([Fortune](https://fortune.com/2026/07/09/starbucks-to-use-ai-to-replace-microsoft-ibm-software/)).
- **2027 финансовый год назван «годом модернизации»:** новые системы заказа запасов, персонала и графиков, касса.
- **Новый CTO** — Ананд Варадараджан, 19 лет в Amazon, с января 2026 года: «Есть явные возможности сократить траты на софт».
- **Технологический хаб в Ченнаи** — около 800 рабочих мест, чтобы перевести внутрь работу подрядчиков ([Starbucks](https://about.starbucks.com/press/2026/starbucks-technology-to-open-new-hub-in-chennai-india/)).

---

## Хронология

| Когда | Что произошло |
|---|---|
| 2017–2019 | Ранняя AI-платформа Deep Brew. В официальных материалах 2025–2026 годов она больше не упоминается |
| Сентябрь 2024 | Брайан Никкол — CEO, старт стратегии Back to Starbucks |
| Март 2025 | Лицензия софта Empower Delivery для очереди заказов |
| Июнь 2025 | Пилот Green Dot Assist в 35 кофейнях |
| Август 2025 | Smart Queue и стандарт Green Apron во всех собственных кофейнях США |
| Сентябрь 2025 | AI-инвентаризация NomadGo на 11 000+ точках |
| Январь 2026 | Первый рост транзакций в США за два года, новый CTO из Amazon |
| Март 2026 | Перезапуск Starbucks Rewards с тремя уровнями |
| Апрель 2026 | Бета-приложение Starbucks в ChatGPT |
| Май 2026 | Заказ на время в приложении, AI-инвентаризация выключена |
| Июль 2026 | Курс на собственный софт вместо Microsoft, IBM и Oracle |
| Сентябрь 2026 | Технологический хаб в Ченнаи, закрытие около 250 кофеен в Северной Америке |

---

## Что говорят в индустрии

- **Мобильная очередь давит на кафе.** Если цифровое удобство портит опыт в зале, бизнес «просто переносит ожидание туда, где его хуже видно» ([Майкл Гуццетта](https://www.linkedin.com/posts/michael-guzzetta_experiencesystemsinnovation-omnichannelretail-activity-7504244776762945536-1KSs)).
- **Готовить к приходу гостя, а не к моменту заказа.** Геолокация в приложении Starbucks используется для маркетинга, а не для производства, тогда как Chick-fil-A и McDonald's давно начинают готовить, когда гость подъезжает ([LeanBlog](https://www.leanblog.org/2026/03/starbucks-mobile-order-timing-problem-chick-fil-a-solved/)).
- **Чего Starbucks не видит.** Компания знает всё о покупке, но не знает, простоял ли гость шесть минут у стойки мобильных заказов и ушёл ли, увидев очередь ([Эрик Калтон](https://www.linkedin.com/posts/ericculton_if-youre-a-fan-of-starbucks-what-do-you-activity-7506052848649015297-_ewR), 49 комментариев).
- **Автоматизировали задачу, а не цепочку.** Нужен контур «AI определяет, оценивает уверенность, человек проверяет спорное, исключения улучшают модель» ([Филипп Абдулай](https://www.linkedin.com/pulse/starbucks-automated-task-value-chain-lesson-ai-philippe-a-abdoulaye-oz0ce)).
- **Проблема была не в подсчёте, а в видимости цепочки поставок.** AI положили на слабый фундамент ([Шао Хэн Лай](https://www.linkedin.com/posts/endlaiers_supplychain-artificialintelligence-operationsmanagement-activity-7472830386298085377-02Gv)).
- **Русскоязычный Telegram** разобрал отказ от AI-учёта ([Foodtech](https://t.me/foodtechonline/6657), [Foodservice](https://t.me/foodservicerus/2590)) и возврат американского фастфуда к живому сервису ([Левицкий](https://t.me/dmitry_levitsky/9665)).

### Критика

- **Бариста «ведут три ресторана одновременно».** Алгоритм балансирует очередь, но напряжение одной последовательностью не снять. Профсоюз хочет право выключать мобильный заказ, когда в очереди пять заказов ([Quartz](https://qz.com/starbucks-mobile-order-labor-barista-workflow-051926)).
- **Сбои планирования смен.** Сотрудницу поставили на восемь дней подряд ([Fast Company](https://www.fastcompany.com/91572019/starbucks-bet-big-ai-tool-national-scale-9-months-inventory-automated-counting-nomadgo)).
- **Риски признаёт сама компания.** В годовом отчёте Starbucks пишет, что AI может не дать ожидаемой эффективности и несёт риски ошибок и галлюцинаций.
- **Неподтверждённые цифры о Deep Brew** в LinkedIn вроде «\$410 млн новой выручки» первоисточника не имеют.

---

## Что подтверждено, а что нет

- **Официально:** стандарт «4-4-12», более 80% кофеен в пределах 4 минут, доли мобильного заказа и лояльности, сопоставимые продажи, вложения в персонал.
- **Не раскрыто:** фактическое время мобильного заказа, вклад Smart Queue отдельно от персонала, охват и эффект Green Dot Assist, использование заказа на время и приложения в ChatGPT.
- **Расхождения:** Green Dot Assist «развёрнут во всей Северной Америке» по GeekWire и «пилот» по словам операционного директора в мае 2026 года. Срок новой кассы, похоже, перенесён с 2026 на 2027 финансовый год.

---

## Значение для Dodo

1. **Отдельная планка для каждого канала.** Starbucks живёт по стандарту «4-4-12» и мерит кафе, драйв-тру и мобильный заказ раздельно. Для Дринкит, где большая доля заказов идёт через приложение, полезно явно решить, кто в очереди бариста первый — гость у стойки или заказ из приложения, — и мерить оба времени отдельно.
2. **Заказ на время и готовность к приходу.** Окна по 5 минут до часа вперёд с учётом загрузки — дешёвый способ выровнять пики. Следующий шаг, которого у Starbucks нет и за который его критикуют, — начинать готовить по сигналу о приближении гостя. Это может стать преимуществом приложения Дринкит.
3. **Критерий выхода — до раскатки.** NomadGo показывал 99% точности в лаборатории и провалился в реальных кофейнях. Для нейробаристы Дринкит и AI в учёте Dodo IS стоит заранее мерить стоимость исправления ошибки, а не только точность, и слушать сотрудников точек.
4. **Ассистент для сотрудников живёт задержкой и доверием.** Green Dot Assist отвечает 10–20 секунд, и бариста ему не доверяют. Если Dodo делает бота знаний для пиццерий и кофеен, базу знаний нужно оставить удобной и без бота, а мерить время ответа и долю эскалаций.
5. **Свой софт против вендоров.** Starbucks тратит около \$400 млн в год на софт и теперь сам пишет замены Microsoft, IBM и Oracle. Собственный стек Dodo — то, к чему Starbucks идёт только сейчас.
6. **Лояльность не как купоны.** Уровни, звёзды за траты и дешёвая награда, которая даёт треть погашений. Это бенчмарк для программ лояльности Дринкит и Додо.

---

## Что отслеживать дальше

- Звонок с инвесторами 29 октября 2026 года: время мобильного заказа и новые AI-функции.
- Запуск AI-помощника для заказа в приложении.
- Новая касса и системы учёта запасов и графиков в 2027 финансовом году.
- Попытка вернуться к автоматическому учёту запасов на другой технологии.

---

## Источники

**Starbucks:** стенограммы за [IV кв. 2025](https://s203.q4cdn.com/326826266/files/doc_financials/2025/q4/SBUX-Q4-2025-Earnings-Call-Corrected-Updated.pdf), [II кв. 2026](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q2/Q2-FY26-SBUX-Transcript.pdf) и [III кв. 2026](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q3/Q3-FY26-SBUX-Transcript.pdf) финансового года · [цифровая отчётность](https://s203.q4cdn.com/326826266/files/doc_financials/2026/q3/Q3-FY26-Digital-IR-Dashboard.pdf) · [отчётность в SEC](https://www.sec.gov/Archives/edgar/data/0000829224/000082922426000129/sbux-06282026xearningsrele.htm) · [AI в Starbucks](https://about.starbucks.com/press/2026/supporting-the-moments-that-matter-with-artificial-intelligence/) · [Green Dot Assist](https://about.starbucks.com/press/2025/meet-green-dot-assist-starbucks-generative-ai-powered-coffeehouse-companion/) · [Starbucks в ChatGPT](https://about.starbucks.com/stories/2026/meet-the-beta-starbucks-app-in-chatgpt-a-new-way-to-discover-your-next-favorite-drink/) · [новый Rewards](https://investor.starbucks.com/news/financial-releases/news-details/2026/Starbucks-Unveils-Reimagined-Loyalty-Program-to-Deliver-More-Meaningful-Value-Personalization-and-Engagement-for-Members/default.aspx) · [Clover Vertica](https://about.starbucks.com/stories/2026/freshly-brewed-coffee-on-demand-how-the-innovative-clover-vertica-is-changing-starbucks-coffeehouses/) · [хаб в Ченнаи](https://about.starbucks.com/press/2026/starbucks-technology-to-open-new-hub-in-chennai-india/)

**Медиа:** [Fast Company о NomadGo](https://www.fastcompany.com/91572019/starbucks-bet-big-ai-tool-national-scale-9-months-inventory-automated-counting-nomadgo) · [GeekWire о запуске NomadGo](https://www.geekwire.com/2025/starbucks-rolls-out-automated-counting-tech-for-inventory-with-help-from-seattle-area-startup/) · [GeekWire о закрытии](https://geekwire.com/2026/report-starbucks-scrapped-an-ai-inventory-tool-and-left-a-seattle-area-startup-blindsided) · [RTN](https://restauranttechnologynews.com/2026/08/why-starbucks-was-right-to-pull-the-plug-on-its-ai-inventory-system/) · [Fortune о своём софте](https://fortune.com/2026/07/09/starbucks-to-use-ai-to-replace-microsoft-ibm-software/) · [Fortune о Green Dot](https://fortune.com/2025/10/16/starbucks-ceo-brian-niccol-secret-ai-barista-green-dot) · [Business Insider](https://www.businessinsider.com/artificial-intelligence-digital-coworkers-restaurants-staff-starbucks-burger-king-chipotle-2026-5) · [Quartz](https://qz.com/starbucks-mobile-order-labor-barista-workflow-051926) · [Restaurant Business об Empower](https://restaurantbusinessonline.com/operations/starbucks-taps-new-tech-help-order-timing) · [NRN о заказе на время](https://www.nrn.com/restaurant-technology/starbucks-will-soon-let-you-plan-your-pickup-times) · [LeanBlog](https://www.leanblog.org/2026/03/starbucks-mobile-order-timing-problem-chick-fil-a-solved/)

**Выпуски Trend-watch:** [технологический дайджест 5–11 августа](2026-08-11_tech) · [основной дайджест 21.09–1.10](2026-10-01_weekly)
