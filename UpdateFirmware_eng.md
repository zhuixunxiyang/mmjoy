**ИНФОРМАЦИЯ УСТАРЕЛА. Используем бутлодер и программу "JoyLoader".**<br>
<b>INFORMATION OUTDATED. Use bootloader and "JoyLoader" on PC.</b><br>


<h1>Programming Pro Micro Leonardo</h1>

1. Hardware. You will need a programmer tool. Get USBasp at ebay. It is very cheap. (LPT programmer with PonyProg does not support the ATmega32U4 micro controller on board Pro Micro.) Look for the later variant of programmer with metal quartz resonator along the board, not across the board. Sometimes it is called USB ISP USBasp programmer. You may also order 20 cm Male to Female Wire Jumper cables, if you don't want to make them yourself.<br>
<br>
2. Software. Install WinAVR. It is distributed freely. It includes several components. For programming you will need 'avrdude' from this set. Still, you won't need to interact with this program directly, if you follow further recommendations (it will be called by the .bat file).<br>
<br>
Download the bat file <a href='http://mmjoy.googlecode.com/svn/wiki/updfrm_promicro.bat'>http://mmjoy.googlecode.com/svn/wiki/updfrm_promicro.bat</a>

Download Pro Micro firmware from the MMJoy download section.<br>
<br>
3. Connections. Connect USBasp programmer as shown in photos. You connect four wires.<br>
<br>
<img src='http://mmjoy.googlecode.com/svn/wiki/updfrm_1pro_micro_pins.png' />

<img src='http://mmjoy.googlecode.com/svn/wiki/updfrm_2cable_pinout.png' />

<img src='http://mmjoy.googlecode.com/svn/wiki/updfrm_3gen_view.png' />

<img src='http://mmjoy.googlecode.com/svn/wiki/updfrm_4promicro_cables.png' />

<img src='http://mmjoy.googlecode.com/svn/wiki/updfrm_5usbasp_cables.png' />

After connecting the programmer, plug the Pro Micro into USB for power supply.<br>
<br>
4. Copying files. Copy  updfrm_promicro.bat file to the firmware directory with .hex file.<br>
<br>
5. Double click updfrm_promicro.bat file. A command prompt window will appear and display the progress of programming.<br>
<br>
6. Configuration. Run JoySetup.exe. If you did everything correctly, the controller is now programmed and you will see it in configuration utility. Configure according to your needs. After configuring you will see your controller in Windows Game Controllers panel.<br>
<br>
