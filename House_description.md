## Заявка на строительство дома

### Описание комнат

#### Начало стройки

Строительство начинается в зоне "Пригород долины титанов", в комнате "Тропинка к морю", VNUM 18198

```
redit
south dig next
done
south
```

#### Причал в долине

На юге от тропинки к морю, на побережье комната с названием "Причал в долине"

```
redit
name web
Причал в долине
Save

desc web
Ты попадаешь на берег моря. Деревянный причал поскрипывает под накатывающимися
волнами. Захватывающая панорама моря расстилается до горизонта. Солнце пытается 
утонуть в волнах, сияя тебе прощальными лучами. В лицо дует свежий ветер, 
принося прохладу, после долгого, знойного дня. В дымке едва виднеется 
далекий остров и маяк над ним. 
У причала стоит старенький баркас, готовый взять тебя в путешествие по 
бушующим волнам. Капитан, старый морской волк, стоит на мостике и курит трубку, 
вглядываясь в морскую даль. 
Капитан обращает свое лицо к тебе и советует поторапливаться и побыстрее 
подниматься на борт, приближается шторм и баркас вот-вот отчаливает. 
Надо успеть доплыть до острова, пока море не стало слишком бурным.
Save

flags dark near_water
sector forest
liquid salt water

south dig next
done

south
```

#### На баркасе

На юге от причала комната с названием "На баркасе"

```
redit
name web
На баркасе
Save

desc web
Ты стоишь на палубе большого баркаса посреди бушующего моря. С одной стороны 
виден берег, бушующие волны разбиваются о прибрежные скалы, поднимая тучи 
брызг и наполняя воздух запахом свежести и соленой морской воды. 
Неподалеку в море впадает широкая река. Вдоль ее брега расположилась рыбацкая 
деревня. Справа, на побережье виднеется красивый уединенный дом. Баркас плывет 
по морю, в сопровождении стаи чаек, кружащих неподалеку. 
Крики чаек и шум волн зовут окунуться в новые приключения. В море виднеется 
необычайно красивый остров с причалом. Над островом возвышается путеводный 
маяк, даруя надежду всем заблудшим и призывая моряков поскорее вернуться домой 
из дальних странствий. Остров покрыт зеленью, среди деревьев виднеется несколько 
строений. Берега манят уединенными пляжами с белоснежным песком.
Save

sector inside
liquid salt water

south dig next
done

south
```

#### Причал на острове

На юге от баркаса комната с названием "Причал на острове"

```
redit
name web
Причал на острове
Save

desc web
Ты стоишь на причале сложенном, из крупных обломков окружающих скал. Причал 
расположен в небольшой бухте, которую окружают две высокие скалы, как будто два 
часовых на посту охраняют остров от непрошенных гостей. 
Одна скала напоминает очертаниями огромного кентавра, другая человека.
Вверх, от причала, уводит неширокая дорога, петляющая по склонам. В конце дороги 
виднеется маяк, лучи которого освещают окружающее пространство таинственным 
{Yзо{Wл{Yот{yист{Yым{x светом. Окружающее море не спокойно. Волны разбивается 
о каменных стражей, а внутри бухты ровная зеркальная гладь воды. Берега усыпаны 
{Wбело{Cс{Wнежным{x песком, под водой ты замечаешь множество рыб и красивые кораллы.
Save

flags near_water
sector mountain
liquid salt water

up dig next
done

up
```

#### Вверх к маяку

На верх от причала на острове комната с названием "Вверх к маяку"

```
redit
name web
{gВв{Gе{gрх к {Gм{gаяку{x
Save

desc web
Дорога от причала поднимается вверх, петляя по склонам. Вдоль дороги 
встречаются красиывые лужайки, усыпанные цветами и травами, их сменяют 
пальмовые рощи из финиковых и кокосовых пальм. Кое-где встречаются стройные 
{gкип{Gа{gри{Gс{gы{x и невысокие раскидистые {gсо{Gс{gны{x, застывшие в экзотическом 
танце. Вдоль дороги вьется небольшой, быстрый {cру{Cч{cей{x. Вода в ручье очень 
холодная и кристально чистая. Ручей вытекает из-под скалы и несет свои воды 
к морю, обрываясь высоким водопадом. Брызги воды играют на солнце, образуя сразу 
несколько {Yр{Gа{Cд{Bу{Mг{x. Берега ручья усыпаны цветами {Mв{mе{Mр{mе{Mс{mк{Mа{x.
Save

sector mountain

south dig next
done

south
```

#### Лужайка - перед маяком

На юге от вверх к маяку комната "Лужайка - перед маяком"

Это комната для перемещения по команде дом.

```
redit
name web
{YЛу{yжай{Wк{yа - пер{Yед м{Wа{yяком{x
Save

desc web
Ты стоишь на лужайке перед маяком. Замля укрыта густой травой, то там, то 
тут яркими огоньками на ней вспыхивают солнечно-желтые цветы {Yо{yд{Wу{Yван{yчи{Yков{x. 
С одной стороны дорога упирается в высокую бело-каменную стену. 
Единственный проход за стену - прочная деревянная дверь, запертая на ключ. 
На двери прикреплена {Wтабличка{x (tablet).
За стеной возвышается громада маяка. Каменные стены, выкрашенные в белый и 
красный цвета, образуют высокую башню, увенчанную куполом, под которым 
расположено помещение с окнами на все стороны. Оттуда бьют лучи яркого 
золотистого цвета. 
На западе дорогу преграждают очень густой и колючий кустарник, через который 
не пробраться. За стену кустарника ведет запертая металлическая калитка, 
увешанная {Yб{yу{Yбе{yн{Yц{Wа{Yми{x.
Save

ed web tablet
Табличка гласит - {RОсторожно! {WЗлая Кентавра с острым копытом.{x
Save

sector mountain
south dig next
south flags isdoor closed locked noscan pickproof
done

south
```

#### На залитой солнцем террасе

Ну юге от лужайки комната с названием "На залитой солнцем террасе"

