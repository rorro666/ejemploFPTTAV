#variables
edad = 0 

print ("==validador de datos==")
print ("ingrese su edad:")
edad = int(input())
##operadores matematicos >,< >=,<=,!=
##operadores logico: or y and 
## 1-10 años niños
## 11- 17 años Adolecentes 
## 18- 60 añoa Adulto
## 60 años o mas adultos mayores 

if edad >= 1 and edad <=10:
    print ("Es un niño")
elif  edad >= 11 and edad <= 17:
    print("Es un adolecente")   
if edad >= 18 and edad <= 60: 
    print ("Es un adulto")
elif edad >= 61 and edad <= 99:
    print("Es un adulto mayor")    

