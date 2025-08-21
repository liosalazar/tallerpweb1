PASO 1 Crear repositorio

PASO 2 Copiar la dirección HTTPS del repositorio y ejecutar comando

git clone https://github.com/liosalazar/tallerpweb1.git

PASO 3 Ingresar correo github en GIT 

git config --global user.email sucorreo
git config --global user.email 20232685@aloe.ulima.edu.pe

cd = change directory

Es una buena practica utilizar multiples ramas o branch en los repositorios ya que  
trabaja de manera conjunta y permita garantizar la organización de los proyectos

git branch nombredelarama
git branch julito

git checkout nombredelarama
git checkout julito

# el comando de abajo agrega todos los archivos para commitear (guardar de manera local)
git add .

# Se realiza el commit
git commit -m "Descripciondelcommit"

# Subir cambios de la rama en el comando git push

git push origin nombredelarama
git push origin julito

# tallerpweb1