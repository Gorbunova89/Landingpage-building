# Landing page site youtube with Bootstrap 5
Ссылка на урок на ютубе [Landing page design bootstrap 5](https://www.youtube.com/watch?v=DFUT5s5SasA)
Результат созданной страницы можно посмотреть [здесь](https://gorbunova89.github.io/Landingpage-building/)
>Верстка страницы выполнена с помощью фреймворка bootstrap 5.
### Структура страницы
* Навигационная панель **navbar**
* Секция 1 карусель **carousel**
* Секция 2 Карточка с описанием **about**
* Секция 3 Карточки сервисов **services**
* Секция 4 Карточки проэктов **portfolio**
* Секция 5 Карточки с командой **our team**
* Секция 6 Форма для обратной связи **contact**
Футер **footer**
### Для создания данной страницы были использованы следующие линки:
* [stylesheet bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/) подключаем в **head**
* [Google fonts](https://fonts.google.com/specimen/Montserrat) подключаем в **head**
* [Icons](<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.2/font/bootstrap-icons.css">) подключаем в **head**
* [Script](https://getbootstrap.com/docs/5.2/getting-started/introduction/) подключаем в **body**
### Детали
1. Выделение части слова желтым цветом в название бренда **navbar-brand** было сделано с помощью команды **span**  и класса **text-warning** в html
<img src="readme/Снимок1.JPG" width="150">
2. Затемнение фона в карусели было сделано с помощью команды **carousel-inner::before** background: rgba(0, 0, 0, 0.7); в css
<img src="readme/Снимок2.JPG" width="500"> 
3. Иконочный шрифт вставляем из самого bootstrap, переходим во кладку **Icons**, спускаемся в с самый низ, копируем **link** в графе **CDN**, вставляем в **head**, используем код с тэгом **i**
<img src="readme/Снимок3.JPG" width="200"> <img src="readme/Снимок4.JPG" width="150">
