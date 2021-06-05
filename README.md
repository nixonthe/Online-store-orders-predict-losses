# Online-store-orders-predict-losses

Легенда:
Анонимизированные и преобразованные данные по заказам интернет-магазина (df_train.csv и df_test.csv).
Задача состоит в предсказании расходов за отказ от покупки конкретного товара (колонка item_losses).
Требуется продемонстрировать умение выбирать метрики качества, валидировать модели, создавать признаки и обучать модели.
Для файла df_test.csv также требуется предсказать целевую переменную (предсказание сохранить в csv файле с сохранением порядка строк как в df_test.csv).

Описание данных:

order_id - id заказа

departure_country - id страны отправления заказа

departure_city - id города отправления заказа

departure_region - id региона города отправления заказа

arrival_country - id страны получения заказа

arrival_city - id города получения заказа

arrival_region - id региона города получения заказа

order_date - дата заказа

stock_departure_date - время отправки со склада

delivery_service_departure_date - время отправки службой доставки

client_arrival_date - время доставки заказа в пункт получения

item_type - тип товара (для кого предназначен)

client_keywords - запрос для перехода клиента

client_device_type - устройство клиента

client_browser - браузер клиента

item_package_type - способ упаковки

client_is_app - заказ из приложения

order_tracking_available - отслеживание заказа

brand_name - название бренда

item_id - id товара

item_category - категория товара

delivery_service_name - название службы доставки

type_prepayment - тип предоплаты

item_price - цена товара

item_losses - расходы за отказ от покупки (целевая переменная)
