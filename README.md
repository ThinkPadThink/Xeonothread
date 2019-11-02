# Гайд по сокету 2011-3

*Он же 2011v3/2011в3*
  ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Xeon%20guide.png?raw=true)
  
*Специально для Зионотреда на борде 2ch.hk/hw*

*Для написания этого гайда использовался [фактически мой старый гайд](http://xeonowiki.wikidot.com/lga2011-3) и [информация анона]( https://pastebin.com/NJFQVgE4) и другие источники.*

*__При копировании информации обязательно указывайте оригинальный источник.__* 

*Если у вас есть что добавить можете воспользоваться __Pull Request__  и я это тогда добавлю в гайд. Хуйцы и прочее я конечно же добавлять не буду.*

*По неизвестным причинам блокировщики рекламы блокируют некоторые картинки в данном гайде. Отключайте их если хотите увидеть их.*

## Оглавление:

*Будет сделано позже.*


# Материнские платы

Для этого сокета родными являются только два чипсета под кодовым именем Wellsburg это Десктопный HEDT X99 и серверный C612. 

##  Брендовые десктопные платы:
**ASUS:** Одни из лучших материнских плат для этого сокета. Отличный питальник даже на дешёвых платах. Съёменая флешка BIOS и возможность прошить BIOS при выключенном пк на платах подороже [ASUS USB BIOS Flashback](https://www.asus.com/ru/support/FAQ/114133/) . Наличие OC сокета  с доп питанием позоляющего лучше гнать цпу. 

**Из минусов:** 
1. Анон будь с ним осторожен при разгоне Broadwell-E i7 6800k/6850k/6900k/65950x ибо при неправильном разгоне со временем выгорает контроллер памяти в ЦПУ.
2. E5 V4 ES не работают. Циклический ребут. POST не проходит.

**ASROCK:** Идут после Асуса по качеству и взоможностям. Питальник похуже чем у ASUS но всё равно всё хорошо. Брать тоже можно. Единственный вендор который выпустил mITX платы под 2011-3. Так же у некоторых плат присутсвует аналог Асусовского OC Socket, например на: ASRock X99 OC Formula/3.1, и других.

**GIGABYTE-AORUS:** Многие платы rev 1.0 имеют проблемы которые либо пофиксили новыми версиями BIOS либо же выпуском новой ревизии. E5 V4 ES не работают. Циклический ребут. POST не проходит. Так же есть проблемы с запуском E5 4600 V3

**MSI:** Имеют проблемы с запуском инженерников v3 с памятью с частотой которая выше 2133. Возможно только ES и QS. *Так же не поддерживают E5 4600 V3.* 

**EVGA:** Вроде как проблем нет, кроме FTW-K у которой могут быть проблемы c V4 ES. На некоторых платах возможно присутствует OC Socket.

**SUPERMICRO-SUPERO:** Ничего не известно в СНГ фактически не встречаются, ну разве что пару раз были в Московском регарде. Продавались под именем **SUPERO** 

## Брендовые серверные платы

**ASUS:** Не самое хорошее качество плат. Есть проблемы с BIOS и с качеством плат, но и при этом есть 2 платы которые лучше всего подходят для разблокировки турбобуста на 2 ЦПУ(Дуалсокетные): ASUS Z10PE-D16 WS/ASUS Z10PE-D8 WS. Есть проблемы с работой E5 V4 ES ~~но их можно запустить в отличие от десктопных плат.~~

**ASROCK:** В СНГ не особо распространены, кроме есть дуалсокетные платы с DDR3 памятью. 

**GIGABYTE, MSI:** В СНГ не встречаются. Поэтому никакой информации нет.

**TYAN:** Хорошие серверные платы, ничего лично не знаю. 

**Intel:** Хорошие серверные платы, но зная Intel возможно платных функций. Другого не знаю. 

**SUPERMICRO:** Очень хорошие серверные платы, но для анлока турбобуста не рекомендуются из-за скудного питальника плат и его охлада. Под сборку сервера отлично подходят из-за того что не имеют проблем с инженерными образцами(ES)  v3/v4. 

## Китайплаты:

Полноценной информации нет но как смогу накину тут:
 
 **HUANANZHI X99-AD3:** Плата с чипсетом X99/C612 и **ВНИМАНИЕ с DDR3 памятью. Работает данная плата только с определёнными процессорами E5 v3. А именно: E5-2678v3, E5-2629v3, E5-2649v3, E5-2669v3, E5-2686v3, E5-2696v3**. На деле оказывается не только: [Оверклокерсы](https://forums.overclockers.ru/viewtopic.php?p=16140360#p16140360) Цитата: *Дошли руки собрал в корпус, установили винду на обычный сата ссд, все стало отлично. NVMe так и не смог увидеть ни в биосе не в винде. Сфоткал скрин аиды, показывает проц 2658, хотя покупал 2673,они похожи очень, может Аида путает хз.* 
 
 Есть информация что корейцы смогли завести на ней турбобуст: [Оверклокерс](https://forums.overclockers.ru/viewtopic.php?p=16321683&sid=b13f1d8102b3f7d8d8cc82d187eafe21#p16321683). Да, завезли [Форум Anandtech](https://forums.anandtech.com/threads/what-controls-turbo-core-in-xeons.2496647/page-111#post-39871817) Модбиос и оригинальный [тут](https://github.com/ThinkPadThink/Guide2011-3/blob/master/HuananX99-AD3_BIOS.zip)
 
 *Примечание:* По неизвестным причинам фото материнкой платы блокируется блокировщиками рекламы. Фото можно просмотреть [тут](https://github.com/ThinkPadThink/Guide2011-3/blob/master/X99_AD3.jpg?raw=true)
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/X99_AD3.jpg?raw=true)
 
 **Running X99 aka Vulcan X99 v1.2:** Плата с чипсетом X99/C612 и DDR4 памятью. Есть несколько вариантов, с радиатором и без. И разной разцветки. **По некоторым данных плата не работает с Xeon E5 V4** но это не точно.
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/RUNING-X991.jpg?raw=true)
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/RUNING-X992.jpg?raw=true)
 
 **HUANANZHI X99-8M:** Плата с чипсетом X99 и DDR4 памятью. Существуют разные варианты разцветки. *Имхо: Безсмысленный огрызок с 2 каналами, не нужен.* Обзор от YouTube канала [Купи дёшево](https://www.youtube.com/watch?v=EbipSmxaeB4)
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/X99-8M1.jpg?raw=true)
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/X99-8M2.jpg?raw=true)
 
 **PlexHD X99 aka ZX_99EV3_V1.21:** Плата с X99/C612 чипсетом. Звук: Realtek ALC662, Сеть REALTEK 8106E/8111. **ВНИМАНИЕ:** на стоковом UEFI/BIOS разгона нет, возможно позднее допилят его как было с 2011 сокетом в своё время.
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/PlexHdnoname.jpg?raw=true)
 
 **NONAME aka Jingsha X99 aka X99 v10Y:** Новая плата с X99/C612 чипсетом и **ВНИМАНИЕ DDR3 памятью. Работает данная плата только с определёнными процессорами E5 v3.** Звук: ALC898, Сеть Realtek. 
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Jingsha_x99_1.jpg_.png?raw=true)
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Jingsha_x99_2.png?raw=true)
 
 **HUANANZHI X99-TF aka G368J ver 1.1** Новая плата с чипсетом C612/X99. 4 слота DDR3 и 4 слота DDR4. Вместе память работать не будет. Плата достаточно добротна по дизайну и наполненности. Подробное описание ниже. Обзор от YouTube канала [Ремонтяш Лайв](https://www.youtube.com/watch?v=BERU3L_rOLo)
  ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/x99-tf.jpg?raw=true)
  ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/15668531847240.jpg?raw=true)
  ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/15668529667151.jpg?raw=true)
 
 **HUANANZHI X99 NONAME:** Пока ничего не известно. Просто мыльная плата. Возможно не существует в природе. 
 ![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/noname_mylo.jpg?raw=true)
 
 По другим платам от китайцев пока ничего не известно.
 
 ## Платы от именитых производителей серверов/рабочих станций:
 
 Это HP/HPE, Dell, Lenovo/IBM, Cisco, Fujitsu и подобные. У этих плат 100% проприетраные фронт панели, подключение вентиляторов, блока питания. Возможен вайтлист на оперативную память и накопители, велика вероятность проприетарного форм-фактора плат и крепления охлаждения цпу. Да и разблокировки турбобуста на этих платах маловероятно что получится сделать из-за другого UEFI/BIOS.
 
 **Hewlett Packard Enterprise/HP/HPE**
 
 Отдельно отмечу пердолинг с платой HP без прочего обвеса, возможно для кого-то это пригодится [Украинский овеклокерс](https://forum.overclockers.ua/viewtopic.php?f=3&t=218885)
 
 
# Оперативная память
 
 Подходит любая DDR4 память. У E5 26xx V3 память не гонится т.е. предел для E5 V3 - 2133 и у E5 V4 - 2400. Но разве что чуть-чуть накинуть по шине, но можно снизить тайминги. Если же у вас 1650v3, 1660v3, 1680v3 то тогда возможно стоит обратить внимание на ту память которая разгоняется. 
- Примечание: Подтверждено что на 2011-3 десктопных платах от ASUS и ASROCK есть поддержка ECC REG памяти, возможно и на других платах серверная память работает. Так же подтверждено что i7 Haswell-EP i7 5820k, 5930k, 5960x работают с ECC REG памятью. Возможно и на Broadwell-E i7 серверная память работает. А так же у младших цпу, например E5 2630 v3 частота памяти будет 1866.
 
 
 # Процессоры:
 
Предисловие: 

Для 2011-3 было выпущено два поколения цпу. Haswell-E/EP E5 V3 и Broadwell-E/EP E5 V4. [Про различия в архитектуре можно прочитать на 3DNews](https://3dnews.ru/933795).

Разблокирование турбобуста на все ядра возможно только на процессорах Haswell-E/EP E5 V3.

Существуют 5 видов степпингов процессоров линейки Haswell-E/EP E5 V3:
1. A0 ES0 пример QDCU 2695v3 - обходить стороной ибо самый ранний степпинг, глючный;
2. B0 ES1 пример Q8YG(QFGH) 2695v3, QEYG 2650v3 - так же рекомендуется обходить стороной;
3. L0 ES2 пример QEY6 2695v3, QEYN 2650v3, QF18 2630v3, QEYP 2658v3 - можно рекомендовать к покупке если они очень дешёвые. Турбобуст на них нельзя разблокировать;
4. M0/C0 Pre-QS пример QG7R 2695v3, QG7U 2696v3, QFQK 2683v3 - можно покупать. Турбобуст на них можно разблокировать;
5. M1/C1/R2 - QS/OEM-RETAIL пример QGN4 2695v3, QGN7 2696v3, QGN5 2683v3 - 100% можно покупать, фактически это тот же степпинг который продаётся в магазинах, поставляется по OEM каналам производителям оборудования(серверов, рабочих станций). Турбобуст на них можно разблокировать.

Отдельным моментом отмечу то что младшие E5 V3 работают с памятью с частотой 1866 или 1600 это их ограничение. Так же отмечу про E5 V3 4S это цпу которые так же могут работать с памятью с частотой ниже 2133 (Модели ниже E5 4650 V3) и имеют более низкий турбобуст множитель. Такие CPU проще всего определить в HWInfo64. 

Для Broadwell-E/EP E5 V4 существуют 2 вида степпингов процессоров:

ES0 и QS-OEM-RETAIL. Брать особого смысла нет. Если только конечно не топ варианты с 18-22 ядрами. 

Замечу сразу несколько вещей:
- У младших процессоров межпроцессорная шина QPI имеет более низкую пропускную способность что может сказаться на производительности, но это актуально только для двухсокетных систем.
- У младших цпу, например E5 2630 v3 частота памяти будет 1866.
- При сборке двухпроцессорных систем подбирайте одинаковые ЦПУ, причём с одинаковым степпингом. E5 1600 v3/v4 не подойдут, они не работают в двухпроцессорных конфигураций. 

Ниже находятся таблица со списком существующих финальных Xeon E5 V3.

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Haswelll-EP.png?raw=true)

*По некоторым данным разгон цпу по множителю и разгон памяти возможен только у 1650v3, 1660v3, 1680v3* и понятное дело линейке i7 (5820K, 5930K, 5960X).

*Не стоит ориентироваться на цены указанные в таблице, они не соответствуют действительности*

И таблица со списком существующих финальных Xeon E5 V4. 

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Broadwell-EP.png?raw=true)

