<br>
<b>Замена электроники Defender Cobra M5</b><br>

<br>
платки TLE5010/5011<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5915.jpg' /><br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5918.jpg' /><br>
шести-проводной интерфейс, из них пять проводов общие(помечены звездочками)<br>
1) "GND" и "VCC/POW" питание, общие для всех сенсоров<br>
2) "SPI-MISO" и "SPI-SCK" цифровая шина SPI, общие для всех цифровых сенсоров<br>
3) "TLE5010-GEN" опорная частота 4Mhz, используется только для TLE5010/5011 и подключается только к "B6" ножке<br>
4) "SPI-CS (TLE5010)" уникальный провод для каждого подключенного сенсора, название подключенной ножки контроллера позже указывается в конфигураторе<br>

<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5903.jpg' /><br>
исходное состояние, контроллер первых версий(atmega8)<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5904.jpg' /><br>
без мозгов<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5906.jpg' /><br>
разборка механики<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5908.jpg' /><br>
старые марсы<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5909.jpg' /><br>
новые TLE5010/5011<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5910.jpg' /><br>
сборка механики<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5845.jpg' /><br>
исходное состояние электроники в ручке кобры<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5845_.jpg' /><br>
схема что нужно сделать. убрать одну перемычку, и добавить две<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5873.jpg' /><br>
исправленная электроника ручки<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5911.jpg' /><br>
готовим подключение ручки к контролеру. внимание, цвета (или их порядок) могут различаться, поэтому отталкиваемся только от порядка в коннекторе. четыре провода общие с проводами от сенсоров TLE5010(питание и SPI-MISO/SPI-SCK)<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5912.jpg' /><br>
колёсико газа<br>
<br>
<a href='https://mmjoy.googlecode.com/svn/wiki/CobraM5/Pins_Sparkfun[promicro].PNG'>https://mmjoy.googlecode.com/svn/wiki/CobraM5/Pins_Sparkfun[promicro].PNG</a>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/DSCF5913.jpg' /><br><br>
подключаем всё к промикро<br>
<br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/MMJoy_cnfg1.png' /><br>
<img src='https://mmjoy.googlecode.com/svn/wiki/CobraM5/MMJoy_cnfg2.png' /><br>
конфигурация, возможно придётся поменять местами X и Y, а также где-то включить инверсию. еще забиндить кнопки по своему усмотрению<br>