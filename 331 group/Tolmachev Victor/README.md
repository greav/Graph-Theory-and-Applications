# Road Graph

Работа по дисциплине "Теория конечных графов и ее приложения"

Выбранный город: Краснодар

## Инструкция

Задание выполнено на языке python 3.6

OSM XML данные по городу можно скачать [здесь](https://drive.google.com/drive/folders/1UxZBQfH1b-pAJvEWIXEC8SY1lWU9PN6_?usp=sharing)

### Зависимости 

* lxml
* svgwrite
* csv

### Использование

Для использования необходимо иметь версию python не ниже 3.6, а также с помощью менеджера пакетов pip установить модули lxml и svgwrite (pip install lxml svgwrite)

После этого программу можно запустить из командой строки: python main.py city-name.osm

Программа создаст папку ```result``` c файлами ```map.svg```, ```adjacency_list.csv```, ```adjacency_matrix.csv``` 

Так как размер матрицы получился довольно большим (380 MB), то ее можно скачать [здесь](https://drive.google.com/drive/folders/1UxZBQfH1b-pAJvEWIXEC8SY1lWU9PN6_?usp=sharing)

### Описание реализации
* TODO
