#### Описание структуры

|     |     |     |
| --- | --- | --- |
| **Название параметра** | **Тип данных** | **Описание** |
| order_id | int | ID заказа |
| company_id | int | ID компании |
| type_id | int | ID типа заказа |
| order_source | int | Источник заказа |
| operator_session_id | int | ID смены оператора |
| price | float | Стоимость заказа |
| done_price | float | Стоимость выполненого заказа |
| contragent_id | int | ID контрагента |
| client_id | int | ID клиента |
| phone | str | Номер телефона клиента |
| car_type_id | int | ID типа авто |
| tariff_id | int | ID тарифа |
| transfer_id | int | ID трансфера |
| car_extras | list[int] | ID опций авто |
| driver_extras | list[int] | ID опций водителя |
| pickup_time | datetime | Время подачи |
| create_time | datetime | Время создания |
| accept_time | datetime | Время установки статуса “Принят“ |
| car_delivery_time | datetime | Ориентировочное время подачи авто |
| done_time | datetime | Время установки статуса “Выполнен“ |
| cancel_time | datetime | Время установки статуса “Отменен“ |
| wait_client_time | datetime | Время установки статуса “На месте“ |
| with_client_time | datetime | Время установки статуса “По маршруту“ |
| driving_time | int | Длительность маршрута |
| discount_price | float | Сумма скидки |
| discount_percent | float | Процент скидки |
| discount_driver_compensation | float | Процент компенсации водителю |
| loyalty_rule_id | int | ID правила лояльности |
| promo_code_id | int | ID промо кода |
| auto_dispatch | bool | Актимность автораспределения |
| comment | str | Комментарий |
| notes | str | Заметка |
| pickup_address | AddressObject | Адрес подачи |
| destinations | list[AddressObject] | Адреса назначения |
| distance | int | Расстояние маршрута |
| driver_id | int | ID водителя |
| state | int | Статус заказа |
| dispatch_method | int | Метод распределения |
| dispatch_state | int | Статус распределения |
| allowed_payment_types | list[int] | Доступные типы оплаты |
| markup_rule_id | int | ID правила наценки |
| markup_price | float | Сумма наценки |
| markup_percent | float | Процент наценки |