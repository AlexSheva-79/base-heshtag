# SKILL: Созерцательный рилз-антология — опыт сессии «Сады» (сентябрь 2026)

Фиксирует всё, что было выведено и исправлено в ходе работы над рилзом «Сады на летающих островах» (@fairyteller_art). Применять при любом рилзе-антологии локаций в восточном техно-фэнтези или схожей эстетике, а также при любом рилзе где есть: (а) анимация ящериц/бабочек, (б) ветер на ткани и волосах в Grok, (в) цветокоррекция красного/зелёного в ChatGPT.

**Кодовые фразы-триггеры:** «рилз Острова», «сады», «ящерицы с крыльями», «летающие острова», «восточное фэнтези», «Grok анимация фауна», «цветокоррекция алый».

---

## 1. ПРОТОКОЛ — обязателен для КАЖДОГО промпта без исключений

**Включая цветокоррекцию. Нет исключений.**

Порядок:
1. Показать **только блок самопроверки** — без промпта
2. Ждать подтверждения (да / ок / подтверждаю)
3. Показать промпт
4. Следующий промпт — только после утверждения предыдущего

### Шаблон блока самопроверки (GPT-статика):
```
Проверка:
- Инструмент: ChatGPT/DALL-E
- Референсы: image1 = [описание] / карта персонажа [нужна / не нужна]
- Identity/geometry lock: [что фиксируется или «не применимо»]
- Цветокоррекция: антикаст-блок встроен, алый — отдельная строка
- Ракурс: [конкретный угол и высота камеры]
```

### Шаблон блока самопроверки (Grok-анимация):
```
Проверка:
- Инструмент: Grok Video
- Референсы: image1 = [финальная статика] / image2 = [карта персонажа если лицо в кадре]
- Identity/geometry lock: [face lock нужен / не нужен — почему]
- Камера: [конкретный приём], ранее использованные в этом рилзе: [список]
- Звук: только диегетика ✓
```

---

## 2. СЦЕНАРИЙ-АНТОЛОГИЯ: 8 локаций, 8 уникальных камер

### Правило камер:
Каждый приём — строго один раз в рилзе. Вести учёт по ходу работы.

### Восемь приёмов рилза «Сады» (не повторять пока не закрыт другой рилз):
| № | Приём | Функция |
|---|---|---|
| 1 | Low-angle locked | Хук — статика с живой сценой, акцент на деталях |
| 2 | Bird's eye drift | Симметрия сверху, героиня узнаётся по волосам |
| 3 | Push-in / Worm's eye | Монументальность — объект нависает над зрителем |
| 4 | Tilt down | Открывает пропасть под ногами, эпический масштаб |
| 5 | Orbit (облёт) | Огибает героиню, Dutch angle — наклон 15° |
| 6 | Reverse pull-out | Отъезд назад раскрывает всю локацию |
| 7 | Handheld (steadicam) | Органическое дрожание — ощущение присутствия оператора |
| 8 | Crane up | Финал — подъём вверх, мир заполняет кадр |

### Якорный персонаж:
Одно существо/символ в сценах 1, 3 и 8 — создаёт скрытую нить, зритель замечает при пересмотре. В «Садах»: синяя ящерица с крыльями стрекозы.

### Акцентный цвет-нить:
Один насыщенный цвет проходит через все сцены. В «Садах»: алый/crimson (лотосы, рукава, паруса, лианы, фонари).

---

## 3. GPT-СТАТИКА: обязательные блоки

### Антикаст-блок (вставлять в КОНЕЦ каждого промпта):
```
STRICT NEUTRAL COLOR BALANCE: maintain neutral, true-to-life color balance
throughout. Actively counteract warm yellow/amber color cast. Keep cool
undertones in shadow areas. Keep white fabric truly white, not cream or ivory.
```

### Блок защиты алого (добавлять когда crimson/красный в кадре):
```
The [crimson flowers / crimson inner robes / crimson sash] must be pure vivid
saturated crimson — bright clean red, not brick, not terracotta, not coral,
not orange-red.
```

### Типовые зоны жёлтого каста в восточном фэнтези:
- Бамбук → «cool deep green, not yellow-green, not olive»
- Мох на камне → «cool dark green, not yellow-green»
- Алые цветы → «pure vivid saturated crimson, not brick»
- Небо-туман → «cool teal-emerald mist, deeply saturated, not warm grey»

---

## 4. ЦВЕТОКОРРЕКЦИЯ: отдельный промпт, раздельные зоны

**Не пытаться исправить всё одним глобальным «fix the colors» — не работает.**

Называть каждую зону отдельным пунктом:

```
Color correction only — do not change composition, figures, or any other element.

Fix only these zones:
1. [НАЗВАНИЕ ЗОНЫ]: has [тёплый / жёлтый / кирпичный] cast →
   shift to [целевой цвет — конкретно]
2. [НАЗВАНИЕ ЗОНЫ]: ...

Do NOT touch: [перечислить каждый элемент с правильным цветом — ящерицы, небо,
персонажи, камень и т.д.].

Vertical portrait orientation, 9:16 aspect ratio.
```

---

## 5. GROK-АНИМАЦИЯ: пять правил

### Правило 1 — Все живые существа в конкретном движении
❌ «стоит и смотрит вверх» / «наблюдает» / «poses thoughtfully»
✅ «медленно поднимает правую руку, указывает вверх на ящерицу, поворачивает голову к соседу, рот приоткрывается»

Каждый персонаж/существо получает цепочку конкретных физических действий с указанием части тела.

