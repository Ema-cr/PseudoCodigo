<<<<<<< HEAD
Algoritmo Interés
Definir capital, tasa, tiempo, interes como real
Escribir "cual es tu capital inicial"
Leer capital
Escribir "cual es tu tasa de interés anual"
Leer tasa
Escribir " cuanto tiempo en años"
Leer tiempo
Interes = (capital*tasa*tiempo)/100
Escribir "el interes es de:" + Interes
FinAlgoritmo


Algoritmo ConversorMoneda
Definir Peso,TasaCambio,Comision,Dolares,Subtotal como real
Escribir "cuantos pesos deseas convertir"
Leer Peso
TasaCambio = 3100
Dolares = (Peso/TasaCambio)
Comision = (Dolares*2)/ 100
Subtotal = (Dolares-Comision)
Escribir "El valor es:" + Subtotal
Escribir "La comision fue de:" + comision
FinAlgoritmo


Algoritmo Nomina
Definir PagoSemanal, HorasTrabajadas, PagoxHora, DescuentoSyP, SalarioNeto como real
Escribir "cuantas horas trabajaste esta semana"
Leer HorasTrabajadas
Escribir "cuanto es el valor por hora trabajada"
Leer PagoxHora
PagoSemanal = (HorasTrabajadas*PagoxHora)
DescuentoSyP = (PagoSemanal*8)/100
SalarioNeto = (PagoSemanal-DescuentoSyP)
Escribir "El salario bruto es:", PagoSemanal
Escribir "El descuento es:", DescuentoSyP
Escribir "El salario neto es:", SalarioNeto
FinAlgoritmo


Algoritmo Combustible
Definir DistanciaTotal, Rendimiento, PrecioCombustible, Personas, LitrosNecesarios, CostoTotal, Monto como real
Escribir "cuantos kilometros dura el viaje" 
Leer DistanciaTotal
Escribir "cuantos litros de combustible usa tu auto por kilometro" 
Leer Rendimiento
Escribir "cuanto es el precio por litro de combustible"
Leer PrecioCombustible
Escribir "cuantas personas viajan en el vehiculo" 
Leer Personas
LitrosNecesarios = (DistanciaTotal/Rendimiento)
CostoTotal = (LitrosNecesarios*PrecioCombustible)
Monto = (CostoTotal/Personas)
Escribir "La cantidad de litros necesarios es:", LitrosNecesarios
Escribir "El costo total del combustible es:" , CostoTotal
Escribir "El monto total de cada pasajero es:", Monto
FinAlgoritmo


Algoritmo Pintura
Definir Ancho, Altura, Rendimiento, PrecioxLitro, AreaTotal, LitrosReq, CostoTotal como real
Escribir "cuantos metros de ancho es el muro?"
Leer Ancho
Escribir "cuantos metros de alto es el muro?"
Leer Altura
Escribir "cuantos metros cubre un litro de pintura?"
Leer Rendimiento
Escribir " cuanto es el precio de un litro de pintura?"
Leer PrecioxLitro
AreaTotal = (Ancho*Altura)
LitrosReq = AreaTotal/Rendimiento
CostoTotal = LitrosReq*PrecioxLitro
Escribir "El costo total de los materiales es:",CostoTotal
FinAlgoritmo

Algoritmo IMC
Definir NombrePaciente como string
Definir PesoActual, Estatura, PesoObjetivo, IMC, KiloSobra  como real
Escribir "Cual es tu nombre"
Leer NombrePaciente
Escribir "Cual es tu peso actual en kg"
Leer PesoActual
Escribir "Cual es tu estatura en metros"
Leer Estatura
Escribir "Cual es tu peso objetivo en kg"
Leer PesoObjetivo
IMC = PesoActual / (Estatura*Estatura)
KiloSobra = (PesoObjetivo - PesoActual)
Escribir "Peso Actual:", PesoActual
Escribir "Estatura Actual:", Estatura
Escribir "Peso objetivo:", PesoObjetivo
Escribir "Tu indice de masa corporal es:", IMC
Escribir "La diferencia de peso es:", KiloSobra
=======
Algoritmo Interés
Definir capital, tasa, tiempo, interes como real
Escribir "cual es tu capital inicial"
Leer capital
Escribir "cual es tu tasa de interés anual"
Leer tasa
Escribir " cuanto tiempo en años"
Leer tiempo
Interes = (capital*tasa*tiempo)/100
Escribir "el interes es de:" + Interes
FinAlgoritmo