*По некоторым данным E5 16XX V4 только ES можно разгонять. Финальные степпинги не гонятся. Ну и понятноен дело линейка i7(6800K, 6850K, 6900K, 6950X)*
*Не стоит ориентироваться на цены указанные в таблице, они не соответствуют действительности*

*Найдено на просторах VK*

С примерным списком инженерных образцов E5 V3 (Haswell-EP) можно ознакомиться тут [xeon-e5450.ru](https://xeon-e5450.ru/socket-2011-3/e5-2600-v3/es-qs-list/) и тут [cpu-world.com](http://www.cpu-world.com/CPUs/Xeon/index.html) 

 # Охлаждение: 
 
Тут всё стандартно, подходят обычные башни с сокета 2011 или нового 2066. У этих сокетов (2011, 2011-3, 2066) одинаковое крепление кулера. Либо же можно использовать кольцо с переходником от AMD сокетов. Но будь осторожен анон, в случае с серверными платами есть подвох в виде двух видов креплений под сокет 2011. Под сокеты 2011-е существуют два типа крепления (не считая проприетарные) Square и Narrow.
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/LGA2011Cooler.jpg?raw=true)

Первый тип встречается в 99% материнок, а Narrow часто встречается только в серверных платах. Часто в двухсокетных платах может быть Square крепление но не все башни получится поставить ибо они могут тупо не встать из-за их размера.