### Правило 2 — Физика ветра: каждый мягкий элемент отдельно
Прописывать для каждого:
```
WIND PHYSICS — applied to every soft element simultaneously:
- Her long wavy auburn-red hair: lifts and flows continuously in a gentle
  breeze — large sections billowing backward, individual strands drifting
  across her profile
- Her dark violet outer robe: billows and ripples — wide sleeves swaying
  with each step, fabric flowing behind her
- Her crimson inner layers: trail and lift slightly at the hem
- Red silk tassels on hair ornaments: sway rhythmically
- [Лианы / лепестки / листья]: sway gently, petals detaching and drifting
```

### Правило 3 — Физика ящерицы-бабочки (НЕ стрекоза)
```
BUTTERFLY FLIGHT PHYSICS — not dragonfly flutter:
Each wingbeat is slow, broad and deliberate — wings sweep fully downward in a
long arc, pause briefly at the bottom, then sweep back up. Body bobs gently
up and down with each stroke. Flight path drifts and wavers, never a straight
line. Wings must be visibly and continuously beating throughout the entire
duration — never freezing or stopping.
```

Чтобы ящерица не замёрзла — добавлять явную директиву:
```
[Lizard name] must be visibly moving from the very first frame — never static
or frozen at any point during the shot.
```

### Правило 4 — Face lock (если лицо именного персонажа в кадре)
Всегда загружать карту персонажа как @image2 и давать идентичную формулировку:
```
@image2 is the character reference — use her face, [цвет] hair, freckles and
[цвет] eyes as an exact identity lock throughout the entire shot. Her face
must not drift, morph or change at any point.
```
Без face lock лицо «плывёт» при движении камеры в Grok.

### Правило 5 — Звук: только диегетика, без «NO MUSIC»
Никогда не писать «NO MUSIC» или «no background music» — это нарушает алгоритм Grok.
Просто не упоминать музыку. Прописывать 5–8 конкретных источников звука:
```
Audio: [конкретный звук 1], [конкретный звук 2], [...], [...], [...].
```

---

## 6. ТОЧЕЧНАЯ ПРАВКА — не пересоздавать сцену

Когда GPT дал 5 ящериц вместо 2 (или лишний персонаж, или не тот цвет):

```
Edit only: remove [конкретный элемент 1] and [конкретный элемент 2].
Keep [элемент А] exactly in its current position.
Keep [элемент Б] exactly in its current position.
Do not change any other element — composition, lighting, background,
remaining figures remain identical.
```

Правило: чем точнее перечислено «что убрать» и «что оставить» — тем меньше GPT трогает лишнего.

---

## 7. ПЕРСОНАЖ А («Острова»): готовый identity-блок

```
Use the character from image1 as an exact reference for the woman's face,
hair color, hair ornaments, and clothing — replicate her long wavy
auburn-red hair, green eyes, freckles, dark violet outer robe with large gold
phoenix embroidery, vivid crimson inner hanfu layers, gold jewelry and
hair pins.
```

Карта: `/mnt/user-data/uploads/1000051364.png`
(9 панелей: Front / ¾ / Side / Back / Face Detail / Expression / Hair / Jewelry / Belt)

---

## 8. КАПШИОН: структура и триггеры

| Элемент | Функция | Примечание |
|---|---|---|
| Хук | Watch-time | ≤125 символов (граница обрезки в ленте) |
| Атмосфера | Удержание | 1–2 строки, эмодзи |
| Save-триггер | Сохранения | «Сохрани — чтобы возвращаться» |
| Send-триггер | Пересылки | «Отправь тому, с кем хотел бы...» |
| Провокация | Досмотр до конца | «Досмотри до последней сцены — там...» |
| Хэштеги | Охват | 3–5 нишевых, из реестра |

Хэштеги линии «Острова»: `#floatingislands #orientalfantasy #fantasyart #aiartcommunity`

---

## 9. ГЕОЛОКАЦИИ: пул для линии «Острова»

| Геолокация | Использована | Совпадение |
|---|---|---|
| Classical Gardens of Suzhou · 苏州古典园林 | «Сады» 30.09.2026 | Лотосы, лунные ворота, павильоны, бамбук |
| Wuzhen Water Town · 乌镇 | «Дождь» | Каналы, мосты, туман, дождь |
| Zhangjiajie National Forest Park | — | Парящие острова/Avatar горы |
| Yangshuo · 阳朔 | — | Карстовые пики, река, туман |

Правило: не повторять геолокацию в рамках одной линии. Выбирать с прямым визуальным совпадением с сеттингом сцен.

---

## 10. ДНЕВНИК ОШИБОК: не повторять

| Ошибка | Сцена | Исправление |
|---|---|---|
| Цветокоррекция без протокола | Сц. 3 | Протокол для ВСЕХ промптов |
| Статичная камера по умолчанию | Сц. 1–3 | Камера = осознанный выбор, учёт по рилзу |
| «Стоит и смотрит» вместо физики | Сц. 3, 4 | Цепочка конкретных действий для каждого |
| GPT дал 5 ящериц вместо 2 | Сц. 4 | Точечный edit-промпт с явным «что убрать» |
| Жёлтый каст по трём зонам | Сц. 6 | Зоны цветокоррекции — каждая отдельно |
| Ящерица заморожена в Grok | Сц. 1 | Цепочка действий + явная директива «never freezing» |

---

## Источник

Составлен по итогам сессии «Сады на летающих островах», сентябрь 2026.
Урок-документ: `Сады_урок_РУ.docx`
Универсальный скилл для читателей урока: https://github.com/AlexSheva-79/base-heshtag/blob/main/oriental-fantasy-reel-SKILL.md
