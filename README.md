Instalación de PocketBase con Nginx Reverse Proxy (pocketbase-80.x)
Este script facilita la instalación de PocketBase v0.29.2 (o cualquier versión que desees) junto con Nginx como reverse proxy en un servidor Ubuntu CLI o GUI, para facilitar su despliegue en producción.

**Requisitos
Acceso con permisos elevados o como root.
Acceso a Internet para descarga de dependencias

**Instrucciones de Instalación
Descargar el script y hacerlo ejecutable:

Asegúrate de tener el archivo pocketbase-80.x

**Dale permisos de ejecución:
chmod +x pocketbase-80.x

**Ejecutar el script:
./pocketbase-80.x

**Seleccionar la opción de instalación:

En el menú interactivo, selecciona 1 para iniciar la instalación de PocketBase y presiona ENTER.

**Seleccionar la versión de PocketBase:

Ingresa la versión de PocketBase que deseas instalar (solo el número, por ejemplo: 0.22.35), luego presiona ENTER.

Si deseas instalar la versión predefinida (0.29.2), simplemente presiona ENTER para que el script descargue y configure esa versión automáticamente.
-- Támbién puedes tener el paquete (zip con su nombre original correspondiente a la versión a instalar ya descargado en la misma ruta del script) EJEMPLO: pocketbase_0.29.2_linux_amd64.zip   <--- solamente funciona con este nombre, no con darwin.

**Configurar el super-usuario:

Una vez completada la instalación, el script mostrará una URL similar a esta:

http://10.0.0.15:8090/_/#/pbinstal/TOKEN-PERSONAL
Haz clic derecho en la URL y cópiala en tu navegador para configurar el email y la contraseña del super-usuario de PocketBase.

**Finalizar la instalación:

Después de crear el perfil del super-usuario, presiona ENTER en el script para finalizar la instalación.

**El script mostrará una URL como la siguiente:

Accede en http://10.0.0.15/
Volver al menú de instalación/desinstalación:

Da el último ENTER para regresar al menú de instalación o desinstalación de PocketBase.

Desinstalación
Si deseas desinstalar PocketBase y Nginx, puedes ejecutar nuevamente el script y seleccionar la opción de desinstalación en el menú interactivo con el número 2 y ENTER.

Licencia
Este proyecto está licenciado bajo la Licencia Apache 2.0.
