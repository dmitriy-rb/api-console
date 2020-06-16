"API-консолька" консоль для отправки запросов к Sendsay API. Проект на React с Redux.</br>
https://sendsay.ru/api/api.html - описание апи;

Реализовано:

форма авторизации, с валидацией логина и пароля;</br>
сохранение авторизации в течение суток;</br>
сохранение истории запросов;</br>
форматирование JSON запроса;</br>
валидация и отображение ошибки запроса;</br>
изменение и сохраниение ширины полей ввода;</br>

Запуск проекта:

Установить зависимости: npm i</br>
Запусить проект: npm start или</br>
Собрать build командой npm run build</br>
Запустить командой serve -s build</br>

Структура проекта:

src/index.js - стартовый файл проекта;</br>
src/store - файлы формирующие хранилище redux;</br>
src/container - модули подключенные к хранилищу redux, а также компоненты уникальные для данного модуля;</br>
src/components - переиспользуемые компоненты;</br>
src/api - модуль реализующий подулючение к api сервера;</br>
src/assets - дополнительные файлы проекта;</br>

В проекте подключены дополнительные библиотеки:

"redux" - организация работы с общим хранилищем данных, однонаправленное изменение состояния хранилища;</br>
"redux-thunk" - позволяет использовать функции при отправке событий redux;</br>
"react-router-dom" - маршрутизация;</br>
"lodash" - методы для работы с массивами, объектами;</br>
"react-onclickoutside" HOC - для обработки клика вне компонента</br>