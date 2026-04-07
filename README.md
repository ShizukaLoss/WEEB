<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
</p>

<h1 align="center">✨ Weeb Project — Landing Page ✨</h1>

<p align="center">
  <strong>Сучасна адаптивна верстка лендингу з акцентом на анімації та чистоту коду.</strong>
</p>

---

### 📝 Про проєкт
Це проєкт адаптивної верстки лендингу **"Weeb"**. Сайт містить головний екран (Hero Section), блоки з послугами, відгуками клієнтів та інтерактивну секцію майбутніх івентів.

### 📌 Джерело та процес розробки

Проєкт реалізовано на основі [відео-уроку](https://www.youtube.com/live/IdtK-QOKbQE?si=uW22qPi-bZ8W_WS4) з використанням оригінального макету у **Figma**. Попри те, що базова структура відповідає навчальному матеріалу, мною було внесено значні авторські зміни:

* **🎨 Стилізація:** Весь процес верстки повністю адаптовано та стилізовано згідно з моїм власним баченням та естетичним смаком.
* **✨ Анімації:** Більшість складних анімацій та інтерактивних ефектів є **моєю власною розробкою**.
* **⚙️ Оптимізація:** Код було перероблено для покращення логічної структури та забезпечення стабільної адаптивності під різні типи пристроїв.

### 🚀 Технології
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

* **HTML5** — семантична та доступна розмітка.
* **CSS3** — методологія **BEM**, Flexbox, Grid Layout.
* **JavaScript** — реалізація бургер-меню та логіки взаємодії.
* **Google Fonts** — використано шрифт *Roboto*.

### 📋 Особливості реалізації
* 🎯 **Pixel Perfect:** Максимальна відповідність макету Figma.
* 📱 **Adaptive Design:** Повна адаптивність (mobile/tablet/desktop) завдяки окремому модулю `media.css`.
* ✨ **Custom Animations:** Унікальні ефекти появи блоків, зібрані у файлі `animations.css`.
* 🏗️ **Architecture:** Модульна структура CSS для легкої підтримки коду.

### 📁 Структура проєкту
```text
├── index.html          # Головна сторінка
├── css/
│   ├── style.css       # Основні стилі
│   ├── reset.css       # Скидання стандартних стилів
│   ├── components.css  # Стилі окремих компонентів
│   ├── media.css       # Адаптивні медіа-запити
│   └── animations.css  # Авторські CSS-анімації
├── js/
│   └── script.js       # Логіка меню та взаємодії
├── img/                # Оптимізовані графічні ресурси
└── README.md
