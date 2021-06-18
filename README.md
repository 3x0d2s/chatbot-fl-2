# chatbot-fl-2

Готовый заказ с фриланса. 

Заказчику было необходимо разработать систему покупки товара в боте. 

Функционал: 
- Добавление товара (После добавления товара уведомление о нём отсылается в публичный канал для товаров.)
- Удаление товара
- Добавление товара в корзину
- Составление заказа с указанием персональных данных, таких как адресс, номер телефона, имя и желаемое время доставки. 

После составления заказа уведомление о нём отсылается в чат администраторов для дальнейшей обработки. 

Для запуска скопируйте файл `bot/config/initial_config.py` в файл `bot/config/config.py`
 ```sh
 $ cp bot/config/initial_config.py bot/config/config.py
 ```
 
 А затем заполните его своими данными.
