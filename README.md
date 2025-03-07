# GOT-Death-Predictor

## 📌 Описание проекта

В данном проекте я буду работать с датасетом о персонажах из вселенной Игры Престолов [A Wiki of Ice and Fire](https://awoiaf.westeros.org/index.php/Main_Page). Буду предсказывать, кто из персонажей умрет, а кто останется вживых, то есть решать задачу бинарной классификации.

🔍 **Задачи проекта**:
- Построить **модели предсказания запасов нефти** для каждого из трёх регионов.
- Оценить **возможную прибыль** от разработки каждого региона.
- Проанализировать **уровень риска убытков** с помощью статистических методов.
- Выбрать **наиболее выгодный регион** для бурения нефтяных скважин.

---

## 📂 Содержание

[📌 Посмотреть проект можно здесь](project/drilling.ipynb)

---

## 🔬 Используемые методы и библиотеки

### 📚 Библиотеки:
- **pandas**, **numpy** – обработка и анализ данных
- **matplotlib**, **seaborn** – визуализация данных
- **scikit-learn** – машинное обучение и статистический анализ
- **scipy** – статистические тесты
- **xgboost**, **lightgbm**, **catboost** – градиентный бустинг
- **shap**, **phik** – анализ важности признаков и корреляции

### 📊 Методы анализа:
- **Исследовательский анализ данных (EDA)**: визуализация, корреляция, распределение запасов нефти.
- **Машинное обучение**: построение моделей **линейной регрессии** и бустинга для прогнозирования запасов нефти.
- **Статистическая оценка рисков**: доверительные интервалы, бутстреп-анализ.
- **Анализ прибыльности**: расчёт прогнозируемой прибыли и вероятности убытков.

---

## 📈 Основные результаты

🔹 **Средняя прибыль по регионам**:
- **Регион 0**: **448 млн руб.** (риск убытков: **4,60%**)
- **Регион 1**: **300 млн руб.** (риск убытков: **5,80%**)
- **Регион 2**: **571 млн руб.** (риск убытков: **1,10%**)

🛢 **Наиболее перспективный регион**: **Регион 2**  
✅ **Минимальный риск убытков (1,10%)**  
✅ **Полностью положительный доверительный интервал прибыли**  
✅ **Высокая предсказуемость модели**

---

## 🔧 Установка

Для работы с проектом потребуется **Python 3.x** и следующие библиотеки:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy xgboost lightgbm catboost shap phik
