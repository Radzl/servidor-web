# Experto B

## ¿Qué son las páginas web estáticas y dinámicas?

### Páginas web estáticas

Las páginas web estáticas son aquellas que tienen contenido fijo, es decir, no cambian aunque el usuario interactúe con ellas. Estas páginas están hechas principalmente con HTML, CSS y a veces un poco de JavaScript, y cuando alguien las visita, el servidor simplemente envía esos archivos tal cual.

**Características principales:**

- El contenido no cambia a menos que alguien modifique los archivos manualmente.
- No usan bases de datos ni necesitan que el servidor haga cálculos para mostrar la información.
- Se cargan rápido y son fáciles de hacer.
- Son ideales para páginas sencillas, como portfolios o sitios informativos.

### Páginas web dinámicas

Las páginas web dinámicas, por otro lado, sí cambian dependiendo de lo que haga el usuario o de la información que haya almacenada en bases de datos. Para esto, usan lenguajes que se ejecutan en el servidor, como PHP, Python, Node.js, entre otros.

**Características principales:**

- El contenido puede cambiar según el usuario o la situación.
- Usan bases de datos y procesamiento en el servidor para generar las páginas.
- Permiten mayor interacción y funcionalidades más complejas.
- Son las que se usan en tiendas online, redes sociales, blogs, etc.

## ¿Qué errores HTTP existen? Clasificación

Cuando accedemos a una página web, el servidor responde con un código HTTP que indica si todo fue bien o si hubo algún problema. Estos códigos se dividen en cinco grupos:

### 1xx: Respuestas informativas

Estos códigos indican que la solicitud está en proceso, pero no son muy comunes de ver.

- **100 Continue:** El servidor está listo para que el cliente siga enviando datos.
- **101 Switching Protocols:** El servidor acepta cambiar el protocolo.

### Éxito

La solicitud fue procesada correctamente.

- **200 OK:** Todo salió bien y la página se muestra correctamente.
- **201 Created:** Se creó un recurso nuevo después de la solicitud.
- **202 Accepted:** La solicitud fue aceptada, pero aún no se ha terminado de procesar.

### Redirecciones

Indican que hay que hacer algo más para completar la solicitud, como ir a otra URL.

- **301 Moved Permanently:** La página se ha movido a otra dirección permanentemente.
- **302 Found:** La página está temporalmente en otro lugar.
- **304 Not Modified:** La página no ha cambiado desde la última vez que se pidió.

### Errores del cliente

Significan que hubo un error en la solicitud que hizo el cliente (el navegador).

- **400 Bad Request:** La solicitud está mal formada o tiene errores.
- **401 Unauthorized:** Se necesita iniciar sesión o autenticar para ver la página.
- **403 Forbidden:** No tienes permiso para acceder a la página.
- **404 Not Found:** No se encontró la página solicitada.

### Errores del servidor

Estos errores indican que el servidor falló al procesar la solicitud.

- **500 Internal Server Error:** Error general en el servidor.
- **502 Bad Gateway:** El servidor recibió una respuesta inválida de otro servidor.
- **503 Service Unavailable:** El servidor está temporalmente fuera de servicio.
- **504 Gateway Timeout:** El servidor no recibió respuesta a tiempo de otro servidor.

## Proveedores de hosting web en España

Aquí dejo algunas páginas que ofrecen servicios de hosting en España, por si quieres montar un sitio web:

- [SiteGround](https://es.siteground.com/): Hosting rápido, con soporte 24/7 y planes desde precios accesibles.
- [Hostinger](https://www.hostinger.es/hosting-web): Ofrece hosting rápido y soporte técnico, con migración gratuita.
- [Dinahosting](https://dinahosting.com/): Ideal para desarrolladores y empresas, con buen soporte.
- [Arsys](https://www.arsys.es/hosting): Alojamiento con discos SSD y buena escalabilidad.
- [IONOS](https://www.ionos.es/alojamiento/alojamiento-web): Hosting con dominio gratis y buen rendimiento.

---

Este trabajo resume lo básico sobre páginas web estáticas y dinámicas, los principales errores HTTP que podemos encontrar y algunas opciones de hosting.
