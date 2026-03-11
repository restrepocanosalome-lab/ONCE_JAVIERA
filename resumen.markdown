# Fundamentos de Internet y Protocolo HTTP

## 1. ¿Cómo funciona Internet?

Internet es una red mundial de computadoras que se comunican mediante protocolos que permiten enviar y recibir información.

### Protocolos TCP/IP

Los **TCP/IP** son reglas que permiten la comunicación entre dispositivos en Internet.

- **IP (Internet Protocol):** identifica cada dispositivo mediante una dirección IP.
- **TCP (Transmission Control Protocol):** divide la información en paquetes y asegura que lleguen correctamente.

### Sistema DNS

El **DNS (Domain Name System)** traduce los nombres de dominio a direcciones IP.

Ejemplo:
- google.com → 142.250.190.78

Esto permite que los usuarios naveguen usando nombres fáciles en lugar de números.

### Protocolo DHCP

El **DHCP (Dynamic Host Configuration Protocol)** asigna automáticamente una dirección IP a los dispositivos cuando se conectan a una red.

Funciones:
* Asignar IP automáticamente
* Evitar conflictos de IP
* Facilitar la conexión a redes



## 2. Protocolo HTTP y la Web

El **HTTP (HyperText Transfer Protocol)** es el protocolo que permite que los navegadores soliciten páginas web a los servidores.

### Componentes de una URL

Una URL tiene tres partes principales:

1. **Esquema:** http o https
2. **Dominio:** nombre del sitio web
3. **Ruta:** ubicación del recurso dentro del servidor

Ejemplo:
- https → esquema  
- www.example.com → dominio  
- /blog/articulo → ruta  



### Verbos HTTP: GET y POST

**GET**
- Se usa para solicitar información.
- Los datos se envían en la URL.

**POST**
- Se usa para enviar información al servidor.
- Los datos se envían en el cuerpo de la solicitud.

# El significado y propósito de los códigos de estado más comunes

. **200 – OK**
   - Significa que la solicitud fue exitosa.
   - El servidor encontró el recurso solicitado y lo envió correctamente al navegador.

2. **301 – Moved Permanently**
   - Indica que la página fue movida permanentemente a otra dirección URL.
   - El navegador redirige automáticamente al usuario a la nueva ubicación.

3. **404 – Not Found**
   - Significa que el servidor no pudo encontrar el recurso solicitado.
   - Ocurre cuando una página fue eliminada o la URL está escrita incorrectamente.

4. **500 – Internal Server Error**
   - Indica que ocurrió un error interno en el servidor.
   - El problema no está en el navegador del usuario sino en el servidor del sitio web.