# Variables
#  Primer Punto de Python#
print("Digite tres numeros para multiplcar")
a = int(input())
b = int(input())
c = int(input())
resultado = a*b*c
print("El resultado de la multiplicacion es :",resultado)

#Segundo Punto de Pytho+n#

print("Digite un numero para sacar su cuadrado ->")
cuadratica= int(input())
resultado2 = cuadratica*cuadratica
print("El resultado de la cuadratica es:",resultado2)

#Tercer punto de Python#
print("Calculo para hallar la distancia recorrida en un movimiento rectilineo")
print("Coloque la velocidad en km/h")
velocidad=int(input())
print("Coloque la cantidad de horas")
horas=int(input())
resultado3= velocidad*horas
print("La distancia recorrida ", resultado3,"Km")

#Cuarto punto de Python#
print("Digite el año de nacimiento")
nacimiento= int(input())
print("Digite el año actual")
actualidad= int(input())
resultado4= actualidad-nacimiento
print("Su edad actual es :",resultado4)

#Quinto y sexto Punto de Python#
print("Digite el numero porcentaje del 1%, al 100% que quiere calcular de un numero")
numeroporcentaje= int(input())
print("Digite el numero para sacarle el ",numeroporcentaje,"%")
numeroparasacarporcentaje= int(input())
resultado5= numeroporcentaje*numeroparasacarporcentaje/100
print("El ",numeroporcentaje,"%, del numero ",numeroparasacarporcentaje,"Es,",resultado5)

#Septimo Punto de Python#

print("Digite el lado del cuadrado para sacarle el area")
area= int(input())
resultado6=area*area
print("El area del cuadrado es :",resultado6,"cm2")


#Octavo punto de Python#
print("Digite 5 numeros para hallar el primedio")
uno=int(input())
dos=int(input())
tres=int(input())
cuatro=int(input())
quinto=int(input())
resultado7=uno+dos+tres+cuatro+quinto
resultado8=resultado7/5
print("El promedio de los 5 numeros es :",resultado8)

#Noveno punto de Python#
print("Digite la cantidad del producto")
producto=int(input())
print("Digite la cantidad de veces que quiere comprarlo")
cantidad=int(input())
resultadoproducto= producto*16/100
resultadoproducto2= producto*cantidad
sumadetodo=resultadoproducto+resultadoproducto2
print("El total de la cantidad de su compra es :",sumadetodo)
print("Suma del IVA del 16%",resultadoproducto)
 
 #Decimo Punto de python#
  
print("Digite el salario que obtiene por dia")
salariodiario=int(input())
print("Digite el numero de dias que trabajo")
dias=int(input())
sueldosindescuento= salariodiario*dias
descuentosalario=sueldosindescuento*25/100
print("Su sueldo sin el descuento de pencion y salud es :",sueldosindescuento)
print("Su sueldo con descuento :",descuentosalario)


#Onceavo Punto Python#
print("Digite el numero al cual le quiere sacar la raiz")
raiz=int(input())
resultado9= pow(raiz,1/2)
print("La raiz es :",resultado9)

#Doceavo Punto Python#
print("Digite un cateto del triangulo ")
cateto1=int(input())
print("Digite el segundo cateto del triangulo")
cateto2=int(input())
resultado10=cateto1*cateto1+cateto2*cateto2
print("La hipotenua es :",resultado10)

#Treceavo Punto de Python#

print("Digite el numero de km que quiere transformar a Cm")
kilometros=int(input())
centimetros=100000
resultado11=kilometros*centimetros
print("Los ",kilometros,"Convertidos a cm son ", resultado11)

#Cartoseavo Punto de Python#
print("Digite la cantidad de Segundos que quiere convertir a minutos y horas")
segundos=int(input())
minuto=60
Hora=3600
resultado12=segundos/Hora
resultado13=segundos/minuto
print("Minutos :",resultado13,"Hora :",resultado12)
