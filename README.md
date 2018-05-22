# Investigacion GIT

## 1. git checkout 
**git checkout practicando** - cambiamos de nuevo a la rama de practicando

en ella se modifica practicando/clase.txt —> “me encuentro en el lis en clase de Analisis y diseño de sistemas II junto con nombre-compañero de al lado”

## 2. git stash
**git stash** — va guardar los cambios temporalmente para poder descargar cambios nuevos y no borrar lo trabajado  
**git status** — verificamos no tener nada que pueda tener conflicto  

## 3. git pull 
**git pull origin analizando**   — traer los cambios alojados en otra rama 

## 4. git stash pop
**git stash pop** — Sirve para mezclar los cambios que habíamos guardado temporalmente y lo nuevo traido de otra rama   

En este punto debe de haber un conflicto, para resolverlo debera dirigirse al archivo que aparece y git le ofrece la posibilidad de identificar la zona de conflicto, en ella usted debe seleccionar que desea dejar, si los cambios traidos(parte superior del conflicto) o sus cambios (parte inferior del conflicto)


## 5. solución conflicto

una vez solucionó el conflicto deberá agregar el archivo para guardarlo
**git add archivo-conflicto**  
y lo guarda (commit)  
git commit -m “solucionando un conflicto”   

para terminar el conflicto lo sube a la rama para que todos puedan tener actualizado los cambios
**git push origin practicando**

## 7. git merge

por ultimo nos dirigimos a la rama master  
**git checkout master**

**git merge practicando**  - y así la rama master queda actualizada con lo ultimo de la rama practicando mezclando sus cambios.




#!Muchas gracias!
