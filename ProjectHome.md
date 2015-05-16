

# ВЕРСИЯ 1.18 #

# Важно #

От 30.04.2014 до сега - СОФБУС 24 ОТНОВО РАБОТИ, като всички намерени от мен проблеми бяха отстранени. Възможно е да има още, тъй като тяхната система още не е дозиградена напълно и постоянно се променя.

# Описание #
Проектът е удобно и бързо за използване, многофункционално Android базирано приложение, посредством което потребителят да бъде постоянно информиран относно разписанието на градския транспорт в София. Приложението позволява на потребителя да бъде информиран във всеки един момент къде около него има спирки на Софийския градски транспорт и кои превозни средства може да използва, за да се придвижи в желаната от него посока. Също така в зависимост от текущото му местоположение, изчислено с помощта на вградения "Wi-Fi" или "GPS" приемник, програмата дава информация за най-близките спирки и колите на градския транспорт, които може да се използват, подробна информация за номера на автобусната, тролейбусната или трамвайната линия, посоката в която се движат, часовете на пристигане, както и разстоянието от текущото местоположение до спирката и не на последно място Google Maps карта която може да се използва, за да се достигне до желаната спирка.

# Нужда от съдействие #
Тъй като BGMaps вече не предоставят координатите на обектите от картата, информацията за сприките е вече малко поостаряла - моля помогнете като изпращате информация за грешни/липсващи спирки в София на email адреса ми - **_zdravko.nestorov@gmail.com_**. Ако имате информация за такива, изпратете ми номера на спирката и координатите й (виж тук http://dbsgeo.com/latlon/?Sofia). Благодаря предварително!

# Линк за сваляне #
Тъй като от Google Code забраниха добавянето на нови файлове в секцията [DOWNLOADS](http://code.google.com/p/sofbus24/downloads/list), новите версии на приложението засега ще бъдат налични само чрез Google Play - [Софбус 24](https://play.google.com/store/apps/details?id=bg.znestorov.sofbus24.main). За да свалите приложението сканирайте QR кода по долу с вашето Андроид устройство (линк към Google Play):
<br />
![https://sofbus24.googlecode.com/svn/Pictures/20.QR_Code.png](https://sofbus24.googlecode.com/svn/Pictures/20.QR_Code.png)

# Ръководство за работа #
Навигацията в съдържанието на приложението е изключително лесно, поради интуитивността на действията, които трябва да се предприемат. При затруднения може да посетите Wiki секцията - [Wiki Page](http://code.google.com/p/sofbus24/wiki/Manual).

# Версии на приложението #
| **Версия №** | **Качена от** | **Дата** | **Линк** | **Коментар** |
|:---------------------|:----------------------|:-------------|:-------------|:---------------------|
| 1.00 | Здравко Несторов | 01.11.2012 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Начална версия на приложението. |
| 1.10 | Здравко Несторов | 20.12.2012 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Възможност за търсене на часовете на пристигане в реално време по име или част от име на спирка, както и допълнителна функционалност в менюто **_РАЗПИСАНИЯ_**. |
| 1.11 | Здравко Несторов | 26.12.2012 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Поправяне на сериозен проблем в опцията **_ВИРТУАЛНИ ТАБЛА_**, появяващ се при съдържащ се номер на спирка в името на някоя друга. |
| 1.12 | Здравко Несторов | 29.12.2012 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Поправяне на сериозен проблем в БД. |
| 1.13 | Здравко Несторов | 17.02.2013 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Преправяне на начина на извличане на информацията, обновяване на базата данни с любимите спирки, добавяне на възможност за изчертаване на маршрут и добавяне на опция настройки. |
| 1.14 | Здравко Несторов | 17.02.2013 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Преправяне на основен бъг с базата данни с "Любими" спирки. |
| 1.15 | Здравко Несторов | 18.04.2013 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Добавяне на английски език и на различни потребителски настройки. |
| 1.16 | Здравко Несторов | 08.02.2014 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Добавяне на италиански и френски и преправяне на бъгове при обработването на инфорамцията |
| 1.17 | Здравко Несторов | 14.04.2014 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Интегриране с новата версия на сайта за градска мобилност (нов начин за извличане на информацията) |
| 1.18 | Здравко Несторов | 30.04.2014 | [Wiki Page](http://code.google.com/p/sofbus24/wiki/Versions) | Интегриране с новата версия на сайта за градска мобилност (нов начин за извличане на информацията) |

# Bug Fixes #
При откриването на каквито и да било проблеми, свържете се с мен на имейл адрес
**_zdravko.nestorov@gmail.com_** или напишете тикет в секцията [Issues](http://code.google.com/p/sofbus24/issues/entry). Моля предоставяйте пълна информация за възникналите грешки, като при възможност добавяйте снимки.

| **Номер** | **Проблем** | **Открито от** | **Решение** | **Версия** |
|:---------------|:-------------------|:------------------------|:-------------------|:-----------------|
| 1. | Проблем със записа в БД | Здравко Несторов | Преправен е достъпът до БД | 1.10 |
| 2. | Бъг в опцията **_РАЗПИСАНИЯ_** при някои Андроид устройства | "Google Play" потребител | Преправена е ориентацията на съответното activity. | 1.10 |
| 3. | Бъг в опцията **_ВИРТУАЛНИ ТАБЛА_**, появяващ се при съдържащ се номер на спирка в името на някоя друга | Kosivi Kosivi | Добавена е допълнителна проверка при извличането на данните за дадена спирка. | 1.11 |
| 4. | Проблем с извличането на информация от БД | Здравко Несторов | Преправен е начинът за достъп до БД. | 1.12 |
| 5. | Проблем с извличането на информация и добавянето в любими, появяващ се при съдържащ се номер на спирка в името на някоя друга | Angel Nikolov, Nikolai Grigorow | Преправен е начинът на извличането на информация и нейното обработване. | 1.14 |
| 6. | Разминавания на линиите на градския транспорт | Nikolai Grigorow | Обновен е списъкът с линиите на градския транспорт. | 1.14 |
| 7. | Проблем с добавяне в Любими | Angel Nikolov | Поправен е начинът на добавяне в Любими. | 1.15 |
| 8. | Проблем при затваряне на **_Loading..._** диалоговия прозорец | Здравко Несторов | Добавена е провека дали прозореца не е вече затворен. | 1.16 |
| 9. | Бъг при липса на мобилен интернет за локализация | g08refem618 | Добавена е проверка на наличните модули за локализация. | 1.16 |
| 10. | Проблем при **_Refresh_** и спирки, съдържащи в името си **_(_** и **_)_** | Dessislava Popova | Преправен е начинът на парсване на информацията. | 1.16 |
| 11. | Проблем при извличане на информация (проблем със сайта) | Rayko Belopitov и много други | Добавяне на допълнителни заявки към сървъра в зависимост от времевия интервал. | 1.16 |
| 12. | Проблем с извличането на информация след 00:00 | Здравко Несторов | Преправен е начинът за изчисляване на оставащото време след полунощ. | 1.16 |
| 13. | Проблем с извличането на информацията | Здравко Несторов | Преправена е цялият алгоритъм за извличане на информацията от сайта за градска мобилност. | 1.17 |
| 14. | Проблем с извличането на разписанията | Georgi Gaydov | Преправен е начинът за ограничаване на извлечената информация. | 1.18 |

# Съвместимост #
Приложението е съвместимо с всички Андроид устройства, използващи версия 1.6 (Android Donut) и нагоре, което го прави използваемо на над 99.99% от Андроид устройствата на пазара - [Версии на Андроид](http://developer.android.com/about/dashboards/index.html).

# Използвани технологии #
  * **Операционна система Android** (платформа на устройството);
  * **Език за програмиране JAVA** (за интегриране на използваните алгоритми програмно);
  * **XML Layouts** (за визуализиране на потребителския интерфейс);
  * **Dalvik Virtual Machine** (за компилиране на кода до разбираем от платформата);
  * **Среда за програмиране Eclipse** (многоезична среда за разработване на софтуер) - [Wiki Page](http://code.google.com/p/sofbus24/wiki/Development);
  * **SQLite** (за съхранение на информацията за спирките на градския транспорт);
  * **Google Maps** (за изобразяване на спирките върху картата);

# Снимки #
![https://sofbus24.googlecode.com/svn/Pictures/25.Start_screen.png](https://sofbus24.googlecode.com/svn/Pictures/25.Start_screen.png)
![https://sofbus24.googlecode.com/svn/Pictures/21.GPS_Stations_Choice.png](https://sofbus24.googlecode.com/svn/Pictures/21.GPS_Stations_Choice.png)
![https://sofbus24.googlecode.com/svn/Pictures/26.Virtual_Boards.png](https://sofbus24.googlecode.com/svn/Pictures/26.Virtual_Boards.png)
![https://sofbus24.googlecode.com/svn/Pictures/36.ClosestStationsList.png](https://sofbus24.googlecode.com/svn/Pictures/36.ClosestStationsList.png)
![https://sofbus24.googlecode.com/svn/Pictures/8.GPS-Map_Menu.jpg](https://sofbus24.googlecode.com/svn/Pictures/8.GPS-Map_Menu.jpg)
![https://sofbus24.googlecode.com/svn/Pictures/11.Search.png](https://sofbus24.googlecode.com/svn/Pictures/11.Search.png)
![https://sofbus24.googlecode.com/svn/Pictures/22.Stations_Cotext_Menu.png](https://sofbus24.googlecode.com/svn/Pictures/22.Stations_Cotext_Menu.png)
![https://sofbus24.googlecode.com/svn/Pictures/15.Show_on_map.png](https://sofbus24.googlecode.com/svn/Pictures/15.Show_on_map.png)
![https://sofbus24.googlecode.com/svn/Pictures/14.Route.jpg](https://sofbus24.googlecode.com/svn/Pictures/14.Route.jpg)
![https://sofbus24.googlecode.com/svn/Pictures/16.Favorites.jpg](https://sofbus24.googlecode.com/svn/Pictures/16.Favorites.jpg)
![https://sofbus24.googlecode.com/svn/Pictures/27.Options.png](https://sofbus24.googlecode.com/svn/Pictures/27.Options.png)

# Подобни приложения #
Разработеното приложение е взаимствало идеи от най-големите вече съществуващи такива. По долу са предоставени линкове към тях - [Wiki Page](http://code.google.com/p/sofbus24/wiki/OtherApplications?ts=1350506909&updated=OtherApplications):
### 1. Градски транспорт в София (от vanangelov) ###
  * [Линк към Google Play](https://play.google.com/store/apps/details?id=bg.angelov.sofiatransport&hl=bg)
  * Това е едно изключително „леко“ приложение, предоставящо информация за разписанието на превозните средства от Софийски градски транспорт. Има семпъл дизайн и удобен за работа интерфейс.
### 2. Софспирка (от Sirma Mobile) ###
  * [Официален сайт](http://sofspirka.sirma.mobi/)
  * [Линк към Google Play](https://play.google.com/store/apps/details?id=com.sirmamobile.busstops&feature=related_apps#?t=W251bGwsMSwyLDEwOSwiY29tLnNpcm1hbW9iaWxlLmJ1c3N0b3BzIl0)
  * Приложението е разработено от Софтуерната компания Сирма Мобайл, която е част от Сирма Груп Холдинг. Приложението „Софспирка“ дава възможност на потребителите на Android – базирани устройства да се информират по всяко време за местоположението на автобусните спирки, разстоянието и пътя до тях, както и след колко време пристигат автобуси, трамваи, тролейбуси и метро.
### 3. Sofia Public Transport Navigator (от Plamen Tanov) ###
  * [Официален сайт](https://code.google.com/p/sofia-public-transport-navigator/)
  * [Линк към Google Play](https://play.google.com/store/apps/details?id=eu.tanov.android.sptn&feature=also_installed#?t=W251bGwsMSwyLDEwNCwiZXUudGFub3YuYW5kcm9pZC5zcHRuIl0)
  * Помага на хората в София при избора на спирка на градски транспорт, на която да чакат. В реално време дава информация за приблизителния час на пристигане за избрана спирка. Данните се взимат от GPS системата на СКГТ и би трябвало да са максимално близки до реалността. Поддържат се времената на пристигане на автобусния, тролейбусния и трамвайния транспорт в София.
### 4. Droid Trans - градски транспорт (от Dro) ###
  * [Линк към Google Play](https://play.google.com/store/apps/details?id=com.ligla.droidtrans)
  * Това е едно изключително „леко“ приложение, предоставящо информация за разписанието на превозните средства от Софийски градски транспорт. Данните се вземат от сайта на Центъра за градска мобилност - http://m.sumc.bg/vt/. Няма нужда да се въвежда картинката с числата от сайта на градски транспорт (captcha кода), защото се декодира автоматично от програмата.