Это первая комната за закрытой дверью

```
redit
name web
{YНа {Wза{Yли{Wтой {Yсол{Wнц{Yем {Rт{Yерр{Wа{yс{Rе{x
Save

desc web
Перед тобой широкая крытая терраса, под кровлей подвешены множество фурин 
самых разных расцветок и форм. Ветер раскачивает {Yко{yло{Yко{Wль{Yчики{x и создает 
причудливую тихую музыку, наполняющую окружающее пространство. В глубине террасы 
установлены пара просторных плетеных кресел. Слева, через террасу можно пройти 
внутрь маяка, а прямо дверь, ведущая в дом. Перед террасой разбита клумба 
с яркими полевыми цветами, разноцветными камнями, мхами и вереском. Возле клумбы
вросла в землю удобная скамейка, плотно укрытая тенью раскидистого, огненно-алого 
японского {yк{rл{Yен{yа{x. Лучи света играют в кроне клена, пытась проскользнуть 
между листьями, и раскрашивают пространство под ним всеми оттенками 
солнечно-желтого, ярко-рыжего, алого и красного.
Save

sector city
flags nowhere mansion

north flags isdoor closed locked noscan pickproof
east dig next
east flags isdoor closed
south dig next
south flags isdoor closed
done

east
```

#### Поднимаясь на маяк

На востоке от террасы комната с названием "Поднимаясь на маяк".

```
redit
name web
Поднимаясь на маяк
Save

desc web
Спиральная лестница обвивает стены, оставляя небольшое пространство в центре 
- глубокий колодец от низа до верха. Если встать в центре этого колодца 
и посмотреть вверх, то кажется что лестница завивается в причудливую морскую 
раковину. Внизу, у входа, к стене прислонен большой морской якорь. Стены маяка 
изнутри покрыты белой штукатуркой, кое-где из-под штукатурки проглядывает 
красный кирпич, из которого состоит все строение. Всесте с лестницей в хороводе 
кружатся прочные металлические перила с дубовыми поручнаями. Дерево 
отполировано до блеска множеством прикосновений рук тех, кто поднимался наверх, 
чтобы разжечь огонь, дать надежду и показать путь всем кто потерялся.
Save

sector inside
flags nowhere mansion

west flags isdoor closed
up dig next
done

up
```

#### Маяк

На верху от подъема на маяк комната с названием "Маяк"

```
redit
name web
Маяк
Save

desc web
Просторная круглая комната наверху - сердце маяка. У комнаты нет стен, вместо 
них огромные окна от пола до потолка, открывающие великолепный обзор во все 
стороны. В центре комнаты подвещен странный янтарно-белый мерцающий кристалл. 
При прикосновении кристалл начинает светить все ярче и ярче и заливает все 
пространство вокруг золотистым светом. Этот свет так ярок, что способен пробить 
мглу и туман на многие мили вокруг и стать путеводной звездой для заблудившихся 
в море.
Save

sector inside
flags nowhere mansion
done

down
west
south
```

#### Прихожая 

На юге от террасы комната с названием "Прихожая"

```
redit
name web
Прихожая
Save

desc web
Широкая деревянная дверь украшена резьбой, за ней терраса залитая солнцем. 
Свет в комнату проникает через насколько окон и через витражное стекло во входной 
двери. На витраже изображено небо, половина неба дневная, с {Yсо{Wлн{Yцем{x и {Dт{wу{Dчками{x,
а другая половина ночная, с {Cлу{Wн{Cой{x и {Wзвез{Yд{Wами{x. Пол комнаты покрыт 
деревянным паркетом, стены выкрашены в белый цвет. На стене висит огромное зеркало 
в деревянной раме. Рядом со входом стоит вешалка для одежды. В углу сложен стог
ароматного сена.
Save

sector inside
flags nowhere mansion

north flags isdoor closed
south dig next
south flags isdoor closed
done

south
```

#### Комната для отдыха и бесед

На юге от прихожей комната с названием "Комната для отдыха и бесед".

```
redit
name web
{cК{Cо{cмната д{Cл{cя отдых{Cа{c и бес{Cе{cд{x
Save

desc web 
{wПрост{Wо{wрная ком{Wн{wат{Wа{w {Wс{wтены, {Wп{wол и потолок кот{Wо{wрой, отделаны различными порода{Wм{wи 
дерева. Все простра{Wн{wство стен, от пола до потолка, зан{Wи{wмают книжные шкафы.  
Возле одной из с{Wте{wн расположился огромный кам{Wи{wн, в кот{Wо{wром уютно потре{Wс{wкивают
буковые пол{Wе{wнья. На каминной полке множество удивительных {Wб{wезд{Wе{wлушек, статуэток 
и два огромных под{Wсве{wчника со множеством горящих свечей. В цен{Wт{wре комнаты 
небольшой круглый стол{Wи{wк, на которо{Wм{w леж{Wи{wт несколько книг и стоит ваза с полевыми 
цветами. Вок{Wр{wуг столика расположились мягкие уютные кресла. Пол комнаты устлан 
пушистым ковром. Из комнаты {Wв{wедут три двери, одн{Wа{w в волшебную кухню, другая в 
прихожую, а третья в сад. В ко{Wм{wнате необычная атмосфера (atmosphere).{x
Save

ed web atmosphere
{cКо{Cм{cната, в кот{Cо{cрой так мн{Cо{cго сч{Cа{cстья, ра{Cд{cости и света, у{Cю{cта и тепла, 
размы{Cш{cлений и и{Cд{cей, прекрас{Cн{cых моментов и пр{Cи{cятных во{Cс{cпоминаний, б{Cе{cсед 
и разг{Со{cворов бессо{Cн{cными ноча{Cм{cи, изобрете{Cн{cий и идей, раз{Wмы{cшлений и раз{Cд{cумий. 
З{Cд{cесь го{Cв{cорили о{Cб{cо вс{Cе{cм {Cн{cа све{Cт{cе {Wдвое{c, он ид{Cе{cй был п{Cо{cлон и {Cс{cветел 
как {Cк{cостер, о{Cн{cа н{Cе{cжна и {Wл{cаскова к{Cа{cк {Wю{cжное м{Cо{cре, по{Cд{cвижна и {Wб{cыстра {Cк{cак г{Wо{cрн{Cы{cй 
руч{Cе{cек. {CК{cак часто {Cо{cни об{Cн{cаружи{Wв{cали {Cа{cбсолютное сх{Cо{cдство сво{Cи{cх мыс{Cл{cей, гармонию 
во всем. {CС{cкол{Wь{cко т{Cы{cсяч часо{Cв{c прове{Cл{cи они вм{Cе{cсте и ск{Cо{cль{Cк{cо еще про{Cв{cедут. 
Зд{Cе{cсь говорил{Cи{c обо вс{Cе{cм на св{Cе{cте д{Cв{cое...{x
Save

sector inside
flags no_mob nowhere mansion
north flags isdoor closed
east dig next
south dig next
south flags isdoor closed
done

east
```

