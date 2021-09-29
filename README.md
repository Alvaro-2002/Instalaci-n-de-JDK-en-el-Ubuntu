# Instalación de JDK en Ubuntu
En este  repositorio se muestran todos los pasos a seguir para instalar JDK en Ubuntu desde la terminal.
* INDICE:
* 1 Instalación de Java en Ubuntu desde repositorios
* 2 Instalación  de una  versión específica de Java
* 3 Comprobación de  la versión de OpenJDK instalada
* 4 Actualización de las variables de entorno


1
Lo primero que debemos hacer es abrir una terminal y poner el siguiente comando :  sudo `apt-get update`; lo que actualizara el sistema. Procederemos a instalar java con 
sudo `  sudo apt-get install default-jdk
` y posteriormente comprobamos la versión  con  `java -version`.

[![Virtual-Box-ubunto-1.png](https://i.postimg.cc/HLrsbCWx/Virtual-Box-ubunto-1.png)](https://postimg.cc/mcGsGJHf)
[![Virtual-Box-ubunto-2-copia.png](https://i.postimg.cc/d3wkYtr1/Virtual-Box-ubunto-2-copia.png)](https://postimg.cc/9RgFP2x5)

2
En la terminal ponemos el comando `sudo apt install openjdk-8-jdk` para insdicar la versión que queremos instlar 
[![Virtual-Box-ubunto-3.png](https://i.postimg.cc/G3fsG3Mf/Virtual-Box-ubunto-3.png)](https://postimg.cc/Z0rRhmzP)
Comprobamos la versión con `java -version`
[![Virtual-Box-ubunto-4.png](https://i.postimg.cc/GmT0tK4N/Virtual-Box-ubunto-4.png)](https://postimg.cc/cvWk5QMM)

3 
Ejecutamos el siguiente comando   `cls /usr/lib/jvm`  y vemos la lista de las versiones de OpenJDK instaladas

4
Actualizamos las variables de entorno `sudo update-alternatives --config java`

[![Virtual-Box-ubunto-5.png](https://i.postimg.cc/28p9TYyH/Virtual-Box-ubunto-5.png)](https://postimg.cc/V5RFL3jM)

Actualizamos las variables de entorno y las configuramos
 `# Java version
JAVA_HOME=/usr/lib/jvm/_____openJdk_____
PATH=$PATH:$HOME/bin:$JAVA_HOME/bin
export JAVA_HOME
export JRE_HOME
expo`

[![Virtual-Box-ubunto-6.png](https://i.postimg.cc/sx8rHNBY/Virtual-Box-ubunto-6.png)](https://postimg.cc/JHbvGK50)rt PATH 
