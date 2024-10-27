Descripción del entregable: En el bloque "App", se encuentran todos los elementos relacionados al código de MIT App Inventor 2, con el objetivo de crear desde cero un control remoto para el robot PRT4 hecho con componentes de Arduino UNO acoplado a un MotorShield. La finalidad de dicho control, permite comandar al robot vía Bluetooth. Por ende, se encuentran adjuntados: El código fuente de la aplicación, cómo se configuraron las partes activas del programa (como botones, etiquetas) y estáticas (estructura de la aplicación) y cómo va a ver el usuario final el software (lo cual refiere al diseño netamente). En los apartados de "app_inventor" y "codigo_app", se encontrarán sus respectivos links, los cuales desembocarán todos en un mismo Drive, para la visualización y/o descarga de contenido.

Instrucciones para uso o reproducción:
1. Descarga y acceso a MIT App Inventor: Dirígase a MIT App Inventor y haga clic en "Create Apps!" o visite directamente el entorno de creación en ai2.appinventor.mit.edu.
2. Inicio de sesión: Inicie sesión con su cuenta de Google. MIT App Inventor requiere de una cuenta de Google para guardar y cargar proyectos.
3. Importe el archivo .aia: Una vez dentro del entorno de App Inventor, en la esquina superior izquierda, haga clic en "Projects" >> "Import project (.aia) from my computer".
4. Selección de proyecto: Navegue hasta el archivo .aia que desee cargar y selecciónelo (el nombre que aparecerá es "Control_Lab1.aia"). Haga clic en "OK" o "Aceptar" para cargar el proyecto.
5. Espera de carga del proyecto: MIT App importará el archivo. Este proceso puede tardar unos segundos, dependiendo de la velocidad de conexión y el tamaño del proyecto. 
6. Revisión del proyecto: Una vez que el proyecto se haya importado, aparecerá en la lista de proyectos. Haga clic en el nombre del proyecto para abrirlo ("Control_Lab1.aia") y revise los bloques y la interfaz de usuario.
7. Prueba de la aplicación (opcional): En el caso que desee verificar que todo funcione correctamente, puede probar la aplicación conectando su dispositivo móvil y usando la aplicación Mit AI2 Companion para escanear el código QR y probar la aplicación en tiempo real. O bien, seleccione "Build" >> "Provide QR code for .apk" para compilar la aplicación y obtener un código QR de descarga. Esto le permitirá instalar la aplicación en su dispositivo.
8. Compilación del proyecto: Cuando esté listo para que el usuario final instale la aplicación, seleccione "Build" >> "App (save .apk to my computer)" para compilar la aplicación en formato .apk. Esto generará un archivo instalable para su dispositivo.
9. Distribución del archivo.apk: Comparta el archivo .apk resultante con el usuario final. Puede instalarlo en sus dispositivos móviles habilitando la opción para instalar aplicaciones desde fuentes desconocidas, si es necesario.
10. Consideraciones de uso: En primer lugar deberá asegurarse de que el robot cuenta con una buena fuente de energía (9V es lo recomendable). Nótese que al momento de colocarle las baterias, el módulo Bluetooth comenzará a parpadear (esto significa que no se ha establecido una conexión con el control remoto). Cuando usted esté dentro de la aplicación, asegúrese que su dispositivo tenga el Bluetooth activado, y presione el botón en la parte superior de la pantalla que dirá "No conectado...". A continuación se le desplegará una lista con dispositivos a los cuales usted podrá conectarse. En este caso, deberá seleccionar el dispositivo con el nombre "HC-06". Acto seguido, notará que dicha luz ya no seguirá titilando, ergo, la conexión ya está realizada y es estable. Ahora, podrá presionar los diversos controles para controlar el robot.

Dependencias: El control básicamente envía distintas señales en forma de letras del abecedario (en un rango a - k), cada señal activa una función distinta del robot, las cuales se anuncian a continuación: 
."a" (representado con un dibujo de una sirena): Los LEDs que posee el robot comenzarán a alternarse entre rojo y blanco, además sonará una sirena característica de un vehículo de emergencia.
."b" (representado con un dibujo de una sirena anulada): Tanto los LEDs, como la sirena se desactivarán. 
."c" (representado con una flecha hacia arriba): Los motores del robot comenzarán a girar hacia adelante.
."d" (representado con una flecha hacia atrás): Los motores del robot comenzarán a girar hacia atrás.
."e" (representado con una flecha hacia la izquierda): El motor izquierdo girará hacia atrás y el motor derecho girará hacia adelante, permitiendo el giro hacia la izquierda.
."f" (representado con una flecha hacia la derecha): El motor izquierdo girará hacia adelante y el motor derecho girará hacia atrás, permitiendo el giro hacia la derecha.
."g" (representado con el dibujo de un robot): Se activarán los servomotores de tal forma que permitirá al robot pasar de su modo vehículo a su modo robot.
."h" (representado con el dibujo de un tanque): Se activarán los servomotores de tal forma que permitirá al robot pasar de su modo robot a su modo vehículo.
."i" (representado con el dibujo de una gota de agua): La bomba de agua se activará dejando salir un flujo de agua.
."j" (representado con el dibujo de una gota de agua anulada): La bomba de agua se desactivará impidiendo el paso del agua. 
."k" (representado por una señal de "alto"): Permitirá anular el movimiento de los motores cuando estén andando, permitiendo un mejor control de la movilidad del robot. 

Archivos principales: 
Archivo .aia, "Control_Lab1.aia" (aplicación del control hecho con MIT App Inventor)
Imagen .png, "Codigo Fuente APP" (código fuente de la aplicación hecha con MIT App Inventor)
Archivo Word, "CodigoFuente, Interfaces, Estructura" (imagenes del código fuente, interfaces y estructura de la aplicación hecha con MIT App Inventor)
