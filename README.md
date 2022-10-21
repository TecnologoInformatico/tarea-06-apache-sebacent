# apache

Reemplace `$ALUMNO` por el nombre de su nombre de usuario en www.tecnologoinformatico.com

![image](https://user-images.githubusercontent.com/87677519/197080968-466af06e-a260-4be4-a5c6-a84dd61edbad.png)

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

![image](https://user-images.githubusercontent.com/87677519/197081347-94875425-f413-4fc7-87b0-d1444c4cac7d.png)


2. Actualice el repositorio de la lista de paquetes.
    `apt update`

![image](https://user-images.githubusercontent.com/87677519/197081902-8290ed41-9eaf-4c72-8774-a37472c00d71.png)

3. Instalar el servidor Apache mediante apt.

![image](https://user-images.githubusercontent.com/87677519/197082157-b4b1c948-cd00-4bef-b849-eaf5adc0b96b.png)


4. Cree el directorio /var/www/$ALUMNO

![image](https://user-images.githubusercontent.com/87677519/197082580-b1f1d481-183e-40d4-b439-e8dfdac21d01.png)


5. Asigne como propietario del directorio su usuario.

![image](https://user-images.githubusercontent.com/87677519/197082977-3caefcd2-08d2-41dc-84c1-554a333edd01.png)


6. Configure un nuevo Virtual host. (copiando el archivo de configuración por defecto)
  6.1. ServerName $ALUMNO.tecnologoinformatico.com
  6.2. Correo de contacto con el administrador.
  6.3. El root de la aplicación. (/var/www/$ALUMNO)
  
  ![image](https://user-images.githubusercontent.com/87677519/197085219-652d070f-2a54-4100-b509-d990fbfd787e.png)


7. Modifique el archivo /etc/hosts de modo que el ServerName coincida con este equipo `127.0.0.1`.

![image](https://user-images.githubusercontent.com/87677519/197085475-241dc0cd-fb1f-40fd-bc4e-90dcebfc26e6.png)


8. Reinicie el servidor apache para que los cambios tengan efecto.


9. Copie el contenido del directorio ~/repositorios/AdmInf-web a /var/www/$ALUMNO, de tal modo que el contenido del repositorio antes clonado se encuentre en el root de la aplicación.

![image](https://user-images.githubusercontent.com/87677519/197088237-0db544ae-e612-4ded-995a-2ac87a3c61cb.png)

10. Verifique que el servidor funcione correctamente.

![image](https://user-images.githubusercontent.com/87677519/197088285-f9051f76-d72d-47ac-9ec0-8c13a1499aec.png)


11. Ingrese la IP del servidor y el servername a continuación:

```json
{
    "serverName": "scenturion.tecnologoinformatico.com",
    "ip": "144.22.172.144"
}
```


