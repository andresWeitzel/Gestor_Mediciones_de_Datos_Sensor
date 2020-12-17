# Gestor Mediciones de Datos Sensor.

**Se desarrolla una GUI en Java con Ant para la gestión de Mediciones de datos  de un Sensor de Temperatura y Humedad implementando la comunicación Serial con Arduino y aplicando JDBC en MYSQL.**
 
 </br>

| **Tecnologías** | **Versión** |               
| ------------- | ------------- |
| Java |   12.0.2 |
| Apache NetBeans IDE |  12.0 |
| Arduino IDE | 1.8.13  |
| XAMPP | 3.2.2  |
| Mysql Workbench | 8.0.20  |

</br>

| **Librerías JAVA** | **Finalidad** |               
| ------------- | ------------- |
| mysql-connector-java-8.0.21.jar |   Driver conexion db mysql |
| jcommon-1.0.23.jar |   Creacion de Gráficos |
| jcommon-xml-1.0.23.jar |  Creacion de Gráficos |
| jfreechart-1.0.19.jar | Creacion de Gráficos  |
| PanamaHitek_Arduino-2.8.2.jar | Conexion Serial con Arduino  |

(Todas las Librerías se encuentran en el repositorio principal de este proyecto y dentro de la carpeta Librerias)

</br>

| **Librerías ARDUINO** | **Finalidad** |               
| ------------- | ------------- |
| DHT-sensor-library-master.zip |  Gestion del sensor dht11  |

(Todas las Librerías se encuentran en el repositorio principal de este proyecto y dentro de la carpeta Librerias)

</br>

| **Hardware Requerido** | **Finalidad** |               
| ------------- | ------------- |
|  Placa Arduino Uno| Controlador   |
| Sensor DHT11 | Sensor de Temperatura y Humedad |
| Cable USB| Comunicacion Gui-Controlador |
| Cables Dupont Macho-Hembra| Conexión Controlador-Sensor|

(El tipo de sensor no es relevante, siempre y cuando se enfatize el puerto a usar, los pines de entrada, etc).


</br>

 
 ## Patrones de Diseño Implementados
 * **Singleton** 
 * **Dao** 
 
 ## Uso de Java8
* **Streams**
* **Lambdas**
* **Filters**
* **Collections**
* **Etc..**

</br>

## Descarga y documentacion del Software empleado:
#### Java-JDK 12:                     https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html
#### Apache Netbeans IDE:             https://netbeans.apache.org/download/index.html
#### Arduino IDE:                     https://www.arduino.cc/en/software
#### XAMPP                            https://www.apachefriends.org/download.html
#### Mysql Workbench                 https://www.mysql.com/products/workbench/



