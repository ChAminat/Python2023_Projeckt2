# __Second Project__
Проект представляет упрощенную модель банковской системы, в кторой, на данный момент, существует один монополист - sber.
Пользователь может:
1) зарегистрироваться в нужном банке (пока только sber, но скоро на рынок выйдут Арабы.PAY)
2) заводить или удалять счета трех типов: кредиты, депозиты, дебетовые
3) совершать внутри банка операции: снятие средств со счета, поплнение счета, перевод на другой счет
4) изменять личную инфорормацию (паспорт, адрес)

### Запуск проекта:
1) Устанавливаем библиотеки из файла requirements.txt
2) Для работы с проектом запускаем файл main.py, затем открываем бот BankBot2023 в telegram
3) Следуем указаниям бота, справочная информация доступна по команде /help

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
- описание всех команд в боте
Примечание: некоторые запросы к боту требуют определенного формата а именно название_поля: информация (разделены пробелом).
Все описано в инструкции.
