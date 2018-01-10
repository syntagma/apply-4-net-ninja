# Apply for .NET Ninja in Syntagma Team

Pre-requisites
------------------------------------

- Git (used to clone this project)
- Visual Studio 2015
- NET Framework v4.5.2
- MVC 5.2

Instructions
------------------------------------

1. (Github) Fork this project (https://github.com/syntagma/apply-4-net-ninja/) with your Github's account.
2. Open the solution file with Visual Studio 2017 or greater.

Test
------------------------------------

#### Introducción:
Solucion 'ninja' es una aplicación que permite generar, modificar y eliminar facturas

#### Pasos

###### Proyecto ninja.test

1. Escribir el código necesario para que la prueba 'DeleteInvoice' ejecute correctamente
2. Escribir el código necesario para que la prueba 'UpdateInvoiceDetail' ejecute correctamente
3. Solucionar el bug para que la prueba 'CalculateInvoiceTotalPriceWithTaxes' ejecute correctamente

###### Proyecto ninja.web
1. Crear la controller 'InvoiceController.cs' con las siguientes acciones
	* Index
	* Detail
	* New
	* Update
	* Delete
	
2. Crear las 4 vistas que respondan a las 4 acciones creadas en el punto anterior
	* Index - Lista todas las facturas en una grilla
	* Detail - Lista el detalle de una factura especifica
	* New - Da de alta una factura, a esta opción se accede desde Index
	* Update - Modifica una factura, a esta opción se accede desde Index
	* Delete - Elimina una factura, a esta opción se accede desde Index
	
###### Si la clase InvoiceManager no provee alguna funcionalidad solicitada, crearla
