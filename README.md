# Фінальний командний проект "Drinkmaster"
Веб додаток, який дозволить вам вивчати різноманітні коктейлі та створювати власні майстер-п'єси в мистецтві коктейльного приготування. У нашому додатку ви можете
відкрити для себе найкращі рецепти, навчитися їх готувати та експериментувати зі смаками.

## Шаблон репозиторія
Цей проект був створений на основі [Create React App](https://github.com/facebook/create-react-app). Для ознайомлення з шаблоном [зверніться до документації](https://facebook.github.io/create-react-app/docs/getting-started).

## Опис проекту 
"Drinkmaster" - це випускний проект курсу "Full Stack Developer" IT-школи GoIT, який використовує всі набуті знання та технології. Він складається з фронтенд-частини: основного сайту, який представлений в даному [репозиторії](https://viktoriarosovska.github.io/drinkmaster-teamproject/), бекенд-частини ([переглянути репозиторій бекенду](https://github.com/Soundlover1984/drinkmaster-backend)), та бази даних MongoDB.

### Фронтенд
Додаток "Drinkmaster" реалізований за допомогою бібліотеки React.js, використовуючи HTML, CSS, Javascript та інструментальної збірки Vite. Він представляє собою багатосторінковий сайт з бібліотекою станів Redux Toolkit, маршрутизацією за допомогою React Router, CRUD-операціями, реалізованими за допомогою Axios з запитами на наш RESTful веб-сервіс.

`Ми реалізували:`
- Аутентифікація користувача за допомогою токену
- Підписка користувача на новини за допомогою електронної пошти
- Створення власного рецепту
- Додавання рецептів в категорію улюблені
- Перегляд власних рецептів
- Перегляд напоїв за категоріями
- Фільтрація та пошук напоїв за різними критеріями
- Зміна теми світла/темна зі збереженням її в базі даних і перегляду додатку на будь-якому іншому пристрої, враховуючи вподобання користувача
- Адаптивність веб-розмітки додатку для зручного перегляду на будь-яких пристроях
- Редагування даних користувача і додавання аватарки
- Мотиваційні модальні вікна для підняття настрою та активності користувача

`Бібліотеки які використовували:`
- emotion
- mui/material
- mui/x-date-pickers
- reduxjs/toolkit
- types/react-transition-group
- vitejs/plugin-react-swc
- axios
- dayjs
- formik
- lodash.throttle
- moment
- prop-types
- reselect
- styled-components
- yup
- react
- react-debounce-input
- react-dom
- react-redux
- react-router-dom
- react-scripts
- react-select
- react-spinners
- react-svg
- react-toastify
- react-transition-group
- redux-persist
- uuidjs
- vite-plugin-svgr
- web-vitals

### Бекенд
Бекенд "Drinkmaster" представляє собою ве6-сервер, реалізований на Node.js, а також NoSQL бази даних MongoDB. Документація по маршрутам описана [тут](https://drink-master-app.onrender.com/api-docs/#/). Проект бекенду був задеплоєний на сервер Render.com, що дозволило працювати розробникам з віддаленою базою даних, робити запити і тестувати роботу додатку.  

`Ми реалізували:`
- Доступ до додатку лише авторизованим користувачам
- Можливість редагування даних користувача, а також збереження, додавання, створення власної колекції напоїв
- Фільтрація напоїв за різними критеріями
- Обмеження щодо показу алкогольних напоїв неповнолітнім дітям та відображення на сторінках лише неалкогольних
- Висвітлення популярних напоїв
- Отримання інформації зі сторонніх баз даних, обробка на бекенді і повернення інформації в фронтенд-додаток: інформація про колекцію напоїв, категорії, необхідну тару, інгредієнти.
- Створення унікальної аватарки для кожного авторизованого користувача
- Збереження зображень на хмарному сервісі Cloudinary
- Підписка на новини за допомогою поштового менеджера Mailgun
- Логування роботи сервера та відстеження помилок

`Бібліотеки які використовували:`
- jsonwebtoken
- mongoose
- morgan
- multer
- multer-storage-cloudinary
- nanoid
- nodemailer
- path
- pug
- swagger-ui-express
- uuid
- bcrypt
- body-parser
- cloudinary
- cors
- cross-env
- crypto
- dotenv
- express
- fs-extra
- gravatar
- html-to-text
- jimp
- joi

## Над проектом працювали:
- Анна Футрик - фронтенд
- Анастасія Савицька - фронтенд
- Денис Ковтун - бекенд
- Дмитро Медведєв - скрам-майстер, фронтенд
- Дар'я Ящук - фронтенд
- Юлія Соловенюк - фронтенд
- Катерина Рябих - бекенд і фронтенд
- Володимир Мусаєлян - фронтенд
- Світлана Буйвол - фронтенд
- Інна Терещенко - фронтенд
- Оксана Пономарьова - фронтенд
- Вікторія Росовська - тімлід, фронтенд