# МедіаПорядок · MediaOrder

**Статус сторінки:** публічний опис продукту від власника; не оголошення загальнодоступного програмного випуску.  
**Відповідальний:** головний чат продукту «💽 МедіаПорядок».  
**Оновлено:** 29 жовтня 2026 року.

[Українська](#українська) · [English](#english)

---

## Українська

### Призначення

МедіаПорядок — локальний застосунок на Mac, з яким автор контенту впорядковує фото, відео й супровідні матеріали своїх медіапроєктів. Він починає з надійної обробки вручну підготовленої теки-проєкту й поступово бере на себе більше рутини: технічну перевірку, субтитри, зв'язок зі сценарієм, інтерфейс, структуру й архівування.

Аналогія: сканер (пристрій) → програма для сканування → готовий документ. МедіаПорядок — це «програма»: робоче вікно автора, з якого він користується спеціалізованими модулями SKLO Media й отримує впорядкований результат.

### Що належить МедіаПорядку

- проєкти автора та їхній контекст;
- теки, які треба переглядати, і пошук у них нових матеріалів;
- каталог медіа проєкту й стан роботи над ним;
- вибір матеріалів і запуск обробки;
- приймання результатів, пошук, перегляд і рішення людини;
- інтерфейс застосунку (запланований).

### Що не належить МедіаПорядку

- **Аналіз відео й звуку** — це Призма.
- **Розшифровка й субтитри**, **зіставлення зі сценарієм**, **аналіз зображень**, **покращення фото** — окремі модулі сімейства.
- **Розпізнавання, назви й переміщення файлів за правилами** — Атлас.
- **Схема й версії бази медіа** — FmediaDB.

МедіаПорядок не переписує код інших продуктів і не залежить від їхніх внутрішніх файлів.

### Правила безпеки

- Оригінали медіа лише читаються.
- Неоднозначний стан — зупинка, а не припущення.
- Дія, що змінює файли чи дані, виконується один раз і перевіряється; після незрозумілого збою її не повторюють автоматично.
- Ручний шлях лишається завжди: автор може сам покласти матеріали в теку проєкту й отримати перевірений результат.

### Поточний стан

| Версія | Стан |
|---|---|
| 1.0 | мінімально корисний продукт: ручний проєкт, технічна обробка, сире розпізнавання мовлення, службові результати |
| 1.2 | **ПРИЙНЯТО** власником (вересень 2026); перевірено на реальному проєкті автора |
| 2.0 | **ЗАПЛАНОВАНО**: субтитри SRT/VTT із таймкодами — через модуль «Розшифровка й субтитри» |
| 3.0 | **НАПРЯМ**: зв'язок дублів із розділами сценарію — через модуль «Зіставлення зі сценарієм» |
| 4.0 | **НАПРЯМ**: окремі режими FAST (масовий прохід) і DEEP (глибока перевірка вибраного) |
| 5.0 | **НАПРЯМ**: перший стандартний інтерфейс macOS |
| 6.0 | **НАПРЯМ**: спрощення й оптимізація за досвідом попередніх версій |

Далі — без номерів: архівування завершених проєктів, джерела камер і знімні носії, контент-план, семантичний пошук.

### Інтеграція з іншими продуктами SKLO Media

Напрям: модулі збору інформації видають результати у форматі FmediaDB, а МедіаПорядок працює з цими даними — з модулями або й без них. Публічних контрактів інтеграції поки **немає**; їх узгоджують із власниками відповідних продуктів.

### Доступність

Репозиторій і пакети поки **НЕ ПУБЛІЧНІ**. Публічних команд встановлення, інтерфейсів чи контрактів для інших продуктів наразі немає.

### Ліцензія

Код ще не опубліковано; ліцензію буде визначено під час публікації. Цей опис поширюється на умовах [LICENSE-DOCS.md](../../LICENSE-DOCS.md).

---

## English

**Page status:** owner-maintained public product description; not a general software release announcement.  
**Owner:** the MediaOrder product owner chat. **Updated:** 29 October 2026.

### Purpose

MediaOrder is a local Mac application that helps a content creator keep the photos, videos and related material of their media projects in order. It starts with reliable processing of a manually prepared project folder and gradually takes over more routine work: technical checks, subtitles, linking to the script, a user interface, structure and archiving.

Analogy: scanner (device) → scanning software → finished document. MediaOrder is the "software": the creator's workspace for using specialised SKLO Media modules and getting an organised result.

### What MediaOrder owns

- the creator's projects and their context;
- the folders to watch and discovery of new material in them;
- the project's media catalogue and work state;
- selecting material and starting processing;
- accepting results, search, viewing and the person's decisions;
- the application interface (planned).

### What MediaOrder does not own

- **Video and audio analysis** — Pryzma.
- **Transcript and subtitles**, **scenario matching**, **image analysis**, **photo enhancement** — separate family modules.
- **Rule-based identification, naming and moving of files** — Atlas.
- **Media database schema and versions** — FmediaDB.

MediaOrder does not rewrite other products' code and does not depend on their internal files.

### Safety rules

- Original media are read-only.
- An ambiguous state means stop, not guess.
- An action that changes files or data runs once and is verified; after an unclear failure it is not retried automatically.
- The manual path always remains: the creator can place material into the project folder and get a verified result.

### Current status

| Version | Status |
|---|---|
| 1.0 | minimum useful product: manual project, technical processing, raw speech recognition, service outputs |
| 1.2 | **ACCEPTED** by the owner (September 2026); verified on a real project of the author |
| 2.0 | **PLANNED**: SRT/VTT subtitles with timecodes — via the Transcript & Subtitles module |
| 3.0 | **DIRECTION**: linking takes to script sections — via the Scenario Matching module |
| 4.0 | **DIRECTION**: separate FAST (bulk pass) and DEEP (in-depth check of selected items) modes |
| 5.0 | **DIRECTION**: first standard macOS interface |
| 6.0 | **DIRECTION**: simplification and optimisation based on earlier versions |

Later, without version numbers: archiving finished projects, camera sources and removable media, content plan, semantic search.

### Integration with other SKLO Media products

Direction: information-gathering modules publish their results in the FmediaDB format, and MediaOrder works with that data — with or without the modules. There are **no** public integration contracts yet; they are agreed with the owners of the respective products.

### Availability

The repository and packages are **NOT YET PUBLIC**. There are no public install commands, interfaces or contracts for other products at this time.

### License

The code is not yet published; its license will be decided at publication. This description is provided under [LICENSE-DOCS.md](../../LICENSE-DOCS.md).
