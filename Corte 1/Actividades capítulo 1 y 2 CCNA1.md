# Actividades capítulo 1 y 2 CCNA1
FECHA: 9/02/2024

NOMBRES: Juan Camilo Sarabino Alegría / Juan Sebastián Bonilla Llantén

CÓDIGO SIMCA: 104618021305 / 104618021331

## Preguntas de lectura: Capítulo 1
1. Listar al menos 5 actividades cotidianas que realiza usted utilizando internet.
- Realizar búsquedas de conceptos en la web.
- Jugar videojuegos Online.
- Realizar trabajos colaborativos.
- Utilizar medios de comunicación.
- Adquirir información de noticieros.

2. Describir los factores que afectan la calidad de las comunicaciones.
* Existen los factores externos:
  - Saturación de las conexiones, por ejemplo, en número de dispositivos que debe atravesar un mensaje para llegar a su destino o número de mensajes simultáneos que se manejan en la red.
  - Cantidad de veces que el mensaje cambia de forma o es redireccionado.
* Existen los factores internos:
  - El tamaño del mensaje.
  - Complejidad del mensaje.
  - Importancia del mensaje.

3. Identificar los componentes clave de cualquier red de datos y describir su funcionamiento.
- Reglas: sirven para regular el modo de envío, redirección y recepción de mensajes.
- Mensaje: la información que viaja de un dispositivo a otro.
- Medio: por donde se transporta el mensaje.
Dispositivos: es decir, los dispositivos que intercambian los mensajes.

4. Responda con sus propias palabras:
   
    A. ¿Qué son los datos? 
    - Los datos, son información, los cuales se envían por medio de una red de comunicación.

    B. ¿Qué es una red de datos?
    - Es el medio por el cual se envía la información.

    C. ¿Qué entiende por arquitectura de red?
    - Es toda la infraestructura, que hace posible la comunicación entre dispositivos y permite el intercambio de información.

    D. ¿Qué es una red convergente?
    - Una red que permite el envío de información en forma de sonido, video y datos.

5. Describir las características de las arquitecturas de red
   
    A. Tolerante a fallas, es cuando se tiene un respaldo de la comunicación cuando ocurre un fallo de software o hardware, a esto se le conoce como redundancia.

    B. Escalabilidad, se refiere al sostenimiento del rendimiento del servicio a medida que se amplían los usuarios.

    C. Calidad del servicio, hace alusión a las características que hacen de un servicio confiable, como por ejemplo la estabilidad del servicio, rapidez de respuesta, etc. 

    D. Seguridad. Son medidas de protección contra ataques maliciosos, se pueden utilizar mediadores como los firewalls o utilizar usuarios con contraseñas para restringir el acceso a la información.

6. Investigar qué son las redes orientadas y no orientadas a la conexión.
- Las redes orientadas a la conexión de manera simplificada utilizan un protocolo de 3 fases para la transferencia de datos; establecer la comunicación, transferencia de datos y cierre de comunicación. En este tipo de redes se envía la información de manera secuencial y se garantiza el envío de la información.
- En las redes no orientadas a la conexión, no se establece un canal de comunicación inicial, tampoco se garantiza el secuenciamiento de los paquetes de datos que se envían, el emisor se limita a envíar los datos sin comprobar la recepción de los mismos por parte del receptor.

7. Describa que es la calidad del servicio y que se necesita para mantener una buena calidad de servicio para las aplicaciones que lo requieren.
- La calidad del servicio es mantener la disponibilidad cuando el tráfico de redes está congestionado. Para mantener la calidad se debe priorizar los tipos de paquetes de datos que deben enviarse a expensas de otros tipos de paquetes que puedan retrasarse o descartarse.

8. ¿Por qué importa la calidad del servicio en una red de datos? 
- Porque cuando el volumen de paquetes es mayor de lo que se puede transportar en la red, los dispositivos colocan los paquetes en cola en la memoria hasta que haya recursos disponibles para transmitirlos, esto provoca retrasos y en términos de ejemplos reales, esto puede ocasionar la falta de conexión de un mensaje de emergencia e incluso de accidentes al controlar maquinaria pesada automatizada.

9. Investiga sobre qué son los proveedores de Internet de Nivel-1 (Tier-1) y Nivel-2 (Tier-2), y cómo se diferencian en términos de infraestructura, alcance y relaciones comerciales.
- Los proveedores de internet de nivel 1 brindan conexiones nacionales e internacionales.
- Los proveedores de internet de nivel 2 son más pequeños y generalmente brindan un servicio regional, les pagan a los proveedores de nivel 1 la conectividad con el resto de internet.

10. Identifica al menos tres proveedores de Internet de nivel mundial y clasifícalos en Nivel-1 (Tier-1) o Nivel-2 (Tier-2) según su posición en la jerarquía de la red. Identifica al menos 2 proveedores de internet en Colombia.
- Nivel-1: AT&T, Verizon y NTT Communications.
- Nivel-2: Comcast, Cox y Charter Communications.
- Colombia: Claro Colombia (parte de América Móvil), Movistar Colombia (parte de Telefónica) y Tigo Colombia (parte de Millicom)

11. Investiga sobre la importancia de los proveedores de Internet de Nivel-1 y Nivel-2 en la conectividad global, incluyendo su papel en la transmisión de datos a través de Internet. 
- La importancia de los proveedores de internet de Nivel-1 radica en su infraestructura global ya que poseen una infraestructura de red extensa que les permite interconectar redes a nivel mundial sin depender de otros proveedores para la transferencia de datos a larga distancia, esto hace que sean el núcleo para la conexión mundial.
- En cuanto a los proveedores de internet de Nivel-2 operan redes regionales o nacionales significativas y proporcionan conectividad a nivel más localizado. Son los responsables de llevar el tráfico de datos a través de áreas específicas dentro de un país o región, logrando en conjunto con los ISP de nivel 1 proporcionar acceso a internet a los consumidores finales.

12. Reflexiona sobre el papel crucial de los proveedores de Internet en la infraestructura digital global y cómo su gestión y regulación pueden impactar en la equidad y la eficiencia del acceso a Internet.
- Las políticas que fomentan la competencia entre proveedores para no generar un monopolio de comunicaciones o al proteger la neutralidad de la red y garantizar la privacidad y la seguridad en línea contribuyen a un acceso equitativo y seguro a la infraestructura digital global.

## Preguntas de lectura: Capítulo 2

La comunicación en una estructura de red puede constar de un dispositivo que requiere enviar un mensaje. El mensaje de origen se denomina como emisor que envía el mensaje de manera codificada a otro dispositivo llamado receptor, el envío se realiza por medio de de un transmisor o canal, para que luego el codificador recibe el mensaje y lo interpreta, lo decodifica.
Los dispositivos y los medios son los elementos físicos o hardware de la red. Son componentes como una computadora portátil o personal, un switch, el cableado o los medios inalámbricos que se usan para conectar estos dispositivos.
Los servicios y procesos son los programas de comunicación, el software que proporciona información en respuesta a una solicitud. Los procesos proporcionan la funcionalidad que direcciona y traslada mensajes a través de la red. Como e‐mail hosting o servicios de Web hosting.
