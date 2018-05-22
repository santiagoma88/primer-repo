# Investigacion GIT

## 1. Instalar Git 

## 2. git config  
Lo primero que deberías hacer cuando instalas Git es establecer tu nombre de usuario y dirección de correo electrónico. Esto es importante porque las confirmaciones de cambios (commits) en Git usan esta información, y es introducida de manera inmutable en los commits que envías   
**git config --global user.name "Git Analisis UdeA"**  
**git config --global user.email git-analisis@udea.edu.com**  

## 3. Abre tu github  
En tu cuenta de github crea un nuevo repositorio  
## Aqui puede crear el [nuevo repositorio](https://github.com/new)   

## 4. comandos para crear repositorio local

**mkdir repositorio** crear carpeta para alojar repositorio  
**cd repositorio** ingresar al repositorio  
**git init**  
**echo “ INICIANDO EN GIT “ >> README.md** — crear un archivo readme    
**git add README.md** - para especificar los archivos que se desean guardar    
**git commit -m "primer commit en git"** - para confirmar los cambios y especificando mensaje de relacion  
**git remote add origin https://github.com/usuario-github/nombre-del-repo.git**  
**git push origin master**  

##Una vez cumplas con estos pasos podras seguir al siguiente [ejercicio](https://github.com/estebanrestrepo07/primer-repo/tree/1) 
