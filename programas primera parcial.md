print("hola ICI ")
print("hola")
x = 10
print(x)
y = 10

# interpolacion de cadenas
name ="Alfredo"
edad= 25
print("hola",name,"tienes",edad,"años")

#fstrings
mensaje = f"hola {name}, tienes {edad} años"
mensaje

print (mensaje)

print(f"hola {name}, tienes {edad} años")

def saludo():
    print("hola mundo!!!")
saludo() #invocando la funcion
mi_funcion= saludo() #asignando la funcion
print(mi_funcion)

def saludo2():
    return "hola mundo!!!"
saludo2() #invocacion
mi_funcion2 = saludo2() #asignacion
print (mi_funcion2)

a= 5
b= 10
res= f"la suma de {a} + {b} ={a+b}"
print(res)
def suma (a,b):
    return a+b
res= f"la suma de {a}+{b}= {suma (a,b)}"
print(res)

 def Saludo_edad(nombre:str, Año_nacimiento:int):
     edad= 2022-Año_nacimiento
     print("hola",nombre, "tienes ", edad, "años")

if __name__=="__main__":
     Saludo("Buenos Dias", "Alfredo")
     Saludo_edad("Alfredo", 1997)

import utilerias as util

if  __name__ == "__main__":
    util.saludo("cualquier mensaje.py")
    
def suma(n1:int, n2:int)-> int: return n1+n2
def resta(n1: int, n2: int) -> float: return n1-n2
def multiplicaion(n1: int, n2: int) -> int:return n1*n2
def division(n1: int, n2: int) -> float: return n1/n2
def cuadrado(n1: int) -> int: return n1*n1

if __name__ == "__main__":
    print(suma(7,6))
    print(resta(5,9))
    print(multiplicaion(5,9))
    print(division(5,9))
    print(cuadrado(3))
    
def suma(n1:int, n2:int)-> int:
    return n1+n2 
    
    if __name__=="__main__":
    print(suma(7,6))
 def resta(n1: int, n2: int) -> float:
    return n1-n2

if __name__ == "__main__":
    print(resta(5,9))
def multiplicaion(n1: int, n2: int) -> int:
    return n1*n2

if __name__ == "__main__":
    print(multiplicaion(5,9))
def division(n1: int, n2: int) -> float:
    return n1/n2

if __name__ == "__main":
    print(division(5,9))
def cuadrado(n1: int) -> int:
    return n1*n1

if __name__ == "__main__":
    print(cuadrado(3))
    
def saludo(msg:str):
    print(msg)

if __name__ == "__main":
    saludo("hola ICI")



lista = ["uno","dos","tres"]
msg_numeros = f"numeros: {lista}"
print(msg_numeros)

tupla_numeros= ("uno","dos","tres")
msg_numeros = f"numeros: {tupla_numeros}"
print(msg_numeros)

set_numeros = {"uno","dos","tres"}
print(set_numeros)

dict_numeros ={"1":"uno","2":"dos","3":"tres"}
msg_dict_numeros = f"numeros: {dict_numeros}"
print(msg_dict_numeros)

dos = f"numero: {dict_numeros['2']}"
print(dos)

def msg (nombre:str, año:int, nacimiento:int)-> str:
    return f"hola!! {nombre}, tienes {año-nacimiento} años"
print(msg("alfredo",2022,1997))

alum =["Luis","Kurt","Diana","Alfredo","Alexis"]
mat1 = [10,9,10,8,9]
mat2 = [8,9,9,10,9]
mat3 = [7,6,8,9,6]
mat4 = [6,6,7,6,9]
mat5 = [10,10,10,10,9]

encabezado = ["Nombre Alumno", "Est. de datos","Ec. diferenciales","Met. Numericos","Prog. funcional","Ingles"]

def reporte (fmt):
    print(f"{encabezado[0]:^{fmt}}{encabezado[1]:^{fmt}}{encabezado[2]:^{fmt}}{encabezado[3]:^{fmt}}{encabezado[4]:^{fmt}}{encabezado[5]:^{fmt}}")
    for i in range(5):
        print(f"{alum[i]:^{fmt}}{mat1[i]:^{fmt}}{mat2[i]:^{fmt}}{mat3[i]:^{fmt}}{mat4[i]:^{fmt}}{mat5[i]:^{fmt}}")
reporte(20)



def tablas(t: int,n: int):
    for i in range(1,t+1):
        tabla(i,n,5)

def tabla(t:int, n:int, spc:int):
    for i in range(1,n+1):
        print(f"{t:^{spc}} x {i:^{spc}} ={t*i:^{spc}}")

t=int(input("¿hasta que tabla desea calcular?"))
n=int(input("¿hasta que numero de la tabla desea calcular?"))

tablas(3,4)
