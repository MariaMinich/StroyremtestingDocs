Regjur05

Регистрация нового пользователя (юр лицо) с вводом невалидных данных в поле "Номер телефона"

* Тестовые данные:
  
  Предусловия:
  
  1. Создан тестовый электронный ящик(и)
  
  2. Открыта форма регистрации и выбрана вкладка "Юридическое лицо"
     
     (ссылка на прод [Регистрация](https://stroyrem-nn.ru/user/register) и на тест [Регистрация](https://test2.stroyrem-nn.ru/user/register))
  
  3. Все поля заполнены валидными данными, кроме поля "Номер телефона"

* Шаги:
1. Оставить поле "Номер телефона" пустым и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Поле "Номер телефона" в рамке красного цвета и надпись "Необходимо заполнить данное поле" 

2. Ввести в поле "Номер телефона" 000 (нули) вместо всех цифр
   
   **ОР:** Поле "Номер телефона" подсвещается красным цветом и появляется надпись "Введите коректные данные"
* Постусловие: удалить тестовые данные/выйти из профиля, если регистрация проходит успешно

Автор: Татьяна

* Тестовый сервер Chrome version 113.0.5672.93 (Official Build) (64-bit)
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:23 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:30 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |
  
  - Продовый сервер Chrome version 113.0.5672.93 (Official Build) (64-bit)
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:25 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:32 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |
  
  - Тестовый сервер Firefox version 113.0.1 (64-bit)
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:30 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:35 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |
  
  - Продовый сервер Firefox version 113.0.1 (64-bit)
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:32 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:37 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |
  
  - Тестовый сервер Мобильное Huawei Mate 10 PRO EMUI 12.0.0.225
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:35 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:40 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |
  
  - Продовый сервер Мобильное Huawei Mate 10 PRO EMUI 12.0.0.225
  
  Тест выполнен
  
  | №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
  | --- | ---------- | ----- | --------- | ------- | ----------------------------- |
  | 1   | 2023-07-13 | 14:37 | PASS      | Татьяна |                               |
  | 2   | 2023-07-13 | 14:42 | FAIL      | Татьяна | https://trello.com/c/UdKpzh1y |