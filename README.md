# Preshax
**Modificación de consola 3Ds**

Preshax es un proceso de modificación de la consola 3Ds que forma parte del proceso Seedminer y toma pasos del proceso USM [https://github.com/zoogie/unSAFE_MODE]. Ambos procesos son del desarrollador Zoogie y todos los agradecimientos son para él y su gran labor. 
Agradecimientos también a los desarrolladores del Team Preshax [https://discord.gg/8Fv8GDg] por facilitar la obtención del archivo Movable.sed, así como su futura continuación y dedicación al proyecto.  

- En primer lugar, necesitaremos:

Consola Virgen 3ds/2ds (Old o New) en versión 11.14 (Todas las Regiones son Válidas)

Tarjeta Sd/Micro Sd en formato FAT32 de 4 a 32 GB

Apuntar nuestro Código de amigo dentro de la aplicación Lista de Amigos

Archivos Hack (se encuentra Luma 10.2.1 Español, Traducido por López Tutoriales [https://github.com/LopezTutoriales/Luma3DS-Spanish] , y Godmode9 2.0.0)

- En segundo lugar, acudiremos a:
https://discord.gg/8Fv8GDg para sacar el archivo .sed. 

Con el anterior archivo.sed, sacaremos los archivos .bin ( F00D43D5.bin y usm.bin). https://movableproject.notsofter.repl.co/public/unsafemode.php.html
El archivo usm.bin deberemos meterlo en la raíz de la SD.
El archivo F00D43D5.bin debemos meterlo en la siguiente ruta: sdmc:/Nintendo 3DS/long hex number/another long hex number/Nintendo DSiWare (si no existe esta carpeta deberemos crearla respetando las Mayúsuclas y Minúsculas) 

- En tercer lugar, introduciremos los Archivos hack en la raíz de la Sd. https://mega.nz/file/e4EQWDbR#mXc0u4NeNO2kQ_GceRbgYkgwPIFtl1yFZtU8ZBetiwc

- En cuarto lugar, encenderemos la consola (con la Sd dentro) y acudiremos a: Configuración de la consola/Gestión de datos/DSiWare/Tarjeta microSD
En este momento la consola se flasheará en ROJO. Esto hará que las conexiones de la consola se renombrarn por HAXXXXXXXX.

- En quinto lugar, apagaremos la consola y acudiremos al Modo Recovery (L+R+A+Arriba+Power) y continuaremos con los siguientes pasos:

¿Quieres conectarte a internet para actualizar la consola? Aceptar. Lanzará un error 003-1099, es algo común.

¿Quieres configurar tu conexión a internet? Aceptar.

Seleccionar: Conexión 1. Modificar ajustes. Segunda página. Servidor Proxy. Ajustes avanzados. La consola se flasheará de nuevo y se acabará de instalar el Boot9

Acto seguido, saldrá el menú de Luma (de no ser así lo abriremos con select+power) y marcaremos la opción: Show current NAND in System Settings. Pulsaremos star para que inicie nuestra consola ya modificada.


- En sexto lugar, acudiremos a la consola y acudiremos a: Configuración de la consola/Gestión de datos/DSiWare/Tarjeta microSD
En este momento la consola se flasheará en VERDE. Esto hará que las conexiones de la consola vuelvan a estar funcionales.

Por último, tendrás que eliminar los archivos F00D43D5.bin y usm.bin que se encuentran dentro de la SD. Con ello, impediremos que vuelva a saltar el exploit. 


Ya habremos terminado el objetivo de la modificación, sin embargo, aún nos quedan cosas que hacer:
- Inyectar el FBI en H&S.
- Inyectar el Splash de seguridad (es opcional pero muy recomendable para idenficiar errores de arranque).
- Crear Respaldo NAND.
