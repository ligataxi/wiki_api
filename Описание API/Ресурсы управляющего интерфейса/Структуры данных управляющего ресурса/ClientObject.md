#### Описание структуры

|     |     |     |
| --- | --- | --- |
| **Название параметра** | **Тип данных** | **Описание** |
| id  | int | ID типа оплаты |
| company_id | int | ID компании |
| discount_number | str | Номер дисконта |
| email | str | Email |
| phone_number | str | Номер телефона клиента |
| blacklist | bool | В черном списке |
| success_orders | int | Кол-во успешных заказов |
| reject_orders | int | Кол-во отмененных заказов |
| personal_discount_sum | float | Персональная скидка (фикс) |
| personal_discount_percent | float | Персональная скидка (процент) |
| bonus_balance | float | Бонусный баланс клиента |
| comment | str | Комментарий |
| phones | list[ClientPhoneObject] | Список номеров телефона клиента |