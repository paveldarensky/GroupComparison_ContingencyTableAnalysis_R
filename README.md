# 🩺 Group Comparison & Contingency Table Analysis (R)

## 🌍 EN

### 📌 About  
This project analyzes **pulse measurements** and **exam grades** across multiple groups using R.  
It demonstrates statistical comparison of groups and analysis of contingency tables.

### 🔑 Features  
- ✅ Pulse analysis for four groups:  
  - **CB** – Patients, before medication  
  - **CA** – Patients, after medication  
  - **EB** – Healthy, before medication  
  - **EA** – Healthy, after medication  
- ✅ Normality check using **Q-Q plots** and **Shapiro-Wilk test**.  
- ✅ Comparison of groups:  
  - Paired and unpaired **t-tests** or **Wilcoxon tests** depending on normality.  
  - Boxplots for visual comparison.  
- ✅ Contingency table analysis for exam grades:  
  - Creation of a table linking **Group** and **Grade**.  
  - Hypothesis testing using **Chi-squared test** and **Fisher's exact test**.  

### 📂 Project Structure  
- `pulse.txt` – pulse measurements for 4 groups.  
- `grades.txt` – exam grades for 4 groups.  
- **Data analysis** – loading, cleaning, and preprocessing of data.  
- **Statistical testing** – Shapiro-Wilk, t-test, Wilcoxon, Chi-squared, Fisher.  
- **Visualization** – histograms, Q-Q plots, boxplots via `ggplot2`.  

### 🖼️ Screenshots  
- 📊 Histograms and Q-Q plots for pulse measurements.  
- 📦 Boxplots comparing pulse distributions across groups.  
- 📈 Contingency tables and test results for exam grades.  

---

## 🌍 RU

### 📌 О проекте  
Проект посвящён анализу **пульса** и **оценок за экзамен** в нескольких группах с использованием R.  
Демонстрируется сравнение групп и анализ таблиц сопряженности.

### 🔑 Возможности  
- ✅ Анализ пульса для четырех групп:  
  - **CB** – Пациенты до лекарства  
  - **CA** – Пациенты после лекарства  
  - **EB** – Здоровые до лекарства  
  - **EA** – Здоровые после лекарства  
- ✅ Проверка нормальности с помощью **квантильных графиков (Q-Q plot)** и **теста Шапиро-Уилка**.  
- ✅ Сравнение групп:  
  - Парные и непарные **t-тесты** или **критерий Вилкоксона** в зависимости от нормальности.  
  - Boxplot для наглядного сравнения.  
- ✅ Анализ таблиц сопряженности для оценок:  
  - Создание таблицы связи **Группа** и **Оценка**.  
  - Проверка гипотезы с помощью **критерия Хи-квадрат** и **точного критерия Фишера**.  

### 📂 Структура проекта  
- `pulse.txt` – измерения пульса для 4 групп.  
- `grades.txt` – оценки за экзамен для 4 групп.  
- **Анализ данных** – загрузка, очистка и подготовка данных.  
- **Статистическая проверка** – тесты Шапиро-Уилка, t-тест, Вилкоксон, Хи-квадрат, Фишер.  
- **Визуализация** – гистограммы, Q-Q plot, boxplot с использованием `ggplot2`.  

### 🖼️ Скриншоты  
- 📊 Гистограммы и Q-Q plot для измерений пульса.  
- 📦 Boxplot для сравнения распределений пульса в группах.  
- 📈 Таблицы сопряженности и результаты тестов для оценок.
