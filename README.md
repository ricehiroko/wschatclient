# wschatclient
Клиент для чата https://sinair.ru/chat в терминале.
## Использование
Загрузка и установка зависимостей:
```
git clone https://github.com/hypersad/wschatclient
cd wschatclient
npm install
```
Для запуска клиента используйте `node chat.js` или `npm start`.

Для автоматической авторизации добавьте логин и пароль от своего аккаунта в соответствующие поля в файле конфигурации `config.js`.
### Горячие клавиши
* `Ctrl + C` - закрыть клиент или диалог
* `Ctrl + E` - открыть диалог подключения к комнате
* `Ctrl + R` - открыть диалог удаления активной комнаты
* `Ctrl + N` - открыть диалог создания комнаты
* `Ctrl + Q` - отключиться от активной комнаты

* `Ctrl + Up` - пролистать историю чата на одну строку вверх
* `Ctrl + Down` - пролистать историю чата на одну строку вниз
* `Ctrl + Left` - выбрать предыдущую комнату
* `Ctrl + Right` - выбрать следующую комнату

* `Escape` - очистить поле ввода
* `Up` - выбрать предыдущее сообщение из истории своих сообщений
* `Down` - выбрать следующее сообщение из истории своих сообщений
