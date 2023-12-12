## 1. [One Day timeseries forecasting task](./OneDayTimeSeriesForecastTask/eda_on_lesson.ipynb)

Задача с собесадования

## 2. TS libraries examples

- Darts: https://github.com/unit8co/darts

- Sktime

  - https://github.com/sktime/sktime

  - intro:
    https://github.com/sktime/sktime/blob/main/examples/00_sktime_intro.ipynb

Нейросетвые предсказания: - Pytorch forecasting: https://github.com/jdb78/pytorch-forecasting

Генерация признаков: - Tsfresh: https://github.com/blue-yonder/tsfresh/tree/main

Библиотека которую рассматриваем на уроке: - ETNA

## 3. ETNA: python timeseries library

![img](img/ENTA%20chat.png)

[пример](./etna/examples/103-EDA.ipynb)

## 4. Termin: Auto Correlation

Формула: Корреляция Пирсона ряда с самим собой со сдвигом на $\tau.

Смысл: оценка степень влияние значения $y_t$ на значение $y_{t + \tau}$

$$
r_\tau=\widehat{\operatorname{corr}}\left(y_t, y_{t+\tau}\right)=\frac{\sum_{t=1}^{T-\tau}\left(y_t-\bar{y}\right)\left(y_{t+\tau}-\bar{y}\right)}{\sum_{t=1}^T\left(y_t-\bar{y}\right)^2}, \quad \bar{y}=\frac{1}{T} \sum_{t=1}^T y_t
$$

(где $\tau$ - лаг автокорреляции)