#### Волшебная Кухня

На востоке от комнаты для отдыха комната с названием "Волшебная Кухня"

```
redit
name web
{CВолшебная {yКухня{x
Save

desc web
Ты стоишь посреди {Cволшебной {yкухни{x, каждый предмет тут живет своей жизнью. Все 
движется в невообразимом танце, подчиняясь своим, странным, неведомым тебе 
законам. Ты замечаешь странную гармонию в множестве одновременно происходящих 
действий. Котел на плите варит суп, поварешка сама помешивает этот суп и иногда 
пробует его на вкус, скептически покачивая своей рукояткой. Плита пританцовывая 
то уменьшает, то прибавляет огонь. Ложки и вилки танцуют с тарелками на полках.
Мочалка периодически хватает то одну, то другую и окунает в таз с мыльной пеной, 
начищает до блеска, а затем отправляет обратно на полку. В полете тарелки 
перехватывает пушистое полотенце, вытирая их насухо. 
На стене висит огромный плакат, изображающий строгую женщину с увесистой 
сковородкой в руке. Надпись на плакате гласит: {CЧИСТОТА И {RДИКТАТУРА{x.
Готовящаяся еда издает аппетитные ароматы и тебе хочется немедленно попробовать 
все на вкус. И как только ты уже почти поднес аппетитный кусок ко рту, из 
воздуха появляется дух строгой домоуправительницы.
Домоуправительница пронзительно вопит: {Y"Ночной дожор! Всем выйти из сумрака!"{x
От изумления ты роняешь еду, так и не успев донести до рта. Дух 
домоуправительницы подметает еду на совок и тут же исчезает.
Save

sector inside
flags no_mob nowhere mansion
done

west
south
```

#### Сад за домом 

На юге от комнаты для отдыха комната с названием "Сад за домом".

```
redit 
name web
{GСад за домом{x
Save

desc web
Полевые цветы и травы укрывают землю плотным ковром. Одуванчики, васильки, 
мята, душица, вереск, зверобой, колокольчики, ландыши, лен, маки, маргаритки, 
ромашки, цикорий и фиалки создают невиданное разнообразие красок. 
В стороне раположился небольшой участок земли, свободный от полевых цветов - 
грядка с сочной и сладкой клубникой. Через сад бежит небольшой ручеек 
с прозрачной водой. В саду растет несколько крупных деревьев. 
Мандариновое дерево наполняет воздух дивным ароматом цитрусовых, черешня усыпана 
розовыми цветами и спелыми ягодами, абрикосовое дерево светит рыжыми огоньками 
абрикосов. В центре сада небольшой фонтан.
Save

sector city
flags no_mob nowhere mansion

north flags isdoor closed
down dig next
done

down
```

#### Уединенный пляж

Вниз от сада за домом комната с названием "Уединенный пляж".

```
redit
name web
{WУединенный пляж{x
Save

desc web
Какой прекрасный пляж! Море теплое и ласковое, нежно накатывает свои волны 
на берег. Вода в море удивительного изумрудно-бирюзового оттенка. В воздухе 
кружатся несколько больших белоснежных чаек. Мягкий белый песок зовет 
прогуляться по берегу. Волны выносят на берег ракушки и красивые разноцветные 
камешки. Из воды на берег иногда выползают небольшие крабики. Кокосовые пальмы 
и манговые деревья создают приятную полутень, в которой можно укрыться, устав 
от знойного солнца. На берегу расстелено большое, мегкое одеяло. В тени стоит
небольшая корзинка с едой и напитками.
Save

sector hills
flags no_mob nowhere near_water mansion
liquid salt water

east dig next
done

east
```

#### Ласковое море

На востоке от пляжа комната с названием "Ласковое море"

```
redit
name web
{cЛасковое море{x
Save

desc web
{cАх как приятно плавать в этой теплой воде, медленно качатся на небольших 
волнах. Море прозрачное, приятного, {gизумрудно{c-бирюзового цвета, можно разглядеть 
все детали морского дна. На дне кипит жизнь, стайки разноцветных рыбок медленно
путешествуют между красочными кораллами. Небольшие медузы дрейфуют в толще воды.
По дну передвигаются крабы и морские звезды. Длинные водоросли грациозно 
покачиваются в такт волнам. В белом песке застыли блестящие морские раковины.
Черепаха высовывает голову из воды и с любопытством оглядывает окрестности.{x
Save

sector water_noswim
flags nowhere near_water mansion
liquid salt water
```

### Предметы по комнатам

#### Причал в долине

##### Баркас

```
edit object create next
name web
баркас longboat
Save

long web
Баркас (longboat) покачивается на волнах возле пристани.
Save

short web
стар|ый|ого|ому|ый|ым|ом баркас||а|у||ом|е
Save

type portal
gender male
material wood
extra hum nopurge nosac nolocate burn_proof nosell noenchant
smell Пахнет морской солью и рыбой.
sound Поскрипывает от ветра и волн.
weight 1000
v0 0
v3 [VNUM комнаты На баркасе]
done

// Добавляем баркас в ресеты комнаты Причал в долине
reset 1 obj [VNUM баркаса] room
redit reset room

// Убираем проход на баркас на юге оставляя выход с баркаса на север
redit
south unlink
done
```

