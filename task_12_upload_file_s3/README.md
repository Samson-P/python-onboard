# Задание 12: Загрузка файла в S3

## Цель
Освоить базовую загрузку файлов в AWS S3.

## Что нужно сделать
1. Создай S3-бакет (вручную или через `create_bucket()`).
2. Загрузи файл `hello.txt` с помощью `upload_file()` или `put_object()`.

## Подсказка

```python
s3.upload_file("hello.txt", "my-bucket", "hello.txt")
```
