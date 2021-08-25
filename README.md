# PostworkBeduBack
## 1.Definan en equipo cuál será la temática de su proyecto.

API para un punto de venta de una miscelánea

## 2.Definan los requerimientos del proyecto, así como su estructura, es decir, respondan las preguntas

* ¿Qué espero que haga el proyecto?

    * Se espera que la api pueda proporcionar endpoints para el registro, ventas y administración del inventario. 
* ¿Qué tipos de usuario tendrá nuestro sistema?
    * Administrador: Dueño del local 
      * Generar reportes 
      * Administración de inventario 
      * Contaduría 
      * Administracion de usuarios
    * Cajero:
      * Encargado de ventas
    * Gerente:
      * Administración de inventario
* ¿Qué acciones puede realizar cada usuario?
   * Administrador:
     * Generar reportes por periodos de ventas 
     * CRUD inventario 
     * CRUD usuarios
   * Gerente:
     * CRUD inventario
   * Cajero:
     * Realizar  y eliminar ventas 
     * Aperturar y cerrar cajas
* ¿Qué información se necesita? 
  * Cantidad de productos dentro del inventario, cantidad de productos vendidos y el costo total de estos.

* ¿Cuáles son las principales entidades? 
  * Admin, gerente, cajero, venta, producto

* ¿Qué características tiene cada entidad? 
  * Inventario: Nombre de producto, categoría, stock, código. 
  * Usuario: Nombre de usuario, Nombre, contraseña, Rol 
  * Venta: Productos, cantidad, subtotal, total
* ¿Qué funcionalidades tiene cada entidad? 
  * Inventario: CRUD, reportes 
  * Usuario: CRUD, iniciar sesión 
  * Venta: CRUD
* Utilicen historias de usuario para ayudarte a responder las preguntas del inciso anterior. 
  * Administrador:
    * Yo administrador, me gustaria poder generar reportes por periodos 
    * Yo administrador quiero tener control sobre mi inventario 
    * Yo administrador quiero administrar mis usuarios
  * Gerente:
    * Yo gerente quiero poder añadir, eliminar, actualizar el inventario.
  * Cajero:
    * Quiero poder generar una venta 
    * Quiero poder eliminar ventas

## 4. Definan en JavaScript las clases que representen cada entidad de su proyecto.
## 5. Crear un repositorio en Git de su proyecto, en donde se debe de subir todo el código.

