Podrá acceder a los archivos en "https://github.com/MatMa4/TP-Dise-o-de-Sistemas-Entrega-"

Para ejecutar la aplicación primero se deben seguir los siguientes pasos:
1) Abrir la carpeta "TrabajoPractico_Backend" desde NetBeans. 
2) Ejecutar el contenido de la carpeta presionando el botón run.
3) Acceder a la carpeta "FrontEnd" y dentro de esta a la carpeta "out".
4) Abrir la terminal de Windows desde esta carpeta.
5) Ingresar en la terminal el comando "npx serve" (es posible que le solicite realizar una instalación, en ese caso debe ingresar "y para instalar" (esto solo debería ocurrir la primera vez))
6) Si esto fue exitoso se mostrará en la consola un mensaje que dice Serving! y dos links
7) Una vez que estén iniciadas las aplicaciones de NetBeans y Next debe acceder al siguiente link desde un explorador: "http://localhost:3000/darAltaHuesped"
8) En el explorador se debería mostrar el formulario para dar alta huéspedes

Aclaraciones y advertencias:
- Antes de ejecutar el proyecto de NetBeans recuerde verificar que no se esté ejecutando si es que realizó pruebas anteriormente. Si se vuelve a ejecutar mostrará un fallo ya que la otra ejecución estará utilizando el puerto que necesita para recibir las solicitudes
- La aplicación actual se encuentra en desarrollo, por lo que puede que se presenten problemas en la visualización que serán corregidos en el futuro
- La aplicación está configurada de forma que la base de datos se elimina al volver a iniciar el proyecto de NetBeans
- Para ver el estado actual de la base de datos recomendamos utilizar Postman y realizar una solicitud GET en "http://localhost:8080/huespedes"

