# Conmutacion
Proyecto


Nuestra aplicación es para la configuración de una red Mpls del proveedor Telconet en la ciudad de Quito y Guayaquil

REQUISITOS

•	Tener Instalado jdk 1.8 de java para el ejecutable
•	Tener permisos de administrador para la red 
•	Conectarse a la vlan y switch adecuado 
•	Tener conocimiento de la topología física y lógica de la red 

RED A CONTROLAR LA APLICACIÓN 
 
INTERFAZ DEL USUARIO
 
Nuestra interfaz consta de 4 partes importantes para realizar la acción debemos presionar el botón ejecutar 
1.	Crear Vrf 
En la parte de crear una Vrf debemos tener en consideración los usuarios en una matriz en la ciudad de Quito y Guayaquil por eso es necesario considerar las siguientes validaciones 
•	No exista el cliente en la Ciudad a Crear
 
•	No exista cliente para la vlan seleccionada
 
•	La vlan seleccionada debe ser un número adecuado
 
•	Debe ingresar todos los parámetros 
 
Si todos los parámetros cumplen con las validaciones la vlan se creara con éxito, y nos mostrara la configuración realizada en el router 
 
2.	Eliminar Vrf
Al eliminar una Vrf debemos validar lo siguiente 
•	Exista el cliente en la Ciudad a Eliminar

•	La vlan seleccionada debe ser un número adecuado
 
•	Debe ingresar todos los parámetros 
 
Si todos los parámetros cumplen con las validaciones la vlan se eliminara con éxito, y nos mostrara la configuración realizada en el router 
 
3.	Conectividad 
Probamos conectividad entre dos PC clientes 
4.	Observar red 
Al presionar el botón presionar red, nos muestra la topología de la red actual de nuestra estructura mpls en una pagina web

RECOMENDACIONES
Leer detalladamente el manual del usuario y observar cómo está compuesta nuestra red 

