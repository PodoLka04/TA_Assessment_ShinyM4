# 🌐 Language / Язык

[🇬🇧 English](#english) | [🇷🇺 Русский](#russian)

---

## <a name="russian"></a>

# TA Assessment Shiny App

Проект выполнен в рамках курса **"Приложения и практика анализа данных"** (Майнор НИУ ВШЭ, 4 семестр).

## 📌 Задание

Повторить интерфейс Shiny-приложения для анализа данных Teaching Assistant (TA) в точности как на скриншоте.

## 🔍 Интерфейс

- **Заголовок:** "TA Assessment"
- **Боковая панель:**
  - Выпадающий список "Instructor:" (pickerInput, значения из данных)
  - Слайдер "Max class size:" (0–70, по умолчанию 0–40)
  - Переключатель "Delete plot background"
- **Основная панель:**
  - Вкладка "График" — bar chart распределения Score
  - Вкладка "Таблица" — отфильтрованные данные

## ✅ Требования

1. Выпадающие списки подтягиваются из данных (не вбиты вручную)
2. Использована библиотека `shinyWidgets`
3. При первом входе значения по умолчанию как на скриншоте

## 💡 Что можно улучшить

1. В график добавить `fill = isNative`
2. В таблицу добавить пейджинг и поиск
3. Добавить фильтры по Season и Course

## 📁 Содержимое репозитория

| Файл | Описание |
|------|----------|
| `TA.csv` | Исходные данные |
| `app.Rmd` | Код приложения |
| `Задание.png` | Скриншот задания |
| `Требования к Интерфейсу.pdf` | Конкретный вид и описание интерфейса, который необходимо было повторить|

## 🚀 Ссылка на приложение

🔗 **https://dpodolin13.shinyapps.io/ta_assessment_app/**

## 🛠 Инструменты

- R
- Shiny
- shinyWidgets
- ggplot2
- dplyr

## 📌 Автор

Подолин Дмитрий  
НИУ ВШЭ, курс "Приложения и практика анализа данных"

---

## <a name="english"></a>

# TA Assessment Shiny App

The project was completed as part of the **"Applications and Practice of Data Analysis"** course (HSE Minor, 4th semester).

## 📌 Assignment

Reproduce the Shiny application interface for Teaching Assistant (TA) data analysis exactly as shown in the screenshot.

## 🔍 Interface

- **Title:** "TA Assessment"
- **Sidebar:**
  - Dropdown list "Instructor:" (pickerInput, values from data)
  - Slider "Max class size:" (0–70, default 0–40)
  - Toggle switch "Delete plot background"
- **Main panel:**
  - Tab "Graph" — bar chart of Score distribution
  - Tab "Table" — filtered data

## ✅ Requirements

1. Dropdown lists are populated from the data (not hardcoded)
2. The `shinyWidgets` library is used
3. Default values on first load match the screenshot

## 💡 Possible improvements

1. Add `fill = isNative` to the graph
2. Add pagination and search to the table
3. Add filters for Season and Course

## 📁 Repository contents

| File | Description |
|------|-------------|
| `TA.csv` | Source data |
| `app.Rmd` | Application code |
| `Задание.png` | Screenshot of the assignment |
| `Требования к Интерфейсу.pdf` | The specific appearance and description of the interface that had to be replicated.|

## 🚀 Application link

🔗 **https://dpodolin13.shinyapps.io/ta_assessment_app/**

## 🛠 Tools

- R
- Shiny
- shinyWidgets
- ggplot2
- dplyr

## 📌 Author

Dmitrii Podolin  
HSE University, "Applications and Practice of Data Analysis" course
