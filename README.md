# readme
describe como se hizo el código en python
primero pues puse las variables y las pedí por teclado,también lo que hice fue las operaciobes básicas y luego las imprimí
para lo de la base de datos ,sólo utilice join,los primeros dos sí me salieron  el útimo ya no pude saber por qué salió mal,no se me complicaron ya que así creo es como lo básico a excepción del último.
"""Crear un programa que sea capaz de calcular 
el resultado de operaciones matemáticas como suma,
 resta, multiplicación, división respetando la precedencia de operadores.
La entrada del programa será una cadena, por ejemplo: **2+5*10**
El resultado esperado sería **52**"""
x=int(input("Primer valor "))
y=int(input("Segundo valor "))
z=int(input("Tercer valor "))

suma=x+y
resta=x-y
multiplicacion=x*y
division=x/y
cal_suma_multiplicacion=x+(y*z)
cal_resta_multiplicacion=x-(y*z)
cal_suma_division=x+(y/z)
cal_resta_division=x-(y/z)

print("el valor  de la suma es : ",suma)
print("el valor de la resta es : ",resta)
print("el valor de la multiplicación es : ",multiplicacion)
print("el valor de la división es : ",division)
print("el valor de la suma con multiplicación es : ",cal_suma_multiplicacion)
print("el valor de la resta con multiplicación es : ",cal_resta_multiplicacion)
print("el valor de la suma con división es : ",cal_suma_division)
print("el valor de la resta con multiplicación es : ",cal_resta_division)
