# SkyStep Stilts — Landing Page

Лендінг-сторінка для реклами та продажу циркових ходуль.

---

## Навігація

- Products
- Why Us
- About
- Contact

---

## Hero

- **Тег:** Handcrafted Circus Equipment
- **Заголовок:** Rise Above the Crowd
- **Опис:** Professional circus stilts for performers, street artists, and entertainers. Built for safety, comfort, and pure spectacle.
- **Кнопки:** Browse Stilts / Get a Quote

---

## Products

Три товари з модальними вікнами (характеристики + ціна):

1. **Junior Stilts** — для початківців, алюміній, висота 30–60 см, від $180
2. **Pro Stage Stilts** — професійні, сталь+алюміній, висота 40–90 см, від $320
3. **Peg Stilts** — класичні циркові, зварна сталь, висота 60–150 см, від $420

---

## Why Us (4 переваги)

- Handcrafted Quality
- Safety First
- Custom Sizes
- Fast Worldwide Shipping

---

## About

- Назва: SkyStep Stilts
- Засновано: 2015
- Статистика: 500+ пар, 40+ країн, 10 років досвіду

---

## Contact

- Email: hello@skystepstilts.com
- Instagram: @skystepstilts
- WhatsApp

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

- http://www.stilts.in.ua
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
