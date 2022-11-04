# Describir la administración de costes en Azure

## 8.1 Introducción

- Describir factores que afectan a los costes en Azure
- Comparar el calculador de precios con el _Total Cost of Ownership_ (TCP)
- Describir la herramienta _Azure Cost Management_
- Describir el propósito de las etiquetas.

## 8.2 Describir factores que afectan a los costes en Azure

¿Cuanto cuesta Azure?, pues depende de cuanto le pidas. Usando TCO puedes entender cuanto sería poner en la nube tu servidor in situ, y el _pricing calculator_ para poder ver que soluciones hay para tu presupuesto actual. Además Azure Advisor te permite visualizar tu coste actual.

Los coste de azure aparecen del mantenimiento de las infraestructuras y el alquilar estas a los usuarios, siendo asi la suma de _capital expense_ (CapEx) y _operational expense_ (OpEx) respectivamente.

### Tipo de recursos

Hay numerosos factores que influyen al coste de recursos Azure.  Como el tipo de recurso, la configuración o la región Azure, además del uso que tiene ese recurso.

>Hay un ejemplo en la página sobre el tamaño de un blob, pero no es de interés para los resúmenes

### Consumo

_Pay-as-you-go_ o paga por lo que usas, es el modelo de pago por tu factura. Si usas más este mes pues te cobran mas, si usas menos pues te cobran menos. Sin embargo se pueden pre-reservar esos recursos para recibir descuento. 

### Mantenimeinto

La flexibilidad de la nube permite ajustar recursos rapidamente, por ello es importante mantenerlos organizados y mantener tu entorno de nube. Por ejemplo si una MV no se vigila puede consumer más recursos de manera no intencional. 

### Geografía

Los recursos Azure requieren que se defina en que región desplegarlos, aunque la infraestructura Azure es global desplegar en zonas donde los costes son mayores puede incrementar el precio de mantener dichos recursos.

### Trafico de red

El ancho de banda (entrada y salida de datos), la trasferencia de datos es gratis, la salida depende de la zona. 

### Tipo de subscripción

Niveles de pagar cosas 

### Azure Marketplace

Es la tienda para comprar soluciones Azure y servicios de terceros, se paga por el servicio del tercero y por los servicios Azure para mantenerlo.

## 8.3 Comparar las calculadoras _Pricing and Total Cost Ownership_

### _Pricing calculator_

El coste que te da sobres los recursos Azure, construir una solución o un ejemplo de escenario es un coste estimado y no real ya que es una herramienta informativa.

### _TCO calculator_

Sirve para comprovar costes de una infraestructura in situ comparada con la infraestructura de Azure Cloud, calcula el cambio y los costes asociados a ello.

## 8.4 Ejericio Pricing

> Simplemente seguirlo y ver el precio

## 8.5 Ejercicio TCO

> Simplemente seguirlo y ver el precio

## 8.6 Describir las herramientas de gestios de coste de Azure

Gestionar los recursos no usados para liberarlos y no encontrar costes no deseados.

### ¿Que es gestion de costes?

La gestion de coste provee la habilidad de rápidamente comprobar los costes de los recursos Azure, crear alertas de gastos y generar presupuestos. Con _Cost analisys_ puedes ver una vista global rápida.

### Alerta de costes

Pueden ser de:

- **Presupuesto:** 