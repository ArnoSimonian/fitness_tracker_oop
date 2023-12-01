# Модуль фитнес-трекера

## Описание
Фитнес-трекер рассчитывает и отображает результаты тренировки. Обрабатывает данные для трёх видов тренировок: бега, спортивной ходьбы и плавания.

Выполняет следующие функции:
- принимает от блока датчиков информацию о прошедшей тренировке;
- определяет вид тренировки;
- рассчитывает результаты тренировки;
- выводит информационное сообщение о результатах тренировки.

Информационное сообщение включает такие данные:
- тип тренировки;
- длительность тренировки;
- дистанция, которую преодолел пользователь, в километрах;
- среднюю скорость на дистанции, в км/ч;
- расход энергии, в килокалориях.


## Технологии

- Python 3.7


## Запуск проекта в dev-режиме

1. Клонируейте проект:

```bash
  git clone https://github.com/ArnoSimonian/fitness_tracker_oop
```

2. Перейдите в директорию проекта:

```bash
  cd fitness_tracker_oop
```

3. Cоздайте и активируйте виртуальное окружение:

```bash
  python3 -m venv venv
  # Для Linux/macOS:
  source venv/bin/activate
  # Для Windows:
  source venv/Scripts/activate
```

4. Установите зависимости из файла requirements.txt:

```bash
  python3 -m pip install --upgrade pip
  pip install -r requirements.txt
```

5. Выполните миграции и запустите проект:

```bash
  python3 manage.py migrate
  python3 manage.py runserver
```


## Authors

Арно Симонян [@ArnoSimonian](https://www.github.com/ArnoSimonian)
