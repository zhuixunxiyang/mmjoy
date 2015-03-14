= Аппаратная платформа METABOARD =<br>
Metaboard - дешевая Arduino-совместимая макетная плата (её можно программировать прямо из популярной среды разработки Arduino IDE). Metaboard имеет интерфейс USB, программируется прямо через него, и позволяет делать USB-устройства на основе библиотеки V-USB. Использование недефицитных деталей (микроконтроллер ATmega168 или ATmega328 в корпусе DIP, резисторы и конденсаторы со штыревыми выводами) позволяет собрать такую плату самостоятельно в домашних условиях.<br>
компилирование прошивки "HARDWARE=3"<br>
<br>
<b>Исходная схема:</b><br>
<img src='http://microsin.net/images/stories/hard/Metaboard-circuit.gif' /><br>
<b>Исходная плата:</b><br>
<a href='http://microsin.net/images/stories/hard/metaboard-IMG_1402.JPG'>http://microsin.net/images/stories/hard/metaboard-IMG_1402.JPG</a><br>
<a href='http://microsin.net/images/stories/hard/metaboard-IMG_1412.JPG'>http://microsin.net/images/stories/hard/metaboard-IMG_1412.JPG</a><br>
<b>Доработка платы:</b><br>
<img src='http://mmjoy.googlecode.com/svn/wiki/METABOARD_bot.png' /> <img src='http://mmjoy.googlecode.com/svn/wiki/METABOARD_bot_sgn.png' /><br>
<img src='http://mmjoy.googlecode.com/svn/wiki/METABOARD_top.png' /> <img src='http://mmjoy.googlecode.com/svn/wiki/METABOARD_top_sgn.png' /><br>
<br>
дорабока минимальная:<br>
выведены штырьки портов A, B и D.<br>
для цепей АЦП еще выведены штырьки для земли и питания.<br>
для АЦП подпаян конденсатор 0.1uF (AREF-GND)<br>
допаяны 6 штук 10ком резисторов для матрицы кнопок<br>
<br>
<b>Перечень делатей (без учета деталей основной платы, только что нужно для джойстика):</b><br>
<table><thead><th> <b>Название/Номинал</b> </th><th> <b>Количество</b> </th><th> <b>Примечание</b> </th></thead><tbody>
<tr><td> Резистор 4.7 кОм </td><td> 6 шт </td><td> (4.7-10 кОм) </td></tr>
<tr><td> Потенциометры (10—100 кОм) </td><td> до 6 шт </td><td> для осей, меньше номинал - лучше </td></tr>
<tr><td> Любой выпрямительный диод </td><td> до 36 шт </td><td> по 1 шт. на кнопку </td></tr>
<tr><td> Кнопки </td><td> до 36 шт </td><td>  </td></tr>
<tr><td> Разъёмы штыри </td><td> до 30 шт </td><td> 18 - вывод 6 осей, 6+6 - матрица кнопок  </td></tr></tbody></table>

<b>Ссылки, источники информации:</b><br>
microsin <a href='http://microsin.net/programming/AVR/metaboard.html'>http://microsin.net/programming/AVR/metaboard.html</a><br>