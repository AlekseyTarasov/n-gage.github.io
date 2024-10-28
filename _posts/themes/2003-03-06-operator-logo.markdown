---
title: "Operator Logo"
screenshot: "/n-gage/themes/logo.jpg"
download: "/n-gage/themes/operator-logo.zip"
mirror: 
file-size: "7.74 kB"
quote: |
    Розробник: [n-gage.site]()\
    Версія: none\
    Контейнер: .bmp\
    Сумісність: n-gage, n-gage qd.
---

Ще один спосіб прикрасити ваш N-Gage — встановити логотип оператора.

Як це зробити без використання спеціальних програм:
Логотип оператора — це зображення формату BMP з назвою у вигляді xxx_yy_zz.bmp, де:

- xxx — код країни (MCC),
- yy — код мережі (MNC),
- zz — код підмережі (зазвичай 0).

Необхідні коди для операторів різних країн можна знайти у [Вікіпедії](https://wikipedia.org/wiki/Mobile_Country_Code).

Приклад: якщо ваш оператор — Life:) в Україні, то ім'я файлу буде 255_06_0.bmp.

Максимальний розмір BMP-файлу — 97x25 пікселів.

Превью декількох готових логотипів:

{:.img-center}
[![Monster](/n-gage/themes/logo.bmp)](/n-gage/themes/logo.bmp)

аватарки Google Chrome

{:.img-center}
[![Cake](/n-gage/themes/Cake.bmp)](/n-gage/themes/Cake.bmp)
[![Ninja](/n-gage/themes/ninja.bmp)](/n-gage/themes/ninja.bmp)
[![Cat](/n-gage/themes/Cat.bmp)](/n-gage/themes/Cat.bmp)

Щоб встановити логотип оператора на ваш N-Gage, виконайте наступні кроки:

1. Підготуйте BMP-файл логотипу оператора, перейменувавши його згідно з кодами країни та мережі (наприклад, 255_06_0.bmp).
2. Скопіюйте файл до папки C:\\System\\Apps\\Phone\\OpLogo.

Зазначте, що спершу папок двох останніх папок (Phone та OpLogo) може не бути, тому створіть їх вручну, якщо вони відсутні.

3. Після перезавантажте пристрій та логотип оператора повинен відобразитися на вашому екрані.