# GOT-Death-Predictor

## Описание

В данном проекте я буду работать с датасетом о персонажах из вселенной Игры Престолов [A Wiki of Ice and Fire](https://awoiaf.westeros.org/index.php/Main_Page). Буду предсказывать, кто из персонажей умрет, а кто останется вживых, то есть решать задачу бинарной классификации. 

**Задачи проекта**:
- Предобработать данные (обработка пропущенных данных, создание новых признаков, удаление ненужных столбцов)
- Выполнить анализ данных (анализ целевой переменной, признаков, влияние признаков на целевую переменную)
- Подготовить данные для обучения
- Применить различные модели классификации из `sklearn` (), сравнить качество классификации и выбрать лучшую модель


---

## Подробнее

[Посмотреть ноутбук можно здесь](project/GOT_Death_Predictor.ipynb)

---

## Используемые библиотеки и методы анализа

### Библиотеки:
- **pandas**, **numpy** – обработка и анализ данных
- **matplotlib**, **seaborn** – визуализация данных
- **scikit-learn** – обучение моделей и нахождение качества классификации

### Методы анализа:
- **Исследовательский анализ данных (EDA)**: визуализация целевой переменной, матрица корреляций, круговые диаграммы.
- **Машинное обучение**: модели классификации LogisticRegression, RandomForestClassifier, AdaBoostClassifier, GaussianProcessClassifier, GaussianNB, KNeighborsClassifier, SVC, DecisionTreeClassifier

---

## Основные результаты
- отработал использование различных методов обработки и анализа данных
- подготовил данные для обучения
- модель логистической регрессии показала себя лучше всего, accuracy на валидации равен 1.0
---

## 🔧 Установка

Для работы с проектом потребуется **Python 3.x** и следующие библиотеки:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy xgboost lightgbm catboost shap phik
