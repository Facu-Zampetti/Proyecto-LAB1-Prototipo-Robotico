Descripción del entregable: contiene todos los archivos relacionados con el diseño y ensamblaje del circuito electrónico del robot. Incluye el diseño del circuito en Tinkercad, donde se modelaron las conexiones electrónicas, y el archivo del esquemático, que detalla las interconexiones de los componentes utilizados en el prototipo. Esta documentación permite visualizar y comprender la estructura eléctrica del robot, facilitando su ensamblaje y posibles modificaciones.

Instrucciones para uso o reproducción: En el repositorio, se incluye una imagen en formato .png que muestra el diseño del circuito en Tinkercad. Para visualizar esta imagen, simplemente ábrela con un visor de imágenes estándar, lo que te permitirá revisar de manera rápida la disposición de los componentes y las conexiones del circuito. Archivo .pdf del esquema del circuito: Este archivo contiene el esquemático completo en un formato fácil de leer y compartir. Puedes abrirlo con cualquier lector de PDF para revisar los detalles del circuito, incluyendo la ubicación de los componentes y las conexiones. Archivo .brd con el esquema detallado del circuito: Este archivo puede ser abierto en software especializado en diseño de PCB, como Eagle (de Autodesk) o KiCad. Para abrirlo, sigue estos pasos:
Instala el software de diseño de PCB de tu preferencia (Eagle o KiCad).
Importa el archivo .brd:
En Eagle: Ve a "File" > "Open" y selecciona el archivo .brd.
Una vez importado, podrás visualizar en detalle el diseño del circuito, incluidas las conexiones, pistas y componentes. Esto también te permitirá realizar simulaciones eléctricas para verificar el correcto funcionamiento antes de la construcción.

Dependencias: Para el funcionamiento correcto del circuito electrónico del robot, se utilizan varios componentes esenciales, cada uno de los cuales depende de la placa Arduino Uno R3 para recibir y ejecutar instrucciones de control. A continuación se detallan las dependencias de cada componente:
1) Arduino Uno R3: Actúa como el microcontrolador central, gestionando las señales y la lógica del circuito. Controla los motores, servomotores, LEDs, la bomba de agua y otros componentes conectados.
2) LED Rojo y LED Amarillo: Estos LEDs, que indican el estado del robot, están conectados a través de resistencias de 1kΩ para limitar la corriente y evitar daños. La Arduino controla su encendido y apagado, generando efectos como parpadeo.
3) 2 Resistencias de 1kΩ: Limitan la corriente hacia los LEDs y otros componentes sensibles. Estas resistencias protegen los LEDs de picos de corriente, asegurando que operen dentro de sus especificaciones.
4) 2 Motores de Aficionado (para las orugas): Controlados mediante una shield de motor o un controlador (como el L298N), que permite manejar la dirección y velocidad de cada motor. La placa Arduino envía señales de PWM para controlar los motores.
5) 4 Microservomotores Posicionales: Los servos permiten el movimiento de las partes móviles del robot, como la transformación de modo tanque a modo humanoide y la orientación de los cañones de agua. La Arduino controla los ángulos de estos servos mediante señales PWM.
6) Motor de CC (representa la bomba de agua): Este motor permite el funcionamiento de la bomba de agua, controlado por la Arduino a través de un relé o un transistor para activar o desactivar la bomba según las instrucciones del control remoto.
7) Piezo (Buzzer): Utilizado para generar sonidos de alerta o sirena, el buzzer está controlado por la Arduino, que modula la frecuencia de la señal para crear diferentes tonos.
8) Pila de 9V: Proporciona energía a todo el sistema. La Arduino regula la energía a los componentes conectados, pero es necesario asegurarse de que el voltaje sea compatible con los diferentes elementos del circuito.
9) Relé SPDT (representa la placa Bluetooth): Actúa como interfaz para recibir señales desde una aplicación de control remoto. Al recibir señales Bluetooth, el relé activa o desactiva funciones específicas del robot, como el movimiento o la activación de la bomba de agua.

Archivos principales: 
1) Imagen en formato .png del circuito en Tinkercad.
2) Archivo .pdf del esquema del circuito.
3) Archivo .brd con el esquema detallado del circuito
