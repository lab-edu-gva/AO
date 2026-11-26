---
tipo: sesion
asignatura: AO
unidad: "UD2 - Gestión de Correo Electrónico, Agenda y Almacenamiento en la Nube"
numero_sesion: 07
fecha:
duracion: 55
estado: preparado
resultado_aprendizaje:
  - RA8
  -   - RA9
criterios_evaluacion:
  - RA8.b
  - RA9.a
  - RA9.c
tags:
  - AO
  - UD2
  - correo-electronico
  - agenda
  - nube
---
---

# S07 - Configuración de clientes de correo electrónico

## 1. Introducción

Hasta ahora hemos utilizado el correo electrónico desde su interfaz web o mediante las herramientas que ofrece el proveedor.

Sin embargo, también podemos gestionar una cuenta de correo mediante un programa instalado en nuestro ordenador.

Este tipo de aplicación se denomina **cliente de correo electrónico**.

En una empresa es habitual configurar los equipos de los trabajadores para que puedan consultar y enviar mensajes desde un programa específico, sin necesidad de acceder continuamente a la página web del proveedor.

Para realizar esta configuración debemos conocer algunos conceptos técnicos, especialmente los protocolos IMAP, POP3 y SMTP.

## 2. ¿Qué es un cliente de correo electrónico?

Un cliente de correo electrónico es un programa que permite gestionar una o varias cuentas de correo desde una misma aplicación.

Entre sus funciones habituales encontramos:

- Recibir mensajes.
    
- Enviar mensajes.
    
- Responder y reenviar correos.
    
- Organizar mensajes en carpetas.
    
- Gestionar contactos.
    
- Consultar calendarios, cuando la aplicación lo permite.
    
- Adjuntar archivos.
    
- Configurar firmas.
    
- Administrar varias cuentas.
    

Algunos ejemplos son:

- Mozilla Thunderbird.
    
- Microsoft Outlook.
    
- Apple Mail.
    

### 2.1. Cliente de correo frente a webmail

Existen dos formas habituales de acceder al correo electrónico.

**Webmail**

Se accede mediante un navegador web, visitando la página del proveedor.

Ejemplos:

- Gmail desde `gmail.com`.
    
- Outlook desde `outlook.com`.
    

**Cliente de correo**

Se utiliza una aplicación instalada en el dispositivo que se conecta al servidor de correo.

Ejemplos:

- Thunderbird.
    
- Outlook de escritorio.
    
- Apple Mail.
    

|Característica|Webmail|Cliente de correo|
|---|---|---|
|Acceso|Navegador web|Aplicación|
|Instalación|No suele necesitar instalación|Normalmente sí|
|Varias cuentas|Depende del servicio|Habitualmente sí|
|Trabajo sin conexión|Limitado|Puede permitir consultar mensajes sincronizados|
|Configuración técnica|Generalmente sencilla|Puede requerir configuración|

Ambas opciones permiten gestionar el correo electrónico. La elección depende de las necesidades del usuario o de la organización.

## 3. ¿Cómo funciona la conexión con el servidor?

Cuando configuramos un cliente de correo, necesitamos establecer una conexión entre el programa y los servidores del proveedor.

Normalmente intervienen dos servicios:

1. Un servidor para recibir o consultar los mensajes.
    
2. Un servidor para enviar los mensajes.
    

Para comunicarse utilizan protocolos específicos.

Un protocolo es un conjunto de reglas que permite que dos sistemas intercambien información correctamente.

Los principales protocolos relacionados con el correo electrónico son:

- IMAP.
    
- POP3.
    
- SMTP.
    

## 4. Protocolo IMAP

IMAP significa _Internet Message Access Protocol_.

Es un protocolo que permite consultar y gestionar los mensajes almacenados en el servidor de correo.

Cuando utilizamos IMAP, el cliente sincroniza los cambios con el servidor.

Por ejemplo:

1. Abrimos el correo desde el ordenador.
    
2. Leemos un mensaje.
    
3. El mensaje aparece como leído en el servidor.
    
4. Accedemos posteriormente desde el móvil.
    
5. El mensaje también aparece como leído.
    

Esto ocurre porque los dispositivos trabajan con la misma información sincronizada.

