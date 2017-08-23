# Taller 1

**Nombre: Carlos Andrés Torres López**  
**Código: A00141804**  

## Descripción  

Primer taller de sisitemas operativos 

## Soluciones  

### 1.  
| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |  
|/boot|------|aplicaciones binarias importantes|  
|/dev| hda(disco primario) |los ficheros disponibles|  
|/etc| passwd(contiene información sobre los usuarios) |ficheros de configuración|  
|/home|operativos|directorios personales para los diferentes usuarios|  
|/initrd|------|se usa cuando se crea un proceso de arranque|  
|/lib|lib64 |librerías del sistema|  
|/media|------| particiones montadas automáticamente en el disco duro y medios extraíbles como CD, usb, cámaras digitales|  
|/mnt|------|sistemas de archivos montados manualmente en el disco duro|  
|/opt|------|proporciona una ubicación para instalar aplicaciones opcionales|  
|/proc|------|directorio dinámico especial que mantiene la información sobre el estado del sistema|  
|/root|------|directorio personal del súper usuario|  
|/srv|------|Contiene archivos que sirven a otros sistemas|   
|/tmp|------|archivos temporales|  
|/usr|local|aplicaciones y archivos a los que pueden acceder la mayoría de usuarios|  
|/var| log  |archivos variables, como archivos de registros y bases de datos |  
|/sbin|------|binarios importantes del sistema|  
|/sys|------|archivos del sistema|  
|/los+found|------| proporciona un sistema de perdido encontrado para los ficheros del sistema |  

### 2.  
| Comando   | Usuario | Descripción   |  
|system restart httpd|root|iniciar , reiniciar  conocer el estado de un servicio en este caso httpd|  
|mkdir|cualquier usuario|crea una carpeta con el nombre que le indiquemos|  
|touch|cualquier usuario| actualiza los registros de fecha y hora|  
|mv|root|se usa para mover o renombrar un archivo|  
|kill|root|elimina el proceso que le indiquemos|  
|rm|root|borra el archivo que le indiquemos|  
|ps|cualquier usuario|se usa para conocer el estado del proceso|  
|df|cualquier usuario| informa cuanto espacio está disponible en cada disco|  
|halt|cualquier usuario|se utiliza para apagar el ordenador|  
|cp|cualquier usuario| copiar archivos y directorios dentro de la jerarquía|  

### 3.  
Este comando printev muestra el valor de todas las variables de ambiente: si se indica un nombre de variable  
muestra el valor de esa variable.  

para crear una variable de entorno se utiliza el comando export el nombre de la variable de entorno = sysadmit  
y para configurar variables de entorno permanentes se configuran dentro de /etc/enviroment


 


## Referencias

http://www.sysadmit.com/2016/04/linux-variables-de-entorno-permanentes.html
https://computernewage.com/2015/06/14/el-arbol-de-directorios-de-linux-al-detalle-que-contiene-cada-carpeta/