#### Причал на острове

##### Баркас

Добавляем тот же самый баркас как и на причале в долине

```
reset 1 obj [VNUM баркаса] room
redit reset room

// Убираем проход на баркас на севере оставляя выход с баркаса на юг
redit
north unlink
done
```

#### Лужайка - перед маяком

##### Одуванчики

```
edit object create next
name web
dandelion flower одуванчики
Save

short web
{YО{yд{Wу{Yван{yчи{Yк|и{x|ов{x|ам{x|и{x|ами{x|ах{x
Save

long web
{YО{yд{Wу{Yван{yчи{Yки {y(dandelion) яркими огоньками светятся в {Gзеленой траве.{x
Save

gender male
weight 1
type treasure
level 1
material flower
wear take wear_head 
extra nopurge nosac burn_proof
smell Пахнет приятными воспоминаниями и неотстирывающейся одеждой.
sound Ты слышишь веселый смех и шуршание босых ног по траве.
done

// Добавляем одуванчики в ресеты комнаты Лужайка - перед маяком
reset 1 obj [VNUM одуванчиков] room
redit reset room
```

##### Ключ от дома

```
edit object create next
name web
ключ маяк key lighthouse
Save

short web
ключ||а|ю||ом|е от дома с маяком
Save

long web
Ключ в форме маяка (lighthouse) ярко светится.
Save

type key
level 1
wear take
extra glow hum water_stand nopurge nosac nolocate burn_proof nosell noenchant
material light
smell Ты ощущаешь запах озона, как будто здесь только что была сильная гроза.
sound Ты слышишь потрескивание электрических разрядов.
gender male
weight 1
v0 1
v1 0
done
```

#### На залитой солнцем террасе

##### Скамейка

```
edit object create next
name web
скамейка bench
Save

short web
скамейк|а|и|е|у|ой|е в тени клена
Save

long web
Скамейка (bench) стоит в тени клена.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material wood
smell Пахнет свежей краской и осенними листьями.
sound Ты слышишь как шуршат осенние листья.
weight 200
v0 4
v1 2000
v2 stand_on sit_on rest_on sleep_on
v3 400
v4 400
done

reset 1 obj [VNUM скамейки] room
redit reset room
```

##### Плетеные кресла

```
edit object create next
name web
плетеные кресла armchairs
Save

short web
пар|а|ы|е|у|ой|е плетеных кресел
Save

long web
Пара плетеных кресел (armchairs) стоит в глубине террасы.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material bamboo
smell Пахнет бамбуком, из которого их сплели.
sound Кресла уютно поскрипывают.
gender netural
weight 20
v0 2
v1 2000
v2 sit_in rest_in sleep_in
v3 400
v4 400
done

reset 2 obj [VNUM кресел] room
redit reset room
```

##### Клумба

```
edit object create next
name web
клумба flowerbed
Save

short web
клумб|а|ы|е|у|ой|е
Save

long web
Красивая клумба (flowerbed) разбита перед скамейкой.
Save

ed web клумба flowerbed
Красивая клумба с горкой крупных, разноцветных камней в центре. Камни покрыти 
зелеными мхами, и обсажены вокруг вереском и полевыми цветами самых разных 
видов. Клумба радует глаз разнообразием красок и гармонией композиции.
Save

type trash
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material ground
smell Пахнет вереском и полевыми цветами.
sound Ты слышишь жужжание пчел, собирающих нектар с цветов вереска.
gender female
weight 1000
done 

reset 3 obj [VNUM клумбы] room
redit reset room
```

#### Поднимаясь на маяк

##### Якорь

```
edit object create next
name web
якорь anchor
Save

short web
якор|ь|я|ю|ь|ем|е
Save

long web
{YОг{yромный ко{Yр{yабельный яко{Yр{yь ({Ya{ynchor) присл{Yо{yнен к стене{x
Save

ed web якорь anchor
{yОгромный якорь сверкает медью. Поверхность отполирована до блеска 
прикосновением тысячи рук. Если его потереть, тебе неприменно улыбнется удача. 
Ты замечаешь странные слова{x (words) {yаккуратно выгравированные на якоре.{x
Save

ed web words
{yБудь менi кимось, будь менi
Як тiльки не звуть тебе: Якiр, Маяк
i якщо суть слова донесуть
Я стану м'якшою

Стань менi кимось
Стань, як хтось, кого майже достатньо
Щоб спокiйно дожити до ста

Я не атомна станцiя
Квартира напiвпуста
Люстра Францiя
i я пiд нею проста
Блискуча, але не глянцева
Без плотi, без статi
Чекаю тебе на паркетному стартi

Вдома
Вдома
Вдома

Гасiть, пора
Несiть торт, кричiть: "Ура!"
Мiй чорний ескорт домчить мене
З пункту Б в пункт А

Нема нiяко гри, а вiд молока
В мене сильна права, слабка лiва рука
Трохи дали згори, i сказали: "Гори"
То я i горю  я така

Будь менi кимось
Будь тим, кого так швидко не заберуть
Глибше вiд образ, бiльше, нiж потяг
Будь менi зараз, а не потiм

Потiм стань менi на шляху
Стань, пiдiйми бунт
Зiрви повстання пiд гаслами: "Ти остання!"
Ти точно остання

Гасiть, пора
Несiть торт, кричiть: "Ура!"
Мiй чорний ескорт домчить мене
З пункту Б в пункт А

Нема нiяко гри, а вiд молока
В мене сильна права, слабка лiва рука
Трохи дали згори, i сказали: "Гори!"
То я i горю  я така{x
Save

type treasure
level 0

extra bless nopurge nosac nolocate burn_proof nosell noenchant
material copper
smell {cЧем может пахнуть якорь? Морской солью, вольным ветром, мечтами и надеждами и {Cверой в {Rлюбовь.{x
sound {CТ{cы слыш{Cи{cшь к{Cа{cк кт{Cо{c-то поет тихим г{Cо{cлосом, по{Cл{cным над{Cе{cжды и в{Cе{cры.{x
gender male
weight 1000
done

reset 1 obj [VNUM якоря] room
redit reset room
```

