#### Описание структуры

|     |     |     |     |
| --- | --- | --- | --- |
| **Название параметра** | **Тип данных** | **Значение по умолчанию** | **Описание** |
| id  | int | null | ID заказа |
| company_id | int | null | ID компании |
| company_id__in_list | list[int] | null | Список ID компании |
| type_id__in_list | list[int] | null | Список ID типов заказов |
| client__pk | int | null | ID клиента |
| state | int | null | Статус заказа |
| state__in_list | list[int] | null | Список статусов заказов |
| dispatch_state | int | null | Статус распределения |
| dispatch_state__in_list | list[int] | null | Список статусов распределения |
| phone_number__endswith | str | null | Номер телефона |
| pickup_time__between | list[datetime, datetime] | null | Диапазон времени подачи |
| pickup_time__lte | datetime | null | Время подачи больше или равно |
| pickup_time__gte | datetime | null | Время подачи меньше или равно |
| parking_id | int | null | ID парковки |
| auto_dispatch | int | null | Автораспределение |
| car_type_id | int | null | ID типа авто |
| pickup_address | str | null | Адрес подачи |
| callsign | int | null | Позывной водителя |
| destination_address | str | null | Адрес назачения |
| pickup_address_locality_id | int | null | ID населенного пункта адреса подачи |
| destination_locality_id | int | null | ID населенного пункта адреса назначения |
| operator_id | int | null | ID оператора |
| operator_session_id | int | null | ID сессии оператора |
| contragent__id | int | null | ID контрагента |