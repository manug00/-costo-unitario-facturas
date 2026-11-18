# Costo unitario por factura

Página para calcular el costo unitario de cada artículo de una factura de compra:

- Reparte el **descuento general** y el **recargo** según el importe de cada artículo.
- Reparte el **flete** por importe o por kilos.
- Las **bolsas sin cargo** (renglones con 100 % de descuento) se cargan al costo de las pagas del mismo código.
- Las **facturas en dólares** se pesifican al tipo de cambio de la factura, incluido el total con IVA y percepciones.
- No tiene en cuenta los pallets ni los impuestos.

Lee los PDF de ACA (pesos) y de Molino Cañuelas (dólares). Cualquier otra factura se puede cargar a mano.
Todo se calcula en el navegador: la factura no se sube a ningún lado.

**Excel:** el botón "Bajar en Excel" arma una planilla con la factura cargada y todas las fórmulas.
`plantilla.xlsx` es la planilla vacía, para cargar las facturas directamente en Excel.
