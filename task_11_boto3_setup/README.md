# Задание 11: Установка boto3

## Цель
Научиться использовать библиотеку AWS SDK — boto3.

## Что нужно сделать

1. Установи библиотеку:

```bash
pip install boto3
```

2. Создай .aws/credentials файл или настрой boto3.Session() вручную.

## Подсказка

Проверку можно начать с:

```python
import boto3
s3 = boto3.client('s3')
print(s3.list_buckets())
```
