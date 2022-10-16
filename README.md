# Pavol Ňachaj, moje projekty

## [Maturitní práce](Maturitní_práce/readme.md)
Maturitní praci jsem dělal pro firmu [NETTO](https://www.nettocontrol.cz/), kde jsem spojoval [kojeneckou váhu](https://www.vahynetto.cz/133-produkt-prisl-754-elektronicka-kojenecka-vaha-soehnle-professional-7752.html) s [měřidlem dékly kojence](https://www.soehnle-professional.com/productgroup/details/99/baby-langenmessstab). Tyto data jsem následně posílal do aplikace pomoci Bluetooth, kterou jsem napsal v Xamarinu, kde jsem je ukladal a zobrazoval.

## [Semestrální práce Leptací box](https://github.com/PNmJunior/Semestralni_prace_Leptaci_box.git)
Využil jsem možnost vrámci předmětu B2B99PPC Praktické programování v C/C++ na ČVUT FEL obor Elektronika a komunikace, naprogramovat aplikaci v Qt.
Vyrobil jsem leptací box z nefunkční inkoustové tiskárny. Vnitřní elektroniku jsem následně úkoloval přes počitač s Windows pomoci USB.

## [BuckysPlasticArm 2022](https://github.com/PNmJunior/RB2022-TymRECYLKON-TCB-BuckysPlasticArm.git)
Za 40 dní jsem vyrobil robota na [Robotický den](http://robotickyden.cz/2022/) pro soutěž [Úklid hraček](http://robotickyden.cz/2022/rules/2022-Toy_Cleanup-CZv1.pdf) pro dálkové ovladání. Vyzkoušel jsem si práci s ESP32  ovládanou pomoci webového rozhraní. Do robota jsem vložil ESP32 a sestavil jsem potřebnou elektroniku, která vytvářela WebServer a ovladála robotické rameno KSR10, ke kterému jsem vyrobil podvozek. Systém jsem postavil pro 8 motorů. Jako základ jsem použil veřejně dostupný projekt [ESP32 Web Server (WebSocket) with Multiple Sliders: Control LEDs Brightness (PWM)](https://randomnerdtutorials.com/esp32-web-server-websocket-sliders/), který jsem upravil tak, aby zvádl přijimat příkazy rychle a z několika zařizení najednou, k tomu všechny údaje synchronizovat.