# WSL2
## Laboratorio 1

1. crear repositorio

2. 
La arquitectura de WSL2
Esta permite que el subsistema  de windows para Linux se ejecute archivos binarios  de linux en Windows, para aumentar el rendimiento del sistema de archivos y hacer compatible con la funciones del sistema.
Esta permite un cambio en manejo de los archivos binarios de Linux para interactuar también con el hardware del equipo, pero tiene las mismas funcionalidades de WSL1.
WLS2  esta arquitectura aprovecha las ventajas del kernel  Linux,además por su tecnología  de virtualizacion   para obtener nuevas características.
Wls2 funcióna con versiones de virtualbox 6 y versiones posteriores
Las maquinas virtuales tradicionales presentaban arranque lento y mucho consumo de recursos y también se necesitaba tiempo para la administración y  con wls2 mejore en cuanto a estas características.

La arquitectura Wls2 se basa en la hiper v,por lo tanto es otra maquina virtual,entonces para utilizar se puede elegir entre  wls2,el Docker y otra maquina virtual.como virtual box. Docker ofrece una opción para usar el contenedor de Windows
WSL 2 no incluye compatibilidad para acceder a los puertos serie. 
Tiene requisitos de memoria limitada
Wls2 no libera memoria  y mantiene las paginas de cache hasta que se cierre  WLS2,y puede ocupar la memoria windows 
Microsotf  creo kernel  de Linux completo como mejora del WSL1,ajustándose y dando lugar a lo que se convertiría wsl2,optimizando en tamaño pero mejorar la experiencia.
El kernel facilita la adminitracion ya que este cuenta con actualizaciones  que presentaran correcciones de seguridad


A través del subsistema de archivos Windows para Linux los usuarios  pueden acceder mas fácilmente a los archivos de  Windows desde Linux por medio de  la vitalización de Microsoft para poder usar Linux en Windows sin ningún inconveniente, y así poder estar conectados de tal manera que se puede acceder  a los recursos de un sistema a otro, como por ejemplo abrir sus archivos.
Para esto se abre powershell y debemos iniciar sesión, y lo siguiente que debemos hacer es

* conocer la ruta  completa en Windows del archivo que queremos abrir.
Por lo cual se pone el siguiente comando 
cmd.exe /C start "ruta-al-archivo".

* Reemplazar la ruta de archivo y al darle Enter automáticamente se abre el archivo y se abrirá con el programa que se haya guardado, con lo cual se podrá modificar 

_Ejemplo:_
cmd.exe /C start C:\xampp\htdocs\proyecleo
para tener acceso al archivo wls2 con Ubuntu a Windows es de la siguiente manera:
