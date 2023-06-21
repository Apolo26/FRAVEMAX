# ![App Screenshot](https://i.ibb.co/42s4GFD/Sin-t-tulo-6.png)




## GUÍA DE USO SOFTWARE FRAVEMAX

![App Screenshot](https://i.ibb.co/Xb3zv20/1.png)

![App Screenshot](https://i.ibb.co/pPpjz6Q/2-2.png)



BOTON CLIENTE: 

>El boton **BUSCAR** sirve para buscar un cliente en la base de datos ingresando un ID (se puede ver el listado de los clientes existentes en la tabla debajo de los botones agregar, editar y eliminar).

>El boton **AGREGAR** sirve para agregar un cliente a la base de datos (llenar los campos de nombre, apellido, direccion y telefono)

>Para **EDITAR** un cliente, se debe buscar el cliente en la base de datos. luego modificar alguno de los campos mostrados y apretar en el boton editar (se activa un mensaje de confirmacion preguntando si quiere editarlo).

>El boton **LIMPIAR** sirve para limpiar los campos escritos.

>Para **ELIMINAR** un cliente. Se debe buscar el ID del cliente en la base de datos, luego apretar en el boton eliminar (se activa un mensaje de alerta preguntando si quiere eliminar el cliente)

![App Screenshot](https://i.ibb.co/CQrzRrT/2.png)

## 

BOTON PROVEEDORES :

> Para **AGREGAR** un proveedor a la base de datos se debe hacer lo siguiente: 

* Ingresar la razón social
* Ingresar el domicilio
* Ingresar el telefono

Luego presionar **AGREGAR**.

####

>  Para **EDITAR** un proveedor, se debera hacer lo siguiente: 
* ingresar el ID del proveedor en el campo con el mismo nombre.

luego apretar en el boton *BUSCAR* (se puede ver el listado de los proveedores existentes en la tabla debajo de los botones agregar, editar y eliminar). Se mostraran los datos en los campos de texto para su modificacion, luego apretar el boton **EDITAR** para efectuar los cambios realizados.

####

> Para **ELIMINAR** un proveedor. se deberá buscar el ID perteneciente al proveedor y luego apretar en el boton **ELIMINAR** (se activa un mensaje de alerta preguntando si quiere eliminar el proveedor).

####

![App Screenshot](https://i.ibb.co/pXk0fq1/3.png)

##

BOTON INVENTARIO : 

> Se mostrará el inventario de la empresa mediante una tabla con los datos *NOMBRE* - *DESCRIPCION* - *PRECIO* - *STOCK* y *ESTADO*.

> Para **EDITAR** un producto se deberá buscar el ID del producto según aparezca en la lista y apretar en el boton *OK*. Luego editar en cualquiera de los campos y hacer click en el boton *GUARDAR CAMBIOS*

> Para **ELIMINAR** un producto se deberá buscar el id del producto y si este no está asociado a una venta se podrá elimnar, caso contrario se mostrará un mensaje de alerta diciendo que se no se puede eliminar porque está asociado a una venta.

![App Screenshot](https://i.ibb.co/syxrxKw/8.png)

##

BOTON COMPRA :

Al iniciar se mostrará una interfaz de compras hacia el proveedor, para realizar una compra se deben seguir los siguientes pasos:

![App Screenshot](https://i.ibb.co/5kqSNdG/4.png)

* Buscar un ID de un proveedor en la base de datos (Se podrán visualizar en la tabla superior derecha).

Seccion Detalle De Compra : 

* Se deberá colocar : *NOMBRE DEL PRODUCTO* - *CANTIDAD* - *PRECIO COSTO* - *DESCRIPCION DEL PRODUCTO* y *FECHA DE COMPRA*


Una vez cargado todos los datos de la compra que quiere realizar se debe apretar en el boton **COMPRAR** y luego **GUARDAR DETALLES**. 

A esto se le asignara un ID de Compra y un ID de Producto automaticamente (Se podrá visualizar en la tabla inferior derecha).

Hecho estos pasos se quedará la compra registrada en la base de datos y se podrá visualizar en la seccion **HISTORIAL DE COMPRAS** donde se tendrá que seleccionar el proveedor al que le hizo la compra y automaticamente saldrá en la tabla la compra realizada.


![App Screenshot](https://i.ibb.co/k34Yr8P/5.png)

## 

BOTON VENTA : 

Al iniciar se mostrará una interfaz de ventas hacia un cliente, para realizar una venta se deben seguir los siguientes pasos:

![App Screenshot](https://i.ibb.co/8XzKBLC/6.png)

* Buscar un ID de un cliente en la base de datos (Se podrán visualizar en la tabla superior derecha).

* Agregar la fecha de compra

Luego en *DETALLE DE VENTA* se le pide un ID del producto pedido del cliente (Se podrán visualizar los productos con sus ID en la tabla a su derecha).

* Agregar una cantidad (En caso de no tener stock se mostrará un mensaje)

Una vez cargado todos los datos de la venta que quiere realizar se debe apretar en el boton **VENDER** y luego **GUARDAR DETALLES DE VENTA**. 

Hecho estos pasos se quedará la venta registrada en la base de datos y se podrá visualizar en la seccion **HISTORIAL DE VENTAS** donde se tendrá que seleccionar el cliente al que se le adjudico la venta y automaticamente saldrá en la tabla la compra realizada por el cliente.

![App Screenshot](https://i.ibb.co/bdzwvVF/7.png)
## FRAVEMAX - cerca tuyo, nunca.
(Porque no existimos 😶‍🌫️)


![App Screenshot](https://i.ibb.co/2KbYSkR/mockup-1.jpg)

![App Screenshot](https://i.ibb.co/Y3tW1Vz/mockup-2.jpg)

![App Screenshot](https://i.ibb.co/XW1Px0Y/facebook-post-mockup.png")

## PROYECTO REALIZADO EN JAVA y MySQL


Integrantes : 

* Muñoz Hugo Emiliano
* Carlos Ezequiel Lucero
* Francisco Agustin Malbec
