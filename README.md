### Лабораторна робота 2. Знайомство з Docker

<p align="center"> <img src="Screenshots/ (1).png" alt="(1)"/> </p>
На першому скріншоті показано вміст контейнера Docker з назвою "agitated_wright". Можна побачити список файлів та директорій, які містяться в контейнері, включаючи системні директорії та файли конфігурації. Використано команду ls -la для відображення детальної інформації про файли.

<p align="center"> <img src="Screenshots/(2).png" alt="(2)"/> </p>
Другий скріншот демонструє інспекцію контейнера через Docker Desktop. Видно налаштування середовища (ENV), команди (CMD) та інші параметри контейнера. Зокрема, контейнер використовує образ nginx версії 1.25.3 та запускається з відключеним режимом демона.

<p align="center"> <img src="Screenshots/(3).png" alt="(3)"/> </p>
На третьому скріншоті показано інтерфейс Docker Desktop з поясненням про контейнери. Тут можна побачити навчальні матеріали про те, що таке контейнер та як його запустити. Також представлено базові команди для роботи з контейнерами.

<p align="center"> <img src="Screenshots/(4).png" alt="(4)"/> </p>
Четвертий скріншот відображає процес завантаження Docker образу "docker/welcome-to-docker". Видно послідовність кроків завантаження різних шарів образу та успішне завершення операції з відображенням SHA256 хешу.

<p align="center"> <img src="Screenshots/(5).png" alt="(5)"/> </p>
П'ятий скріншот показує вітальне повідомлення після успішного запуску першого контейнера. На синьому фоні з конфеті відображається напис "Congratulations!!!" та підтвердження успішного запуску першого контейнера, а також посилання на соціальні мережі.

<p align="center"> <img src="Screenshots/(6).png" alt="(6)"/> </p>

На шостому скріншоті показано код JavaScript файлу getGreeting.js, який містить масив вітальних повідомлень та експортує асинхронну функцію, що випадковим чином обирає одне з цих повідомлень. Код використовує сучасний синтаксис ES6+ та демонструє роботу з модулями.

<p align="center"> <img src="Screenshots/(7).png" alt="(7)"/> </p>

Сьомий скріншот відображає інтерфейс веб-додатку Todo з вітальним повідомленням "All hands on deck!". Інтерфейс містить поле для введення нового завдання та кнопку "Add Item". Наразі список завдань порожній, про що свідчить повідомлення "No items yet! Add one above!".

<p align="center"> <img src="Screenshots/(8).png" alt="(8)"/> </p>

На восьмому скріншоті показано процес клонування репозиторію getting-started-todo-app з GitHub. Термінал відображає прогрес завантаження об'єктів, їх стиснення та вирішення залежностей. Загалом було завантажено 207 об'єктів загальним розміром 4.51 МіБ.

<p align="center"> <img src="Screenshots/(9).png" alt="(9)"/> </p>

Дев'ятий скріншот демонструє виконання команди docker compose watch. Видно процес збірки та запуску контейнерів, включаючи встановлення залежностей через yarn, копіювання файлів та налаштування мережі. Успішно запущено контейнери для клієнта, бекенда, бази даних MySQL та phpMyAdmin.

<p align="center"> <img src="Screenshots/(10).png" alt="(10)"/> </p>

На десятому скріншоті показано оновлений інтерфейс Todo додатку з заголовком "Hello world!". Як і раніше, інтерфейс містить форму для додавання нових завдань, але список завдань залишається порожнім.

<p align="center"> <img src="Screenshots/(11).png" alt="(11)"/> </p>

На одинадцятому скріншоті показано інтерфейс Todo додатку з новим вітальним повідомленням "Whalecome!". Інтерфейс має поле введення з плейсхолдером "What do you need to do?" та кнопку "Add Item" для додавання нових завдань.

<p align="center"> <img src="Screenshots/(12).png" alt="(12)"/> </p>

Дванадцятий скріншот демонструє форму створення нового репозиторію в Docker Hub. Обрано публічний тип репозиторію з назвою "getting-started-todo-app" в просторі імен "dilitvinova". Форма містить поле для короткого опису та опції налаштування видимості.

<p align="center"> <img src="Screenshots/(13).png" alt="(13)"/> </p>

На тринадцятому скріншоті показано код компонента AddItemForm.jsx, який відповідає за форму додавання нових завдань. Компонент використовує Form.Control з параметрами для обробки введення та доступності (aria-label).

<p align="center"> <img src="Screenshots/(14).png" alt="(14)"/> </p>

Чотирнадцятий скріншот відображає інтерфейс Todo додатку з заголовком "All hands on deck!". Інтерфейс містить форму для введення нових завдань та інформаційне повідомлення про відсутність завдань.

<p align="center"> <img src="Screenshots/(15).png" alt="(15)"/> </p>

П'ятнадцятий скріншот показує файл стилів index.scss, який містить базові налаштування стилів для додатку. Код включає імпорт Bootstrap та визначає стилі для body з використанням шрифту 'Lato' та світло-блакитного фону (#99bbff).

<p align="center"> <img src="Screenshots/(16).png" alt="(16)"/> </p>
На шістнадцятому скріншоті показано процес збірки Docker образу командою docker build. Відображено послідовність кроків збірки, включаючи завантаження залежностей, копіювання файлів та встановлення пакетів через yarn. В кінці виконання показано список створених образів з їх розмірами, де основний образ займає 1.12GB.
<p align="center"> <img src="Screenshots/(17).png" alt="(17)"/> </p>
Сімнадцятий скріншот демонструє процес відправки (push) створеного Docker образу до репозиторію dilitvinova/getting-started-todo-app. Видно послідовність відправлених шарів та їх монтування з бібліотеки Node.js. Процес завершується успішно з відображенням SHA256 хешу та розміру фінального образу.
