*Actividad 1
*Sistemas Distribuidos

*Christian Cárdenas A00212740
*Luis F. Rosales A00315320

Se instalo CentOS 7 15.11 x64 bits con las siguientes caracteristicas:

HDD 20 GB
1.Interfaz de red tipo Bridge
se configuro un usuario sin privilegios llamado distribuidos 

Para instalar un servidor web se deben seguir los siguientes comandos desde usuario root:


1. listamos las interfaces con el comando
	ifup ens33
2. luego actualizamos el repositorio de paquetes e instalamos el servidor web con los comandos:
	sudo yum update
	sudo yum install httpd -y 
3. 
