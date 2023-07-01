# Replicas
### Eduardo Almachi
### Paul Hidalgo
### Aldahir Lascano
### Gilmar Morales
### David Vallejo

-------------------------------------------------------------------------------------------------------------------------------------------------------

Pasos del video:

1. Se crea un servidor dentro de hamachi por el cual a través de una ip los demas integrantes se podran conectar a través de la ip del dueño del servidor

![image](https://github.com/DavidPK8/Replicas/assets/127541791/fc16fd2f-bbd0-4b30-8839-c4deacb4bdc7)

2. Se crea la base de datos por la cual se enviaran 10 mil documentos a través de conexion remota la cual llevara el nombre de "videojuegos"

![image](https://github.com/DavidPK8/Replicas/assets/127541791/2ccd1124-7224-4075-97da-522d213634b9)

3. Además de crear la base de datos principal se crea una replica de tipo "continua" por conexion remota la cual se van a enviar todos los documentos existentes dentro de la base de datos de cada integrante 

![image](https://github.com/DavidPK8/Replicas/assets/127541791/da0ef2de-9147-45ee-a126-cb788906c420)


4. Mediante el siguiente codigo se van a enviar los 10 mil documentos (2 mil por integrante) lo cual se enviara entre el 0 y 2000 mil datos existentes dentro del csv "val_stats.csv" junto con los campos de nombre y apellido de los integrantes del equipo a la replica que se creo anteriormente

![image](https://github.com/DavidPK8/Replicas/assets/127541791/e82d81b7-a71a-492f-9cd6-181c79892501)



