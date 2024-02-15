
# Actividades capítulo 3 y 4 CCNA1
FECHA: 14/02/2024

NOMBRES: Juan Camilo Sarabino Alegría / Juan Sebastián Bonilla Llantén

CÓDIGO SIMCA: 104618021305 / 104618021331

## Preguntas de lectura: Capítulo 3

1. Describir las funciones de las tres capas superiores del modelo OSI y como estas proporcionan servicios de red a las aplicaciones de usuario final.

  Las 3 capas superiores del modelo OSI:
Estas son implementadas por los desarrolladores.
* Capa de Aplicación: 
Es la capa que proporciona la interfaz entre las aplicaciones que utilizamos para comunicarnos y la red subyacente en la cual se transmiten los mensajes. Es la capa con la que el usuario final interactúa con los servicios.

* Capa de Presentación:
Codificación: Obtención de los datos de origen, del usuario.
Compresión: Reducción del volumen de los datos, para mejor cantidad de espacio.
Encriptación: Conversión de la información en texto cifrado.

* Capa de Sesión:
Crear y mantener el intercambio de información, estableciendo el diálogo entre las aplicaciones de origen y destino. Gestiona y controla la sesión del usuario.

2. Dentro de la capa de Aplicación, existen dos formas de procesos o programas de software que proporcionan acceso a la red: aplicaciones y servicios. Describir su respectiva función y/o propósito.
* Aplicaciones de la red:
Las aplicaciones son los programas de software que utilizan los usuarios para comunicarse a través de la red. Estas implementan protocolos de la capa de aplicación para comunicarse directamente con las capas inferiores del stack de protocolos. Ejemplo: Correo electrónico y exploradores web.
* Servicios de la capa de aplicación:
Los servicios de la capa de aplicación no son visibles por el usuario, estos servicios son los programas que se comunican con la red y preparan los datos para la transferencia. Ejemplo: Diversos tipos de datos, texto, gráfico o video.

