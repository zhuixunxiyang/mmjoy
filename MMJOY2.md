# Аппаратная платформа MMJOY2(USB 2.0) #

**MMJOY2.a(AT90USB646)**<br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy.JPG'>http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy.JPG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board1.JPG'>http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board1.JPG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board2.JPG'>http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board2.JPG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board3.JPG'>http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy_board3.JPG</a><br>
файл схемы: <a href='http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy.LAY'>http://mmjoy.googlecode.com/svn/wiki/AT90USB646_MMJoy.LAY</a> (c)mega_mozg<br>


<br>
<br>
<hr><br>
<br>
<br>
<b>MMJOY2.b(ATMEGA32U4-ProMicro)</b><br>
(схема аналог для самостоятельного изготовления)<br>
<a href='http://mmjoy.googlecode.com/svn/wiki/m32u4.JPG'>http://mmjoy.googlecode.com/svn/wiki/m32u4.JPG</a><br>
файл схемы: <a href='http://mmjoy.googlecode.com/svn/wiki/m32u4.lay'>http://mmjoy.googlecode.com/svn/wiki/m32u4.lay</a> (c)China<br>

готовая плата<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/ProMicro.jpg' /><br>


<br>
<br>
<hr><br>
<br>
<br>
<b>MMJOY2.c(ATMEGA32U4-Teensy2)</b><br>

готовая плата<br>
<a href='http://mmjoy.googlecode.com/svn/wiki/Teensy_2_pins.PNG'>http://mmjoy.googlecode.com/svn/wiki/Teensy_2_pins.PNG</a><br>
<img src='http://mmjoy.googlecode.com/svn/wiki/Teensy_2_pins_joy.png' /><br>


<br>
<br>
<hr><br>
<br>
<br>
<b>MMJOY2.d (ATMEGA32U4-Void_6/36)</b><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/m32u4_6axis_36btn_void.PNG'>http://mmjoy.googlecode.com/svn/wiki/m32u4_6axis_36btn_void.PNG</a><br>
файл схемы: <a href='http://mmjoy.googlecode.com/svn/wiki/m32u4_6axis_36btn_void.lay6'>http://mmjoy.googlecode.com/svn/wiki/m32u4_6axis_36btn_void.lay6</a> (c)Void/China<br>

<br>
<br>
<hr><br>
<br>
<br>
<b>MMJOY2.e (ATMEGA32U4-YoZHeG_888, USB2.0)</b><br>
материалы в разработке<br>

<br>
<br>
<hr><br>
<br>
<br>
<b>MMJOY2.f (AT90USB1286-Teensy++2.0, USB2.0)</b><br>
<img src='http://mmjoy.googlecode.com/svn/wiki/Teensy++_2_pins_joy.png' /><br>
<br>
<br>
<hr><br>
<br>
<br>
<br>
<b>Примечания по прошивке с помощью родного бутлоадера и программы Flip</b><br>
(информация для пользователей кто собирает контроллер с нуля)<br>
Микроконтроллеры "AT90USB646" и "ATMEGA32U4" с завода имеют встроенный бутлоадер - встроенный загрузчик прошивальщик. Поэтому правильно собранная плата при подключении к компьютеру сразу опознается ОС. Для прошивки необходимо скачать и установить бесплатный софт FLIP с сайта ATMEL.<br>
Ссылка на страничку загрузки <a href='http://www.atmel.com/tools/flip.aspx'>http://www.atmel.com/tools/flip.aspx</a><br>
<br>
Для активации загрузчика необходимо выполнить следующие действия.<br>
На платах с кнопками:<br>
- подключаем плату через USB<br>
- нажимаем кнопку RST<br>
- удерживая кнопку RST, нажимаем кнопку HWB<br>
- удерживая кнопку HWB, отпускаем кнопку RST<br>
- отпускаем HWB<br>
На платах без кнопки, с перемычкой HWB:<br>
- ставим перемычку HWB<br>
- подключаем плату через USB<br>
- снимаем перемычку HWB<br>
<br>
Если всё сделано верно ОС определит новое устройство. Название соответственно используемому микроконтроллеру.<br>
Если в ОС устройство определяется с ошибкой, необходимо в диспетчере устройств найти устройство, и обновить драйвер, указав в качестве источника каталог с установленным ПО Flip.<br>
<br>
<br>
<hr><br>
<br>
