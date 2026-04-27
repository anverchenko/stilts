# Dragon.Stilts — Landing Page

Лендінг-сторінка для реклами та продажу циркових ходуль.

---

## Навігація

- Products
- Why Us
- Gallery
- About
- Contact

---

## Hero

- **Тег:** Handcrafted Circus Stilts Equipment
- **Заголовок:** Rise Above the Crowd
- **Опис:** Professional circus stilts for performers, street artists, and entertainers. Built for safety, comfort, and pure spectacle.
- **Кнопки:** Browse Stilts / Get a Quote

---

## Products

Три товари з немодальними вікнами (характеристики + ціна):

1. **Model D1** — Suitable for both beginners and experienced performers. Height range: 30–120 cm. Starting from $350.
2. **Чохол для ходуль** — Stilts carrying bag with adjustable length, starting from $25.
3. **Model D2** — Professional stilts, steel + aluminum, height range 50–150 cm, starting from $450.


Роширений Опис товарів:

тут треба вставити список виробів. клікаючи на виріб- випадає модальне вікно з розширеним описом виробу


---

Опис виробів (окремі модальні вікна):

    1. Картка товару "Виріб 1"
   Назва: **Model D1**
  
    # Короткий опис: 
   Suitable for both beginners and experienced performers. Height range: 30–120 cm. Perfect for beginners and younger performers. Adjustable height, padded foot rests, lightweight aluminum frame.

   # Розширений опис: 
   **Stilts Model D1**

   тут вставляємо **Зображення:**
        "Stilts01.jpg"
        "Stilts02.jpg"
        "Stilts03.jpg"

  Зображення повинні збільшуватись до оригінального розміру при клікі на ньому
    Suitable for both beginners and experienced performers. Height range: 30–120 cm. Lightweight, stable, and easy to adjust.

    Specifications
        Height range: 30–60 cm above the ground
        Material: aluminum + steel
        Weight: 3200+ g per pair (2 stilts)
        Max load: 85 kg
        Steel foot rests with a clip fastening system
        Rubber non-slip foot caps
        Disassembles and assembles in 1 minute (all necessary tools are stored inside the stilts)
        Size when assembled: 600 mm
        Ages 13+ recommended

        

   Ціна Виробу1 =$350    

тут потрібно вставити dropdown1. 
Назва dropdown1: "Stilt Height" 
По замовчуванню стоїть пункт "30-50 см"  
Ось пункти dropdown1: 
    1)" Aluminum lower section 30-50 cm. Weight 1600g (1 pc.)". При виборі цього пункту - dropdown1_price = 0
    2)"Aluminum lower section 50-90 cm". Weight 1800g (1 pc.)" При виборі цього пункту - dropdown1_price = 20
    3)"Carbon lower section 30-50 cm". Weight 1400g (1 pc.)" При виборі цього пункту - dropdown1_price = 70
    4)"Carbon lower section 50-90 cm". Weight 1600g (1 pc.)" При виборі цього пункту - dropdown1_price = 90

поруч (справа від dropdown1) потрібно вставити dropdown2. 
Назва dropdown2: "Upper Part Height" 
По замовчуванню стоїть пункт "30-40 см"  
Ось пункти dropdown2: 
    1)"30-40 сm". При виборі цього пункту - dropdown2_price = 0
    2)"20-30 сm". При виборі цього пункту - dropdown2_price = 0
    3)"40-50 сm". При виборі цього пункту - dropdown2_price = 0

 При кождній зміні в dropdown1 або dropdown2 -- перераховуємо Ціну Виробу1: 
   Ціна Виробу1 =$350 + dropdown1_price + dropdown2_price   



"Technical Documentation:"

      ...

  //Зображення повинно збільшуватись до оригінального розміру при клікі на ньому


  Далі хочу вставити кнопку "Download Technical Documentation",  яка завантажує pdf-файл   "Ergo Tripod Dragon.Kinbaku 2026_04_13.pdf". 

---

## Why Us (4 переваги)

### Why Dragon.Stilts
## Built Different

# Handcrafted Quality
Every pair is built by hand by experienced craftsmen. No mass production — only precision and care.

# Safety First
All models are tested for loads up to 200 kg. The leg fastening system uses roller clips and secure Velcro straps.

# Custom Sizes
You can adjust the height of the stilts to match your costume.

# Fast Worldwide Shipping
We are based in Ukraine (Kyiv). You can purchase stilts in our Etsy store or order directly from us.


## Gallery
Загружаємо в галерею наступні фото:

stilts01.jpg
stilts02.jpg
stilts03.jpg
stilts04.jpg
stilts05.jpg
stilts06.jpg
stilts07.jpg
stilts08.jpg



## About Us

# The Dragon.Stilts Story
- We founded Dragon.Stilts in 2024 with a simple idea: performers deserve equipment that matches their art. With years of experience in designing and manufacturing metal structures, we applied that expertise to create ultra-modern lightweight stilts. 
We actively use the stilts we create ourselves and also teach children and anyone who is interested.
  

---

## Contact

- Email: dragon.spiritus@gmail.com
- Instagram: @dragon.spiritus
- WhatsApp: +380 93 767 7311

---

## Стилі та дизайн

- Темна палітра (`#0d0d0d`) з золотим акцентом (`#d4a017`)
- Шрифти: Playfair Display (заголовки) + Inter (текст)
- Адаптивність для мобільних
- Анімації при прокрутці (fade-in)
- Модальні вікна для товарів

---

## Технічні деталі

- Файли: `index.html`, `style.css`
- Чистий HTML/CSS/JS без фреймворків
- GitHub: https://github.com/anverchenko/stilts

---

## Домени

 <!-- - http://www.stilts.in.ua -->
- http://www.dragon.stilts.in.ua

---

## Деплой

Сервер: Docker + nginx на VPS
Контейнер: порт 4052
Nginx virtual host: `/etc/nginx/sites-available/stilts`

```bash
# Оновити сайт на сервері:
cd /root/stilts && git pull && docker compose up -d --build
```

---

## ::TO DO::

Поточні задачі:
1. Додати реальні фото ходуль
2. Замінити назву бренду (зараз "SkyStep Stilts" — placeholder)
3. Вставити реальні контакти (email, Instagram, WhatsApp)
4. Налаштувати SSL (https) після оновлення DNS
5. Замінити placeholder ціни на реальні

6. Запустити двомовний сайт. Основна мова -- українська, друга мова - англійська.
7. Український варіант ---  роби автоматично на основі англійського тексту!


