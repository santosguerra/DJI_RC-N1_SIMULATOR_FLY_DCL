DJI RC-N1
===============
 - Conecta tu control remoto DJI a tu PC y úsalo para jugar simuladores incluido el DJI Flygth Simulator
  - For Mavic Mini or a Python interface, take a look at [justin97530/miniDjiController](https://github.com/justin97530/miniDjiController)
 - For DJI Mini 2 or a Python interface, take a look at [usatenko/DjiMini2RCasJoystick](https://github.com/usatenko/DjiMini2RCasJoystick)
 - For DJI Phantom 3 take a look at [mishavoloshchuk/mDjiController](https://github.com/mishavoloshchuk/mDjiController)
-----------------------------------------------------------------------------


Este es un programa que se conecta a tu control remoto DJI Mavic 3 (RC-N1) como un gamepad de XBox360, lee las posiciones de los joysticks y le dice a Windows esa posición.

<img height="400" src="DJI-RC-N1-Remote-Controller.png" width="400"/>

-----------------------------------------------------------------------------
Instalación / Uso
- Instale los paquetes antes de usarlos:
- pip3 install vgamepad
- pip3 install pyserial

- Encienda el RC-N1
- Conectar a través de la parte inferior tipo-C
- ejecuta main.py
- ejecuta tu simulador

![](connect_ok.png)

para reiniciar el juego o recuperar el dron: usa la rueda de la cámara, desplazamiento a la izquierda

![](control.png)


SOLUCIÓN DE PROBLEMA
-----------------------------------------------------------------------------
Búsque el puerto serie con la descripción «DJI USB VCOM For Protocol» en el administrador de dispositivos,
asegúrese de que su dispositivo conectado a través del conector inferior Tipo-C
![](connect.png)

[Tested with DCL - The game](https://store.steampowered.com/app/964570/DCL__The_Game/) 

    Preset:
    Mode 2
    Acro
    Zero throttle at stick center

![](preset1.png)
![](preset2.png)
