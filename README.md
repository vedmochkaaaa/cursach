# АНАЛИЗ СОВРЕМЕННЫХ САЙТОВ
## ЛАБОРАТОРНАЯ РАБОТА № 10 по дисциплине «Веб-технологии»
**Выполнила**: Студентка группы 241-671 Панфилова А.А.

### Подбор сайтов и их описание
1. [Liqium](https://www.liqium.com/) -специализирующаяся на разработке и внедрении решений для автоматизации управления водными ресурсами.
1. [Notamedia](https://nota.media/) -  специализирующееся на разработке комплексных IT-решений, создании бренд-стратегий и медиапроектов.
1. [MWI](https://mwi.me/) - специализирующееся на цифровых стратегиях.
1. [ADV](https://adv.ru/?rrcid=173670833132867035#CoreVerticals) - специализирующаяся на предоставлении комплексных решений для цифровой рекламы.
1. [PINKMAN](https://www.pinkman.ru/) - специализирующаяся на разработке уникальных визуальных решений для брендов.
1. [Факт](https://fact.digital/) - проектирование и развитие гибких цифровых экосистем.
1. [BRAIND](https://braind.agency/?erid=2W5zFGRQtV6&utm_source=ratingruneta&utm_medium=advmiddle&utm_campaign=production&rrcid=173670833132867035) - посвящен современным решениям в области нейротехнологий, искусственного интеллекта и когнитивных наук.
1. [Космос-Веб](https://www.cosmos-web.ru/) - специализируется на предоставлении услуг в области веб-разработки и IT-решений.
1. [Uplab](https://www.uplab.ru/?utm_source=ratingruneta&utm_medium=cpc&utm_content=web&utm_campaign=hyperlink_option&rrcid=173670833132867035) - специализируется на создании современных сайтов, мобильных приложений и сложных IT-решений.
1. [Магвай](https://magwai.ru/) - специализирующаяся на разработке и внедрении технологий для автоматизации бизнес-процессов.

### Описание свойств CSS
|№|Свойство|Назначение|Где встретилось|
|-|--------|----------|---------------|
|1|-webkit-text-size-adjust|адаптирование текста  к изменениям масштаба|[Космос-Веб](https://www.cosmos-web.ru/)|
|2|--swiper-theme-color|задает основной цвет для различных элементов слайдера|[Liqium](https://www.liqium.com/)|
|3|unicode-bidi:[normal, embed, bidi-override, isolate, plaintext, initial, inherit]|отображение текста и его составляющих в зависимости от их направления|[MWI](https://mwi.me/)|
|4|--swiper-theme-color|отображение текста и его составляющих в зависимости от их направления|[ADV](https://adv.ru/?rrcid=173670833132867035#CoreVerticals)|
|5|aspect-ratio:[width/height, auto, inherit, initial, revert, unset]|явная установка соотношения сторон элемента|[Факт](https://fact.digital/)|
|6|--smart-captcha-doc-height|используется для хранения и динамического управления определённой высотой|[Uplab](https://www.uplab.ru/?utm_source=ratingruneta&utm_medium=cpc&utm_content=web&utm_campaign=hyperlink_option&rrcid=173670833132867035)|
|7|visibility:[visible;hidden;collapse; inherit;]|используется для управления видимостью элемента на веб-странице|[Notamedia](https://nota.media/)|
|8|mobile|стиль, применяющийся только к мобильным устройствам|[PINKMAN](https://www.pinkman.ru/)|
|9|list-style:[disc inside]|является сокращением для установки нескольких связанных со списком свойств|[Магвай](https://magwai.ru/)|
|10|overflow:[visible; hidden; scroll; auto;]|отображение содержимого эмемента, если оно выходит за пределы области видимости|[Космос-Веб](https://www.cosmos-web.ru/)|

### Структура страницы [BRAIND](https://braind.agency/?erid=2W5zFGRQtV6&utm_source=ratingruneta&utm_medium=advmiddle&utm_campaign=production&rrcid=173670833132867035) до 5 уровней вложенности 

![Вид сайта](https://github.com/vedmochkaaaa/2/blob/main/braind.png)
```
<body>
  <!-- Уровень 1 -->
  <header class="header">
    <!-- Уровень 2 -->
    <div class="header__content">
      <div class="logo"></div> <!-- Логотип -->
      <nav class="navigation">
        <!-- Уровень 3, список навигации -->
        <ul class="navigation__list">
          <li class="navigation__item"><a href="#" class="navigation__link">About</a></li>
          <li class="navigation__item"><a href="#" class="navigation__link">Services</a></li>
          <li class="navigation__item"><a href="#" class="navigation__link">Portfolio</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
  <main class="main-content">
    <!-- Уровень 2 -->
    <section class="hero-section">
      <!-- Уровень 3 -->
      <div class="hero-section__content">
        <!-- Уровень 4 -->
        <h1 class="hero-section__title">Build iconic brands</h1>
        <p class="hero-section__subtitle">We create strategies to inspire your audience.</p>
        <a href="#" class="hero-section__cta">Get in Touch</a>
      </div>
    </section>

    <section class="services-section">
      <!-- Уровень 3 -->
      <div class="services-list">
        <!-- Уровень 4 -->
        <div class="services-item">
          <h3 class="services-item__title">Strategy</h3>
          <p class="services-item__description">Business strategy for long-term success.</p>
        </div>
        <div class="services-item">
          <h3 class="services-item__title">Branding</h3>
          <p class="services-item__description">Design and identity to make your brand memorable.</p>
        </div>
      </div>
    </section>
  </main>
  
  <footer class="footer">
    <!-- Уровень 2 -->
    <div class="footer-content">
      <!-- Уровень 3 -->
      <div class="footer-contacts">
        <a href="mailto:info@braind.agency" class="footer-email">info@braind.agency</a>
      </div>
    </div>
  </footer>
</body>

```
### Характеристика сайта BRAIND

1. Использованная методология именования классов:
   Сайт использует BEM методологию.
   - Примеры классов:
     - header__content - элемент блока "header".
     - services-item__title - элемент блока "services-item".

2. Использование HTML5-тегов:
   Сайт использует HTML5-теги, такие как ``` <header>, <main>, <section>, <footer> ```.

3. Количество оберток ``` <div> ```:
   - Применяются так, чтобы не увеличивать сложность.
   - <div> используются только для группировки и стилизации элементов.

4. Насколько легко разобраться в коде:
   - Оптимально организованный код.
   - Использование BEM-методологии делает код удобным для чтения и поддержания. 
   - Семантические элементы ясны и логичны, что помогает быстро понять структуру страницы.

---
### Итог

Сайт BRAIND демонстрирует разумное использование современных подходов к разработке веб-интерфейса, таких как BEM и HTML5. Код легок в понимании и обслуживании, с логичной структурой и ясной семантикой, что подчеркивает качественный подход к веб-разработке.

# Описание реализации контактной формы [BRAIND](https://braind.agency/?erid=2W5zFGRQtV6&utm_source=ratingruneta&utm_medium=advmiddle&utm_campaign=production&rrcid=173670833132867035)

Шаг 1: Создание HTML-структуры

1. Откройте ваш HTML-файл и создайте основной контейнер для контактной формы, используя тег <div> с классом, например, .contact-form-container.

    ```
    <div class="contact-form-container">
        <!-- Ваша контактная форма будет здесь -->
    </div>
    ```

Шаг 2: Добавление заголовка

2. Внутри контейнера добавьте заголовок с помощью тега ``` <h2> ```, например, "Свяжитесь с нами".

    ```
    <h2>Свяжитесь с нами</h2>
    ```

Шаг 3: Создание формы

3. Добавьте элемент ```<form>``` внутри контейнера для создания формы и укажите метод отправки, например, post.
    
    ```
    <form method="post" action="/submit-form">
        <!-- Поля формы будут здесь -->
    </form>
    ```

Шаг 4: Поле для имени

4. Внутри формы добавьте поле ввода для имени пользователя с помощью тега ```<input>``` с типом text.

    ```
    <input type="text" name="name" placeholder="Ваше имя" required>
    ```

Шаг 5: Поле для электронной почты

5. Добавьте поле ввода для электронной почты с типом email.

    ```
    <input type="email" name="email" placeholder="Ваш Email" required>
    ```

Шаг 6: Поле для сообщения

6. Добавьте текстовое поле для ввода сообщения с помощью тега ```<textarea>```.

    ```
    <textarea name="message" placeholder="Ваше сообщение" required></textarea>
    ```

Шаг 7: Кнопка отправки

7. Добавьте кнопку для отправки формы с помощью тега ```<button>```.

    ```
    <button type="submit">Отправить</button>
    ```

Шаг 8: Стилизация контейнера

8. Перейдите к вашему CSS-файлу, чтобы стилизовать контейнер формы. Установите ширину, отступы и выберите шрифт.

    ```
    .contact-form-container {
        width: 80%;
        margin: auto;
        font-family: Arial, sans-serif;
    }
    ```

Шаг 9: Стилизация формы

9. Задайте стиль для элементов формы, таких как поля ввода и текстовые поля, добавив отступы и границы.

    ```
    input, textarea {
        width: 100%;
        padding: 10px;
        margin: 5px 0;
        border: 1px solid #ccc;
    }
    ```

Шаг 10: Стилизация кнопки

10. Стилизуйте кнопку отправки, добавив фон, цвет текста и другие эффекты визуального оформления.

    ```
    button {
        background-color: #333;
        color: white;
        padding: 10px 15px;
        border: none;
        cursor: pointer;
    }
    ```

Шаг 11: Добавление hover-эффекта

11. Добавьте эффект наведения для кнопки, чтобы улучшить интерактивность.

    ```
    button:hover {
        background-color: #555;
    }
    ```

Шаг 12: Валидация формы на стороне клиента

12. Добавьте валидацию формы на стороне клиента, используя простые HTML-атрибуты, такие как required, и регулярные выражения для проверки формата электронной почты.

    ```
    <input type="email" name="email" placeholder="Ваш Email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" required>
    ```

Шаг 13: Настройка отправки на стороне сервера

13. Настройте серверный файл для обработки данных формы. Например, используйте Python или PHP для сохранения информации.

Шаг 14: Тестирование

14. Проверьте работу формы в разных браузерах и проверьте корректность передачи данных.

Следуя этим шагам, вы сможете реализовать контактную форму, аналогичную той, что находится на сайте BRAIND.

### Результат
![Результат работы](https://github.com/vedmochkaaaa/2/blob/main/svaz.png)

### Ресурсы для изучения верстки
1. [Курс на Skillbox](https://bootcamp.skillbox.ru/digital-design-mini?utm_source=yandex&utm_medium=cpc&utm_campaign=all_all_yandex_cpc_master-campaign_bootcamp-623_all_short_skillbox_99997794&utm_content=adg_5325525788%7Cad_16397234244%7Cph_48245231145%7Ckey_---autotargeting%7Cdev_desktop%7Cpst_premium_1%7Crgnid_172_Уфа%7Cplacement_none%7Ccreative_%7Bcreative_name%7D&utm_term=---autotargeting&yclid=683355871678038015)
1. [Обучающие уроки](https://vk.com/web_and_graph?search_track_code=63957072r5TWKLxmrsxcCjkwinuMeO_LdCrC9O9A-m1KGxDuANj3C33ZaqAwW-TGDwnPKdUzv6VGKtzzh0GX&from=search)
1. [Канал веб-программирования](https://youtube.com/@educatterofficial?feature=shared)
1. [Создание веб-сайтов](https://youtube.com/@brainscloud?feature=shared)
1. [Онлайн школа программирования и веб-разработки](https://youtube.com/@itproger?feature=shared)
1. [Онлайн школа программирования и веб-разработки(2)](https://youtube.com/@webproschool?feature=shared)
1. [Веб-дизайн в Figma](https://t.me/figmaweb)
1. [HTML и CSS для новичков](https://code.mu/ru/markup/book/prime/)
1. [CSS учебник](https://www.schoolsw3.com/css/)
1. [HTML учебник](https://www.schoolsw3.com/html/index.php)
