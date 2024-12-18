# WineQuality: Предсказание качества вина

Этот проект посвящен предсказанию качества вина на основе его физико-химических характеристик.  Для обучения модели используется нейронная сеть, реализованная с помощью PyTorch.

---

## Описание

Проект исследует два набора данных о вине (красном и белом) и строит модель для предсказания качества вина по шкале от 3 до 9.  В связи с сильным дисбалансом классов в данных используются методы oversampling'а `SMOTE` и undersampling'а `RandomUnderSampler` для балансировки классов и улучшения качества предсказаний.

---

## Файлы

- `winequality-red.csv:`  Набор данных о красном вине. Содержит физико-химические характеристики и оценку качества.
- `winequality-white.csv:` Набор данных о белом вине.  Содержит физико-химические характеристики и оценку качества.
- `wine.ipynb:` Jupyter Notebook с кодом проекта.  Включает в себя этапы загрузки данных, предобработки, обучения модели, оценки результатов и анализа.
- `Results.txt:`  Текстовый файл с результатами экспериментов, включая метрики качества (R2, MAE) и анализ производительности модели.  Также содержит обратную связь по работе с датасетом и предложения по улучшению модели.
- `winequality.names:`  Описание признаков в наборах данных (метаданные).

---

## Инструкция по запуску

1. Клонируйте репозиторий:
```bash
git clone (https://github.com/den1ksk/WineQuality)>
```

2. Перейдите в директорию репозитория:
```bash
cd <WineQuality>
```

3. Для воспроизведения обучения модели и анализа данных, запустите `wine`.
