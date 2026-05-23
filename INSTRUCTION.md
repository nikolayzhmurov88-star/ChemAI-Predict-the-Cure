# Инструкция по воспроизведению результатов

## Требования к окружению

- **Платформа:** Google Colab

---

### Шаг 1. Открытие ноутбука

1. Перейти на [Google Colab](https://colab.research.google.com/)
2. Нажать `File → Upload notebook`
3. Выбрать файл `ChemAI-Final.ipynb` из репозитория

### Шаг 2. Запуск всех ячеек

В Colab нажать `Runtime → Run all` (или `Ctrl+F9`)

Ноутбук автоматически выполнит:
- Скачивание данных с Google Drive
- Заполнение пропусков
- Обучение моделей LightGBM
- Создание файла сабмита

### Шаг 3. Проверка выполнения

После успешного выполнения в конце ноутбука появится сообщение:  submission_boxcox.csv сохранён


### Шаг 4. Скачивание результата

**В Colab:**
1. Нажать на иконку папки слева (`Files`)
2. Найти файл `submission_boxcox.csv`
3. Нажать на три точки → `Download`


### Шаг 5. Отправка на Kaggle

1. Зайти на [страницу соревнования](https://www.kaggle.com/competitions/chem-ai-predict-the-cure)
2. Нажать кнопку `Submit Predictions`
3. Загрузить файл `submission_boxcox.csv`
4. Нажать `Make Submission`

### Ожидаемый результат

**Score на Kaggle: 295.85**

