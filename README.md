# Anyelita

Tienda online de accesorios de cómputo para Anyelita, en Miraflores, Lima. Sitio estático, adaptable a móviles, con catálogo ilustrado en CSS, filtros, selección de vendedor, carrito persistente y asistente de preguntas frecuentes.

## Ejecutar

Abre `index.html` directamente o sirve la carpeta con cualquier servidor estático. No necesita dependencias de compilación.

## Venta y correo

El checkout prepara un correo dirigido a `richardgereholliwod@gmail.com` con el vendedor, productos, cantidades y total. Usa el cliente de correo configurado por el visitante (`mailto:`); el navegador no puede confirmar si el mensaje fue enviado. Para enviar el correo automáticamente y confirmar el resultado de forma fiable, conecta el botón a una función backend/API con un proveedor de correo (por ejemplo, Resend o SMTP), guarda las credenciales como variables de entorno y cambia el mensaje de éxito para que dependa de la respuesta real. No pongas claves privadas en `app.js`.

El chatbot incluido responde preguntas frecuentes desde una base local, sin IA generativa ni transmisión de datos. Puede conectarse a un modelo mediante un endpoint backend si se desea conversación generativa.

## Publicar

Puede publicarse en GitHub Pages u otro host estático. Para subirlo a GitHub, configura un remote que pertenezca a la cuenta/repositorio deseado y ejecuta `git push` después del commit.
