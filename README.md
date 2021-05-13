# Semana-2.-Reto-de-viaje.


# En este repositorio se encuentra el reto master de la semana 2.
### 1. Creación de las redes virtuales.
Este paso es muy sencillo ya que solo es darle y nombre y crearlas ( no se debe ocupar la misma red virtual para las 2 MV).
![IMG1](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(508).png)
### 2. Después empezamos creando la máquina virtual.
En este caso ocupe Debian ya que estoy un poco familiarizado con ella, llenamos las opciones para su creación, en las dos máquinas se selecciona las mismas propiedades y en puertos ocuparemos ssh.
![img2](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(509).png)
### 3. Acceder a nuestra máquina virtual.
Ocupe MobaXterm ya que este es un cliente ssh, ejecutamos el comando ssh (dirección ip de la MV) y luego nos pide la contraseña.
![img3](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(512).png)
### 4. Emparejar ambas máquinas virtuales.
Iremos a la parte de maquinas virtuales y seleccionamos la primera maquina virtual. Y seleccionamos la opción de emparejamiento, llenamos datos y listo.
![img4](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/C1.png)
### 5. Hacemos ping de MV1 a MV2.
Haremos ping a 10.0.0.4 
![img5](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(514).png)
# Hasta este paso ya hemos concluido la práctica, pero haremos que la MV2 se conecte a la MV1 de manera remota.
### 1. instalar ssh.
El primer paso es instalar ssh mediante el comando sudo apt-get install ssh.
![img6](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(517).png)
### 2. Instalar nmap.
Siguiente paso es instalar nmap mediante el comando sudo apt install nmap, en esta captura también se ejecuto el comando sudo nmap 10.0.0.4 que es mi dirección privada y me muestra que tengo el puerto ssh 22.
![img7](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(521).png)
### 3. Conectarse a la máquina virtual 1 
En la MV2 iniciamos sesión como en la primera y para conectarnos a la primera ejecutamos el comando ssh -p 22 (nombre de la MV1) y la dirección ip privada. Asi tengo acceso a mi máquina virtual 1 desde la máquina virtual 2.
![img8](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(519).png)
### 4. Detener las máquinas virtuales, consumirá tus créditos si no lo haces.
![img9](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(522).png)
### 5. Comprobar que si eran máquinas virtuales de Azure.
Cuando se detuvieron las máquinas virtuales, automáticamente me cerro la conexión.
![img5](https://github.com/CarlosM5250/Semana-2.-Reto-de-viaje/blob/main/img/Captura%20de%20pantalla%20(521).png)
# PD. Perdón por no hacer video 😐

