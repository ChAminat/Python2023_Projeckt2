# __Second Project__
Проект представляет упрощенную модель банковской системы, в кторой, на данный момент, существует один монополист - sber.
Пользователь может:
1) зарегистрироваться в нужном банке (пока только sber, но скоро на рынок выйдут Арабы.PAY)
2) заводить или удалять счета трех типов: кредиты, депозиты, дебетовые
3) совершать внутри банка операции: снятие средств со счета, поплнение счета, перевод на другой счет
4) изменять личную инфорормацию (паспорт, адрес)

### Запуск
1. клонировать репозиторий:
```
git clone git@github.com:ChAminat/Python2023_Projeckt1.git
```
2. установить нужные библиотеки командой:
  ```
  pip install -r /path/to/requirements.txt
  ```
3. запустить проект командой:
 ```
 python3 main.py
 ```
4. перейти в telegrem и открыть бота BankBot2023
5. следовать указаниям бота, справочная информация доступна по команде /help

Примечание: изначально проект был консольным (закомментированная функция run), поэтому из web его можно легко вернуть в 
первоначальное состояние. Сохранившийся список команд из консольки: 
## Console interface
### ___commands for console working:___
- to exit from your working space - ___exit___
- to show all your accounts - ___show_account___
- to create new account - ___create_account___
- to check balance of a concrete account - ___check_balance___
- to make transfer - ___transfer___
- to make top up - ___top_up___
- to make withdraw - ___withdraw___
- to close account - ___close_account___
- update your address and passport info - ___update_my_info___
- show your user info - ___show_my_info___

## Web interface
### ___commands for bot working:___
- /start - начало работы
- /log_in - войти в существующий аккаунт
- /register - зарегистрироваться
a) Если вы выбрали /log_in, то после сообщения бота "What bank would you like to be logged in?" вам следует отправить сообщение следующего вида:
 ```
bank: название
 ```
В данный момент работает только sber, поэтому команда bank: sber. Затем вызовите команду /username и отправьте 2 сообщения боту следующего вида:
 ```
login: yourLogin 
password: yourPassword
 ```
Примечание: в базе данных есть несколько пользователей. Для теста можно зайти по следующему логину и паролю:
 ```
login: aminat2004
password: 12345
 ```
б) Если вы выбрали /register, то аналагично форме из пункта а) запоняете о себе информацию последовательно выполняя команды бота (при необходимости /help)

После входа или регистрации пользователю становится доступен набор кнопок для работы с аккаунтом.