3. Explicar, por medio de un dibujo, el funcionamiento del modelo cliente-servidor y su relación con el término Daemon.
![Ilustración Daemon](https://raw.githubusercontent.com/SebastianBonilla13/Redes/main/Corte%201/daemon.png)

4. Describir la diferencia entre los términos: redes punto a punto y aplicaciones punto a punto (P2P).
* Redes punto a punto: 
Este se da cuando dos o más computadoras están conectadas a través de una red y pueden compartir recursos sin necesidad de tener un servidor dedicado o intermediario. Durante una transacción una computadora puede ser servidor mientras que la otra como cliente. Ejemplo: Dos computadoras conectadas a una gran red que utilizan aplicaciones de software para compartir recursos entre ellas a través de la red.

* Aplicaciones punto a punto:
Permite a un dispositivo actuar como cliente o como servidor dentro de la misma comunicación. Cada cliente puede ser un proveedor como consumidor de recursos. Cada dispositivo requiere de una interfaz de usuario(enviar peticiones) y ejecuta un servicio en segundo plano (recibir peticiones).
Ejemplo: Transferencia de datos de dos dispositivos mediante Bluetooth.

5. Explicar, con sus palabras, los procesos y protocolos de envío y recepción de un e-mail.
   Cuando una persona escribe mensajes de correo electrónico, generalmente lo hace mediante un MUA (Agente de Usuario de Correo) o cliente de correo electrónico. El MUA permite gestionar los mensajes, así como: leer, enviar, recibir y organizar sus mensajes de correo electrónico.
Para recibir e‐mails desde un servidor de e‐mail, el cliente de correo electrónico puede utilizar el protocolo POP (Post Office Protocol). Y al enviar un e‐mail desde un cliente o un servidor, se utilizan formatos de mensajes y cadenas de comando definidas por el protocolo SMTP (Simple Mail Transfer Protocol).

6. Describir la función de las aplicaciones TCP/IP conocidas, tales como World Wide Web e e-mail y sus servicios relacionados (HTTP, DNS, SMB, DHCP, SMTP/POP y Telnet).

  TCP/IP es un conjunto de protocolos de comunicación utilizados para la interconexión, tales como:
- World Wide Web (WWW):
    Permite el acceso a información y recursos en la Internet mediante el uso de hipertexto. HTTP y HTTPS.
- Correo Electrónico (e-mail):
    Facilita el intercambio de mensajes y archivos entre usuarios a través de redes informáticas. Haciendo uso de POP para recibir y SMTP para enviar mensajes.
- HTTP (Hypertext Transfer Protocol):
    Protocolo de transferencia de hipertexto que define cómo se transmiten y muestran los recursos web.
- DNS (Domain Name System):
    Asocia nombres de dominio legibles por humanos con direcciones IP numéricas para permitir la localización de recursos en Internet.
- Server Message Block (SMB):
    Facilita el intercambio de archivos, impresoras y otros recursos entre dispositivos en una red local.
- Dynamic Host Configuration Protocol (DHCP):
    Automatiza la asignación de direcciones IP y otros parámetros de configuración de red a dispositivos en una red.
- Simple Mail Transfer Protocol/Post Office Protocol (SMTP/POP):
    SMTP es utilizado para enviar correos electrónicos, mientras que POP se utiliza para recuperarlos del servidor de correo.
- Telnet:
    Permite el control remoto de dispositivos y la administración de sistemas a través de una conexión de red.

7. Investigar y explicar la diferencia entre Telnet y SSH

  La principal diferencia entre Telnet y SSH es la seguridad. Mientras que Telnet carece de cifrado y autenticación segura, lo que lo hace vulnerable a ataques, SSH proporciona un entorno de comunicación seguro que protege la confidencialidad e integridad de los datos durante la transmisión, siendo esta última una mejor opción de aplicación.

8. Utilizando la utilidad nslookup obtener manualmente la dirección IP de al menos tres (3) sitios web que usted frecuente.

  www.youtube.com, web.whatsapp.com, www.facebook.com
![Ilustración nslookup1](https://raw.githubusercontent.com/SebastianBonilla13/Redes/main/Corte%201/nslookup1.png)

9. Conectado a la red de la Universidad del Cauca y utilizando la utilidad nslookup obtener manualmente la URL asociada a las siguientes direcciones IP:10.200.1.250, 10.20.5.11, 10.20.4.43.
  ![Ilustración nslookup2](https://raw.githubusercontent.com/SebastianBonilla13/Redes/main/Corte%201/nsloookup2.png)

## Preguntas de lectura: Capítulo 4
1. Describir las funciones de la capa de Transporte.
* Seguimiento de Conversaciones individuales:
La capa de Transporte gestiona las comunicaciones entre aplicaciones, dividiendo los datos (segmentación), enviándolos y reconstruyéndolos (reensamble).

* Identificación de las aplicaciones:
Cada aplicación se identifica con un número de puerto, permitiendo que la capa de Transporte los dirija a la aplicación correcta.

* La capa de Transporte como puente:
Actúa como un enlace entre las aplicaciones y las capas inferiores de la red, asegurando la entrega de datos sin que las aplicaciones conozcan los detalles de la red.

* Diferencia de responsabilidades:
Las capas inferiores se ocupan de la transmisión sin conocer las aplicaciones específicas, mientras que la capa de Transporte organiza y entrega los datos a las aplicaciones correspondientes.

2. ¿Por qué es importante la segmentación?

  La capa de Transporte divide y reensambla los datos para cumplir con estos límites.
* Multiplexación de conversaciones: Identifica cada aplicación o servicio en un host mediante puertos asignados, facilitando el direccionamiento correcto de los datos. Asegura que los datos lleguen al destino, solicitando retransmisiones si es necesario.
Garantiza que los datos se reensamblen en el orden correcto, a pesar de variaciones en la llegada, mediante numeración y secuenciación de segmentos.
Regula la velocidad de transmisión de datos para prevenir sobrecargas de recursos, minimizando la pérdida de segmentos y la necesidad de retransmisiones.

3. Describir a través de un cuadro de ideas, las funciones y diferencias de dos protocolos TCP/IP de la capa de transporte: TCP y UDP, además Identificar cuándo es apropiado usar TCP o UDP y proveer ejemplos de aplicaciones que usan cada protocolo.


4. Explicar cómo funciona y para que se utiliza el control de congestión de TCP.

  TCP es un protocolo orientado a la conexión, la funciones de TCP es el mismo orden de entrega, entrega confiable y de control de flujo.
Es utilizado en exploradores Web, e‐mail, y transferencia de archivos.

5. Explicar las funciones clave de la capa de Transporte incluyendo confiabilidad, direccionamiento de puerto y segmentación.

  La capa de Transporte puede asegurar que todas las secciones lleguen a destino al contar con el dispositivo de origen para volver a transmitir los datos que se hayan perdido, así evitando que los datos se corrompa o se pierda por completo.

6. ¿Cuáles son los diferentes tipos de número de puerto?

* Puertos bien conocidos (Números del 0 al 1 023): Reservados para servicios y aplicaciones. como HTTP, POP3/SMTP, Telnet.
* Puertos Registrados (Números 1024 al 49151): Asignados a procesos o aplicaciones del usuario. Generalmente aplicaciones comunes que el usuario desea instalar y recibo un puesto predeterminado.
* Puertos dinámicos o privados (Números del 49 152 al 65 535): Puertos efímeros, suelen asignarse de manera dinámica a aplicaciones de cliente cuando se inicia una conexión.

7. Explicar, por medio de un dibujo, el establecimiento y finalización de una conexión TCP (intercambio de señales de tres vías).
  ![Ilustración Establecimiento_finalizacion](https://raw.githubusercontent.com/SebastianBonilla13/Redes/main/Corte%201/Establecimiento_finalizacion.png)
