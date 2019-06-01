# Практическая работа №7. Алгоритмы сортировки. Часть №2

### Задание №1. Быстрая сортировка

Считать количество элементов n.
Считать n целочисленных элементов.
Отсортировать полученный массив Быстрой сортировкой.
Вывести отсортированный массив на экран через пробел. (после
чего перейти на новую строку)

#### Пример входных и выходных данных

| input     | output      |
| ----------| ------------|
| 10 |  |
|13 4 1 0 45 11 -3 18 33 -8|-8 -3 0 1 4 11 13 18 33 45 |

### Задание №2. Пирамидальная сортировка

Считать количество элементов n.
Считать n целочисленных элементов.
Отсортировать полученный массив Пирамидальной сортировкой.
Вывести отсортированный массив на экран через пробел. (после
чего перейти на новую строку)


#### Пример входных и выходных данных

| input     | output      |
| ----------| ------------|
| 10 |  |
|13 4 1 0 45 11 -3 18 33 -8|-8 -3 0 1 4 11 13 18 33 45 | 

##  Ход работы

1. Были реализованы функции и выполнены задания.
2. Для перехода в папку проекта, создания файлов, компиляции и запуска программы были использованы следующие команды:
```sh
$ cd timp
$ touch 01_qsort.c 02_pyramid.c
$ gcc 01_qsort.c -o r1
$ gcc 02_pyramid.c -o r2
$ ./r1
$ ./r2
```
3. Далее файлы были загружены на удаленный репозиторий:
```sh
$ git checkout -b pr7
$ git add .
$ git commit -m "added 2 files of seventh practical work and README.md"
$ git push -u origin pr7
```

## Результаты

Результат работы - Быстрая сортировка (r1), Пирамидальная сортировка (r2):
![](https://cdn1.savepice.ru/uploads/2019/4/7/262ea40738953fc4addd858e4c7e1cc6-full.png "sort")

---
