# Атлас · SKLO Atlas

**Статус сторінки:** публічний опис продукту від власника; не оголошення загальнодоступного програмного випуску.  
**Відповідальний:** керівний чат продукту «🎬 Атлас».  
**Оновлено:** 29 жовтня 2026 року.

[Українська](#українська) · [English](#english)

---

## Українська

### Призначення

Атлас наводить лад у медіабібліотеці. Він визначає, що за твір лежить у файлі, дає файлу правильну назву й структуру тек, а потім переносить його в бібліотеку, нічого не перезаписуючи й не видаляючи.

### Що вміє перша версія (1.0)

Один фільм із неправильною назвою кладуть у вхідну теку. Далі Атлас:

1. визначає фільм через TMDb за точною назвою (і роком, якщо він відомий), а якщо збіг неоднозначний — зупиняється й показує кандидатів;
2. читає заголовки відеофайлу й визначає мітку кодека (`x265`, `x265_10bit`, `x264`, `x264_10bit`, `AV1`);
3. складає план: `Назва (Рік)/Назва (Рік) - мітка.розширення` у формі, яку документує Plex для кількох версій одного фільму;
4. виконує саме затверджений план один раз: створює нову теку фільму й переносить у неї файл без копіювання;
5. перевіряє результат і, якщо треба, повертає файл на початкове місце.

### Правила безпеки

- Кожну операцію людина затверджує окремо, за точним відбитком плану.
- Атлас не перезаписує, не видаляє і не повторює операцію автоматично.
- Якщо тека фільму вже існує або назва збігається з наявною, Атлас зупиняється й просить рішення людини.
- Якщо результат неможливо довести, Атлас так і повідомляє: «результат невідомий», а не «успіх».
- Атлас не звертається до бази даних Plex і не керує Plex.

### Чого не слід очікувати

Атлас 1.0 працює з фільмами, по одному файлу. Він не перейменовує наявну бібліотеку масово і не працює із серіалами чи музикою. У теки-колекції всередині бібліотеки він поки не заглядає.

### Поточний стан

| Версія | Стан |
|---|---|
| 1.0 | **ПРИЙНЯТО** власником 29.10.2026; працює в домашньому середовищі власника |
| 1.1 | **ЗАПЛАНОВАНО**: перевірка тек-колекцій, правила для символів, які не переносяться між системами, рішення щодо давніх дефектів бібліотеки |
| 2.0 | **НАПРЯМ**: той самий контрольований сценарій для серіалів |

### Доступність

Репозиторій і пакети поки **НЕ ПУБЛІЧНІ**. Публічних команд встановлення, інтерфейсів чи контрактів для інших продуктів наразі немає.

### Інтеграція з іншими продуктами SKLO Media

Окремих публічних контрактів для інтеграції Атлас поки не має. Інші продукти не повинні залежати від його внутрішніх файлів, форматів чи команд.

### Ліцензія

Код ще не опубліковано; ліцензія буде визначена під час публікації. Цей опис поширюється на умовах [LICENSE-DOCS.md](../../LICENSE-DOCS.md).

---

## English

**Page status:** owner-maintained public product description; not a general software release announcement.  
**Owner:** the SKLO Atlas product owner chat. **Updated:** 29 October 2026.

### Purpose

Atlas keeps a media library in order: it identifies what a file contains, gives it the correct name and folder structure, and moves it into the library without overwriting or deleting anything.

### What version 1.0 does

For one wrongly named movie placed in an intake folder, Atlas:

1. identifies the movie on TMDb from its exact title (and year, if known); if the match is ambiguous, it stops and shows candidates;
2. reads the video headers and derives a codec label (`x265`, `x265_10bit`, `x264`, `x264_10bit`, `AV1`);
3. builds a plan: `Title (Year)/Title (Year) - label.ext`, using the Plex-documented multi-version form;
4. executes exactly the approved plan once: it creates the new movie folder and moves the file into it, with no copy;
5. verifies the result and can move the file back if needed.

### Safety rules

- A person approves each operation separately, by the exact plan digest.
- Atlas never overwrites, never deletes and never retries automatically.
- If the movie folder already exists, or a name matches an existing entry, Atlas stops and asks a person to decide.
- If the outcome cannot be proven, Atlas reports it as unknown, never as success.
- Atlas does not access the Plex database and does not control Plex.

### What not to expect

Atlas 1.0 handles movies, one file at a time. It does not bulk-rename an existing library and does not handle TV series or music. It does not yet look inside collection folders in the library.

### Status

| Version | Status |
|---|---|
| 1.0 | **ACCEPTED** by the owner on 2026-10-29; running in the owner's home environment |
| 1.1 | **PLANNED**: collection folders, rules for characters that do not carry across systems, decisions on old library defects |
| 2.0 | **DIRECTION**: the same controlled flow for TV series |

### Availability

The repository and packages are **NOT YET PUBLIC**. There are no public installation commands, interfaces or cross-product contracts yet.

### Integration with other SKLO Media products

Atlas has no public integration contracts yet. Other products must not depend on its internal files, formats or commands.

### License

The code is not published yet; its license will be defined on publication. This description is covered by [LICENSE-DOCS.md](../../LICENSE-DOCS.md).

---

Before publishing changes, follow the [Public Documentation Policy](../PUBLICATION_POLICY.md).
