# Road Graph (task3)

Третье задание по дисциплине "Теория конечных графов и ее приложения"

Выбранный город: Краснодар

## Инструкция

Задание выполнено на языке python 3.6

OSM XML данные по городу можно скачать [здесь](https://drive.google.com/drive/folders/1UxZBQfH1b-pAJvEWIXEC8SY1lWU9PN6_?usp=sharing)

### Зависимости 

* lxml
* svgwrite
* csv
* haversine

### Использование

Для использования необходимо иметь версию python не ниже 3.6, а также с помощью менеджера пакетов pip установить модули lxml, svgwrite, haversine (pip install lxml svgwrite haversine)

После этого программу можно запустить из командой строки: python main.py city-name.osm

Программа создаст папку ```result``` c файлами ```dmst_routes.csv```, ```nna_routes.csv```, ```tsp_dmts_map.svg```, ```tsp_nna_map.svg``` 
 
* В качестве примера берется точка (45.1203, 39.0363) 
