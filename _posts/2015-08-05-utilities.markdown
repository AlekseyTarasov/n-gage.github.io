---
title: "Utilities"
date: 2015-08-05
tags: [utilities]
---

## almalert v1.00##

![almalert](https://www.dropbox.com/s/9wzi8s1250g4eya/almalert.jpg?raw=1)

Заменяет собой стандартный будильник расширяя его функциональность. В данный момент по сравнению с обычным реализована следующая дополнительная функциональность:

1. установка любой mid/wav/amr/rng мелодии на звонок будильника.
2. установка любой mid/wav/amr/rng мелодии на звонок календаря.
3. сигнал в начале каждого часа с настройкой мелодии и периода срабатывания.
4. настройка snooze period.
5. настройка snooze count.
6. оповещение о днях рождения на основе информации из адресной книги.

В отличии от всех остальных будильников сторонних разработчиков, almalert выполнен не в виде отдельного, чужеродного для symbian os сервиса, а в виде плагина к стандартному alarm сервису, что дает следующие плюсы:

1. более низкую вероятность потери сигнала будильника.
2. работа при выключенном устройстве.
3. совместимость со стандартным проигрывателем музыкальных файлов и стандартным радио.

ченжлог относительно almalert 0.90:
• синхронизация времени по интернету;
• русский язык;
• какая-то поддержка siemens sx1;
• кое-что по мелочи.

ps: недокументированные хоткеи — присутствуют :)

Совместимость: n-gage, qd, 3650.

[download 42 kB](http://downloads.sourceforge.net/almalert/almalert_1_00.zip?download)
- alt [download 41.64 kB](https://www.dropbox.com/s/s9tkedforg07jed/almalert.sis?raw=1)


## fixss v1.06##

исправляет три проблемы:

1. устраняется часто возникающая ошибка при старте телефона, связанная с ошибкой в реализации стандартного проигрывателя музыкальных файлов;
2. отключается часть механизма защиты, которая приводит к лагам телефона при большом количестве игр и приложений на карте.
3. отключается писк каждые пять секунд во время записи телефонных разговоров. совместимость: n-gage.

[download 3.4 kB](http://sourceforge.net/projects/almalert/files/fixss/1.06/fixss_1_06.zip/download)
- alt [download 3.4 kB](https://www.dropbox.com/s/pv9onbl60cdz7m8/fixss_1_06.zip?raw=1)


## langsw v1.0 ##

плагин к fixss для n-gage classic, для быстрого переключения английского и русского языков по "комбинации карандаш + c". После установки обязательно перезагрузиться. 

[download 2.7 kB](http://sourceforge.net/projects/almalert/files/langsw/1.0/langsw_1_0.zip/download)
- alt [download 2.7 kB](https://www.dropbox.com/s/qi97xc9ntmuj0y3/langsw_1_0.zip?raw=1)


## fixqd ##

отключается часть механизма защиты, которая приводит к лагам телефона при большом колличестве игр и приложений на карте. для n-gage qd

[download 2.1 kB](http://sourceforge.net/projects/almalert/files/fixqd/0.666/fixqd_0_666.zip/download)
- alt [download 2.1 kB](https://www.dropbox.com/s/p85gyxmn2onep1r/fixqd_0_666.zip?raw=1)


## batmon v1.01 ##

![batmon](https://www.dropbox.com/s/m7ojl08rvi885tx/batmon.jpg?raw=1)

Мониторинг баттареи 

работает на:
• n-gage classic, прошивки 3.30 и 4.03;
• n-gage qd, прошивки 3.15, 4.00 и 4.10;
• 3650, прошивка 4.17.

очень предварительные результаты иследования энергопотребления n-gage classic:
• телефон со 100% подсветкой экрана и включённой подсветкой кнопок потребляет 190mAh.
далее подсветка кнопок была выключена:
• телефон со 100% подсветкой экрана потребляет 172mAh.
• телефон со 50% подсветкой экрана потребляет 116mAh.
• телефон со 13% подсветкой экрана потребляет 58mAh.
• телефон с выключенной подсветкой экрана потребляет 43mAh.
• телефон при работе стандартного скринсейвера потребляет 7mAh.
далее подсветка кнопок и дисплея была выключена:
• телефон при работе стандартного радио потребляет 100mAh.
• телефон при работе стандартного музыкального проигрывателя потребляет 125mAh.

выводы: nlights — дико полезная программа.


[download 11 kB](http://prdownloads.sourceforge.net/almalert/batmon_1_01.zip?download)
- alt [download 10.77 kB](https://www.dropbox.com/s/ql2fyfvmuvpl1e7/batmon.sis?raw=1)


## netmon v0.90 ##

![netmon](https://www.dropbox.com/s/0ifxboi71gqy8e0/netmon.jpg?raw=1)

обычный нетмонитор. функциональность:
1. информация о сети;
2. информация о текущей базовой станции;
3. информация о соседних базовых станций;
4. bts test;
5. изменение критерия выбора сот;
6. настройка dtx.

ченжлог относительно netmon 0.60:
• исправлен показ cellid как отрицательного числа;
• посылка flash sms;
• редактирование sms сервис центра на sim;
• редактирование собственного номера на sim;
• показ imsi.

совместимость: n-gage, qd, 3650.

[download 15 kB](http://prdownloads.sourceforge.net/almalert/netmon_0_90.zip?download)
- alt [download 15.26 kB](https://www.dropbox.com/s/rk253wr4d6l8pzr/netmon_0_90.sis?raw=1)


## MsvDriveE ##

![MsvDriveE](https://www.dropbox.com/s/pkorp3xd263pux2/MsvDriveE.jpg?raw=1)

Программка которая позволяет сохранять сообщения на карту памяти, для тех телефонов где это не предусмотрено.

[download 1.2 kB](https://www.dropbox.com/s/77hcom3c6ec30m5/MsvDriveE.sis?raw=1)


## EQ HashSilent ##

программа для аппаратов, в которых нельзя переключать беззвучный режим зажатием клавиши "#" (N-Gage).
Никаких настроек, никаких значков - установил и забыл. Потребление памяти минимально.

[download 6 kB](https://www.dropbox.com/s/lnsywg3vzg9u7sf/eqhashsilent.sis?raw=1)


## NLights v0.15 ##

![NLights](https://www.dropbox.com/s/woqgnhqdadp337m/nlights.jpg?raw=1)

NLights позволяет управлять подсветкой. 

[download 8.53 kB](https://www.dropbox.com/s/5qzvib54437uccg/nlights-0-15.sis?raw=1)


## HideMusic ##

![HideMusic](https://www.dropbox.com/s/v1xknd73cgf0g29/hidemusic.jpg?raw=1)

Программа которая помогает избавиться от долгого включения родного плеера на n-gage classic. hidemusic помогает выбрать только те папки, которые вы хотите прослушать, делая для плеера невидимыми остальные.

Папки с музыкой кладeте по пути E:\Music\ Треки по отдельности программа не видит! Только для на n-gage classic.

## Menu Speedup v1.3 ##

Утилита от BodyZ ставящая Меню в автозапуск. На N-Gage Classic меню запускается после прогрузки режима ожидания.

[download 4.47 kB](https://www.dropbox.com/s/7zhaqj2ustqz2vf/Menu_Speedup.sis?raw=1)