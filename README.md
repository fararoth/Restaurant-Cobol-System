# Restaurant-Cobol-System

Este es un programa para el Trabajo Práctico de la materia Procesamiento de Datos (330) en el lapso 2023-1

Estudiante Luis Farias

Uso exclusivo académico

## Especificaciones

Un nuevo restaurant está a punto de ser inaugurado. En este 
momento se le está dando los últimos toques para su apertura. El 
gerente a cargo del proyecto, se ha planteado la necesidad de un 
sistema automatizado, para llevar el servicio de pedido del cliente
dentro del local.
Para satisfacer los requerimientos propuestos por el gerente, el 
software debe contar con las siguientes prestancias:

* Carta del restaurante: Datos correspondientes a los diferentes tipos de platillos:
  * Código
  * Desayunos
  * Entradas
  * Ensaladas
  * Contornos
  * Carnes
  * Pescados y Mariscos
  * Bebidas
  
* Platillos por tipos: Datos sobre cada plato por tipo
  * Código del platillo
  * Descripción del platillo 
* Meseros: Datos sobre los meseros que atienden. 
  * Nombre y Apellido
  * Cédula
* Mesas enumeradas: Datos sobre las mesas
  * No. Mesa
  * Mesero Asignado
  * Cantidad de Mesas

* Pedidos: Datos de los pedidos realizados durante el día.
  * Nº de pedido pre impreso en talonario 
  * Nº de mesa
  * Nº de cédula del mesero
  * Descripción del pedido
  * Cantidad
  * Precio Unitario
  * Tipo de pago
  * Importe
  * Propina
  * Enviado (s/n)
  
El programa debe permitir realizar lo siguiente:
* Registro y modificación de datos de
  * Meseros
  * Pedidos
  * Platillos
  * Mesas
* Las siguientes consultas:
  * Platillos disponibles
  * Pedidos realizados por fecha
  * Meseros con pedidos por Nº de Pedido
  * Meseros ausentes
  
### ESPECIFICACIONES GENERALES PARA LA IMPLEMENTACIÓN:

El programa a realizar debe presentar un Menú con las opciones, descritas a continuación.

1) Carta del restaurante: Esta opción permite ingresar o modificar los datos de los tipos de platillos que se encuentran en la carta. La clave es el código asignado por tipo.

2) Platillos por tipos: Esta opción permite ingresar o modificar los datos de los diferentes platillos que conforman los tipos. La clave de acceso de cada platillo es el código asignado.

3) Registro de Meseros: Esta opción permite ingresar o modificar los datos de los meseros. La clave de acceso será la cédula de cada mesero.

4) Registro de Mesas enumeradas: Esta opción permite ingresar o modificar los datos de las mesas que conforman el comedor. Su clave será el Nº de mesa.

5) Registro de Pedidos: Esta opción permite ingresar, modificar o eliminar un pedido. Su clave será el No. de pedido.

Consultas: El programa permitirá realizar las siguientes consultas: 
* Platillos por tipos.
* Meseros ausentes o retirados por fecha
* Mesas atendidas por mesero y fecha
* Pedidos enviados y/o anulados por fecha
* Importe por pedidos y total por fecha

Para la implementación se deberán diseñar los archivos para almacenar los datos de:

* CARTA DEL RESTAURANTE
* PLATILLOS POR TIPOS
* MESEROS
* MESAS
* PEDIDOS

El programa deberá controlar la integridad de los datos, realizando validaciones como:
* No permitirá registrar el mismo pedido por dos meseros diferentes.
* No permitirá que una mesa sea atendida por un mesero diferente al asignado. Sin embargo, en caso de su ausencia deberá la gerencia tener la opción de reasignar la mesa. (Validación especial).

