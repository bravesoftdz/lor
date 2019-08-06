[1](http://www.handhelds.org/) - общая информация по поддержке
наладонников.

**Нужен доброволец для наполнения этого раздела FAQ\!**

## Синхронизация. Как синхронизировать КПК или смартфон с Windows Mobile? Как получить доступ к такому КПК/смартфону?

Доступ к устройству дает [SynCE](http://www.synce.org). Графические
интерфейсы реализованы для
[KDE](http://www.kde-apps.org/content/show.php?content=14162) и
[Gnome](http://www.synce.org/moin/SynceTools/SynceGnome).

Если на машине нет KDE или Gnome, можно воспользоваться реализацией под
названием [PyRapi](http://freshmeat.net/projects/pyrapi/).

Для синхронизации календарей, почты и прочего есть проект
[multisync](http://multisync.sourceforge.net/news.php), работающий в
паре с SynCE. В данный момент можно синхронизироваться с Evolution и
адресной книгой KDE.

## На какие КПК можно установить Linux?

Ответить на этот вопрос поможет ресурс [2](http://www.handhelds.org/).
Самые хорошие результаты дают установки Linux на HP iPaq стары�
версий, например hx4700.

## Какие КПК идут сразу с установленным Linux?

  - [Sharp
    Zaurus](http://www.sharpusa.com/products/support/view_all_models/0,2326,16,00.html)
    (производство прекращено)
  - [Nokia 770](http://europe.nokia.com/770), [Nokia
    N800](http://europe.nokia.com/A4305062), [Nokia
    N810](http://europe.nokia.com/link?cid=PLAIN_TEXT_508842)

## Какие смартфоны идут с установленным Linux?

### Смартфоны Nokia

  - [Nokia N900](http://europe.nokia.com/n900)

### Смартфоны Motorola

Список моделей с Linux: A728, A760, A768, A780, A910, A1200, E680,
E680i, E680g, E690, Rokr E2, Rokr E6, Rokr E8, Rizr Z6, Razr 2 (v8, v9),
i876.

Из них в СНГ продаются [A1200e](http://wiki.openezx.org/A1200) и
[Razr2](http://wiki.openezx.org/Razr2).

Linux в этих телефонах используется исключительно для запуска закрытой
оболочки, написанной на Qt Embedded.

Информация о телефонах:

  - [OpenEZX](http://openezx.org) - сборник информации, портирование
    драйверов устройств телефонов Motorola в ветку ядра 2.6
  - [Раздел](http://forum.motofan.ru/index.php?showforum=100) форума
    motofan.ru, посвященный linux-смартфонам
  - Описание модификации linux, установленной в телефоне A1200e с точки
    зрения линуксоида: [ссылка](http://muromec.org.ua/tag/a1200/)
  - Модифицированная прошивка, с возможностью записи в rootfs (убрана
    защита на уровне mtd, тип корневой файловой системы сменен с
    cramfs на jffs2, изменена таблица разделов mtd, плюс стандартные
    улучшения) -
    [3](http://forum.motofan.ru/index.php?showtopic=140881)

## Какой дистрибутив ставить на PDA

Наиболее динамично развивающимся дистрибутивом на 2008 год является
[Ångström Linux](http://www.angstrom-distribution.org). Структура взята
из debian. В качестве пакетного менеджера используется ipkg. Для
построения используется система
[OpenEmbedded](http://www.openembedded.org). Есть версия также на i686.

Вторым дистрибутивом можно назвать [Familiar
Linux](http://familiar.handhelds.org).

## Какие графические среды существуют под PDA

  - [Qtopia](http://www.trolltech.com/products/qtopia/index.html) -
    закрытая рабочая среда, разрабатываемой компанией Trolltech для
    ограниченного набора устройств, и использующая библиотеку Qt. Для
    PDA hx4700 ее стоимость составляет $50.

<!-- end list -->

  - [OPIE](http://opie.handhelds.org/cgi-bin/moin.cgi/) - очень красивая
    и быстрая рабочая среда, написанная на Qt. Является форком закрытой
    рабочей среды
    [Qtopia](http://www.trolltech.com/products/qtopia/index.html). Не
    использует для вывода графики [X Window
    System](http://freedesktop.org/Software/xorg), поэтому портировать
    графические приложения сложнее, чем для GPE. Имеет приличную
    поддержку PIM и мультимедии.

<!-- end list -->

  - [GPE](http://gpe.handhelds.org/) - наиболее популярная среда,
    использующая для вывода графики [X Window
    System](http://freedesktop.org/Software/xorg). Написана на
    библиотеке GTK. Без ложного преувеличения можно назвать
    данную систему Gnome на PDA, так как существуют порты самы�
    популярных библиотек и приложений этой рабочей среды. Если вы
    хотите использовать свой PDA как мини-компьютер и органайзер и
    работать с полнофункциональными приложениями документооборота
    (например, abiword и gnumeric) - это наиболее подходящая для вас
    среда.

<!-- end list -->

  - [Maemo](http://maemo.org/) — базирующаяся на Debian Linux платформа
    для портативных устройств. Используется в интернет-планшетах Nokia
    770, Nokia N800, N810 и коммуникаторе Nokia N900. В основе Maemo
    лежат компоненты среды Gnome, в том числе графическая библиотека
    gtk. Б́ольшая часть кода Maemo открыта, и послужила основой для
    создания Ubuntu Mobile.

## Какие загрузчики используются Linux для мобильных устройств

Существует несколько загрузчиков Linux для PDA:

  - [LinExec](http://wiki.xda-developers.com/index.php?pagename=LinExec)
  - [HaRET](http://www.handhelds.org/moin/moin.cgi/HaRET)
  - [Garux](http://garux.sourceforge.net/), для устройств Palm
  - [SDG
    Bootloader](http://container.watje.org/index.php?title=SDG_bootloader).
    Также существует модифицированная версия загрузчика (автор, если не
    ошибаюсь, kmeaw), позволяющая грузиться не только с внутренней
    флешки, но и с CF-карты.
  - [bootldr-pxa](http://www.handhelds.org/feeds/bootldr/pxa/)

## Как установить Ångström Linux на PDA

Установка Linux на разных устройствах отличается в ряде моментов,
например, при установке загрузчика, вызове сервисного меню
устройства и частично бэкапе системы.

### Бэкап системы Windows Mobile и установка загрузчика

#### hx4700 и SDG Bootloader

Для начала нам потребуется карта памяти SD объемом от 128 мегабайт,
компьютер с линуксом и кредл. Все, что было на карте, будет
удалено\!

1\. Нажимаем одновременно кнопки Addressbook + iTask + Reset. 2.
Вставляем наладонник в кредл. 3. Запускаем minicom с параметром
-os. Наше устройство, если все нормально, называется /dev/ttyUSB0
(убедитесь в этом). 4. Копируем образ командой d2s.

Теперь на карточке окажется образ Windows Mobile. Предполагая, что карта
является устройством /dev/sda, скинуть образ на рабочий компьютер можно
как обычно с помощью команды dd:

    dd if=/dev/sda of=windows.img bs=130M count=1

Теперь установим загрузчик.

1\. Скачаем загрузчик
[отсюда](http://sdgsystems.net/pub/ipaq/hx4700/starterkit/) - файл
будет называться bootldr-1.X.X-hp.rom. 2. Поместим загрузчик на карту:

    dd if=bootldr.rom of=/dev/sda

3\. Установим загрузчик на устройство. Для этого вставим карту в
наладонник и нажмем Contacts + iTask + Reset.

### Установка дистрибутива

#### hx4700

Скачиваем файлы дистрибутива
[отсюда](http://www.angstrom-distribution.org/releases/2007.12/images/hx4700):

  - reflash.ctl - контрольный файл, в котором прописаны названия и файлы
    прошивок.
  - zImage-2.6.xx-hhXX-rX-hx4700.bin - ядро.
  - И один из файлов, название которого называется Angstrom.

Какой из Angstrom'ов? Это просто:

  - base - базовая система, только консоль, большинство утилит
    управления устройством отсутствует, ядро имеет
    ограниченное количество модулей.
  - console - полнофункциональная консольная система.
  - minimalist - система с минимальным набором графических программ.
  - x11-image - полнофункциональная система с набором графически�
    программ под большинство нужд.

Скачиваем те, что имеют расширение jffs2.

Установка: 1. Проверяем, правильно ли прописаны файлы в reflash.ctl. 2.
Переписываем файлы на карту CF. Если карта имеет объем больше 128Мб, то
безопаснее создать первый раздел на 128Mb и переписать файлы туда. Карта
должна иметь файловую систему FAT (рекомендуется FAT16, но прекрасно
работает и FAT32). 3. Вставляем карту CF в наладонник. 4. Нажимаем
Contact + Mail + Reset. 5. Загрузчик покажет строчки с названиями ядер
(zImage) и системы (Angstrom). Клавишами Contact и Calendar можно
перемещать курсор, а клавишей iTask делать выбор. Выберите ядро и
нажмите iTask. 6. Когда загрузчик проверит целостность файла, он
попросит подтверждение на прошивку. Нажмите клавишу Record. 7.
После того, как ядро прошьется, нажмите Record еще раз, чтобы
вернуться в меню и выбрать для прошивки систему. 8. После
прошивки вытащите все карточки и нажмите Power. Первая загрузка
будет довольно долгой. В конце система предложит откалибровать экран
и ввести имя пользователя, который будет работать с наладонником.

Иногда загрузчик может не увидеть файлов вообще. Нажмите Record для
повторения чтения.

### Настройка сети

Пакетный менеджер мобильного линукса умеет обновляться и ставить
необходимые программы из репозиториев в Интернете. Поэтому
необходимо как-то подключить наладонник к сети. Наиболее простым
способом является подключение интернета через настольный компьютер -
это же позволит сразу заходить в консоль со всеми вытекающими.

Для дистрибутива Fedora создаем файл
/etc/sysconfig/network-script/ifcfg-usb0

    # Realtek Semiconductor Co., Ltd. RTL-8139/8139C/8139C+
    DEVICE=usb0
    BOOTPROTO=none
    IPADDR=192.168.0.200
    ONBOOT=no
    NETMASK=255.255.255.0
    NETWORK=192.168.0.0
    BROADCAST=192.168.0.255
    TYPE=Неизвестный

Вот такой файлик под названием ipaqh кладем куда-нибудь в /usr/local/bin

    ROUTE=/sbin/route
    IPTABLES=/sbin/iptables
    MODPROBE=/sbin/modprobe
    AWK=/bin/awk
    IFCONFIG=/sbin/ifconfig
    LOCAL=127.0.0.1/32

    EXT_IF="eth0"
    EXT_IP=172.16.128.5
    EXT_NET=172.16.128.0/255.255.0.0

    sudo $MODPROBE cdc_subset
    sudo $MODPROBE usbnet
    sudo $IFCONFIG usb0 192.168.0.200
    echo 1 > /proc/sys/net/ipv4/ip_forward

    INT_NET=192.168.0.0
    INT_MASK=255.255.255.0
    INT_IP=192.168.0.200

    sudo $MODPROBE ip_conntrack
    sudo $MODPROBE ip_tables
    sudo $MODPROBE iptable_filter
    sudo $MODPROBE iptable_mangle
    sudo $MODPROBE iptable_nat
    sudo $MODPROBE ipt_LOG
    sudo $MODPROBE ipt_limit
    sudo $MODPROBE ipt_MASQUERADE
    sudo $MODPROBE ipt_REJECT
    sudo $MODPROBE ip_conntrack_ftp
    sudo $MODPROBE ip_nat_ftp

    #Remove # if you don't have another iptables firewall rules
    #sudo $IPTABLES -X
    #sudo $IPTABLES -F FORWARD
    #sudo $IPTABLES -F INPUT
    #sudo $IPTABLES -F OUTPUT
    #sudo $IPTABLES -t nat -F POSTROUTING

    sudo $IPTABLES -A INPUT -j ACCEPT
    sudo $IPTABLES -A OUTPUT -j ACCEPT

    #Forwarding
    sudo $IPTABLES -A FORWARD -j ACCEPT

    sudo $IPTABLES -t nat -A POSTROUTING -o $EXT_IF -j MASQUERADE

    sudo $ROUTE del default gw 192.168.10.200

На наладоннике в файле /etc/network/interfaces:

```
        auto usb0
        iface usb0 inet static
        address 192.168.0.202
        netmask 255.255.255.0
        network 192.168.0.0
        gateway 192.168.0.200
```

На наладоннике в файле /etc/resolv.conf прописываем ваш DNS.

Теперь вставляем устройство в кредл и запускаем ipaqh. Должен появиться
сетевой usb-интерфейс, а на наладоннике - интернет.

### Зачем подключать файл подкачки (swap-файл) и как это сделать?

На наладоннике достаточно ограниченный объем памяти - от 32-х до 128-ми
мегабайт. При запуске тяжелых приложений память потребляется зачастую в
большем объеме, чем есть на устройстве. Поэтому, как и на больши�
компьютерах, мы создадим swap-файл на карте памяти. Обычно с
картой CF проблем меньше. Чем быстрее ваша карта памяти, тем
быстрее будут работать приложения.

Для этого воспользуемся линуксом на настольном компьютере. Создаем
подкачки на 98Мб:

    root@linux# touch swap
    root@linux# dd if=/dev/zero of=./swap bs=1M count=98
    root@linux# mkswap ./swap

Копируем файл на второй раздел карты CF и пропишем в файле /etc/fstab
наладонника такую строчку:

    /media/hda2/swap        swap        swap    defaults        0 0

Теперь подключаем swap:

    root@linux# swapon -a

### Как обновить программы установленного дистрибутива

Как и любой другой, использующий пакетный менеджер ipkg, дистрибутив
можно и нужно обновить сразу после установки двумя командами:

    root@linux# ipkg update
    root@linux# ipkg upgrade

Иногда последнюю команду стоит повторить.

### Установка полезного комплекта программ

Часть программ будет взята из нестабильных репозитариев. Поэтому для
начала нам следует их подключить.

Создайте файл /etc/ipkg/hx4700un-feed.conf

    src/gz hx4700un http://www.angstrom-distribution.org/unstable/feed/armv5te/machine/hx4700/

и файл /etc/ipkg/unstable-feed.conf

    src/gz unstable http://www.angstrom-distribution.org/unstable/feed/armv5te/base

После этого выполните команду

    ipkg update

Дальше создадим файлик с любым названием, который и установит
необходимые нам программы.

    #!/bin/sh
    ipkg update
    ipkg upgrade
    ipkg install fbreader
    ipkg install abiword
    ipkg install abiword-plugin-opendocument
    ipkg install abiword-plugin-openwriter
    ipkg install abiword-plugin-mswrite
    ipkg install abiword-plugin-jpeg
    ipkg install gnumeric
    ipkg install gnumeric-plugin-openoffice
    ipkg install gnumeric-plugin-excel
    ipkg install mplayer
    ipkg install gpdf
    ipkg install gaim
    ipkg install gaim-protocol-oscar
    ipkg install gpe-gallery
    ipkg install gpe-today
    ipkg install gpe-task-pim
    ipkg install xstroke
    ipkg install sudo
    ipkg install xev
    ipkg install x11vnc
    ipkg install mc

### Дальнейшая доработка дистрибутива

#### Как настроить русский ввод на виртуальной клавиатуре?

В состав дистрибутива входит matchbox и, соответственно,
matchbox-keyboard. Русская раскладка есть, но нет значка с лого
клавиатуры и файла, благодаря которому происходит включение
этой клавиатуры.

В каталоге /usr/share/applications/inputmethods создаем файл
matchbox-keyboard-ru.desktop:

    [Desktop Entry]
    Name=Ru-Keyboard
    Comment=Russian Virtual Keyboard
    Exec=matchbox-keyboard ru
    Type=Application
    Icon=matchbox-keyboard-ru.png
    Categories=Panel;Utility;MB
    X-MB-INPUT-MECHANSIM=True

Значок можно взять на сайте [Linux на КПК](http://www.mobilelinux.ru)
вот
[тут](http://www.mobilelinux.ru/user_files/articles/matchbox-keyboard-ru.png)
и скопировать в папку /usr/share/pixmaps.

#### Как подключить нормальные шрифты?

Копируем шрифты из Windows в папку /usr/share/fonts/truetype. Если не
сильно экономить место, то там должны оказаться следующие файлы:

    andalemo.ttf
    arialbd.ttf
    arialbi.ttf
    ariali.ttf
    arial.ttf
    ariblk.ttf
    comicbd.ttf
    comic.ttf
    courbd.ttf
    courbi.ttf
    couri.ttf
    cour.ttf
    DejaVuSans-BoldOblique.ttf
    DejaVuSans-Bold.ttf
    DejaVuSans-ExtraLight.ttf
    DejaVuSansMono-BoldOblique.ttf
    DejaVuSansMono-Bold.ttf
    DejaVuSansMono-Oblique.ttf
    DejaVuSansMono.ttf
    DejaVuSans-Oblique.ttf
    DejaVuSans.ttf
    georgiab.ttf
    georgiai.ttf
    georgia.ttf
    georgiaz.ttf
    impact.ttf
    list.txt
    symbol.ttf
    tahomabd.ttf
    tahoma.ttf
    timesbd.ttf
    timesbi.ttf
    timesi.ttf
    times.ttf
    verdanab.ttf
    verdanai.ttf
    verdana.ttf
    verdanaz.ttf
    webdings.ttf
    wingding.ttf

Для моноширинных шрифтов, за исключением терминала, рекомендуется Andale
Mono. Для интерфейса - Arial или Tahoma.

### Как подключить беспроводную клавиатуру Луч-BT? Как сделать переключения языка прямо с клавиатуры?

Беспроводные клавиатуры бывают двух типов:

  - Serial, соединяющиеся через bluetooth с компьютером и далее
    открывающие com-порт, через который и идет общение.
  - HID, работающие по специальному протоколу, созданному как раз для
    устройств управления.

Если со вторыми работа идет стандартными методами, то с первыми все
сложнее - для каждой клавиатуры необходим драйвер под программу с
названием kbdd. Клавиатура Луч-BT относится к типу Serial. Для того,
чтобы подключить клавиатуру, использовался вот [этот
документ](http://www.teleology.ru/projects_ru/informatics_ru/open_ru/hx4700_ru/angstrom_ru).
Поэтому за объяснениями - в него. А здесь будет описана сжатая
установка.

В папке /etc/X11/ создаем файлик xmodmap.rus. Это раскладка с qwerty и
йцукен. Первой должна идти английская клавиатура, иначе не заработает
терминал.

    keycode 75 = XF86Calendar
    keycode 76 = telephone
    keycode 95 = XF86Mail
    keycode 96 = XF86AudioRecord
    keycode 110 = XF86Start
    keycode 124 = XF86PowerDown

    clear shift
    clear control
    clear mod1
    clear mod2
    clear mod3
    clear mod4

    keycode  10 = 1 exclam
    keycode  11 = 2 at 2 quotedbl
    keycode  12 = 3 sterling 3 numbersign
    keycode  13 = 4 semicolon 4 dollar
    keycode  14 = 5 percent 5 percent
    keycode  15 = 6 asciicircum 6 colon
    keycode  16 = 7 ampersand 7 question
    keycode  17 = 8 asterisk 8 asterisk
    keycode  18 = 9 parenleft 9 parenleft
    keycode  19 = 0 parenright 0 parenright
    keycode  20 = minus underscore
    keycode  21 = equal plus
    keycode  22 = BackSpace
    keycode  23 = Tab Tab
    keycode  24 = q Q Cyrillic_shorti Cyrillic_SHORTI
    keycode  25 = w W Cyrillic_tse Cyrillic_TSE
    keycode  26 = e E Cyrillic_u Cyrillic_U
    keycode  27 = r R Cyrillic_ka Cyrillic_KA
    keycode  28 = t T Cyrillic_ie Cyrillic_IE
    keycode  29 = y Y Cyrillic_en Cyrillic_EN
    keycode  30 = u U Cyrillic_ghe Cyrillic_GHE
    keycode  31 = i I Cyrillic_sha Cyrillic_SHA
    keycode  32 = o O Cyrillic_shcha Cyrillic_SHCHA
    keycode  33 = p P Cyrillic_ze Cyrillic_ZE
    keycode  34 = bracketleft braceleft Cyrillic_ha Cyrillic_HA
    keycode  35 = bracketright braceright Cyrillic_hardsign Cyrillic_HARDSIGN
    keycode  36 = Return
    keycode  37 = Control_L
    keycode  38 = a A Cyrillic_ef Cyrillic_EF
    keycode  39 = s S Cyrillic_yeru Cyrillic_YERU
    keycode  40 = d D Cyrillic_ve Cyrillic_VE
    keycode  41 = f F Cyrillic_a Cyrillic_A
    keycode  42 = g G Cyrillic_pe Cyrillic_PE
    keycode  43 = h H Cyrillic_er Cyrillic_ER
    keycode  44 = j J Cyrillic_o Cyrillic_O
    keycode  45 = k K Cyrillic_el Cyrillic_EL
    keycode  46 = l L Cyrillic_de Cyrillic_DE
    keycode  47 = semicolon colon Cyrillic_zhe Cyrillic_ZHE
    keycode  48 = apostrophe quotedbl Cyrillic_e Cyrillic_E
    keycode  50 = Shift_L
    keycode  52 = z Z Cyrillic_ya Cyrillic_YA
    keycode  53 = x X Cyrillic_che Cyrillic_CHE
    keycode  54 = c C Cyrillic_es Cyrillic_ES
    keycode  55 = v V Cyrillic_em Cyrillic_EM
    keycode  56 = b B Cyrillic_i Cyrillic_I
    keycode  57 = n N Cyrillic_te Cyrillic_TE
    keycode  58 = m M Cyrillic_softsign Cyrillic_SOFTSIGN
    keycode  59 = colon less Cyrillic_be Cyrillic_BE
    keycode  60 = period greater Cyrillic_yu Cyrillic_YU
    keycode  61 = question slash period comma
    keycode  62 = Shift_R
    keycode  64 = Meta_L Alt_L
    keycode  65 = space space
    keycode  66 = Caps_Lock
    keycode  78 = Mode_switch
    keycode 131 = backslash bar slash backslash
    keycode 119 = Delete
    keycode 133 = Insert

    add shift   = Shift_L
    add control = Control_L
    add mod1    = Alt_L

    ! Use CapsLock as rus/lat switch key.

    clear lock
    clear mod5
    add mod5 = Caps_Lock Mode_switch

Меняем параметры в файлах xmodmap-left:

    keycode 111 = Up
    keycode 116 = Down
    keycode 114 = Right
    keycode 113 = Left

и xmodmap-portrait:

    keycode 111 = Up
    keycode 113 = Left
    keycode 114 = Right
    keycode 116 = Down

Создаем симлинки с названиями hx4700.xmodmap и keyboardless.xmodmap на
файл xmodmap.rus. Согласно документу, упоминаемому выше, создаем пару
файлов для включения клавиатуры. bt-kbd-on:

    #!/bin/sh
    PATH=/sbin:/bin:/usr/sbin:/usr/bin
    RF=rfcomm0
    DEV=/dev/$RF
    BD=00:0A:3A:32:9B:09
    pidof hciattach >/dev/null || sudo hciattach /dev/ttyS1 texas 115200
    sleep 1
    rfcomm | grep ^$RF: >/dev/null && sudo rfcomm release $DEV
    sudo rfcomm bind $DEV $BD
    sleep 1
    sudo kbdd -p $DEV -t smartbt
    sudo rfcomm release $DEV
    sudo fuser /dev/rfcomm* >/dev/null 2>/dev/null || sudo killall hciattach

В параметре BD нужно прописать адрес своей клавиатуры. Его можно узнать
с помощью команды hcitool scan

bt-kbd.sw:

    #!/bin/sh
    pidof kbdd >/dev/null && sudo killall kbdd || exec ~/bin/bt-kbd-on

В файле \~/.keylaunchrc:прописываем:

    key=???XF86Start:-:/usr/bin/xrandr.sw
    key=???Held XF86Start:-:/usr/bin/bt-kbd.sw &

По большой и светлой идее это должно заставить включать и выключать
клавиатуру (у меня, jackill'а, не работает). Установим kbdd. Лучше
будет собрать программу с помощью bitbake. В файле sudoers пропишем:

    your_user ALL=/sbin/hciattach,/bin/rfcomm,/usr/sbin/kbdd,/usr/bin/fuser,/usr/bin/killall

Теперь можно запустить bt-kbd-on и через пару-тройку секунд клавиатура
заработает. Переключение на русский и обратно осуществляется клавишей
Caps Lock. Клавишу Esc не делал. Клавиша alt является, похоже,
аппаратной, посему ее не удалось запрограммировать. Рекомендую
просто поменять ее местом со стоящей рядом, ибо alt повешен на нее.

### Как починить автомонтирование карты SD, имеющей разделы?

Ребятам из Angstrom удалось как-то поломать автомонтирование, работающее
даже в Familiar. При первой загрузке карта с разделами монтируется
правильно, а вот при второй уже начинаются глюки - система
монтирует карту напрямую, не видя разделов.

Поэтому либо придется монтировать карточку вручную, либо удалить с нее
разделы и форматировать само устройство, т.е. вставить ее на большой
компьютер и сказать нечто вроде такого:

    mkfs.vfat /dev/sda

Карты CF монтируются нормально.

Ещё вариант: отключить автомонтирование от angstrom, установить hal и
монтировать флешки из thunar или из другой утилиты, поддерживающей
hal.

## Как посмотреть содержимое пакета .ipk?

    ar x packet_name.ipk