# apache

Reemplace `$ALUMNO` por el nombre de su nombre de usuario en www.tecnologoinformatico.com

![image](https://user-images.githubusercontent.com/87677519/196560268-3bbf1347-66a0-4cdc-8c57-b33d7f2a6109.png)

EJ: `dmascheroni`

1. Cree el directorio ~/repositorios y dentro clone el
repositorio: `https://github.com/TecnologoInformatico/AdmInf-web.git`
2. Actualice el repositorio de la lista de paquetes.
    `apt update`
3. Instalar el servidor Apache mediante apt.
4. Cree el directorio /var/www/$ALUMNO
5. Asigne como propietario del directorio su usuario.
6. Configure un nuevo Virtual host. (copiando el archivo de configuración por defecto)
  6.1. ServerName $ALUMNO.tecnologoinformatico.com
  6.2. Correo de contacto con el administrador.
  6.3. El root de la aplicación. (/var/www/$ALUMNO)
7. Modifique el archivo /etc/hosts de modo que el ServerName coincida con este equipo `127.0.0.1`.
8. Reinicie el servidor apache para que los cambios tengan efecto.
9. Copie el contenido del directorio ~/repositorios/AdmInf-web a /var/www/$ALUMNO, de tal modo que el contenido del repositorio antes clonado se encuentre en el root de la aplicación.
10. Verifique que el servidor funcione correctamente.
11. Ingrese la IP del servidor y el servername a continuación:

```json
{
    "serverName": "",
    "ip": ""
}
```

##Respuestas

1. Cree el directorio ~/repositorios y dentro clone el
repositorio: `https://github.com/TecnologoInformatico/AdmInf-web.git`



2. Actualice el repositorio de la lista de paquetes.
    `apt update`
    
   --SIN PERMISOS--  
    ![image](https://user-images.githubusercontent.com/87677519/196558719-98c32434-3ad1-428e-aaf1-83fe801d89cb.png)

3. Instalar el servidor Apache mediante apt.

--SIN PERMISOS SUDO--  
![image](https://user-images.githubusercontent.com/87677519/196558882-391446b5-6c59-45ad-86c9-6503ee51e2bb.png)

Chequeo si esta instalado

![image](https://user-images.githubusercontent.com/87677519/196558975-ea009dd2-d92f-4b15-9251-76387be90f5e.png)

4. Cree el directorio /var/www/$ALUMNO


5. Asigne como propietario del directorio su usuario.
6. Configure un nuevo Virtual host. (copiando el archivo de configuración por defecto)
  6.1. ServerName $ALUMNO.tecnologoinformatico.com
  6.2. Correo de contacto con el administrador.
  6.3. El root de la aplicación. (/var/www/$ALUMNO)
7. Modifique el archivo /etc/hosts de modo que el ServerName coincida con este equipo `127.0.0.1`.
8. Reinicie el servidor apache para que los cambios tengan efecto.
9. Copie el contenido del directorio ~/repositorios/AdmInf-web a /var/www/$ALUMNO, de tal modo que el contenido del repositorio antes clonado se encuentre en el root de la aplicación.
10. Verifique que el servidor funcione correctamente.
11. Ingrese la IP del servidor y el servername a continuación:

```json
{
    "serverName": "",
    "ip": ""
}
```


