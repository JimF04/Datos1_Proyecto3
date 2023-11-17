# Datos1_Proyecto3
Proyecto 3 de Algoritmos y Estructuras de Datos I

App:
https://github.com/JimF04/NotUber

Server:
https://github.com/JimF04/NotUberServer

**Descripción del problema**

Una empresa ha decidido implementar un sistema para contribuir con la solución del problema de
disponibilidad de espacios de parqueo en su sede central. Para esto ha iniciado un proyecto que
consiste en una aplicación mobile que tiene por fin motivar el Carpooling entre sus empleados y
disminuir la cantidad de vehículos en el recinto.
Esta aplicación debe permitir que los empleados que cuentan con un vehículo para trasladarse a la
empresa indiquen si cuentan con espacios disponibles y que los empleados que requieren transporte
registren su requerimiento. Con base en esta información, el sistema debe seleccionar dos opciones:

1. la aplicación determina cuales empleados estarán en la ruta para que el empleado-conductor
los pueda recoger

3. el conductor selecciona los pasajeros que trasladará con base en la información que tiene
registrada. El sistema calcula la mejor ruta para pasar por los empleados y llegar a la empresa.
Como parte del proyecto la empresa ha solicitado la implementación de un prototipo que simule el
funcionamiento de la aplicación. Lo anterior tiene por fin validar con los empleados aspectos de
usabilidad de la versión final del producto.
Este prototipo estará compuesto por los siguientes elementos:

➔ EmployeeApp: Aplicación mobile para uso de los empleados sin vehículo.

➔ DriverApp: Aplicación mobile que usan los empleados que tienen vehículos.

➔ CarpoolingServer: Encargado de gestionar toda la lógica del sistema.

La comunicación entre los elementos anteriores debe ser utilizando archivos JSON y toda información
que sea almacenada debe ser utilizando archivos XML.

**Estrucutras de datos desarrollados**

-Queue:
Un Queue o cola, es una estructura de datos que sigue  la filosofia FIFO (First in First Out), esto quiere decir que el elemento que ingresa primero a la cola sera el primero que salga, y el ultimo que entre sera el ultimo en salir

-Priority Queue: La cola de prioridad es una variante de la cola basica, en la que los elementos en la cola se organizan y se ordenan basado en su valor, por ejemplo, si son numeros, se ordenan de menor a mayor.

-Array Lists: La clase Array List en java, es una clase que permite almacenar los datos de manera similiar a los arrays, con la ventaja de que el numero de elementos que almacena, lo hace de forma dinamica, es decir, que no es necesario declarar su tamaño, como pasa con los arrays.

-Graphs: Los grafos son estructuras de datos, es decir de tipos de datos abstractos, comunmente los grafos son utilizados para el modelado de problemas, este consiste de un grupo de nodos, estos conectados entre si, o creando nuevas conexiones.


-HashMaps: Un Hashmap en Java es un mapeo de clave-valor, lo que significa que cada clave se asigna exactamente a un valor y que podemos usar clave para recuperar el valor correspondiente de un HashMap



**Algoritmos desarrollados**

-Dijkstra Algoritm: Es tambien denominado el algoritmo de caminos cortos, es un modelo que se clasifica dentro de los modelos de busqueda. Si objetivo es denominar la ruta mad corta desde el nodo de origen hasta cualquier nodo de la red. Su metodologia se basa en iteraciones, de manera de que en la practica, su desarollo se complica a medida de que el tamaño de la red aumenta.

-DFS Algoritm (Depth Firs Search): Este es un algoritmo recursivo que usa el principio de retroceso. Implica realizar búsquedas exhaustivas de todos los nodos, avanzando si es posible y retrocediendo si es necesario.



