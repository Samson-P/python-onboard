# Задание 13: Загрузка чанков в S3

## Цель
Загружать сжатые чанки данных в облако.

## Что нужно сделать
1. Для каждого сжатого чанка:
   - Назначь имя (например, `chunk_0001.gz`)
   - Загрузи его в бакет

## Подсказка
Можно использовать `put_object(Body=..., Bucket=..., Key=...)`.

