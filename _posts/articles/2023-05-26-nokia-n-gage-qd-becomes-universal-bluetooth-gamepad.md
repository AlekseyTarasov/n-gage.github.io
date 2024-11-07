---
title: "Nokia N-Gage QD стає універсальним Bluetooth-геймпадом"
description: "Хоча Nokia N-Gage не змогла стати серйозним конкурентом для портативних консолей Nintendo, їй не можна відмовити в досить передовій на той час технології. [BeardoGuy] має повністю функціональний N-Gage QD, який він перетворив на універсальний геймпад із Bluetooth. -- Hackaday"
---

{:.video-center}
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMz5dQX0W8A?si=1jIPvnkWYVyNFsoj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

На пристрої працює програма, яка змушує його діяти як геймпад, а на клієнтському боці потрібен саморобний Bluetooth-адаптер. Адаптер складається з плати на базі ATtiny85 і модуля HC-06, і він розпізнається як USB-геймпад на будь-якому пристрої, до якого підключається.

<img alt="Colin McRae Rally" src="/n-gage/utilities/Scr. shot.Main.jpg" vspace="5" hspace="5" border="1" align="right">

Програма GamepadBT, розроблена [BeardoGuy](https://github.com/BeardoGuy), відправляє події кнопок через Bluetooth на адаптер, який передає їх через USB, і ці події виглядають як сигнали від звичайного геймпада.

Цей проєкт можна використовувати як ресурс для реалізації USB-геймпада — як на Nokia N-Gage, так і на інших пристроях. Усі деталі можна знайти в [репозиторії проєкту на GitHub](https://github.com/BeardoGuy/GamepadBT), а також переглянути відео з демонстрацією роботи.

Що стосується самого Nokia N-Gage, варто відзначити, що для нього є оновлене середовище розробки, а навіть гра Wordle була портована на N-Gage. Хоча вона може виглядати як артефакт минулого, але далеко не забута.

Перекладений текст з репозиторія GamepadBT, оригінал можна подивитися [за посиланням](https://github.com/BeardoGuy/GamepadBT).

{:.img-center}
![GamepadBT](/n-gage/articles/GamepadBT_v3.01.jpg)

Проєкт перетворення Symbian Series60 на Bluetooth-геймпад, зокрема для Nokia N-Gage та N-Gage QD.
Цей проєкт має працювати з усіма пристроями Symbian Series 60 1-го та 2-го видань. Тестування проводилося на Nokia N-Gage QD з прошивкою v4.60.

Програмне забезпечення для N-Gage:
Для роботи потрібна встановлена Python for S60 (PyS60). Завантажте відповідну версію за посиланням нижче:

Для Series 60 1-го видання (N-Gage та N-Gage QD) – [Завантажити за цим посиланням](https://sourceforge.net/projects/pys60/files/pys60/1.3.1/PythonForS60_1stEd_1_3_1.SIS/download) також оновлена збірка та модулі знаходяться в нашому розділі [Programs](https://n-gage.site/programs/)
Для Series 60 2-го видання (6600, 3230, 7610 тощо) – [Завантажити за цим посиланням](https://sourceforge.net/projects/pys60/files/pys60/1.3.23/PythonForS60_1_3_23_2ndEd.SIS/download)
Завантажте SIS-файл із розділу [Releases](https://sourceforge.net/projects/pys60/files/pys60/1.3.23/PythonForS60_1_3_23_2ndEd.SIS/download).

Програмне забезпечення для Windows (НОВЕ):

Якщо ви хочете використовувати N-Gage як геймпад тільки для Windows ПК, спробуйте нову програму GamepadBT-Server. Додаткове обладнання не потрібне.

Програма-сервер працюватиме лише в тому випадку, якщо ваш N-Gage/Symbian пристрій може безпомилково підключатися до ПК через Bluetooth і передавати файли (в іншому випадку див. розділ "Обладнання"). Деякі сучасні вбудовані Bluetooth-адаптери можуть не підтримувати підключення до старих Symbian-пристроїв, тому перед використанням спробуйте спочатку з’єднати та надіслати файл.

Обладнання:

(Потрібне лише у випадку, якщо ви хочете створити універсальний USB-адаптер для всіх пристроїв, якщо програма-сервер не працює або якщо потрібна підтримка Direct Input Joystick).
