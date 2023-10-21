# L3MON 
</p>


# <a>ACTUALIZACIÓN GRATUITA DE L3MON</a>:
- Registro GPS
- Grabación de micrófono
- Visualización de contactos
- Registros de SMS
- Envío de SMS
- Registros de llamadas
- Visualización de aplicaciones instaladas
- Inspección de permisos de Stub
- Visualización de redes WiFi (incluidos registros de redes previamente accedidas)
- Explorador de archivos y descargador
- Cola de comandos
- Constructor de APK incorporado
- Autorun (contactar para configurar de forma gratuita)



## Requisitos previos 
 - Java Runtime Environment 8
    - Consulta [instalación](#Instalación) para detalles específicos del sistema operativo
 - NodeJs 
 - Un servidor

## Instalación 
1. Instala JRE 8


2. Instala NodeJS [Instrucciones aquí](https://nodejs.org/en/download/package-manager/) (Si tienes dificultades para comprender estas instrucciones, es recomendable reconsiderar tu idoneidad para utilizar esta herramienta.)

3. Instala PM2 
    - `npm install pm2 -g`
    - `npm install`
    - `npm audit fix`
    - `npm audit`

4. Descarga y extrae la última versión desde [AQUÍ](https://t.me/deVL33014)

5. En la carpeta extraída, ejecuta estos comandos
    - `npm install` <- instala las dependencias
    - `pm2 start index.js` <-- inicia el script
    - `pm2 startup` <- para ejecutar L3MON al inicio

6. Establece un nombre de usuario y contraseña
    1. Detén L3MON `pm2 stop index`
    2. Abre `maindb.json` en un editor de texto
    3. Hash MD5 `echo -n deVL33014 | openssl md5|awk '{print $2}'`
    4. Bajo `admin` 
        - establece el `nombre de usuario` como texto plano
        - establece la `contraseña` como un hash MD5 en minúsculas
    4. Guarda el archivo
    5. Ejecuta 
        - `pm2 restart all`

7. En tu navegador, accede a 
        - `http://127.0.0.1:22533`

## Notas
Cuando abras un problema, DEBES usar las plantillas proporcionadas. Los problemas sin esto no recibirán soporte rápidamente y se pondrán al final de la pila figurativa.

Por favor, revisa los problemas actuales, tanto abiertos como cerrados, para ver si tu problema ya ha sido abordado. Si está relacionado con Java, definitivamente ya ha sido abordado. En resumen, utiliza Java 1.8.0.

## Descargo de responsabilidad
- L3MON es una aplicación de software diseñada para propósitos legítimos y éticos de seguridad e investigación. Es esencial comprender y aceptar los siguientes términos y condiciones antes de utilizar esta herramienta:

- Uso legal y ético: Se prohíbe estrictamente a los usuarios utilizar L3MON para actividades ilegales, no éticas o perjudiciales. Esto incluye, pero no se limita a, el acceso no autorizado a sistemas móviles, robo de datos, acoso o cualquier actividad que viole las leyes locales, nacionales o internacionales.

- Propiedad y responsabilidad: Los desarrolladores y proveedores de L3MON renuncian a cualquier responsabilidad por el mal uso de esta herramienta. Los usuarios son los únicos responsables de sus acciones y deben usar L3MON solo cumpliendo con las leyes aplicables y los estándares éticos.

- Consentimiento y privacidad: Es responsabilidad del usuario obtener el consentimiento explícito de las personas cuyos dispositivos o datos pueden ser accesados o monitoreados mediante L3MON. Se prohíbe estrictamente la invasión de la privacidad o el acceso no autorizado a información personal.

- Sin garantía: L3MON se proporciona "tal cual", sin garantías expresas o implícitas. Los desarrolladores no ofrecen garantías sobre su rendimiento, confiabilidad o idoneidad para un propósito particular.

- Fines educativos e investigación: L3MON puede ser utilizado con fines educativos e investigativos por profesionales, expertos en ciberseguridad y hackers éticos. Sin embargo, incluso en estos casos, debe utilizarse de manera responsable y de acuerdo con las leyes y regulaciones aplicables.

- Documentación e informes: Se recomienda a los usuarios mantener una documentación clara y precisa de sus actividades al utilizar L3MON. Cualquier vulnerabilidad o problema descubierto debe informarse a las partes correspondientes de inmediato.

- Discreción del usuario: Se aconseja a los usuarios que ejerzan discreción y precaución al utilizar L3MON para evitar consecuencias no deseadas, problemas legales o daños a personas, organizaciones o sistemas.

- Al utilizar L3MON, reconoces que has leído y entendido estos términos y condiciones, y aceptas cumplir con ellos. Cualquier mal uso o violación de estos términos puede resultar en consecuencias legales.

- L3MON es una herramienta poderosa que debe utilizarse de manera responsable y ética. No hacerlo puede resultar en acciones legales y daño a tu reputación.

## Thanks
L3MON Builds off and utilizes several opensource software, Without these, L3MON Wouldn't be what it is!
 - Inspiration for the project and the basic building blocks for the Android App are based on [AhMyth](https://github.com/AhMyth/AhMyth-Android-RAT) 
 - [express](https://github.com/expressjs/express)
 - [node-geoip](https://github.com/bluesmoon/node-geoip)
 - [lowdb](https://github.com/typicode/lowdb)
 - [socket.io](https://github.com/socketio/socket.io)
 - [Open Street Map](https://www.openstreetmap.org)
 - [Leaflet](https://leafletjs.com/)

## More
<b>D3VL Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
L3MON is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">Made with ❤️ By <a href="//d3vl.com">D3VL</a></p>
<p align="center" style="font-size: 8px">v1.1.2 <a href="https://github.com/D3VL/L3MON">Credit!</a></p>
