# Configuración básica del sistema

## Tareas

### Actualizar los paquetes del sistema

- Limpiamos el caché 
- Actualizamos los paquetes, tipo apt update apt upgrade

``` bash
sudo apt list --upgradable
```

![alt text](image.png)

###  Configurar la zona horaria y locales

- Configuración de zona America Latina con Hora Lima UTC - 5

``` bash
timedatectl
```

![alt text](image-1.png)

### Crear un grupo llamado admin
- Creación de usuario admin

``` bash
getent group admin
```

![alt text](image-2.png)

### Crear un usuario devuser pertenenciente al grupo admin con contra cifrada

- Asignación de devuser a admin con contraseña cifrada
``` bash
sudo cat /etc/shadow
```

![alt text](image-3.png)
