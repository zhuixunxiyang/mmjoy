= Аппаратная платформа AVR\_USB\_MEGA16 =<br>
Макетная плата AVR-USB-MEGA16 спроектирована для быстрой разработки низкоскоростных (low-speed) устройств USB на микроконтроллере ATmega16 (или ATmega32), при этом протокол USB реализован программно, без использования дополнительных специализированных чипов. Это решение хорошо подходит для проектирования таких периферийных устройств для компьютера, которые не требуют высоких скоростей обмена по шине USB (подключение датчиков, устройств ввода, специализированных программаторов для чипов).<br>
компилирование прошивки "HARDWARE=4"<br>

<b>Исходная схема:</b><br>
<img src='http://microsin.net/images/stories/hard/avr-usb-mega16-sch.jpg' /><br>
<b>Исходная плата:</b><br>
<a href='http://microsin.net/images/stories/hard/avr-usb-mega16-IMG_8082.JPG'>http://microsin.net/images/stories/hard/avr-usb-mega16-IMG_8082.JPG</a><br>
<a href='http://microsin.net/images/stories/hard/avr-usb-mega16-IMG_8085.JPG'>http://microsin.net/images/stories/hard/avr-usb-mega16-IMG_8085.JPG</a><br>

<b>Схема доработки:</b><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_lay.PNG'>http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_lay.PNG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16.LAY'>http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16.LAY</a><br>
<b>Доработка платы:</b><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_top.JPG'>http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_top.JPG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_top_sgn.JPG'>http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_top_sgn.JPG</a><br>
<a href='http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_bot.JPG'>http://mmjoy.googlecode.com/svn/wiki/AVR_USB_MEGA16_bot.JPG</a><br>
<b>Перечень делатей (без учета деталей основной платы, только что нужно для джойстика):</b><br>
<table><thead><th> <b>Название/Номинал</b> </th><th> <b>Количество</b> </th><th> <b>Примечание</b> </th></thead><tbody>
<tr><td> Резистор 4.7 кОм </td><td> 6 шт </td><td> (4.7-10 кОм) </td></tr>
<tr><td> Потенциометры (10—100 кОм) </td><td> до 8 шт </td><td> для осей, меньше номинал - лучше </td></tr>
<tr><td> Любой выпрямительный диод </td><td> до 48 шт </td><td> по 1 шт. на кнопку </td></tr>
<tr><td> Кнопки </td><td> до 48 шт </td><td>  </td></tr>
<tr><td> Разъёмы штыри </td><td> до 38 шт </td><td> 24 - вывод 8 осей, 6+8 - матрица кнопок  </td></tr></tbody></table>

<b>Ссылки, источники информации:</b><br>
microsin <a href='http://microsin.net/programming/AVR/avr-usb-mega16.html'>http://microsin.net/programming/AVR/avr-usb-mega16.html</a><br>