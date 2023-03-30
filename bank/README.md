# Исследование надежности заемщиков

## Задачи 
Определить существует ли зависимость между:
- количеством детей и возвратом кредита в срок
- семейным положением и возвратом кредита в срок
- уровнем дохода и возвратом кредита в срок
- целью кредита и возвратом его в срок


`Заказчик` — кредитный отдел банка. Необходимо разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. 

## Описание данных
`Входные данные` от банка — статистика о платёжеспособности клиентов (*учебный датасет*). Содержат следующую информацию:
- `children` — количество детей в семье
- `days_employed` — общий трудовой стаж в днях
- `dob_years` — возраст клиента в годах
- `education` — уровень образования клиента
- `education_id` — идентификатор уровня образования
- `family_status` — семейное положение
- `family_status_id` — идентификатор семейного положения
- `gender` — пол клиента
- `income_type` — тип занятости
- `debt` — имел ли задолженность по возврату кредитов
- `total_income` — ежемесячный доход
- `purpose` — цель получения кредита

## Используемые библиотеки
- `pandas` 
- `seaborn` 
- `pylab`