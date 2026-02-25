# DataFusion TASK1: Страж

Решение задачи антифрода (классификация неподтвержденных операций) для соревнования DataFusion.

## Результат

- `Public score`: **0,1151853940006162**
- Основной код: `main1.ipynb`
- Выходной файл: `submission.csv`

## Конфигурация запуска

- GPU: **NVIDIA GeForce RTX 4080**
- RAM: **64 GB**

## Структура проекта

- `main1.ipynb` - ноутбук с полным пайплайном обучения и инференса
- `submission.csv` - файл предсказаний для отправки
- `data/` - входные данные соревнования
- `cache/` - промежуточные кэшированные признаки

## Зависимости:

- `numpy`
- `pandas`
- `polars`
- `scikit-learn`
- `catboost`
- `pyarrow`
- `jupyter`
```bash
pip install numpy pandas polars scikit-learn catboost pyarrow jupyter
```

## Как запустить

1. Положить все файлы датасета в папку `data/`.
2. Открыть `main1.ipynb`.
3. Выполнить все ячейки последовательно (`Run All`).
4. После завершения будет создан `submission.csv`.

## Формат результата

`submission.csv` содержит 2 колонки:

- `event_id`
- `predict`

и готов к загрузке в систему соревнования.

Контакт: [@fle3n](https://t.me/Fle3n)
