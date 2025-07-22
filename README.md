### 🏡 Apartment Price Forecasting

Этот проект представляет собой модель машинного обучения для прогнозирования стоимости квартир на основе различных признаков.

---

#### 📦 Используемые технологии

- **CatBoost**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**

---

#### 🔧 Основные этапы

1. Импорт и очистка данных
2. Анализ и визуализация
3. Разделение на train/test
4. Обучение модели `CatBoostRegressor`
5. Оценка точности модели
6. Сохранение модели

---

#### 📈 Формулы

MAE - Mean Absolute Error (Средняя абсолютная ошибка)
```bash
MAE = (1/n) * Σ |yᵢ - ŷᵢ|
```
Где `yᵢ` — фактические значения, `ŷᵢ` — предсказанные значения.

---

MSE - Mean Squared Error (Среднеквадратичная ошибка)
```bash
MSE = (1/n) * Σ (yᵢ - ŷᵢ)²
```

---

RMSE - Root Mean Squared Error (Корень из MSE)

```bash
RMSE = sqrt((1/n) * Σ (yᵢ - ŷᵢ)²)
```
    
---

R² - Coefficient of Determination (Коэффициент детерминации)

```bash
R² = 1 - [Σ (yᵢ - ŷᵢ)² / Σ (yᵢ - ȳ)²]
```
Где `ȳ` — среднее значение по всем `yᵢ`.

---

🔧 Установка

1. Установите зависимости:
```bash
pip install catboost pandas numpy scikit-learn matplotlib
```
