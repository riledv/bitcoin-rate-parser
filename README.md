# bitcoins-price-parser
Парсер курса биткоина в обменнике и на бирже

Попробовать бота в телеграмме: **@coinRateParserBot**

# Парсер курса биткоина на node.js
Предназначен для быстрого реагирования на падение курса биткоина.
<br />
Получает информацию о курсе акций коина и курсе покупки коина на обменнике.

### Использование
Для запуска должен быть установлен node.js и npm.
<br />
Перед запуском парсера, находясь в папке с ним, выполнить в командной строке команду: <code>npm i</code>
<br />
После этого создайте файл в корне проекта с именем .env, скопируйте cодержимое файла .env_example
<br />
и замените значения переменных на ваши
<br />
##### Файл .env должен содержать:
botToken = <токен вашего бота>
<br />
proxySocks5Host = <хост вашего бота>
<br />
proxyPort = <порт на хосте>
<br />
proxyUsername = <имя пользователя>
<br />
proxyPassword = <пароль>
<br />
<br />
Затем в консоли введите команду: <code>npm run start</code>
<br />
Для разработки используется команда npm run dev, которая запускает авторелоад при изменениях в файлах
