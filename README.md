# kolesa-upgrade-homework-10


**Ссылка к боту:**
@nurzhas_bot

### Задача
Создать телеграм-бота планеровщика, который умеет сохранять пользователя и его задачи в БД и отдавать при запросе

**Требования к телеграм-боту:**
1) Запись данных пользователя при вызове команды /start
2) Запись задачи при вызове команды /addTask
3) Выдача всех задач пользователя при вызове команды /tasks
4) Удаление задачи по id при вызове команды /deleteTask {id}

**Параметры модели Пользователь**
- name
- telegram_id
- first_name
- last_name
- chat_id
- 
**Параметры модели Задача**
1) title
2) description
3) end_date

### Дополнительные требования
1) Задачи должны быть связаны с пользователем в БД с помощью ключа foreignKey. 
2) Получение задач должно быть реализовано с помощью has Many в пакете gorm

По желанию можно подключить БД Sqlite или Mysql

## Полезные ссылки
- [Документация API Telegram](https://core.telegram.org/bots/api)
- [BotFather](https://t.me/BotFather)
- [Документация gorm](https://gorm.io/docs/query.html)
