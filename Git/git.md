# [Click aqui para ir a mi GitHub](https://github.com/alejimenezgit)

## Git – Commands Proyectos
-------------------------------------------------------------------------------
Primero de todo estar en la carpeta donde quiero poner el proyecto

Fork desde el github ( fork es para poder tener el proyecto de alguien y subir mis cambios)

git clone (url sin ssh del github)

ir a la carpeta cd y trabajar code .

Añadir cambios:      git add .

Guardar cambios: 	git commit -m "mensaje" 

Ver cambios: 		git status (si sale % hacer otra vez el commit) / git log

Subir los cambios: 	git push origin master (o la rama que tenga)

Enviar el trabajo:	Github pull request name: 	[BCN-WDPT-1219] - Alejandro Jiménez

## Git – Change branch
--------------------------------------------------------------------------------
git checkout dev				==> cambiar a rama

git checkout -b dev 				==> crear rama

## Git – Commands Info
--------------------------------------------------------------------------------
iterm (recomendacion)

root es el c de ubuntu

cd – change directory

. donde estoy actualmente

cd .. ir al padre

ll – muestra lo actual

salir del manual es – q

.carpeta – carpetaoculta

ls -la – muestra los ocultos tambien

alias buscar que es – buscar como crearlos

touch index.html

git init       			iniciailza el document en git

git diff index.html		ver las diferencias anteriores de los commits


## Git – Delete node modules if you push it
--------------------------------------------------------------------------------
- Para eliminar nodemodules del github (una vez subido)
- Tengo que crear el .gitignore y añadir el .node_modules
- Luego ejecutar estas lineas de ejecución
```
git rm -r --cached node_modules 
git commit -m 'Remove the now ignored directory node_modules' <br/>
git rm -r --cached node_modules
```

## Git – Subir Proyecto a github desde el terminal	
--------------------------------------------------------------------------------
- Primero tengo que crear el proyecto en mi pc
- Luego tengo que crear un nuevo repositorio en mi github
- Para poderlo subir tengo que hacer estas lineas de ejecución

```
git remote add origin https://github.com/alejimenezgit/searchname.git    
git remote -v                                  
git push -u origin master                      
Y ya estaria listo en github 
```