Ещё стоит отметить одну вещь. При монтаже материнской платы рекомендую осмотреть крепление кулеров Square/Narrow не важно. Существует несколько вариантов крепления. И некоторые из них не очень хорошие. Те отверстия куда вкручиваются m4 винты может соприкасаться с pcb платы и тем самым можно спокойно её повредить. Поэтому рекомендую при сборке проверить какого типа у вас крепление. У некоторых производителей типа ASUS в местах где находятся отверстия для крепления имеют вырезы в pcb платы. А у некоторых как у ASROCK такого нет. 

Отдельным моментом стоит отметить в случае разблокировки турбобуста на все ядра процессора стоит озаботиться охлаждением VRM зоны материнской платы, особенно если это многоядерный и высокочастотный ЦПУ. Иначе есть риск спалить материнскую плату. 


# Покупка:

Существуют много площадок где можно приобрести Xeon Haswell-EP. Авито - не советую из-за завышенных цен у барыг в 95% случаев. Банальный пример: E5 2696 v3 стоит ~ 47000 рублей и это в ДС. AliExpress - фактически тоже самое, даже дороже ~ 50000 рублей. Оптимальный вариант для покупки это Ebay. На данный момент (Июнь 2019 года) Американский Ebay. [Как покупать на Американском Ebay подробно расписал анон и я в своё время для ThinkPad Thread](https://github.com/pepe-i-shim/thinkpad-from-ebay) 

**UPD:** На ~ноябрь 2019 есть вкусные цены на Ali например на 1650 v3, 2640 v3, 2678 v3.
 
Если коротко то регистрируешься на Ebay, регистрируешься на PayPal+подтверждаешь свою учётную запись+привязывешь банковскую карту к PayPal и выбираешь регистрируешь учётку у посредника. Затем в качестве основного адреса для доставки указываешь адрес посредника. Всё!

**Внимание:** При выборе цпу желательно чтобы продавец прикладывал скриншот с CPU-Z, а лучше HWInfo64 ибо они сразу показывают какой это именно цпу инженерник или нет и его степпинг SSpec/QDF. На крышки не ориентируйтесь! Китайцы умеют затирать инфолрмацию и наносить гравировку нужного ЦПУ. Так же скриншот HWINFO нужен для точного знания значения турбобуста, а также уточнения, что продавец не наебывает пытаясь продать 4S 46xx v3 (в Codename будет написано Haswell-EP 4S) вместо 26хх v3. 

# Оптимальный выбор:

**Этот раздел пока не дописан и больше является сугубо моим личным мнением.**

ES2 и прочие не советую к покупке ибо они не особо актуальны. Да и если вы будете менять цпу то инженерник можно будет пустить только на брелок. Да и турбобуст на них нельзя выставить на все ядра.

Оптимально я считаю нормальным вариантом покупку многоядерника  M1/C1/R2 - QS/OEM-RETAIL степпингов с 12-18 ядрами и разблокировка турбобуста на все ядра. Примерно с моделей E5 2680 v3 и выше. Либо же E5 1650 v3 и другие цпу E5 16** v3  серии. Для охлада стоит смотреть мостроподобные башни типо Thermalright Macho Rev.A/B, Noctua NH-D15/D14, be quiet! DARK ROCK PRO 4 и подобные. Ну либо же водянка если вы сантехник. Да и не забудте про охлаждение VRM.

### Примеры сборок от анонов с треда:

1 Вариант:
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Sborka_V1.jpg?raw=true)

