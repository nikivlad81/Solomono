# Solomono

тестове завдання 1: 
Категорії і товари (приклад: https://demo.solomono.net/ultrabuki/c-378.html)
1. створити в базі даних таблицю товарів і таблицю категорій, і зв'язати їх між собою.
2. занести в БД 10-20 товарів (в кожному має бути дата, ціна, назва товару) і 3-5 категорій
3. вивести сторінку, на якій зліва буде список категорій (біля кожної назви категорій має бути число товарів в даній категорії), а справа список товарів.
4. коли натискаємо на категорію, справа аяксом мають виводитись товари тільки вибраної категорії.
5. вивести селектбокс в якому будуть три види сортування: спочатку дешевші, по алфавіту, спочатку нові
6. при виборі порядку сортування в селектбоксі, має змінюватись порядок виведених товарів.
7. у кожного товара має бути кнопка "купить" при нажиманні на яку відкривається модалка бустрапа, в якій буде виведений вибраний товар.

обов'язково: використовувати ООП
обов'язково: чистий php, без фреймворків.
обов'язково: зробити зміну сортування без перезавантаження сторінки.
обов'язково: передавати дані з php до js в вигляді json

додатково: при зміні категорій і сортування в адресному рядку щоб додавались відповідні get-параметри, і при перезавантаженні сторінки ми маємо залишитись на тій же вибраній категорії яка була до перезавантаження сторінки.

тестове завдання 2:
Зробити php скрипт, який з бази візьме всі категорії https://tests.solomono.net/test_task2/test.sql і побудує дерево наступного виду https://take.ms/8GLxE - масив де ключ це id категорії. Якщо є підкатегорії у категорії, то значення - масив з підкатегоріями, якщо немає, то просто дублюється ключ.
Час виконання скрипта не більше 2 сек, запит в базу не повинен бути закешованим.

