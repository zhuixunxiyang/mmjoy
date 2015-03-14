**Прошивка проекта MMJOY.**<br>

Инструменты использованные для разработки прошивки:<br>
1) "V-USB" версия от 20121206<br>
2) "WinAVR" версия от 20100110<br>

Моя структура каталогов инструментов и исходников:<br>
1) Каталог "v-usb" D:\Develop\vusb-20121206\examples\MMJoy\mmjoy_firmware<br>
2) Каталог "WinAVR" D:\Develop\WinAvr<br>
3) Исходники прошивки D:\Develop\vusb-20121206\examples\MMJoy\mmjoy_firmware<br>

Настройка прошивки под разные платформы, кварцы и(или) микроконтроллеры:<br>
все изменения вносятся в файл "Makefile" (D:\Develop\vusb-20121206\examples\MMJoy\mmjoy_firmware)<br>
1) выбор аппаратной платформы<br>
HARDWARE = ??? # выбор аппаратной платформы (1-MJOY8(2011); 2-MJOY16; 3-METABOARD; 4-AVR_USB_MEGA16)<br>
2) используемый МК<br>
DEVICE = ??? # микроконтроллер платформы<br>
3) Частота кварца<br>
F_CPU = ??? # частота кварца<br>

<b>Конфигуратор проекта MMJOY.</b><br>

Инструменты использованные для разработки конфигуратора:<br>
1) "Delphi 7"<br>
2) "JEDI Visual Component Library" версия JVCL347CompleteJCL241-Build4571<br>

Моя структура каталогов инструментов и исходников:<br>
1) Каталог "Delphi 7" D:\Develop\Delphi7<br>
2) Каталог "JEDI jcl" D:\Develop\Delphi7\jcl<br>
3) Каталог "JEDI jvcl" D:\Develop\Delphi7\jvcl<br>
4) Исходники конфигуратора D:\Develop\vusb-20121206\examples\MMJoy\mmjoy_software<br>

Никаких измненений исходного текста конфигуратора для разных аппаратных платформ не нужно.<br>

<b>Ссылки для скачивания:</b><br>
V-USB <a href='http://www.obdev.at/products/vusb/download.html'>http://www.obdev.at/products/vusb/download.html</a><br>
WinAVR <a href='http://winavr.sourceforge.net/'>http://winavr.sourceforge.net/</a><br>
JEDI Visual Component Library <a href='http://jvcl.delphi-jedi.org/'>http://jvcl.delphi-jedi.org/</a><br>