2 Вариант:
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Sborka_V2.jpg?raw=true)

# Производительнось:
 
## Xeon E5 2696v3 без разблокировки TurboBoost на все ядра

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/memcache2696v31.jpg?raw=true)

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/cpuz2696v3.png?raw=true)

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/cinebenchr20%202696v3.png?raw=true)

Примечание: *косячный ASUSовский UEFI/BIOS+Windows 10 из-за чего все ядра работают всегда на частоте 2.8Ghz и в однопотоке CPU не может выйти в турбобуст (3.8) на 1 ядро, а так же тест памяти может быть из-за неоптимального количества планок озу, 6 штук*

*Позднее данный раздел будет вынесен отдельно дабы не засорять гайд всеми тестами-не-тестами*

# Некоторые фишки которые сверху не влезут:

## Как выглядят Xeon Haswell-E/EP и Broadwell-E/EP

Haswell-E/EP:
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/intel-xeon-e5-2699-v3.jpg?raw=true)
Broadwell-E/EP:
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/2699v4.jpg?raw=true)

## Конфигурация ядер Haswell-EP и Broadwell-EP

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Haswell-ep_dieconf.png?raw=true)

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/Broadwell-ep_dieconfpng.png?raw=true)

## Как отличить ES от QS и от Финальника?

