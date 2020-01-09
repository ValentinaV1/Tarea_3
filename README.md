# Tarea_3

**Valentina Vega Farias.

#EJERCICIO 1# 

Al reemplazar un 5 por un cero no arrojará ningun valor.

Al poner poner un numero mayor a la cantidad de elementos que hay en la lista r me entrega "NULL".

Al poner poner un numero negativo, eliminará el elementos en la lista. Por ejemplo poner -5, retirará el elemento de la posición 5


#EJERICICIO 2# 

La diferencia entre usar o no unlist es que elimina el formato lista, solo me entrega el numero y no la posicion donde se encuentra ni el largo.


#EJERCICIO 3# 

Lo que ocurre es que reemplaza el numero que se encuentra en posicion asignada en este caso se cambio el 1 por el 12.


#EJERCICIO 4# 

Lenght me entrega el largo de la lista. 


#EJERCICIO 5# 

Si el valor inical y final me arroja valores desde 5 hasta el 20 y al cambiar o al invetir el final con el inicial me entrega valores desde 20 al 5.

Al usar length entregara la cantidad de elementos:leght(listadenumeros) lo que hace es entregar numero desde el valor final (que es un numero hasta el (lenght que es otro numero ) en este caso me entrega valores de 20 al 11. 


#EJERCICIO 6# 

Genera un elemento llamado "i" que va desde el 1 al 100 misisipi


#EJERCICIO 7# 

En este caso donde los elementos que tenia en la lista de numeros se le asigno a la definicion de la variable i y se cambiaron los numeros de acuerdo a la lista, por lo que ahora los numeros corresponden a los de la "lista de numero" y no a los que eran del 1 al 100.


#EJERCICIO 8# 

Las condiciontes permite entregar la cualidad de los numeros (par e impar) 2"Par",5"impar",6"Par",2"Par",1"impar",5"impar",6"Par",10"Par",11"impar",20"Par",15"impar"


#EJERCICIO 9#

Al realizar un plebiscito con las siguientes caractertisticas: 

plebiscito<-200 votos_no<-20 votos_si<-60 quorum<-(plebiscito0.5)+1 total_votos<-votos_no+votos_si if((total_votos<quorum)&(votos_si>=0.3plebiscito)) {print("EL SI GANA") } else if((total_votos<quorum)&(votos_no>=0.3plebiscito)) {print("EL NO GANA") } else if((total_votos<quorum)&((votos_no<0.3plebiscito)&(votos_si<0.3*plebiscito))) {print("EL NO GANA") } else if(total_votos>quorum&&votos_no<votos_si) {print("EL SI GANA") } else if(total_votos>quorumvotos_no>votos_si) { Print("EL NO GANA")} else if (total_votos>quorumvotos_no==votos_si) {print("EL SI GANA") } else {"OTRO"}

En este caso se cumple que gano el"SI" ya que tiene una votacion mayor o igual al 30%.


#EJERCICIO 10# 

Al realizar las diferentes funciones esta arroja los siguentes resultados. suma=15, resta=-3, multiplicacion=54, y la division=0,66


#EJERCICIO 11#

Al asignar valores y crear una funcion donde se asigna primero las variables y sus respectivos valores tanto para los 2 rectangulos como para ambos circulos y puedo con sus formular correspondientes a las areas solo las ejecute

Datos: X=lado del rectangulo grande, Y=lado del rectangulo grande,

#x=lado del rectangulo pequeño, y=lado del rectangulo pequeño Diferencia_de_areas_figura_1<-function(X,Y,x,y){(XY)-(xy)} Diferencia_de_areas_figura_1(100,50,20,10) [1] 4800

Datos: Rad=Radio de ciruclo grande,Rad2=Radio de ciruclo pequeño

Diferencia_de_areas_figura_2<-function(Rad,Rad2,pi){(piRad^2)-(piRad2^2)} Diferencia_de_areas_figura_2(100,50,3.14) [1] 23550

#EJERCICIO OPCIONAL#

El loop "for" lo ultilizamos cuando conocemos la iteracion que vamos a ocupar, por lo cual llevamos un orden con los parentesis, llave, corchetes. el loop en una lista o un rango nos facilita recabar solo lo que necesitamos, ayuda a llevar un orden al trabajar con rangos y listas.