### 4.1. Ventajas de IMAP

- Permite consultar el correo desde varios dispositivos.
    
- Mantiene los mensajes sincronizados.
    
- Conserva la organización de carpetas en el servidor.
    
- Facilita el trabajo desde diferentes ubicaciones.
    

### 4.2. Inconvenientes de IMAP

- Necesita conexión a Internet para sincronizar.
    
- El almacenamiento del servidor puede llenarse.
    
- La configuración incorrecta puede provocar problemas de sincronización.
    

**Uso habitual:** es una opción muy recomendable cuando una persona consulta su correo desde varios dispositivos.

## 5. Protocolo POP3

POP3 significa _Post Office Protocol version 3_.

Es un protocolo que permite descargar mensajes desde el servidor al dispositivo.

Tradicionalmente, se utilizaba para descargar los mensajes al ordenador y gestionarlos localmente.

Dependiendo de la configuración, el programa puede eliminar los mensajes del servidor después de descargarlos o conservar una copia.

### 5.1. Ventajas de POP3

- Permite descargar mensajes al equipo.
    
- Facilita trabajar con mensajes almacenados localmente.
    
- Puede reducir el espacio utilizado en el servidor si se descargan y eliminan los mensajes.
    

### 5.2. Inconvenientes de POP3

- La sincronización entre dispositivos es más limitada.
    
- La organización de mensajes puede ser diferente en cada equipo.
    
- Si se elimina la copia del servidor, puede resultar complicado acceder a esos mensajes desde otros dispositivos.
    

**Uso habitual:** puede utilizarse cuando se desea descargar el correo en un equipo concreto y gestionarlo principalmente desde él.

## 6. Diferencias entre IMAP y POP3

|Característica|IMAP|POP3|
|---|---|---|
|Funcionamiento|Sincroniza con el servidor|Descarga mensajes|
|Varios dispositivos|Muy adecuado|Menos adecuado|
|Carpetas|Sincronizadas|Gestión principalmente local|
|Estado leído/no leído|Se sincroniza|Puede variar entre dispositivos|
|Almacenamiento|Principalmente en servidor|Puede ser local|
|Uso habitual|Correo multidispositivo|Descarga en un equipo|

**Ejemplo:**

Una trabajadora consulta el correo desde el ordenador de la oficina y desde su teléfono móvil.

Lo más adecuado normalmente sería utilizar IMAP para que ambos dispositivos mantengan sincronizados los mensajes y sus estados.

## 7. Protocolo SMTP

SMTP significa _Simple Mail Transfer Protocol_.

Es el protocolo utilizado para enviar mensajes de correo electrónico.

Cuando escribimos un correo y pulsamos el botón Enviar, el cliente utiliza un servidor SMTP para transmitir el mensaje.

Por tanto:

- IMAP permite consultar y gestionar mensajes.
    
- POP3 permite descargar mensajes.
    
- SMTP permite enviar mensajes.
    

Es importante no confundirlos: SMTP no es el protocolo utilizado para recibir mensajes.

## 8. Puertos habituales del correo electrónico

Además del protocolo, necesitamos conocer el puerto de conexión.

Un puerto es un número que identifica un servicio de comunicación dentro de un servidor.

Los puertos habituales son:

|Servicio|Puerto|Seguridad|
|---|---|---|
|IMAP|143|Sin cifrado implícito|
|IMAP|993|SSL/TLS|
|POP3|110|Sin cifrado implícito|
|POP3|995|SSL/TLS|
|SMTP|25|Habitualmente comunicación entre servidores|
|SMTP|465|SSL/TLS|
|SMTP|587|STARTTLS, habitual para envío autenticado|

### 8.1. ¿Qué significa SSL/TLS?

SSL y TLS son tecnologías utilizadas para proteger las comunicaciones mediante cifrado.

Cuando una conexión utiliza cifrado, la información transmitida queda protegida frente a determinadas formas de interceptación.

En la configuración de una cuenta debemos utilizar los parámetros de seguridad indicados por el proveedor.

**Importante:** no debemos elegir los puertos únicamente porque aparezcan en esta tabla. Cada proveedor puede establecer sus propios requisitos.

