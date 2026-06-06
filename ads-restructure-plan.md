# Google Ads — Seamless CI Campaign Restructure

## 1. Negative Keywords (CSV готов — negative-keywords-ci.csv)

## 2. Keywords — только точные и фразовые

### ✅ Фразовое (" ")
```
"contact improvisation class"
"contact improvisation course"
"contact improvisation online"
"contact improvisation beginner"
"contact improvisation beginners"
"contact improvisation workshop"
"contact improvisation lesson"
"contact improvisation lessons"
"contact improvisation practice"
"online contact improvisation"
"learn contact improvisation"
"contact improvisation for beginners"
```

### ✅ Точное [ ]
```
[contact improvisation class]
[contact improvisation course]
[contact improvisation online]
[contact improvisation for beginners]
```

### ⛔ ОСТАВИТЬ НО ПЕРЕВЕСТИ В ФРАЗОВОЕ (сейчас Broad Match — сливают бюджет!)
```
"contact improvisation"      (было Broad — 4 клика, TRY 240.45)
"dance improvisation"         (было Broad — 11 кликов, TRY 174.71 — много мусора)
"improvisation dance"        (было Broad — 4 клика, TRY 57.06)
```

## 3. Настройки которые надо изменить

| Настройка | Было | Надо |
|-----------|------|------|
| Search Networks | Google + Partners | **Только Google Search** |
| Location | Presence or interest | **Presence only** |
| Keyword match | Broad | **Phrase + Exact** |
| Bidding | Auto | **Manual CPC (max 35-40 TRY)** |

## 4. Структура Ad Groups

**Ad Group 1: CI Beginners (Buying Intent)**
- "contact improvisation class"
- "contact improvisation course"
- "contact improvisation online"
- [contact improvisation class]

**Ad Group 2: CI Awareness (Research)**
- "contact improvisation"
- "contact improvisation beginner"
- "contact improvisation for beginners"
- "learn contact improvisation"

**Ad Group 3: Floorwork (Solo)**
- "floorwork dance"
- "floor movement practice"
- "floorwork improvisation"

## 5. Дневной бюджет
Сейчас ~TRY 200/день. Для старта хватит TRY 100-150, пока не пойдут конверсии.
