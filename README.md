# README.md
# MI PROYECTO
Este es mi proyecto en python
## AUTOR
Pascual Isaac Paez Rangel
## como ejecutar
python proyecto.py
es una aplicaion de un gimnasio
primero es ingresar tu nombre 
segundo te pedira numero de socio que es 1234
al ingresar esos datos te dara la bienvenida y te dara la opcion de que musculo deseas trabajar 
pones el musculo que quieras te dara la rutina 
despues volvera a preguntar que sii deseas trabajar otro musculo 
de poner si, te dara la opcion de elegir otro musculo que deseas trabajar
te dara los ejercicios y se cerrara el programa 
de poner no, solo se cerrara el programa
## codigo
print ("gimnasio majeco")

print ("como te llamas")
nombre = input("ingresa tu nombre: ")
print ("ingrese codigo de acceso")
codigo = input("numero de socio: ")

if codigo == "1234":
    print("bienvenido", nombre)
else:
    print("acceso denegado")
    exit()

opcion = input("que musculo deseas trabajar? (pecho, espalda, biceps, triceps, hombros, piernas): ")
if opcion == "pecho":
    print("ejercicios para pecho: press de banca, flexiones, aperturas con mancuernas")

elif opcion == "espalda":   
      print("ejercicios para espalda: dominadas, remo con barra, peso muerto")

elif opcion == "biceps":    
     print("ejercicios para biceps: curl con barra, curl con mancuernas, curl martillo")

elif opcion == "triceps":   
     print("ejercicios para triceps: fondos, extensiones de triceps, press francés")

elif opcion == "hombros":    
     print("ejercicios para hombros: press militar, elevaciones laterales, pájaros")

elif opcion == "piernas":    
     print("ejercicios para piernas: sentadillas, zancadas, peso muerto rumano")

print ("¿deseas trabarjar otro musculo? (si/no)")
respuesta = input("ingresa tu respuesta: ")
if respuesta == "si":
    opcion = input("que musculo deseas trabajar? (pecho, espalda, biceps, triceps, hombros, piernas): ")
    if opcion == "pecho":
        print("ejercicios para pecho: press de banca, flexiones, aperturas con mancuernas")

    elif opcion == "espalda":   
          print("ejercicios para espalda: dominadas, remo con barra, peso muerto")

    elif opcion == "biceps":    
         print("ejercicios para biceps: curl con barra, curl con mancuernas, curl martillo")

    elif opcion == "triceps":   
         print("ejercicios para triceps: fondos, extensiones de triceps, press francés")

    elif opcion == "hombros":    
         print("ejercicios para hombros: press militar, elevaciones laterales, pájaros")

    elif opcion == "piernas":    
         print("ejercicios para piernas: sentadillas, zancadas, peso muerto rumano")
    print ("gracias que disfrutes tu entrenamiento, hasta luego")

elif respuesta == "no":
    print("gracias que disfrutes tu entrenamiento, hasta luego")
   