## 9. Configuración automática y manual

Al añadir una cuenta a un cliente de correo, normalmente podemos encontrarnos con dos posibilidades.

### 9.1. Configuración automática

Es la opción más sencilla.

El programa solicita normalmente:

- Dirección de correo electrónico.
    
- Contraseña o método de autenticación.
    

Después intenta detectar automáticamente los servidores y parámetros necesarios.

Si el proveedor es compatible, puede configurar la cuenta sin que tengamos que introducir los datos técnicos.

### 9.2. Configuración manual

Si la detección automática falla, podemos tener que introducir los datos proporcionados por el administrador o proveedor de correo.

Los parámetros habituales son:

**Servidor de entrada:**

- Nombre del servidor.
    
- Protocolo IMAP o POP3.
    
- Puerto.
    
- Tipo de cifrado.
    
- Método de autenticación.
    

**Servidor de salida:**

- Nombre del servidor SMTP.
    
- Puerto.
    
- Tipo de cifrado.
    
- Autenticación, si es necesaria.
    

Ejemplo ficticio de configuración:

|Parámetro|Valor|
|---|---|
|Correo|[usuario@empresa.es](mailto:usuario@empresa.es)|
|Servidor IMAP|imap.empresa.es|
|Puerto IMAP|993|
|Seguridad IMAP|SSL/TLS|
|Servidor SMTP|smtp.empresa.es|
|Puerto SMTP|587|
|Seguridad SMTP|STARTTLS|
|Autenticación SMTP|Sí|

Estos valores son un ejemplo didáctico. No deben utilizarse para configurar una cuenta real sin confirmar los datos del proveedor.

## 10. Ejemplo guiado: configurar una cuenta en Thunderbird

Mozilla Thunderbird es un cliente de correo electrónico gratuito que permite gestionar diferentes cuentas.

<PRIVATE_PERSON>

### Paso 1. Abrir Thunderbird

Iniciamos la aplicación y buscamos la opción para añadir una cuenta de correo existente.

### Paso 2. Introducir los datos

Escribimos:

- Nombre del usuario.
    
- Dirección de correo electrónico.
    
- Contraseña o método de autenticación solicitado.
    

### Paso 3. Comprobar la configuración

Thunderbird intenta detectar los servidores automáticamente.

Si no lo consigue, podemos introducir manualmente los parámetros IMAP o POP3 y SMTP.

### Paso 4. Revisar la seguridad

Comprobamos que los servidores utilizan los puertos y mecanismos de cifrado indicados por el proveedor.

### Paso 5. Finalizar

Guardamos la configuración y comprobamos que podemos:

1. Recibir mensajes.
    
2. Enviar mensajes.
    
3. Consultar las carpetas.
    
4. Sincronizar los cambios.
    

## 11. Seguridad y autenticación

Configurar una cuenta de correo implica manejar información que puede ser confidencial.

Por eso debemos aplicar algunas medidas de seguridad:

- Utilizar conexiones cifradas.
    
- No compartir las contraseñas.
    
- Utilizar contraseñas robustas.
    
- Activar la autenticación multifactor cuando esté disponible.
    
- Evitar configurar cuentas en equipos públicos.
    
- Cerrar las sesiones cuando corresponda.
    
- Utilizar los parámetros oficiales del proveedor.
    

### 11.1. Contraseñas y autenticación moderna

Algunos proveedores ya no permiten introducir directamente la contraseña habitual en cualquier programa.

En su lugar, utilizan sistemas de autenticación modernos, como OAuth 2.0, que permiten autorizar una aplicación sin entregar directamente la contraseña a esa aplicación.

Por ejemplo, al configurar una cuenta de Microsoft o Google, puede aparecer una ventana del proveedor para iniciar sesión y conceder permisos al cliente de correo.

## 12. Problemas habituales de configuración

Al configurar un cliente de correo pueden aparecer diferentes errores.

|Problema|Posible causa|
|---|---|
|No se reciben mensajes|Servidor o puerto de entrada incorrecto|
|No se pueden enviar mensajes|Configuración SMTP incorrecta|
|Error de autenticación|Contraseña o método de acceso incorrecto|
|No se sincronizan las carpetas|Problema de conexión o configuración IMAP|
|Error de certificado|Problema con la validación de la conexión segura|
|La cuenta no se configura automáticamente|El proveedor no facilita la detección automática|

