# Flying Bear Reborn2 FAQ & Wiki
Telegram RU-community Flying Bear Reborn2 3D-Printer wiki

wiki по первой модели (Flying Bear Reborn) находится [здесь](https://github.com/flyingbear-reborn/wiki)

Все [ждут](https://t.me/fbg5_waiters) поставку принтеров, пока (на 04.09.2022) их получили считанные единицы людей, информации мало.

Собираем всю инфу подряд, что может помочь.

----
Что уже известно про Reborn2.

[Официальный сайт](https://3dflyingbear.com/products/flying-bear-reborn-2-3d-printer)

* Распиновка соответствует плате Robin Nano v.3
* Тип температурного датчика pt1000 4.7кОм;
* Тип температурного датчика на столе 100кОм EPCOS;
* Стоковые шаги 160,160,800,420;
* Тип экрана в прошивке: mks_ts35_v2_0

[Первые фото принтера от участников чата](https://t.me/fbg5_waiters/121716)

[Размер до крепежных болтов на штатном столе](https://t.me/fbg5_waiters/106563)

[Стоковая голова](https://t.me/fbg5_waiters/123310)

[Горло на стоковой голове](https://t.me/fbg5_waiters/123349)

[длина радиатора](https://t.me/fbg5_waiters/123378)

----
#### Список полезного с AliExpress, Я.Маркет, Озон и других интернет-площадок:

[Клей лак для 3D печати](https://aliexpress.ru/item/1005002056065320.html)

Растворитель Дихлорметан (Метилен хлористый) 1 литр (1,3 кг) [раз](https://market.yandex.ru/product--dikhlormetan-khloristyi-metilen-99-9-1-litr/2000452799897) и [два](https://market.yandex.ru/product--metilen-khloristyi-dikhlormetan-metallicheskaia-banka-1-l/1468091199)

[Лента светодиодная адресная](https://aliexpress.ru/item/1005002605903154.html) - какую именно брать?

[понижайка с 24 до 5 вольт](https://aliexpress.ru/item/1005003761299868.html) - 5 ампер (25W) хватит же для питания светодиодов? Можно также запитать малинку или апельсинку, если планируете ставить Klipper, но есть одно "но". Одноплатник будет отключаться вместе с принтером. Чаще всего это не то, что хочется, поэтому для малинки нужен отдельный блок питания.

[проводочки все соединить](https://aliexpress.ru/item/1005002509747445.html)

[инструмент для проводочков](https://aliexpress.ru/item/32898220840.html)

[Вентиляторы 4010](https://aliexpress.ru/item/32798634077.html) - если менять, то на какой именно? напряжение, подшипник/гидравлика, RPM?

[акселерометр ADXL345 для клиппера](https://aliexpress.ru/item/1005001621867550.html)

[гаечки вплавляемые](https://aliexpress.ru/item/1005002288716120.html)

[болтики м3 на замену штатных](https://aliexpress.ru/item/1005002109863123.html)

[апельсинка она же orange pi 3 lts](https://aliexpress.ru/item/1005003577312703.html)

[умная розетка чтобы удаленно отключать принтер или по событию](https://aliexpress.ru/item/1005003640070178.html)

[сушилка для пластика](https://aliexpress.ru/item/1005003818855727.html)

[абс пластик](https://aliexpress.ru/item/32964875934.html)

[пла пластик](https://aliexpress.ru/item/1005004270970940.html)

[Клей для пластика Дихлорэтан](https://aliexpress.ru/item/1005002160390868.html)

[ABS стеклонаполненный пластик](https://rec3d.ru/plastik-dlya-3d-printerov/eksperimentalnye-materialy/abs-steklo-plastik-rec-1-75-natyralniy/)

[Рукав для кабеля](https://aliexpress.ru/item/4001224829191.html)

#### Прошивки, клиппер, марлин и все такое прочее
[Reborn2_v0.1 default - штатная прошивка из архива медведей](https://t.me/fbg5_waiters/115178) - оставлена для истории, не стоит ее использовать на практике! + [архив](https://t.me/fbg5_waiters/115181)

[Исправленная прошивка V5](https://t.me/fbg5_waiters/125515)

[Дистриб линукса для клиппера](https://redirect.armbian.com/region/EU/orangepi3-lts/Bullseye_current)

[Установка Kilpper](https://youtu.be/-0fHoq7IlHA) - там ошибка в видео, c USART3 нужно собирать P10/11.

[Полный видеогайд по установке клиппера (18 роликов)](https://www.youtube.com/watch?v=gfZ9Lbyh8qU&list=PL7zrGeKp_8CRmVTuBaUQcHKlS9bJRU6vT)

[После момента с установкой клиппера и флуида видео закрывается.](https://t.me/fbg5_waiters/116626) - тут еще много деталей, что делать дальше.

[И еще один краткий гайд по установке Клиппера](https://t.me/fbg5_waiters/127352)

Первые конфиги клиппера [раз](https://t.me/fbg5_waiters/123268), [два](https://t.me/fbg5_waiters/128133)

[Как подключать Orange Pi к принтеру (на примере Ghost5?)](https://t.me/fbg5_waiters/116547) и [еще](https://t.me/fbg5_waiters/116593)

[Как рассчитать K-фактор для LA](https://marlinfw.org/tools/lin_advance/k-factor.html)

[Альтернативаная калибровка Linear Advance (LA)](https://youtu.be/p9IKwwKTIFM)

[Как настроить timlapse в Клиппере](https://www.youtube.com/watch?v=n-BVPidUDLI&ab_channel=Vez3D)

[Подбор параметров в Cura и Prusaslicer](https://www.youtube.com/watch?v=Tu-ropzwhco&t=3711s) - стрим K3D

[Калькулятор тока драйверов шаговых двигателей](https://3drob.ru/stati/pro_3d_pechat/elektronika_3d_printera/kalkulyator_toka_drayverov_shagovyh_dvigateley). Для нашего принтера пока не известны опорные напряжения, китайцы не дают даташит на моторы.

#### Апгрейды
[Доработка блока питания (уменьшаем шум)](https://www.youtube.com/watch?v=wAFuxwjFUGo&ab_channel=DenisDrugov) - пока никто не проверял, пойдет ли такой вариант для Reborn2

[Как поменять драйвер - общая теория и практика](https://youtu.be/MQE7OZ34_eE)

#### Разные модельки из чата

[Калибровочный кубик](https://www.thingiverse.com/thing:1278865)

[Болты %)](https://www.thingiverse.com/thing:5445157)

[Индикатор натяжения ремня](https://t.me/fbg5_waiters/120487) - важно не где риски, а чтобы оба ремня показывали одинаковые значения + [еще один](https://www.thingiverse.com/thing:5467334) и + [еще один](https://www.thingiverse.com/thing:2230598/files) - пружинка от ручки с диаметром стержня 4.2мм

[Корпус на Orange PI 3 LTS](https://t.me/fbg5_waiters/121929)

[Кронштейн для камеры Logitech C270](https://t.me/fbg5_waiters/123793)

[Модель дракончика](https://t.me/fbg5_waiters/116379)

[Органайзер и переноска из катушки для пластика](https://t.me/fbg5_waiters/117937)

[гирлянда гайвера](https://t.me/fbg5_waiters/119923)

[Держатель филамента](https://t.me/fbg5_waiters/121630)

[Сушилка для филамента](https://www.thingiverse.com/thing:5247416)

[Канал в телеге с моделями (фигурки, аниме...)](https://t.me/STLcompilation)
