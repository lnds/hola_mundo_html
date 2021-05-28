# Laboratorio 

Despliegue de páginas estáticas en Digital Ocean

Sigue los siguientes pasos para desplegar este laboratorio en Digital Ocean
1. Visitar https://cloud.digitalocean.com/apps (si no has ingresado puedes ver un mensaje de error, visita https://cloud.digitalocean.com/login directamente y autentícate, luego intenta de nuevo).
1. Click en "Launch Your App" o "Create App"
1. Elegir GitHub y autenticarse con las credenciales de GitHub.
1. Bajo Repository, elegir este repository (e.g. <your-org>/hola_mundo_html), elegir la rama (branch) main, marcar la checkbox que dice autodeploy code changes y click en **Next**.
1. Aparece un pantalla con el título **Configure your app**, la dejamos tal cual y presionamos el botón azul que dice **Next**
1. Aparece un pantalla con el título **Name your static site**, acá podemos darle el nombre que queramos, esto nos permite conigurar el dominio que usará Digital ocean para desplegar nuestro sitio. Cambiamos el nombre y presionamos **Next**
1. Finalmente aparece una página con los planes, elegimos el plan **Starter** de costo cero y presionamos el botón que dice "Launch Starter App".
1. Luego del mensaje que indica que tu app fue creada, debes presionar el botón **Deploy** que aparece en el lado derecho de la consola de control de tu app. 
1. Verás que status dice mensaje "Building..." con un indicador de progreso. También aparece un enlace de con el nombre de la app que definiste arriba, al hacer click podrás acceder a tu sitio estático.
  
# Prueba lo siguiente
  
Tu sitio ha quedado configurado en modo de actualización automático, por lo tanto cualquier cambio que hagas en la página index.html se verá reflejado en el dominio configurado por DigitalOcean.
  
1. Modifica el texto de index.html, agrega un saludo, una imagenl lo que quieras
1. Verifica cómo se activa el proceso de building en la consola de gestión de Apps de Digital Persona
1. Revisa los logs
1. Refresca tu sitio
  
