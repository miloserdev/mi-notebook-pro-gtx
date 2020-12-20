# mi-notebook-pro-gtx

## English guide

Xiaomi Mi Notebook Pro GTX BIOS Firmware or how to unbrick your laptop

How to unbrick your Xiaomi Mi Notebook Pro GTX if you flashed the BIOS with non Pro GTX firmware.

`XMAKB5R**0**P0 - Notebook Pro MX150/MX250 BIOS version`

`XMAKB5R**R**P0 - Notebook Pro GTX BIOS version`

If you flashed your Pro GTX with XMAKB5R0P0*** (XMAKB5R0P0A07, XMAKB5R0P0E07, XMAKB5R0P0300, XMAKB5R0P0401, XMAKB5R0P0502, XMAKB5R0P0603, XMAKB5R0P0906) versions of Pro MX150/MX250 firmware do this things to unbrick your laptop

1. Download [XMAKB5RRP0804.zip](https://github.com/miloserdev/mi-notebook-pro-gtx/blob/main/XMAKB5RRP0804.zip) and unzip.
2. Open platform.ini and find Platform_Check then change Flag=1 to Flag=0 (as shown in the picture)
![image](https://user-images.githubusercontent.com/37951044/102706465-2868ee80-42a3-11eb-95ab-0bdf469f2632.png)
(This option needed because now your Pro GTX think he is Pro MX150/MX250 version)
3. Plug in the power and don't unplug!
4. Run H2OFFT-Wx64.exe as administrator.
Your laptop will be restart several times and finnaly the BIOS will be updated to XMAKB5RRP0(XMAKB5RRP0804)



## Гайд на русском

Прошивка БИОС Xiaomi Mi Notebook Pro GTX или как восстановить свой ноут.

Как восстановить свой Xiaomi Mi Notebook Pro GTX если вы прошили БИОС не родной прошивкой.

`XMAKB5R**0**P0 - Версия БИОС для Notebook Pro MX150/MX250`

`XMAKB5R**R**P0 - Версия БИОС для Notebook Pro GTX`

Если вы прошили БИОС Pro GTX прошивкой для Pro MX150/MX250 XMAKB5R0P0*** (GTXMAKB5R0P0A07, XMAKB5R0P0E07, XMAKB5R0P0300, XMAKB5R0P0401, XMAKB5R0P0502, XMAKB5R0P0603, XMAKB5R0P0906) то делайте как написано в гайде чтобы восстановить свой ноут

Итак, вы прошили БИОС своей Pro GTX версией для ноутбуков Pro MX150/MX250.
Сейчас ваша GTX версия думает что работает на чипе TM1701 и в ней стоит видеокарта MX150 или MX250, напоминаю что её родной чип это TM1707 и в ней стоит GTX 1050 Max-Q,
следовательно она не знает как работать с оборудованием гарантировано появятся проблемы с работой такие как отвал звука (при этом драйвер Realtek будет думать что звук есть) и невозможность инициализировать графический чип GTX 1050

Решение:
1. Скачиваем [XMAKB5RRP0804.zip](https://github.com/miloserdev/mi-notebook-pro-gtx/blob/main/XMAKB5RRP0804.zip) и распаковываем
2. Открываем platform.ini, ищем Platform_Check и меняем Flag=1 на Flag=0 (как показано на картинке)
![image](https://user-images.githubusercontent.com/37951044/102706465-2868ee80-42a3-11eb-95ab-0bdf469f2632.png)
(Это нужно нам потому что Pro GTX думает что он Pro MX150/MX250)
3. Включаем ноут в зарядку и не отключаем! Если отключите питание то может вообще полететь БИОС и восстановить его можно будет только при помощи программатора.
4. Запускаем H2OFFT-Wx64.exe от имени администратора.
Ноут будет перезагружен несколько раз и в результате БИОС будет обновлён до XMAKB5RRP0(XMAKB5RRP0804)
