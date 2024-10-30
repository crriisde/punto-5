print (" ") #este linea deja el espacio para el nombre 
print ("Cristian David Salas De La O 3,W") #este linea define el nombre del programador 
print (" ") #este linea defa el espacio para el nonbre 
# Crear un archivo y agregar contenido

with open("demofile2.txt", "w") as f: #este linea define el whith
    f.write("Contenido inicial.\n") #este linea define el contenido inicial 

with open("demofile2.txt", "a") as f: #este linea define el with 
    f.write("Ahora el archivo tiene más contenido!\n") #este linea define el archivo del contenido 

# Leer el archivo después de anexar
with open("demofile2.txt", "r") as f: #este linea define el with
    print("Contenido de demofile2.txt:") #este linea define el demofile
    print(f.read()) #este linea muestra el codigo 
    ![image](https://github.com/user-attachments/assets/dd31dab4-afcb-436d-a40a-e7aef6f7ee2d)
![image](https://github.com/user-attachments/assets/e1024b36-020b-4994-b22d-7360ecda6e19)
