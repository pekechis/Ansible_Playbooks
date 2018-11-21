# PRACTICAS ANSIBLE NOV-2018

## EJERCICIO 1:  Configuración de máquinas para el acceso mediante SSH sin contraseña.

Partiendo de un VagrantFile  que cree dos máquinas virtuales configurar mediantes dos playbooks esas máquinas virtuales para que se pueda acceder a ellas mediante un usuario y sin contraseña.

El nombre del usuario habrá que solicitarlo al ejecutar el aprovisionamiento.

En el aprovisionamiento habrá que:

* Crear los usuarios.
* Instalar SSH y configurarlo.
* Crear las claves necesarias.
* Colocar las claves en los directorios adecuados.

## EJERCICIO 2:  Instalación de phpMyAdmin partiendo de una repositorio de GitHUB.

URL del repositorio: https://github.com/phpmyadmin/phpmyadmin

Partiendo de un Vagrantfile aprovisionar la máquina virtual para que:

* Instale todos los paquetes necesarios para que funcione una aplicación web como phpMyAdmin
* Se nos pida el nombre del usuario que queremos que sea administrador de la base de datos así como su contraseña.
* Instale GIT
* Obtenga el código de la aplicación usando los módulos de GIT de Ansible
* Coloque ese código en el lugar adecuado
* Se pueda acceder a través del puerto 8080 de nuestra máquina real.

## EJERCICIO 3: Creación de un maestro MySQL con 1 Esclavo.

Partiendo de un Vagrantfile que cree 2 máquinas aprovisionar esas dos máquinas para que cree de manera directa una configuración Maestro-Esclavo.

Durante ese aprovisionamiento deberé:

* Instalar MySQL en las dos máquinas.
* Hacer que ambas máquinas pertenezcan a la misma red y se vean mediante los nombres maestro y esclavo
* Configurar adecuadamente los dos servidores MySQL. Usuarios, permisos y replicación

## EJERCICIO 4: Creación de un máquina con docker y 10 imágenes de Docker.

Partiendo de un Vagrantfile que cree una máquina virtual aprovisionar esa máquina para que:

* Se instale docker (habrá que añadir los repositorios y ejectuar todas las órdenes necesarios).
* Se añada el usuario docker al grupo sudoers para que tengamos que ejecutar docker sin hacer sudo
* Se instalen 10 imágenes diferentes desde dockerHub. El nombre  habrá que solicitarlo al ejecutar el aprovisionamiento.
* Conforme se instala cada contenedor habrá que mostrar un mensaje personalizado por pantalla.

**NOTA:** Podemos usar roles per hay que documentar su uso y explicar cómo lo habéis configurado.