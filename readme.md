# CONFIGURACION GLOBAL DE GIT
git config --global user.name "montoyitag"
git config --global user.email "montoyaguzman7@gmail.com"

# Inicializar una carpeta como repositorio
git init

# Comprobar el estado del repo
git status

# Ver la historia de commits
git log --oneline

# Ver la historia de commits
git log

# Agregar archivos al stagging area
git add name-file.txt
git add .

# Hacer un commit
git commit -m "mi mensaje"

# Crear ramas
git checkout -B nombre-rama

# Ver mis ramas
git branch

# Cambiarme de ramas
git checkout nombre-rama