Algoritmo ConversorMoneda
Definir Peso,TasaCambio,Comision,Dolares,Subtotal como real
Escribir "cuantos pesos deseas convertir"
Leer Peso
TasaCambio = 3100
Dolares = (Peso/TasaCambio)
Comision = (Dolares*2)/ 100
Subtotal = (Dolares-Comision)
Escribir "El valor es:" + Subtotal
Escribir "La comision fue de:" + comision
FinAlgoritmo


Algoritmo Nomina
Definir PagoSemanal, HorasTrabajadas, PagoxHora, DescuentoSyP, SalarioNeto como real
Escribir "cuantas horas trabajaste esta semana"
Leer HorasTrabajadas
Escribir "cuanto es el valor por hora trabajada"
Leer PagoxHora
PagoSemanal = (HorasTrabajadas*PagoxHora)
DescuentoSyP = (PagoSemanal*8)/100
SalarioNeto = (PagoSemanal-DescuentoSyP)
Escribir "El salario bruto es:", PagoSemanal
Escribir "El descuento es:", DescuentoSyP
Escribir "El salario neto es:", SalarioNeto
FinAlgoritmo


Algoritmo Combustible
Definir DistanciaTotal, Rendimiento, PrecioCombustible, Personas, LitrosNecesarios, CostoTotal, Monto como real
Escribir "cuantos kilometros dura el viaje" 
Leer DistanciaTotal
Escribir "cuantos litros de combustible usa tu auto por kilometro" 
Leer Rendimiento
Escribir "cuanto es el precio por litro de combustible"
Leer PrecioCombustible
Escribir "cuantas personas viajan en el vehiculo" 
Leer Personas
LitrosNecesarios = (DistanciaTotal/Rendimiento)
CostoTotal = (LitrosNecesarios*PrecioCombustible)
Monto = (CostoTotal/Personas)
Escribir "La cantidad de litros necesarios es:", LitrosNecesarios
Escribir "El costo total del combustible es:" , CostoTotal
Escribir "El monto total de cada pasajero es:", Monto
FinAlgoritmo


Algoritmo Pintura
Definir Ancho, Altura, Rendimiento, PrecioxLitro, AreaTotal, LitrosReq, CostoTotal como real
Escribir "cuantos metros de ancho es el muro?"
Leer Ancho
Escribir "cuantos metros de alto es el muro?"
Leer Altura
Escribir "cuantos metros cubre un litro de pintura?"
Leer Rendimiento
Escribir " cuanto es el precio de un litro de pintura?"
Leer PrecioxLitro
AreaTotal = (Ancho*Altura)
LitrosReq = AreaTotal/Rendimiento
CostoTotal = LitrosReq*PrecioxLitro
Escribir "El costo total de los materiales es:",CostoTotal
FinAlgoritmo

Algoritmo IMC
Definir NombrePaciente como string
Definir PesoActual, Estatura, PesoObjetivo, IMC, KiloSobra  como real
Escribir "Cual es tu nombre"
Leer NombrePaciente
Escribir "Cual es tu peso actual en kg"
Leer PesoActual
Escribir "Cual es tu estatura en metros"
Leer Estatura
Escribir "Cual es tu peso objetivo en kg"
Leer PesoObjetivo
IMC = PesoActual / (Estatura*Estatura)
KiloSobra = (PesoObjetivo - PesoActual)
Escribir "Peso Actual:", PesoActual
Escribir "Estatura Actual:", Estatura
Escribir "Peso objetivo:", PesoObjetivo
Escribir "Tu indice de masa corporal es:", IMC
Escribir "La diferencia de peso es:", KiloSobra
>>>>>>> c2c3f361c8eb1b1a0f46fae38536180356b55c54
FinAlgoritmo