Самое главное не смотреть на крышку. Китайцы перенаносят гравировку и продают ES как финальники.
Очень легко это делать через CPU-Z и HWInfo64

Как отображаются ES0/1/2 в CPU-Z и HWInfo64:

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/e5v3escpuz.jpg?raw=true)
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/e5v3eshwinfo.jpg?raw=true)

Как отображаются QS/Pre-QS в CPU-Z и HWInfo64: Иногда в HWInfo64 пишет сразу финальный степпинг заместо QS. С Pre-QS такого я не встречал.

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/2686v3qs.png?raw=true)
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/2699V3qscpuz.jpg?raw=true)

Как отображаются RETAIL/OEM CPU в CPU-Z и HWInfo64:

![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/2696v3final.png?raw=true)

## Про ASUS OC Socket LGA2011-3

Прямая цитата с [3DNews](https://3dnews.ru/901435): А вот что практически невероятно, так это то, что процессорный разъём LGA2011-v3, используемый ASUS, отличается от разъёмов, которые применяются в платах других производителей для тех же процессоров Haswell-E. Разъём, уникален тем, что обладает не 2011 контактами, а на несколько десятков большим их количеством. И самое интересное, что все эти дополнительные контакты действительно используются. Дело в том, что процессоры Haswell-E изначально имеют большее число контактных площадок, чем их предусмотрено в разъёме стандартного дизайна, и часть площадок должна оставаться неподключённой. Предполагается, что такие площадки предназначаются исключительно для целей тестирования процессоров при их производстве. Однако инженеры ASUS обнаружили, что некоторые недокументированные процессорные выводы просто заведены на линии питания, чем они и решили воспользоваться. Практические испытания подтвердили, что подача на процессор питания по большему числу проводников не только увеличивает максимально допустимую электрическую мощность, но и улучшает «чистоту» и постоянство напряжений при высокой нагрузке на процессор. В результате было решено внедрить технологию в серийных продуктах.

## Сравнение родных чипсетов для сокета 2011-3:
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/x99_1.png?raw=true)
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/x99_2.png?raw=true)
![](https://github.com/ThinkPadThink/Guide2011-3/blob/master/x99_3.png?raw=true)

## Код для IPMI на материнских плат SuperMicro:

Предисловие: У многих серверных материнских плат есть встроенный IPMI для удалённого управление системой(конфигурация UEFI/BIOS, установка ОС и т.д.) Но многие бонусы данной функции по умолчанию заблокированы, например обновление UEFI/BIOS. Производители требуют специальные коды для разблокировки всех функций IPMI.

SuperMicro не исключение. [Но это можно обойти](https://dotnetfiddle.net/87E5Xm). Где нужно вводите MAC адресс IPMI и запускаете. В ответ получите Нужный ключ. Проверено на X8, X9, X10, X11 сериях SUPERMICRO.

# РАЗБЛОКИРОВКА ТУРБОБУСТА ДЛЯ XEON E5 V3:
Гайд будет написан позже. Ибо пока нет в наличии ЦПУ с которым это можно провернуть.
Но пока будут ссылки: 
- https://greentechreviews.ru/2017/03/14/instrukciya-po-uvelicheniyu-taktovoj-chastoty-v-boost-dlya-processorov-intel-xeon-e5-v3/
- https://goo.gl/CHSBKV

Полный гайд со всем софтом можно найти в архиве по ссылке из этого [поста](https://forums.anandtech.com/threads/what-controls-turbo-core-in-xeons.2496647/page-10#post-38755809). Так же, для того, чтобы обойти ошибку "Error in Replacing File" при замене микрокодов биоса с помощью UBU - необходимо ознакомиться с этим [постом](http://www.win-raid.com/t18f16-Guide-Manual-AMI-UEFI-BIOS-Modding-4.html#msg21755)

Можете так же обращаться в VK в группу [TheSellHard](https://vk.com/thesellhard), там народ может помочь с биосом, либо сразу найдите биос под свою мамку в [этой теме](https://vk.com/topic-70826500_34866008)

# Ссылки: 
- [ARK Intel - информация по Финальным ЦПУ Интела](https://ark.intel.com/content/www/ru/ru/ark.html);
- [CPU World - огромная база данных по ЦПУ, есть и информация по инженерным образцам и ОЕМ ](http://www.cpu-world.com);
- [Гайд о покупку железа и не только на Американском Ebay](https://github.com/pepe-i-shim/thinkpad-from-ebay);
- [SUPERMICRO IPMI CODE](https://dotnetfiddle.net/87E5Xm).
