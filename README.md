# Урок 7. Вложенные структуры - домашнее задание

# Краткий алгоритм.
1) Запросить у пользваотеля номер студента, если он существует, вывести о нем информацию:
```
Программа: Введите номер студента
Пользователь: 1
Программа: Студент Jane Snake
Программа: Знает Python, Go, Linux
```

2) Запросить у пользователя профессию, если она существует, то вывести анализ по студенту:
```
Программа: Выберите специальность для оценки студента Jane Snake
Пользователь: Backend
Программа: Пригодность 40%
Программа: Jane Snake знает Python, Linux
Программа: Jane Snake не знает Flask, SQL, Docker
```

3) Если данные от пользователя не существуют, то завершить программу
```
Программа: У нас нет такого студента
Программа: У нас нет такой специальности
```

# Данные

Необходимые данные берутся из json - файлов
* Список студентов: [students.json](https://github.com/Mirudan/academic_work_2/blob/main/students.json)
* Список профессий: [professions.json](https://github.com/Mirudan/academic_work_2/blob/main/professions.json)
