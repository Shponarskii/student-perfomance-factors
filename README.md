# student-perfomance-factors

## Описание проекта

В данном проекте проводился статистический анализ успеваемости учащихся и влияющих на нее факторов.

В ходе работы проведены:

* Графический анализ (2D и 3D графики)
* Дисперсионный анализ
* Корреляционный анализ
* Кластерный анализ
* Факторный анализ
* Тесты параметрической статистики
* Тесты непараметрической статистики

Данные для анализа были взяты со следующего источника:  
*https://www.kaggle.com/datasets/lainguyn123/student-performance-factors*

Все расчеты проводились с использованием Python в Jupyter Notebook, а также в пакете прикладных программ *Statistica*. Также был подготовлен отчет о проделанной работе в Microsoft Word, который расположен в папке **docs**.

## Используемые библиотеки

* pandas
* numpy
* scipy
* statsmodels
* sklearn
* matplotlib

## Структура проекта

```tree
student-perfomance-factors/
│
├── data/
│   ├── student_perfomance_factors.csv
│   └── student_perfomance_sample.csv
│
├── docs/
│   └── student_perfomance_factors_report.docx
│
├── notebooks/
│   ├── analysis_of_variance.ipynb
│   ├── basic_statistics.ipynb
│   ├── cluster_analysis.ipynb
│   ├── factor_analysis.ipynb
│   ├── graphical_analysis.ipynb
│   ├── linear_regression.ipynb
│   └── nonparametric_statistics.ipynb
│
├── .gitignore
└── README.md
```