Inicio Costeo
Definir nombreProducto como string;
Definir costoBase, porcentajeGanancia,valor,subTotal,impuesto,precioFinal como decimal;
Definir const IVA= 19 como decimal;
//Entrada
Escribir "Ingresa el nombre del producto";
Leer nombreProducto   
Escribir "Ingresa el costo base";
Leer costoBase 
Escribir "Ingresa el porcentaje de ganancia esperado";
Leer porcentajeGanancia; 
//Proceso
valor = (costoBase*porcentajeGanancia)/100
subTotal = costoBase + valor
impuesto = (subTotal*IVA)/100
precioFinal = subTotal + impuesto
//Salida
Escribir "El valor monetario de la ganancia es:" + valor;
Escribir "El subtotal del producto es:" + subTotal;
Escribir "El impuesto del iva es:" + impuesto;
Escribir "El precio final del producto es:" + precioFinal;
Fin Costeo