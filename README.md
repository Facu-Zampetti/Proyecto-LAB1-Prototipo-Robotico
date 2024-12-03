Nombre del Proyecto: PRT4 - Proyecto LAB 1

Descripción: El proyecto consiste en un prototipo robótico innovador basado en una plataforma Arduino Uno, diseñado específicamente para asistir en zonas de incendios. Este tanque transformable, capaz de adoptar una figura humanoide, combina la movilidad robusta de un tanque con la precisión y adaptabilidad de un humanoide. Este diseño único permite al robot cambiar de forma para enfrentar desafíos específicos en operaciones de rescate o apoyo en incendios. Mientras que la forma de tanque le permite moverse con estabilidad en terrenos accidentados y alcanzar zonas de difícil acceso, la transformación a humanoide facilita la manipulación de herramientas y el acceso a áreas reducidas, mejorando su versatilidad en tareas de asistencia en entornos complejos y hostiles.

Tecnologías utilizadas: Para el diseño 3D y la simulación para poner a prueba los componentes y el código, se utilizó Tinkercad. Para el diseño y creación del control remoto vía Bluetooth, se utilizó MIT App Inventor 2. Por último, para la escritura del código en un ámbito diferente de Tinkercad se precisó de Arduino IDE para el testeo de componentes no encontrados en Tinkercad. Cabe recalcar que para la programación del robot se necesitaron conocimientos previos del lenguaje C++.

Contenido del repositorio: La estructura del repositorio para el proyecto "Proyecto-LAB1-Prototipo-Robótico" se organiza en varias carpetas, cada una con archivos y descripciones específicos que corresponden a distintos aspectos del desarrollo y documentación del prototipo robótico. Esta estructura facilita la navegación y acceso a todos los componentes y documentación necesarios para entender, modificar y replicar el proyecto de manera organizada. A continuación se describe cada carpeta y su contenido:
1) App/: Contiene los archivos de la aplicación de control remoto desarrollada en MIT App Inventor.

   app_inventor/: Archivos de diseño y código fuente de la aplicación.

   codigo_app/: Código fuente de la app, necesario para el funcionamiento del control del robot.

   README.md: Archivo con instrucciones y detalles sobre el uso de la aplicación.

2) Arduino/: Incluye el código y las instrucciones para programar la placa Arduino que controla el prototipo.
 
   codigo_c++/: Código fuente en C++ del robot, programado para la placa Arduino.
 
   diagrama_de_flujo/: pseudocódigo donde se detalla la lógica de control del robot.

   README.md: Instrucciones sobre cómo compilar y ejecutar el código.

3) Diseño_3D/: Archivos relacionados con el diseño tridimensional del robot.

   tinkercad/: Modelos 3D creados en Tinkercad para las distintas piezas del robot.

   README.md: Descripción de cada archivo 3D y su uso en la construcción del prototipo.

4) Diseño_Electronico/: Archivos del diseño electrónico del robot, necesarios para ensamblar el circuito.

   tinkercad/: Diseño de circuitos electrónicos en Tinkercad.

   esquematicos/: Esquemáticos del circuito utilizado en el robot.

   README.md: Instrucciones y descripción de los circuitos electrónicos.

5) Informe/: Documentación detallada del proyecto.

   informe_proyecto.pdf: Informe completo sobre el desarrollo del prototipo, su funcionamiento y otros detalles técnicos.

6) Presentación/: Material de apoyo para la presentación del proyecto.

   presentacion_defensa.pdf: Presentación utilizada durante la defensa del proyecto, que resume los puntos clave.

   Logo.png: Logo de la empresa desarrolladora del proyecto PRT4

8) Tutorial/: Guía paso a paso para replicar el proyecto.

   tutorial.md: Instrucciones detalladas para ensamblar, programar y poner en funcionamiento el robot.

Guía de Instalación:
1) Control Remoto:
   
   a) Descarga e ingreso a MIT App Inventor para importar el archivo .aia.
   
   b) Inicia sesión con tu cuenta de Google.
   
   c) Importa el archivo .aia desde tu computadora y ábrelo.
   
   d) Prueba la aplicación en tiempo real con Mit AI2 Companion o compila el archivo .apk.
   
   e) Distribuye el archivo .apk para instalación en dispositivos finales.

2) Código Arduino:
   
   a) Descarga e instala el Arduino IDE desde la página oficial.
   
   b) Abre el archivo .ino en el IDE y conecta la placa Arduino.
   
   c) Selecciona el modelo de la placa y el puerto correspondiente.
   
   d) Instala las bibliotecas necesarias desde el gestor de bibliotecas del IDE.
   
   e) Verifica, carga el código en la placa y prueba el proyecto con el Monitor Serial.

3) Diseño 3D:
   
   a) Descarga los archivos .stl desde la carpeta Diseño_3D en el repositorio.
   
   b) Abre Tinkercad, crea un nuevo diseño e importa los modelos .stl.

   c) Visualiza y modifica los modelos según sea necesario.
   
   d) Guarda o exporta los archivos para impresión 3D o distribución.

4) Diseño Electrónico:

    a) Localiza la imagen en formato .png del diseño del circuito en el repositorio y ábrela con un visor de imágenes.
    
    b) Abre el archivo .pdf del esquema del circuito con un lector de PDF para revisar los detalles.
    
    c) Instala un software de diseño de PCB como Eagle o KiCad.
    
    d) Importa el archivo .brd en el software instalado para visualizar el diseño del circuito.
    
    e) Revisa el diseño y realiza simulaciones eléctricas en el software para verificar su correcto funcionamiento.

Instrucciones para contribuir:

1) Clona el repositorio y crea una rama nueva: Duplica el repositorio en tu entorno local y crea una nueva rama que refleje los cambios específicos que deseas realizar. Nombra la rama de forma descriptiva (por ejemplo, feature/funcion-nueva o fix/error-x).

2) Realiza tus cambios, prueba y documenta: Modifica el código o los archivos necesarios en tu nueva rama. Asegúrate de que los cambios funcionan correctamente probando el código y agregando comentarios o documentación en los archivos, si es necesario. Sigue los estándares de estilo y contribución del proyecto.

3) Envía un Pull Request (PR): Sube tus cambios al repositorio original y abre un PR para revisión. Explica los cambios realizados y por qué son necesarios. Responde a los comentarios o sugerencias del equipo hasta que se apruebe el PR.

Licencia: Copyright © [2024] [PTR4]. Todos los derechos reservados.
