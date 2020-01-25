# Studio-Microphone-Controller

A projekt leírása felhasználói szinten:

A projekt egyik fő alkotó eleme a mikroszámítógép. Erre a feladatra egy Raspberry Pi 3 Model B+ modellt használunk. 
Rövid leírás: Processzor: Broadcom négymagos, 64 bit, Memória: 1 GB, Bluetooth, Ethernet, USB, 40 tűs GPIO csatlakozó, HDMI, Tároló: microSD, Áramellátás: USB csatlakozó.

Raspberry Pi 3 Model B+

![myimage-alt-tag](http://www.infolex.hu/kep/65936/nagy/raspberry-pi-3-model-b.jpg)

A másik fontos hardware az infravörös szenzor (infrared sensor). Ez fogja a jelet adni a Raspberry-nek.

![myimage-alt-tag](https://ae01.alicdn.com/kf/HTB1W4uFXITxK1Rjy0Fgq6yovpXa5.jpg)

A szenzor működése:

![myimage-alt-tag](https://circuitdigest.com/sites/default/files/inlineimages/IR__.jpg)

Működés:
A mikrofonra szerelt szenzor érzékeli a beállított távolságon, ha valaki a mikrofon  előtt van. (obstacle sensor)
(What is obstacle sensor? Obstacle detection is the process of using sensors, data structures, and algorithms to detect objects or terrain types that impede motion.)
Ekkor bekapcsolja a mikrofont, elindítja a felvételt, aminek input-ja a mikrofon. A bakapcsolásról e-mail-t küld a megadott címre. Ha a felhasználó a beállított távolságon kívül van, a felvétel leáll. A működések idejéről, időtartamairól statisztikát készít. A bekapcsolt állapot ideje alatt a mátrix kijelzőn is a működést igazoló karakterek vannak. A felhasználó tájékoztatására a hangerő mérése is a programba került, így használat közben a kijelzőn láthatja, ha túl halk, vagy túl hangos a hangja.