#### Маяк 

##### Волшебный кристалл

```
edit object create next
name web
crystal кристалл
Save

short web
волшебн|ый|ого|ому|ый|ым|ом кристалл||а|у||ом|е
Save

long web
{yВолш{Yе{yбный кр{Yи{yсталл (crystal) подв{Yе{yшен в центре к{Yо{yмнаты.{x
Save

type light
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material energy
smell Пахнет озоном.
sound Гудит как рой разъяренных пчел.
gender male
weight 1
v2 0
done

reset 1 obj [VNUM кристалла] room
redit reset room
```

#### Прихожая 

##### Стог сена

```
edit object create next
name web
стог stack
Save

short web
стог||а|у||ом|е сена
Save

long web
Стог сена (stack) сложен в углу.
Save

type furniture
level 1
wear take
extra nopurge nosac nolocate burn_proof nosell noenchant
material hay
smell Пахнет скошенной травой, свежестью и полевыми цветами.
sound Шуршит и хрустит.
gender male
weight 10
v0 4
v1 2000
v2 stand_in sit_in rest_in sleep_in
v3 200
v4 200
done

reset 1 obj [VNUM стога сена] room
redit reset room
```

##### Вешалка

```
edit object create next
name web
вешалка hanger
Save

short web
вешалк|а|и|е|у|ой|е для подков и попон
Save

long web
Вешалка (hanger) для подков и попон стоит у стены.
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material softwood
smell Охххх зря, пахнет подковами... и попонами.
sound Ты слышишь как позвякивают подковы и шелестят на ветру попоны.
gender female
weight 100
v0 1000
v1 closeable with_pockets
v3 1000
v4 25
done

reset 2 obj [VNUM вешалки] room
redit reset room
```

#### Комната для отдыха и бесед

##### Большой книжный шкаф

```
edit object create next
name web
книжный шкаф bookcase 
Save

short web
книжн|ый|ого|ому|ый|ым|ом шкаф||а|у||ом|е
Save

long web
Большой книжный шкаф (bookcase) занимает одну из стен комнаты.
Save

ed web книжный шкаф bookcase
Это большой книжный шкаф из красного дерева. Он занимает всю стену как в ширину,
так и в высоту. На полках стоят сотни книг, с описаниями местных форм жизни
и предметов. В другом отделении лежит куча свитков с картами мира. На некоторых 
полках лежат фотооальбомы с большим количеством снимков и различные рисунки.
Здесь собрано множество знаний и воспоминаний.
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material redwood
smell Пахнет старыми книгами и свитками пергамента.
sound Там тихо.
gender male
weight 1000
v0 10000
v1 closeable with_pockets
v3 10000
v4 10
done 

reset 1 obj [VNUM шкафа] room
redit reset room
```

##### Пушистый ковер

```
edit object create next
name web
ковер carpet
Save

short web
шерстян|ой|ого|ому|ой|ым|ом ков|ер|ра|ру|ер|ром|ре
Save

long web
Пушистый шерстяной ковер (carpet) покрывает пол.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material wool
smell Пахнет шерстью.
sound Ты слышишь как под ковром поскрипывают половицы.
gender male
weight 100
v0 4
v1 3000
v2 stand_on sit_on rest_on sleep_on
v3 400
v4 400
done

reset 2 obj [VNUM ковра] room
redit reset room
```

##### Камин

```
edit object create next
name web
камин fireplace
Save

short web
камин||а|у||ом|е
Save

long web
Камин (fireplace) наполняет комнату теплом и уютом.
Save

ed web камин fireplace
Красивый мраморный камин, в верхней части раположена полка, на которой стоят 
большие бронзовые подсвечники со множеством зажженых свечей и огромное 
количество различных безделушек, фигурок, статуэток и картинок. В камине
весело потрескивают буковые поленья, наполняя комнату теплом и уютом.
Огонь отбрасывает блики по всей комнате, создавая причудливый тенец теней 
и света на окружающих предметах. 
Save

type light
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material marble
smell Ты ощущаешь легкий запах горящих буковых поленьев, исходящий от камина.
sound Ты слышишь как дрова в камине уютно потрескивают.
gender male
weight 1000
v2 0
done

reset 3 obj [VNUM камина] room
redit reset room
```

##### Кофейный столик

```
edit object create next
name web
coffee table кофейный столик
Save

short web
кофейн|ый|ого|ому|ый|ым|ом столик||а|у||ом|е
Save

long web
Кофейный столик (coffee table) стоит рядом с камином.
Save

ed web coffee table кофейный столик
Круглый кофейный столик сделан из корня какого-то огромного дерева. Поверхность
столешницы отполирована до зеркального блеска и покрыта причудливым древесным 
узором. На столике стоит красивая ваза с букетом полевых цветов, большой 
кофейник со свежесваренным кофе и лежит несколько книг. 
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material root
smell Пахнет древесным ароматом, смешанным с запахом кофе и сладостей.
sound Тишина...
gender male
v0 4
v1 300
v2 stand_on sit_on rest_on sleep_on
v3 100
v4 100
done 

reset 4 obj [VNUM столика] room
redit reset room
```

##### Большой кофейник

```
edit object create next
name web
кофейник coffee pot
Save

short web
больш|ой|ого|ому|ой|им|ом кофейник||а|у||ом|е
Save

long web
Большой кофейник (coffee pot) стоит на кофейном столике.
Save

type fountain
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material copper
smell Как пахнет кофе? Говорят, что он пахнет солнечными лучами, впитавшимимися в зерна, пока они росли. Бодростью и тягой к новым свершениям.
sound Ты слышишь как внутри что-то булькает.
gender male
weight 50
v0 300
v1 300
v2 coffee
done

reset 5 obj [VNUM кофейника] room
redit reset room
```

