---
title: "Nokia N-Gage QD стає універсальним Bluetooth-геймпадом"
description: "Хоча Nokia N-Gage не змогла стати серйозним конкурентом для портативних консолей Nintendo, їй не можна відмовити в досить передовій на той час технології. [BeardoGuy] має повністю функціональний N-Gage QD, який він перетворив на універсальний геймпад із Bluetooth. -- Hackaday"
---

{:.img-center}
![GamepadBT](/n-gage/programs/menu.jpg)

На пристрої працює програма, яка змушує його діяти як геймпад, а на клієнтському боці потрібен саморобний Bluetooth-адаптер. Адаптер складається з плати на базі ATtiny85 і модуля HC-06, і він розпізнається як USB-геймпад на будь-якому пристрої, до якого підключається.

Програма GamepadBT, розроблена [BeardoGuy], відправляє події кнопок через Bluetooth на адаптер, який передає їх через USB, і ці події виглядають як сигнали від звичайного геймпада.

Цей проєкт можна використовувати як ресурс для реалізації USB-геймпада — як на Nokia N-Gage, так і на інших пристроях. Усі деталі можна знайти в репозиторії проєкту на GitHub, а також переглянути відео з демонстрацією роботи.

Що стосується самого Nokia N-Gage, варто відзначити, що для нього є оновлене середовище розробки, а навіть гра Wordle була портована на N-Gage. Хоча вона може виглядати як артефакт минулого, але далеко не забута.

https://github.com/BeardoGuy/GamepadBT

{:.img-center}
![GamepadBT](/n-gage/programs/menu.jpg)


<iframe width="560" height="315" src="https://www.youtube.com/embed/HMz5dQX0W8A?si=1jIPvnkWYVyNFsoj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>