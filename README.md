# ![COVID-19 Prediction](https://via.placeholder.com/15/889eff/000000?text=+) `COVID-19 Prediction`

COVID-19 Prediction представляет собой реализацию проекта 
«Прогнозирование заболеваемости COVID-19» в рамках зимней школы
[CompTech School 2022](https://comptechschool.com/).

## Папки и файлы репозитория:
- 🗂️[`.github`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/.github/workflows) - папка содержит конфиг настройки для Github Actions.
- 🗂️[`docs`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/docs) - папка содержит проектную документацию.
- 🗂️[`etl`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/etl) - папка содержит скрипты для работы с данными.
- [`.gitignore`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/.gitignore) - каких файлов не должно быть в удалённом репозитории.
- [`dodo.py`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/dodo.py) - скрипт, отвечающий за последовательность выполнения скриптов для обновления данных.
- [`requirements.in`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/requirements.in) - список библиотек для компиляции зависимостей requirements.txt с помощью библиотеки pip-tools.
- [`requirements.txt`](https://github.com/comptech-winter-school/covid19-prediction/tree/main/requirements.txt) - список зависимостей, необходимых для работы скриптов.
## Назначение
![](https://i.ibb.co/0Kkd7Mn/Global-Spread-COVID-19-2.gif)
```
Пандемия продолжает влиять на страны по всему миру - COVID‐19 
затронул 195 стран с примерно 366 млн подтвержденными случаями
заболевания (к январю 2022). Понимание динамики передачи 
инфекции в каждой стране и прогнозы имеют решающее значение для 
дальнейших действий по борьбе с пандемией. Целью проекта
является разработка и визуализация модели, которая предсказывает
заболеваемость COVID-19.
```
## Принцип работы
```
Исходя из имеющихся данных о заболеваемости в разных странах, 
модель ищет схожие страны и делает предсказания заболеваемости
на 30, 60 дней.
```
## Целевая аудитория (пользователи продукта)
```
Проект может представлять интерес для государства, ВОЗ, страховых 
компаний, частных клиник, так как появится возможность:
- предсказывать спрос на медицинские услуги и нагрузку на
госпитали,
- принять меры заблаговременно, 
- сократить расходы.
```
## Установка и настройка

[Ссылка на дэшборд в Yandex DataLens](https://datalens.yandex.ru/xxq1yyazn27mp-covid-19-comptech-2022)

Детальная установка и настройка описана в [официальной документации сервиса Yandex DataLens](https://cloud.yandex.ru/docs/datalens/).

Для настройки требуется наличие учетной записи Яндекс / SSO.

### Зависимости

Указаны в [`requirements.txt`](https://github.com/comptech-winter-school/covid19-prediction/blob/main/requirements.txt).

## Использование

1. Перейти на [страницу дэшборда в Yandex DataLens](https://datalens.yandex.ru/xxq1yyazn27mp-covid-19-comptech-2022).
2. В первом фильтре выбрать интересующую страну (например, `Russia`).
3. Во втором фильтре выбрать интересующий период времени (например, `29.01.2022 - 04.02.2022`)
4. Смотреть графики динамики заражений и госпитализаций, смертности и схожести стран. 
5. Наводить курсор на элементы для отображения дополнительной информации. 

## Команда
```
- Антон Агейков - Data Scientist, капитан команды
- Ассем Ибраева - Data Scientist
- Тимофей Акимкин - ML Engineer
- Яна Бучковски - технический писатель
- Татьяна Плевако - DevOps

Куратор: Артем Карасюк
```