##### Мягкие кресла

```
edit object create next
name web
мягкие кресла soft armchairs 
Save

short web
мягки|е|х|м|е|ми|х крес|ла|ел|лам|ла|лами|лах
Save

long web
Мягкие кресла (armchairs) стоят вокруг кофейного столика.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material wool
smell Пахнет уютом, покоем и домом.
sound Ты поппеременно слышишь самые разые звуки. Тихий шорох ветра в листве. Пение птиц в лесу. Звуки капель дождя по крыше. Потрескивание поленьев в камине. Шум морского прибоя.
gender netural
v0 4
v1 4000
v2 stand_on sit_on rest_on sleep_on
v3 400
v4 400
done 

reset 6 obj [VNUM кресел] room
redit reset room
```

#### Волшебная Кухня

##### Шкаф с посудой

```
edit object create next
name web
cupboard шкаф
Save

short web
шкаф||а|у||ом|е с посудой
Save

long web
Шкаф с посудой (cupboard) стоит у стены.
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material rosewood
smell Ты чувствуешь интенсивный запах чистоты и едва уловимый запах диктатуры.
sound Ты слышишь как волшебные тарелки тихо перешептываются с волшебными чашками.
gender male
weight 500
v0 10000
v1 closeable closed with_pockets
v3 10000
v4 25
done 

reset 1 obj [VNUM шкафа] room
redit reset room
```

##### Холодильник

```
edit object create next
name web
холодильник fridge refridgerator
Save

short web
холодильник||а|у||ом|е
Save

long web
{RК{Dрасный х{wо{Cл{wо{Dдильник (fridge) полон вкусной еды.{x
Save

type container
level 0
extra hum magic bless nopurge nosac nolocate burn_proof nosell noenchant
material titanium
smell Пахнет вкусной едой
sound Ты слышишь тихое жужжание неведомых {Cволшебных {Dмеханизмов.{x
gender male
weight 500
v0 10000
v1 closeable closed with_pockets
v3 10000
v4 25
done 

reset 2 obj [VNUM холодильника] room
redit reset room
```

##### Плита

```
edit object create next
name web
плита cooker
Save

short web
плит|а|ы|е|у|ой|е
Save

long web
{CВолшебная {yплита {x(cooker) пышит жаром.
Save

ed web плита cooker
{CВолшебная {yплита {xпышит жаром, внутри потрескивают горящие дрова.
На плите заманчиво булькает суп в кастрюлях, что-то аппетитно шкварчит на 
сковородках. Плита то добавляет, то убавялет огонь. В духовке печется 
свежий хлеб, вкусные булочки с {Dк{yорицей {x и пироги. На одной из конфорок 
вот-вот закипит кофейник.
Save

type container
level 1
extra hum magic bless nopurge nosac nolocate burn_proof nosell noenchant
material iron
smell Пахнет вкусной выпечкой и горячим хлебом.
sound Ты слышишь потрескивание дров внутри.
gender female
v0 500
v1 closeable closed
v3 500
v4 50
done 

reset 3 obj [VNUM плиты] room
redit reset room
```

##### Загадочный котел

```
edit object create next
name web
котел cauldron
Save

short web
загадочн|ый|ого|ому|ый|ым|ом кот|ел|ла|лу|ел|лом|ле
Save

long web
{CЗ{cагадочный котел {x(cauldron) {cбулькает на плите.{x
Save

type fountain
level 0
extra magic nopurge nosac nolocate burn_proof nosell noenchant
material silver
smell Пахнет чем-то непонятным, но видимо вкусным.
sound Ты слышишь закадочное бульканье.
gender male
v0 3000
v1 3000
v2 chocolate
done 

reset 4 obj [VNUM котла] room
redit reset room
```

##### Пара дубовых скамеек

```
edit object create next
name web
oak bench дубовая скамья
Save

short web
дубов|ая|ой|ой|ую|ой|ой скамь|я|и|е|ю|ей|е
Save

long web
Пара дубовых скамеек (bench) стоит возле стола.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material oak
gender female
weight 200
v0 4
v1 10000
v2 stand_on sit_on rest_on sleep_on put_on
v3 200
v4 200
done 

reset 5 obj [VNUM скамеек] room
redit reset room
```

##### Большой дубовый стол

```
edit object create next
name web
oak table дубовый стол
Save

short web
больш|ой|ого|ому|ой|им|ом дубов|ый|ого|ому|ый|ым|ом стол||а|у||ом|е
Save

long web
Большой дубовый стол (table) стоит посреди кухни.
Save

ed web oak table дубовый стол
На столе ты видишь разнообразную вкусную еду. Здесь каждый может найти 
что-то, что он особенно любит. Супы и салаты, овощи, мясо и фрукты, сладости и 
выпечка, кофе, чай и напитки покрепче. По краям расставлены тарелки, чашки, 
бокалы и разложены столовые приборы. От стола исходят заманчивые ароматы 
домашней еды.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material oak
smell Пахнет дубовым лесом и вкусной домашней едой. У тебя тут же просыпается аппетит и хочется что-то немедленно съесть.
sound Позвякивание посуды и столовых приборов, шорох листьев леса, в котором когда-то росло дерево, из которого сделан стол.
gender male
weight 500
v0 4
v1 10000
v2 stand_on sit_on rest_on sleep_on put_on
v3 400
v4 400
done 

reset 6 obj [VNUM стола] room
redit reset room
```

##### Декантер с соком

```
edit object create next
name web
decanter декантер сосуд
Save

short web
декантер||а|у||ом|е
Save

long web
На столе стоит декантер (decanter) с апельсиновым соком.
Save

type fountain
level 0
extra magic nopurge nosac nolocate burn_proof nosell noenchant
material crystal
smell Пахнет апельсиновым соком.
sound Там тихо.
gender male
weight 50
v0 3000
v1 3000
v2 orange juice
done

reset 7 obj [VNUM декантера] room
redit reset room
```

#### Сад за домом

