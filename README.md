Primer fichero en el primer repositorio de Carlos Parodi de la Fuente
**Configurar git:**
```
git config --global user.name "cparodif" 
git config --global user.email "cparodif@no-email.com"     
git config --global init.defaultBranch main
```
**Primer uso de git:**
```
git init
git add .
git commit -m "comentario del primer commit"
git branch -M main
git remote add origin https://github.com/cparodif/Arch4hack.git
git push -u origin main
```
usuario: cparodif
contraseña: PAT (Personal Acceso Token) 

**Trabajo habitual:**
```
git pull origin main
git branch nuevo
git checkout nuevo
git status
git branch
ll
```
editar y añadir y eliminar ficheros y directorios
```
git add -A
```
o
```
git add .
```

```
git commit -m "comentario de las modificaciones"
git push -u origin nuevo
git log
git branch -a
git checkout main
git pull origin main
git branch --merge
git merge nuevo
git push origin main
```
Eliminar ramas
```
git push origin --delete nuevo
git branch -a
git branch -d nuevo
```

origin= nombre del repositorio remoto principal

HEAD= commit en el que está posicionado tu repositorio



### Sintaxis de markdown: 
https://markdown.es/sintaxis-markdown/


