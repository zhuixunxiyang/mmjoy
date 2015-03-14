= Аппаратная платформа. Общая информация. =<br>
<br>
Для разработки собственной аппаратной платформы необходимы выполнить следующие условия<br>
<br>
1.)подобрать совместимый с библиотекой V-USB микроконтроллер Atmel AVR:<br>
1.1.) микроконтроллер должен работать на частотах как минимум 12Мгц (16Мгц или 20Мгц)<br>
1.2.) не меньше 16Кб флеш памяти(из них 2Кб на реализацию V-USB)<br>
1.3.) не меньше 512Б ЕЕПРОМ памяти(для хранения конфигурации джойстика)<br>
<br>
2.) Выполнить разводку платы с учетом компонентов необходимых V-USB, и для джойстика:<br>
2.1.) Варианты схемы V-USB<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/hardware_overall_vusb.gif' /><br>
стандартная схема<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/hardware_overall_vusb_mjoy.gif' /><br>
схема mjoy8<br>
2.2.) Схема подключения датчиков осей<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/hardware_overall_adc.gif' /><br>
(взято из схемы mjoy8)<br>
2.3.) Схема подключения матрицы кнопок<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/hardware_overall_btn.gif' />
(взято из схемы mjoy8)<br>
<br>
3.) Произвести необходимые изменения в исходном коде прошивки:<br>
3.1.) добавить название аппаратной платформы (usbconfig.h)<br>
3.2.) указать порты ввода/вывода V-USB (usbconfig.h)<br>
3.3.) опрос матрицы кнопок, функции GetFirstBtn() и GetHardwareData()<br>
<br>
4.) Произвести необходимые изменения в исходном коде конфигуратора:<br>
4.1.) добавить название аппаратной платформы<br>
<br>
Пример программирования фьюз битов<br>
<a href='http://mmjoy.googlecode.com/svn/wiki/avr_fuse.PNG'>http://mmjoy.googlecode.com/svn/wiki/avr_fuse.PNG</a>