#### Пример структуры

```java
{
  "bort_number": 0,
  "car_number": "AA7788AA",
  "color": "Синий",
  "color_id": 2,
  "comment": "",
  "id": 337,
  "manufacture_year": null,
  "model": "Шевроле Авео",
  "model_id": 14,
  "photo": null,
  "resource_uri": "/api/v1/cars/337/",
  "type": <CarTypeObject>
}
```

#### Описание структуры

|     |     |     |
| --- | --- | --- |
| **Название поля** | **Тип данных** | **Описание** |
| bort_number | int | Бортовой номер авто |
| car_number | str | ГОС номер авто |
| color | str | Цвет |
| color_id | int | ID цвета |
| comment | str | Комментарий |
| id  | int | ID записи |
| manufacture_year | int | Год выпуска автомобиля |
| model | str | Модель автомобиля |
| model_id | int | ID модели автомобиля |
| photo | str | Ссылка на фотографию автомобиля |
| resource_uri | str | Ссылка на детальный просмотр записи |
| type | CarTypeObject | Структура типа автомобиля |