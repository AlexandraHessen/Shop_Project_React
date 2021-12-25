# Интернет магазин растений "Plants"

### `npm run builddev`
Запускает dev сборку
### `npm run buildprod`
Запускает prod сборку
### `npm run startLite`
Запускает lite-server
### `npm test`
Запускает тесты 

*** 
При добавлении товара в корзину вкладка автоматически переключается на вкладку корзины. Есть валидация формы которая при введении значения, автоматически отображает сообщение об ошибке, если форма не валидна кнопка “Оформить заказ” запрещена

*** 
Компонент Catalog является Pure Component, отображается более 50 динамичных однородных элементов, вносятся иммутабельные изменения при фильтрации товаров. При удалении товара из корзины используется анимация

*** 
Кнопки браузера "вперёд", "назад", "освежить" работают полностью корректно, в т.ч. появляется предупреждение о потере данных при оформлении заказа в корзине, также, реализован постраничный просмотр списка товаров

*** 
Приложения работает в Chrome, Firefox, Edge и на мобильном устройстве; адаптивная вёрстка

*** 
Использован AjaxStringStorage для загрузки каталога товаров, так же Ajax использован для хранения оформленных заказов

*** 
Использован Redux для хранения списка всех товаров, для товаров в корзине, для оформленных заказов

*** 
Использована Basis сборка, полная работоспособность prod-сборки проекта

*** 
Протестированы компоненты JSX код, некоторые функции, кнопки, dispatch, Action Creator, Reducers

