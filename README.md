# MICROTIENDA CON MICROSERVICIOS (Microservices Shop)
Este ejercicio muestra a grandes rasgos la implemetación de una arquitectura de microservicios de una tienda pequeña, que dispone de:

* Gestión de inventarios
* Gestion de clientes

como microservicios. 

Para poner en funcionamiento esta implementación siga las siguientes instrucciones:

1. Considere la instalación de docker y nginx.
2. Ubiquese sobre la carpeta donde clono o descargo la información del repositorio y abra el cmd. Escriba "docker-compose up"
3. Dirijase a un navegador y consulte la información mediante http://localhost:8080/clientes y http://localhost:8080/inventario
4. Verá la  información de Gestión de inventarios y Gestión de clientes

Esta implementación tuvo un procedimiento previo que consideró el diseño de la arquitectura de la aplicación, que seexplicará a continuación.

# MODELADO DE ARQUITECTURA

Se subraya que "El diseño crea una representación o modelo del software, pero, a diferencia del modelo de los requerimientos (que se centra en describir los datos que se
necesitan, la función y el comportamiento),** el modelo de diseño proporciona detalles sobre arquitectura del software, estructuras de datos, interfaces y componentes que
se necesitan para implementar el sistema."**

Según esto se ha realizado un trabajo de arquitectura de software en el que según la comprensión del negocio, infraestructura y funcionamiento se generaron las siguientes vistas:

## Vista de Organización

## Vista de Uso de infraestructura

## Vista de capas

![Diagrama Clases-JuegoComeCirculos](imagenes/DiagramaClasesJuegoPython-DiagramaFinal.png)



## Explicación general del Código que se presenta
Para el desarrollo de la implementación se usa python, nginx, flask y docker como contenedor. De esta forma encontramos la siguiente información: 
```
//Created Stage
var stageFrame = new Stage('canvas', 600, 400);
//Created Game
var  game1 = new Game(stageFrame);
game1.menu();
stageFrame.context.canvas.focus();

```
