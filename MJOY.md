# Аппаратная платформа MJOY(MJOY8) #
> Изначально MJoy был построен литовцем Mindaugas Milasauskas (он же MeanDog).<br>
<blockquote>Русский электронщик, известный под ником LazyCamel, серьёзно упростил монтажную схему MJoy'я.<br></blockquote>

<b>Схема Mercury (2011):</b><br>
компилирование прошивки "HARDWARE=1"<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/Mjoy_2011.png' /><br>

Изначально платформа MJOY была основана на МК ATmega8A-PU, к сожалению размер новой прошивки MMJOY никак не умещается в 8 Кб, поэтому МК заменен на более прогрессивные ATMEGA168-PU (16 Кб) или ATMEGA328-PU (32 Кб).<br>
<br>
<br>
<hr><br>
<br>
<br>
Вариант платы от Iran F. Oliveira<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/Mjoy_2011_Oliveira.png' /><br>
в формате Sprint-Layout 5.0 <a href='http://mmjoy.googlecode.com/svn/wiki/Mjoy_2011_Oliveira.lay'>http://mmjoy.googlecode.com/svn/wiki/Mjoy_2011_Oliveira.lay</a><br>
<br>
<br>
<hr><br>
<br>
<br>
<b>Перечень делатей (без учета деталей для программатора):</b>
<table><thead><th> <b>Название/Номинал</b> </th><th> <b>Количество</b> </th><th> <b>Примечание</b> </th></thead><tbody>
<tr><td> Резистор 82 Ом </td><td> 2 шт </td><td> (68-82 Ом) </td></tr>
<tr><td> Резистор 2.2 кОм </td><td> 1 шт </td><td>  </td></tr>
<tr><td> Резистор 4.7 кОм </td><td> 4 шт </td><td> (4.7-10 кОм) </td></tr>
<tr><td> Потенциометры (10—100 кОм) </td><td> до 6 шт </td><td> для осей, меньше номинал - лучше </td></tr>
<tr><td> Конденсатор 22 пФ </td><td> 2 шт </td><td> (15-22 пФ) </td></tr>
<tr><td> Конденсатор 100 нФ </td><td> 3 шт </td><td>  </td></tr>
<tr><td> Конденсатор 10 мкФ </td><td> 1 шт </td><td> (10-100мкФ) электролит  </td></tr>
<tr><td> Стабилитрон 3.6 в </td><td> 2 шт </td><td> (3.3-3.6 в) </td></tr>
<tr><td> Любой выпрямительный диод </td><td> до 28 шт </td><td> по 1 шт. на кнопку </td></tr>
<tr><td> Панелька DIP28 </td><td> 1 шт </td><td>  </td></tr>
<tr><td> Микросхема ATMEGA8/ATMEGA168/ATMEGA328 </td><td> 1 шт </td><td> DIP корпус </td></tr>
<tr><td> (ATMEGA8 - урезанная прошивка, до 4х осей и 16 кнопок)</td><td>  </td><td>  </td></tr>
<tr><td> Кварц 12/16/20 МГц </td><td> 1 шт </td><td> прошивка м.б. скомпилирована для 12/16/20 МГц </td></tr>
<tr><td> Катушка 10 мкГн </td><td> 1 шт </td><td>  </td></tr>
<tr><td> Кнопки </td><td> до 28 шт </td><td>  </td></tr>
<tr><td> Разъём USB </td><td> 1 шт </td><td>  </td></tr>
<tr><td> Разъёмы штыри </td><td> до 29 шт </td><td> 18 - вывод 6 осей, 4+7 - матрица кнопок  </td></tr>
<br>
<br>
<hr><br>
<br>
<br>
<b>Модификация MJOY8_35btn(35 аппаратных кнопок):</b><br>
компилирование прошивки "HARDWARE=5"<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/Mjoy_2011_35_btn.png' />
<br>
<br>
<hr><br>
<br>
<br>
<b>Ссылки, источники информации:</b><br>
Форум сухой <a href='http://www.sukhoi.ru/forum/showthread.php?t=24406'>http://www.sukhoi.ru/forum/showthread.php?t=24406</a><br>
Страничка mercury13 <a href='http://mercury13.tut.su/?q=mjoy'>http://mercury13.tut.su/?q=mjoy</a><br>