﻿## Lab2

# Варіант 7

Неорієнтований граф без петель та кратних ребер заданий матрицею суміжності. Потрібно визначити, чи цей граф є деревом.

## Вхідні дані

У вхідному файлі INPUT.TXT записано спочатку число N - кількість вершин графа (від 1 до 100). Далі записана матриця суміжності розміром N N, в якій 1 позначає наявність ребра, 0 - його відсутність. Матриця симетрична щодо головної діагоналі.

## Вихідні дані

У вихідний файл OUTPUT.TXT виведіть повідомлення YES, якщо граф є деревом, і NO інакше.

## Приклади

| №  | INPUT.TXT        | OUTPUT.TXT  |
|----|------------------|-------------|
| 1  |3 <br>0 1 0<br>1 0 1<br>0 1 0| YES  |


### Запуск програми
```bash
dotnet run --project App
```
### Запуск тестів
Без проміжних результатів
```bash
dotnet test
```
З проміжними результатами
```bash
dotnet test --logger "console;verbosity=detailed"
```

### Результати

Вхідні дані беруться з файлу `INPUT.TXT`, результати записуються в файл `OUTPUT.TXT`


