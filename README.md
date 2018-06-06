ALUMNO: JOSE MANUEL CALDERA CARDONA

Material utilizado:

1 Display LCD 16x2.
1 Sensor de temperatura LM35
1 1 potenciometro de 10k.
1 Arduino UNO.
1 Protoboard
Cable conectores (Macho-hembra, maho-macho).
Funcionamiento

El proyecto cuenta con una interfaz Java en la cual es posible enviar un mensaje para que este sea impreso en el LCD, el programa .ino obtiene la hora y la fecha del sistema, mostrándo estos datos de manera alternada al mensaje que se manda imprimir desde la interfaz Java.

La interfaz (archivo window.java) cuenta con una caja de texto para ingresar el mensaje que se desee imprimir y un botón de envío para enviar esta información al arduino e imprimirla mediante el lcd-

La comunicación Java-arduino se da mediante el puerto serial.

La temperatura es obtenida mediante el sensor LM35 el cual detecta la temperatura ambiental y manda este dato a uno de los puertos análogos del arduino, este dato es convertido para que se muestre en grados centígrados y es impreso en el lcd.

La fecha y la hora son obtenidas del sistema operativo y se imprimen de igual manera en el display lcd.
