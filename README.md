# AWS Midterm Project - Full Data Pipeline

## 📚 Описание

Этот проект построен на AWS и охватывает полный жизненный цикл данных:
- Сбор и хранение данных в Amazon S3
- ETL пайплайн через AWS Glue (Crawler и Jobs)
- SQL-запросы через Amazon Athena
- Классификация изображений через SageMaker (PyTorch модель FasterRCNN)

---

## 🏗️ Структура проекта

- `classification.ipynb` — код для SageMaker Notebook.
- `metadata/` — папка с метаданными изображений (CSV).
- `source/` — папка с оригинальными изображениями (`jpg`).
- `target/` — папка с результатами обработки в формате `Parquet`.
- `README.md` — это описание проекта.

---

## 🛠️ Используемые AWS сервисы

- **Amazon S3** — Хранилище данных.
- **AWS Glue** — Автоматическое построение ETL пайплайна.
- **Amazon Athena** — Аналитика SQL-запросами по данным в S3.
- **Amazon SageMaker** — Классификация изображений (Cat, Dog, Other).

---

## 🚀 Как запустить

1. Загрузить исходные изображения в S3.
2. Создать таблицу через Glue Crawler.
3. Выполнить Glue Job для трансформации данных.
4. Выполнить SQL-запросы в Athena.
5. Классифицировать изображения через SageMaker Notebook.

---

## ✍️ Автор : Marzhan Dauren

**Marzhan013**

Проект выполнен в рамках курса по AWS Data Engineering.

---
