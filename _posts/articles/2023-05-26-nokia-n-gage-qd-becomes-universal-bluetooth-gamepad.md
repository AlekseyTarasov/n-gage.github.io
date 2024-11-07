---
title: "Nokia N-Gage QD стає універсальним Bluetooth-геймпадом"
description: "Хоча Nokia N-Gage не змогла стати серйозним конкурентом для портативних консолей Nintendo, їй не можна відмовити в досить передовій на той час технології. [BeardoGuy] має повністю функціональний N-Gage QD, який він перетворив на універсальний геймпад із Bluetooth. -- Hackaday"
---

{:.img-center}
![GamepadBT](/n-gage/programs/menu.jpg)

На пристрої працює програма, яка змушує його діяти як геймпад, а на клієнтському боці потрібен саморобний Bluetooth-адаптер. Адаптер складається з плати на базі ATtiny85 і модуля HC-06, і він розпізнається як USB-геймпад на будь-якому пристрої, до якого підключається.

<img alt="Colin McRae Rally" src="/n-gage/utilities/Scr. shot.Main.jpg" vspace="5" hspace="5" border="1" align="left">

Програма GamepadBT, розроблена [BeardoGuy](https://github.com/BeardoGuy), відправляє події кнопок через Bluetooth на адаптер, який передає їх через USB, і ці події виглядають як сигнали від звичайного геймпада.

Цей проєкт можна використовувати як ресурс для реалізації USB-геймпада — як на Nokia N-Gage, так і на інших пристроях. Усі деталі можна знайти в [репозиторії проєкту на GitHub](https://github.com/BeardoGuy/GamepadBT), а також переглянути відео з демонстрацією роботи.

<iframe width="560" height="315" src="https://www.youtube.com/embed/HMz5dQX0W8A?si=1jIPvnkWYVyNFsoj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Що стосується самого Nokia N-Gage, варто відзначити, що для нього є оновлене середовище розробки, а навіть гра Wordle була портована на N-Gage. Хоча вона може виглядати як артефакт минулого, але далеко не забута.

{:.img-center}
![GamepadBT](/n-gage/articles/GamepadBT_v3.01.jpg)


Проєкт перетворення Symbian Series60 на Bluetooth-геймпад, зокрема для Nokia N-Gage та N-Gage QD.
Цей проєкт має працювати з усіма пристроями Symbian Series 60 1-го та 2-го видань. Тестування проводилося на Nokia N-Gage QD з прошивкою v4.60.

Програмне забезпечення для N-Gage:
Для роботи потрібна встановлена Python for S60 (PyS60). Завантажте відповідну версію за посиланням нижче:

Для Series 60 1-го видання (N-Gage та N-Gage QD) – [Завантажити за цим посиланням]
Для Series 60 2-го видання (6600, 3230, 7610 тощо) – [Завантажити за цим посиланням]
Завантажте SIS-файл із розділу Releases.