Ante una incidencia debemos comprobar los parámetros, revisar la conexión y consultar la documentación del proveedor.

No debemos desactivar las medidas de seguridad para solucionar un problema sin conocer sus consecuencias.

## 13. Actividades prácticas

### Actividad 1. Identificar protocolos

Indica qué protocolo utilizarías en cada situación:

1. Consultar los mensajes desde varios dispositivos manteniéndolos sincronizados.
    
2. Descargar mensajes en un ordenador concreto.
    
3. Enviar un correo electrónico a un cliente.
    
4. Sincronizar el estado leído de un mensaje entre el ordenador y el móvil.
    

### Actividad 2. Interpretar una configuración

Una empresa facilita estos datos:

|Parámetro|Valor|
|---|---|
|Servidor de entrada|imap.empresa.es|
|Puerto de entrada|993|
|Seguridad|SSL/TLS|
|Servidor de salida|smtp.empresa.es|
|Puerto de salida|587|
|Seguridad|STARTTLS|

Responde:

1. ¿Qué protocolo utiliza para recibir mensajes?
    
2. ¿Qué protocolo utiliza para enviar mensajes?
    
3. ¿Qué puerto utiliza el servidor de entrada?
    
4. ¿Qué puerto utiliza el servidor de salida?
    
5. ¿Por qué se utilizan conexiones cifradas?
    

### Actividad 3. Elegir IMAP o POP3

Una empresa tiene tres trabajadores que consultan sus cuentas desde el ordenador de la oficina y desde sus teléfonos móviles.

Responde:

1. ¿Qué protocolo recomendarías para recibir el correo?
    
2. ¿Por qué?
    
3. ¿Qué problemas podrían aparecer si utilizaran POP3 descargando y eliminando los mensajes del servidor?
    

### Actividad 4. Documentar una configuración

Busca la documentación oficial de un proveedor de correo electrónico y localiza los parámetros necesarios para configurar una cuenta mediante un cliente externo.

Elabora una tabla con:

- Servidor de entrada.
    
- Protocolo de entrada.
    
- Puerto de entrada.
    
- Tipo de cifrado.
    
- Servidor de salida.
    
- Puerto de salida.
    
- Tipo de cifrado.
    
- Método de autenticación.
    

No es necesario introducir una contraseña real ni compartir datos personales.

## 14. Preguntas de repaso

1. ¿Qué es un cliente de correo electrónico?
    
2. ¿Qué diferencia existe entre webmail y un cliente de correo?
    
3. ¿Qué significa IMAP?
    
4. ¿Qué significa POP3?
    
5. ¿Qué protocolo se utiliza para enviar mensajes?
    
6. ¿Qué diferencia existe entre IMAP y POP3?
    
7. ¿Qué puerto utiliza habitualmente IMAP con SSL/TLS?
    
8. ¿Qué puerto utiliza habitualmente SMTP con STARTTLS?
    
9. ¿Qué significa que una conexión esté cifrada?
    
10. ¿Qué datos necesitamos para configurar manualmente una cuenta?
    
11. ¿Qué es OAuth 2.0?
    
12. ¿Por qué no debemos desactivar la seguridad para solucionar errores de configuración?
    

## Resumen de la sesión

- Un cliente de correo permite gestionar cuentas desde una aplicación.
    
- Webmail utiliza un navegador; un cliente de correo utiliza un programa específico.
    
- IMAP sincroniza los mensajes con el servidor.
    
- POP3 permite descargar mensajes al dispositivo.
    
- SMTP se utiliza para enviar mensajes.
    
- Los puertos identifican los servicios de comunicación.
    
- SSL/TLS protege las comunicaciones mediante cifrado.
    
- La configuración puede ser automática o manual.
    
- Los parámetros deben obtenerse del proveedor o administrador del servicio.
    

**Relación curricular:** esta sesión contribuye al RA8, especialmente al criterio RA8.b, mediante la configuración de clientes de correo electrónico según los requerimientos de una organización.