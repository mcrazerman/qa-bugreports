| Поле | Значение |
| --- | --- |
| Проект | https://www.saucedemo.com/ |
| Component (Компонент) | Каталог/корзина |
| Автор | Булат Камалов |
| Назначен | NaN |
| Статус | Открыт |
| Severity | Major |
| Priority | High |
| Environment (Окружение) | Linux Mint 22.2 (Zara), Mozilla Firefox for Linux Mint 149.0 (64-bit) |
| Preconditions (Предусловия) | 1. Открыт сайт https://www.saucedemo.com/.<br>2. Пользователь авторизован как `problem\_user`.<br>3. Корзина пуста<br>4. Открыта страница списка товаров (/inventory.html). |
| Steps to reproduce (Шаги воспроизведения) | 1. Нажать кнопку `Add to cart` на карточке товара Sauce Labs Backpack.<br>2. Нажать кнопку `Remove` на карточке добавленного товара |
| Actual Result (Фактический результат): | 1. Товар не удаляется из корзины<br>2. Значение счетчике на иконке корзины равно «1»<br>3. Кнопка `Remove` не меняется |
| Expected Result (Ожидаемый результат): | 1. Корзина пуста<br>2. Красного бейдж на иконке корзины исчезает<br>3. Кнопка `Remove` меняется на `Add to cart` |
| Вложение | videocaption.mp4 |
