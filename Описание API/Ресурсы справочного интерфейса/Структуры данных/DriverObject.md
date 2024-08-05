#### Пример структуры

```java
{
    "active": true,
    "balance": 486.85,
    "birthday": null,
    "call_sign": 2,
    "car": "Бежевый Опель Вектра | 111 | Легковой",
    "car_id": 1,
    "comment": "",
    "company_id": 1,
    "driver_licence": "",
    "fire_date": null,
    "full_name": "Иванов Иван",
    "fullname": "Иванов Иван",
    "group_id": 1,
    "home_address": "",
    "id": 1,
    "online": true,
    "order_id": null,
    "password": "333",
    "phone": "79110009988",
    "photo": null,
    "rate_id": 2,
    "resource_uri": "/api/v1/drivers/1/",
    "session": true,
    "session_start": "2020-08-18T11:13:50.873931+03:00",
    "state": 1,
    "taxi_licence": ""
  }
```

#### Описание структуры

|     |     |     |
| --- | --- | --- |
| **Название поля** | **Тип данных** | **Описание** |
| active | bool | Активность профиля водителя |
| balance | float | Баланс водителя |
| birthday | datetime | Кол-во пропущенных записей |
| call_sign | int | Позывной водителя |
| car | str | Информация об автомобиле |
| car_id | int | ID автомобиля |
| comment | str | Комментарий |
| company_id | int | ID компании |
| driver_licence | str | Серия и номер водительского удостоверения водителя |
| fire_date | datetime | Дата увольнения водителя |
| full_name | str | Полное имя |
| group_id | int | ID группы |
| home_address | str | Домашний адрес |
| id  | int | ID записи |
| password | str | Пароль для авторизации |
| phone | str | Контактный телефон |
| photo | str | Ссылка на фотографию |
| rate_id | int | ID условия работы |
| resource_uri | str | Ссылка на детальный просмотр записи |
| session | bool | Статус открытия смены |
| session_start | datetime | Время открытия смены |
| state | int | Текущее состояние водителя |
| taxi_licence | str | Серия и номер лицензии такси |