# jboss-docker
Este es un laboratorio para instalar Jboss 6.4 a traves de Docker, con un cantenedor basado en Centos 7 y optimizado.
Añadimos los ficheros:

standalone.xml--> Esta configurado con el driver de mysql
mysql-connector-java-5.1.27-bin.jar--> Driver de mysql para instalarlo en el servidor de Aplicaciones Jboss EAP 6.4
module.xml--> Modulo para base de datos mysql configurado para Jboss EAP 6.4
java.sh--> Para configurar las variables de entorno al conedor de Jboss con la version de java jdk1.7.0_80

En el proyecto se ha utilizado los siguientes archivos que pasamos al contenedor a traves del Dockerfile:
-jboss-eap-6.4.0.zip
-jdk-7u80-linux-x64.rpm


