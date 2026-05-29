| Поле | Значение |
| --- | --- |
| Проект | https://www.saucedemo.com/ |
| Component (Компонент) | Каталог/сортировка |
| Автор | Булат Камалов |
| Назначен | NaN |
| Статус | Открыт |
| Severity | Minor |
| Priority | Medium |
| Environment (Окружение) | Linux Mint 22.2 (Zara), Mozilla Firefox for Linux Mint 149.0 (64-bit) |
| Preconditions (Предусловия) | 1. Открыт сайт https://www.saucedemo.com/.<br>2. Пользователь авторизован как `problem\_user`.<br>3. Открыта страница списка товаров (/inventory.html).<br>4. По умолчанию установлена сортировка «Name (A to Z)». |
| Steps to reproduce (Шаги воспроизведения) | 1. Кликнуть на выпадающий список сортировки (product\_sort\_container) в правом верхнем углу страницы.<br>2. Выбрать опцию «Price (low to high)». |
| Actual Result (Фактический результат): | 1. Товары в каталоге не отсортированы по возрастанию цены<br>2. Селектор не изменил своего значения |
| Expected Result (Ожидаемый результат): | 1. Товары в каталоге отсортированы по возрастанию цены<br>2. Селектор изменил своё значение на «Price (low to high)» |
| Вложение | videocaption.mp4 |
