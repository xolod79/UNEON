# FPGA - [Soyuz Neon PK11/16](https://ru.wikipedia.org/wiki/Союз-Неон_ПК-11/16) for:
 - [MiST](https://github.com/mist-devel/mist-board/wiki).
 - [MiSTer](https://github.com/MiSTer-devel/Wiki_MiSTer/wiki).
 - [Terasic DE1](https://www.terasic.com.tw/cgi-bin/page/archive.pl?No=83).
 - and maybe other. 

Based on [1801ВМ2 (PDP-11 compatible) microprocessors reverse engineering](https://github.com/1801BM1/cpu11) and [Open replica Soyuz Neon PK11/16](https://zx-pk.ru/threads/29407-proekt-otkrytoj-repliki-soyuz-neon-pk-11-16.html).

Install on MiST:
For work with IDE HDD you need install firmware 240105 or later.
Copy UNEON.VHD to root directory SD Card and rename to UNEON.HD0

Install on MiSTer:
For work with IDE HDD you need copy MiSTer_Uneon on root Fat SDCard and add the following lines to Mister.ini:
[Uneon]
main=MiSTer_Uneon

Copy UNEON.VHD to Games\Uneon directory SD Card. Mount VHD file in core and select Reset on menu. 

Keyboard:
![Keyborad layout](/doc/ms7007.png)

| PC key       |  UNEON Key     |
|:------------:|:--------------:|
| F1           | К1             |
| F2           | К2             |
| F3           | К3             |
| F4           | К4             |
| F5           | К5             |
| Delete       | ПОМ   (HELP)   |
| End          | УСТ   (SET)    | 
| PageDown     | ИСП   (RUN)    |
| Insert       | СБРОС (RESET)  |
| Home         | СТОП  (STOP)   |
| Esc          | АР2            |
| Tab          | ТАБ            |
| RShift       | АЛФ            |
| LCrtl        | УПР            |
| RCtrl        | ГРАФ           |
| Caps Lock    | ФИКС           |
| Numpad ENTER | ВВОД           |
| :            | : *            |
| /            | / ?            |
| "            | @              |

TODO: 
