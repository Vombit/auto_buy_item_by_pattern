Бот предназначен для автоматической скупки предметов стим по заданному флоату, после чего уведомляет в телеграмм боте (RAW)

# Запуск
### Windows:
 - заполнить данные в файле ".env" на свои
 - установлен python >= 3.10 
 - запустить "win_create.bat" чтобы установить зависимости 
 - запустить "win_start.bat" чтобы запустить программу 

### Doker-compose (debian):
 - заполнить данные в docker-compose.yml в пункте "environment" на свои
 - в консоли в директории папки прописать "docker-compose up"



# Информация по окружению

* steamid =  `ид аккаунта стим`
* shared_secret = `данные из mafile`
* identity_secret = `данные из mafile`
<br><br>

* STEAM_API_KEY = `сгенерированный API key` (https://steamcommunity.com/dev/apikey)
* STEAM_LOGIN = `логин аккаунта`
* STEAM_PASSOWORD = `пароль аккаунта`
<br><br>

* TELEGRAM_TOKEN = `токен бота телеграм`
* TELEGRAM_CHAT_ID = `ид пользователя, которому будут приходить уведомления`
<br><br>

* PROXY = `прокси:порт (можно оставить пустым)`
* USERNAME_PROXY = `логин прокси если требуется (можно оставить пустым)`
* PASSWORD_PROXY = `пароль прокси если требуется (можно оставить пустым)`
<br><br>

* LOTS_PER_PAGE = `колличество лотов на странице`