##### Мандариновое дерево

```
edit object create next
name web
mandarin tree мандариновое дерево
Save

short web
{yм{Yанда{yр{Yино{yв{Y|ое|ого|ому|ое|ым|ом д{yе{Yрев|о{x|а{x|у{x|о{x|ом{x|е{x
Save

long web
{yМ{Yанда{yр{Yино{yв{Yое д{yе{Yрево (mandarin) покрыто цветами и сочными мандаринами.{x
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material wood
smell Пахнет кисло-сладким цитрусом с небольшой горчинкой.
sound Дерево шелестит листьями.
gender netural
weight 500
v0 100
v3 100
v4 50
done 

reset 1 obj [VNUM мандаринового дерева] room
redit reset room
```

##### Мандарины

```
edit object create next
name web
mandarin мандарин
Save

short web
{yм{Yанда{yр{Yи|н{x|на{x|ну{x|н{x|ном{x|не{x
Save

long web
{yСочный сладкий {yм{Yанда{yр{Yин (mandarin) {yлежит здесь.{x
Save

type food
level 0
wear take
extra water_stand nolocate nosell
material fruit
smell {yпахнет м{Yанда{yр{Yинами {yи новогодним праздником.{x
sound Мандарин угрожающе шипит соком: не ешь меня, а то в глаз брызну!
gender male
weight 0
v0 4
v1 4
v3 no
done

reset 2 obj [VNUM мандарина] inside [VNUM мандаринового дерева] 0 3
redit reset room
```

##### Черешневое дерево

```
edit object create next
name web
cherries cherry tree черешня дерево
Save

short web
черешнев|ое|ого|ому|ое|ым|ом дерев|о|а|у|о|ом|е
Save

long web
Здесь растет высокая черешня. (cherries)
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material softwood
smell Пахнет спелой черешней.
sound Дерево шелестит листьями.
gender netural
weight 500
v0 100
v3 100
v4 50
done

reset 3 obj [VNUM черешневого дерева] room
redit reset room

```

##### Крупная сладкая черешня

```
edit object create next
name web
черешня cherries
Save

short web
{rч{Rе{rрешн|я{x|и{x|е{x|ю{x|ей{x|е{x
Save

long web
{rКрупная сладкая ч{Rе{rрешня (cherries) висит на дереве.{x
Save

type food
level 0
wear take
extra water_stand nolocate nosell
material fruit
smell Пахнет сладкой черешней и летом.
sound Ты слышишь голоса у себя в голове. Голоса говорят - лучше съешь абрикос.
gender female
weight 0
v0 4
v1 4
v3 no
done

reset 4 obj [VNUM черешни] inside [VNUM черешневого дерева] 0 3
redit reset room
```

##### Абрикосовое дерево

```
edit object create next
name web
абрикос дерево apricot tree
Save

short web
абрикосов|ое|ого|ому|ое|ым|ом дерев|о|а|у|о|ом|е
Save

long web
Абрикосовое дерево (apricot) протягивает ветви во все стороны.
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material wood
smell Пахнет сладкими абрикосами.
sound Дерево шелестит листьями.
gender netural
weight 500
v0 100
v3 100
v4 50
done

reset 5 obj [VNUM абрикосового дерева] room
redit reset room
```

##### Сочный сладкий абрикос

```
edit object create next
name web
абрикос apricot
Save

short web
{Yа{yб{Yрикос|{x|а{x|у{x|{x|ом{x|е{x
Save

long web
{YСочный сладкий а{yб{Yрикос (apricot) - съешь его немедленно.{x
Save

type food
level 0
wear take
extra water_stand nolocate nosell
material fruit
smell Пахнет сладким абрикосом.
sound Ты слышишь тихий сладкий шепот - съешь меня.
gender male
weight 0
v0 4
v1 4
v3 no
done

reset 6 obj [VNUM абрикоса] inside [VNUM абрикосового дерева] 0 3
redit reset room
```

##### Грядка с клубникой

```
edit object create next
name web
грядка клубника strawberries bed
Save

short web
грядк|а|и|е|у|ой|е с клубникой
Save

long web
{GГрядка с {rклубникой{G (strawberries) сверкает красными огоньками ягод.{x
Save

type container
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material ground
smell Пахнет клубникой и зелеными листьями.
sound Nothing is real and nothing to get hung about strawberry fields forever.
gender female
weight 500
v0 100
v3 100
v4 50
done

reset 7 obj [VNUM грядки] room
redit reset room
```

##### Сладкая спелая клубника

```
edit object create next
name web
клубника strawberry
Save

short web
{Rклубник|а{x|и{x|е{x|у{x|ой{x|е{x
Save

long web
{RСладкая спелая клубника (strawberry) горит красным огнем.{x
Save

type food
level 0
wear take
extra water_stand nolocate nosell
material fruit
smell Пахнет клубникой и возможно сливками.
sound Клубника шепчет тебе: одну ягодку бери, на другую смотри, третью примечай, а четвёртая померещится.
gender female
weight 0
v0 4
v1 4
v3 no
done

reset 8 obj [VNUM клубники] inside [VNUM грядки с клубникой] 0 3
redit reset room
```

##### Небольшой фонтан

```
edit object create next
name web
фонтан fountain
Save

short web
небольш|ой|ого|ому|ой|им|ом фонтан||а|у||ом|е
Save

long web
Небольшой фонтан (fountain) журчит в центре сада.
Save

ed web фонтан fountain
В центре фонтана ты видишь скульптурную композицию: незадачливый начинающий 
игрок сжался в ужасе, над ним нависает огромная страшная русалка, в руках у 
которой огромный гвоздь. Русалка вопит: {Y"Шляпу сними!"{x  
На фонтане закреплена табличка {C"Русалка, прокалывающая ухо нубу"{x.
Save

type fountain
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material stone
smell Пахнет свежестью.
sound Ты слышишь журчание воды.
gender male
weight 1000
v0 3000
v1 3000
x2 water
done

reset 9 obj [VNUM фонтана] room
redit reset room
```

