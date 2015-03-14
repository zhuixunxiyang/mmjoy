После замены родного контроллера на контроллер Pro Micro, встал вопрос о подключении органов управления и кнопок.

Задача стояла следующая:

1. Сохранить штатные разъемы и проводку;

2. Максимально использовать разводку плат;

3. Свести к минимуму работы с паяльником.


Начнем с кнопок корпуса. Они готовы к подключению как есть.

![http://pick.cyberpe.org/upl/alf/joy.logitech/002_1.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/002_1.jpg)

Но, если не будет хватать пинов BC, можно проделать следующее:


1. Перецарапать дорожки контактов 5 и 6 согласно рисунку.

2. Замкнуть между собой контакты 3 и 4 на разъеме платы (два посредине). Провод с 4-го контакта  не будет использоваться при подключении. Потому, лучше его вынуть из колодки.

4. Соединить проводом контакты указанные стрелками на изображении.

![http://pick.cyberpe.org/upl/alf/joy.logitech/002_2.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/002_2.jpg)

Ручка, в доработке, не нуждается.
От автора:

"По поводу подключения кнопок из ручки логитека.
Путем простого прозванивания, я определил, что трехногие SOT-23 на платке, в ручке, являются сдвоенными диодами. И по сути, эту платку, можно спокойно использовать в качестве диодной матрицы для любого контроллера.
Да, там матрица 3 на 4, без диодов для двух кнопок. Но, учитывая гигантское количество строк и столбцов кнопочных матриц, для большинства контроллеров из проекта MMJoy, я не вижу причины переформатировать имеющуюся разводку и диодную матрицу. Ведь достаточно подключить имеющиеся провода куда требуется. А все мелкие погрешности и перестановки в порядке кнопок, если это так уж необходимо, делаются тем же конфигуратором.
Лично я, таким образом, подключал ее еще к ArtJoy, и никаких проблем не испытывал. И, кстати, пользовался SV\_mapper.

Прикрепляю к письму табличку. С обозначением кто там столбцы, а кто - колонки. И направление диодов между ними. Дабы определить, к какой группе выводов, того или иного контроллера, подключать.
В итоге, по имеющимся 7 проводам, подключается 10 кнопок. И еще две, можно поставить, добавив свои диоды.

С уважением, YoZHeG."

![http://pick.cyberpe.org/upl/alf/joy.logitech/003_1.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/003_1.jpg)


Еще схемы:

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_1.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_1.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_2.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_2.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_3.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_3.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_4.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_4.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_5.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_5.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_6.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_6.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_7.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_7.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_8.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_8.jpg)

![http://pick.cyberpe.org/upl/alf/joy.logitech/001_9.jpg](http://pick.cyberpe.org/upl/alf/joy.logitech/001_9.jpg)


Материал подготовил xxx\_ALF\_xxx. При поддержке Mega\_mozg.