##### Ковер из полевых цветов

```
edit object create next
name web
flowers carpet ковер цветы
Save

short web
ковер||а|у||ом|е из полевых цветов
Save

long web
Под ногами расстилается ковер (carpet) из {Wп{Yо{Bл{Gе{Yв{Mы{Wх {Yц{Wв{Mе{Wт{Gо{Mв{x.
Save

type furniture
level 0
extra nopurge nosac nolocate burn_proof nosell noenchant
material flower
smell Пахнет полевыми цветами и травами.
sound Ты слышишь веянье ветра и звон колокльчиков.
gender male
weight 1000
v0 4
v1 10000
v2 stand_on sit_on rest_on sleep_on
v3 400
v4 400
done

reset 10 obj [VNUM ковра] room
redit reset room
```

#### Уединенный пляж

##### Большое лоскутное одеяло

```
edit object create next
name web
лоскутное одеяло patchwork quilt
Save

short web
{Gболь{Dш|ое|ого|ому|ое|им|ом {Bлос{Wкут{Cн|ое|ого|ому|ое|ым|ом {Yоде{Mял|о{x|а{x|у{x|о{x|ом{x|е{x
Save

long web
{GБоль{Dшое {Bлос{Wкут{Cное {Yоде{Mяло {G(patchwork) расстелено на песке.{x
Save

type furniture
level 1
wear take
extra water_stand nopurge nosac nolocate burn_proof nosell noenchant
material satin
smell Пахнет горячим песком, кремом от солнца и соком арбуза.
sound Одеяло говорит тебе - не садись на меня, иди своей дорогой!
gender netural
weight 2
v0 4
v1 2000
v2 stand_on sit_on rest_on sleep_on
v3 400
v4 400
done

reset 1 obj [VNUM одеяла] room
redit reset room
```

##### Корзинка для пикника

```
edit object create next
name web
корзинка basket
Save

short web
корзинк|а|и|е|у|ой|е для пикника
Save

long web
Корзинка для пикника (basket) заботливо принесена сюда.
Save

type container
level 1
wear take
extra water_stand nopurge nosac nolocate burn_proof nosell noenchant
material softwood
smell Пахнет фруктами, вареной кукурузой и чем-то сладким.
sound Внутри что-то загадочно плещется и шуршит оберточная бумага.
gender female
weight 2
v0 500
v1 closeable closed
v3 500
v4 10
done

reset 2 obj [VNUM корзинки] room
redit reset room
```

#### Ласковое море

##### Деревянная лодка

```
edit object create next
name web
лодка boat
Save

short web
{yдеревянн|ая|ой|ой|ую|ой|ой лодк|а{x|и{x|е{x|у{x|ой{x|е{x
Save

long web
{yДеревянная лодка (boat) покачивается на волнах.{x
Save

type furniture
level 0
extra water_stand nopurge nosac nolocate burn_proof nosell noenchant
material wood
smell Пахнет морской солью.
sound Ты слышишь плеск волн о борта и поскрипывание весел в уключинах.
gender female
weight 500
v0 2
v1 1500
v2 stand_in sit_in rest_in sleep_in
v3 200
v4 200
done

reset 1 obj [VNUM лодки] room
redit reset room
```

### Мобы по комнатам

#### На баркасе

##### Капитан

```
edit mob create next
name web
капитан captain
Save

short web
капитан||а|у|а|ом|е
Save

long web
Капитан (captain), старый морской волк, управляет баркасом.
Save

desc web
Когда-то капитан был молод и бороздил моря и океаны на разных кораблях. 
Он был и юнгой и матросом и много кем еще пока стал капитаном. Он прожил
долгую и полную приключений жизнь. Устав от дальних странствий, он перебрался
поближе к родному дому и теперь плавает на стареньком баркасе, перевозя 
пассажиров на остров и обратно.
Save

level 100
race human
sex male
number singular
hitdice 1 d 1 + 9999
damdice 10 d 10 + 20
manadice 1d1 + 999
hitroll 300
ac -9000 -9000 -9000 -9000
aff infrared sneak haste
det evil invis hidden dark_vision
imm summon charm spell weapon bash pierce slash fire cold acid poison negative holy energy mental disease drowning sound wood silver iron
res charm spell weapon fire cold drowning
form edible sentient biped mammal
part head arms legs heart brains guts hands feet fingers ear eye long_tongue legs
act npc sentinel nopurge notrack
pos start stand
pos def stand
smell Ты чувствуешь запах рома и крепкого табака.

fenia onArea
.apply(function () {
   var captain;
   captain = .get_mob_index("[!!!SET VNUM HERE]");


   captain.onGreet = function (mob, ch) {
	  mob.say("Привет, %^C1!", ch);
	  mob.say("На моем корабле я не приветствую насилие. Веди себя прилично если не хочешь оказаться за бортом.");
   };

   captain.onAttack = function (mob, ch, victim) {
	  mob.say("НУ КА ПРЕКРАТИ ЭТО НЕМЕДЛЕННО, %^C1!", ch);
	  ch.stop_fighting(true);
	  mob.recho("Капитан усмиряет нарушителя.");
   };

   captain.onArea = function (mob) {
	  var dice;
	  dice = .dice(1, 4);
	  if (dice == 1) {
		 mob.recho("Капитан задумчиво крякает и бормочет себе под нос: {gМоре переплыть - не поле перейти.{x");
	  } else if (dice == 2) {
		 mob.recho("Капитан мудро кивает и бормочет себе под нос: {gМорской волк во всем знает толк.{x");
	  } else if (dice == 3) {
		 mob.recho("Капитан отхлебывает ром из бутылки и и тихо напевает: {gПятнадцать человек на сундук мертвеца.{x");
	  } else if (dice == 4) {
		 mob.recho("Капитан встревоженно чешет бороду и бормочет: {gСегодня определенно будет шторм, чтобы мне пойти на корм акулам.{x");
	  }
   };

})
Run

done

reset 1 mob [VNUM капитана] 1 1
redit reset room
```

