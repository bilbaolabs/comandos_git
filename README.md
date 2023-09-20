# Guía rápida de comandos GIT

- Configura el nombre de usuario de git local.
```
git config --global user.name "Nombre Usuario"
```
- Configura el correo del usuario de git local.
```
git config --global user.email "usuario@correo.cl"
```
- El proyecto actual lo "transforma" a proyecto git.
```
git init
```
- Muestra el estado actual de los archivos del proyecto.
```
git status
```
- Agrega a la etapa de STAGE un archivo especifico
```
git add nombre_archivo
```
- Agrega a la etapa de STAGE todos los archivos del proyecto.
```
git add .
```
- Agrega los archivos a la etapa COMMIT y le asigna un nombre a ese compromiso
```
git commit -m "nombre del commit"
```
- Conecta el repositorio local al repositorio remoto
```
git remote add origin <url de tu proyecto remoto>
```
- Verifica el repositorio remoto.
```
git remote -v
```
- Elimina la referencia al repositorio remoto. 
```
git remote rm origin
```
- Carga los cambios del COMMIT al repositorio remoto
```
git push origin nombre_de_rama_remota
```
- Muestra la información de los COMMIT
```
git log
```
- Muestra la información mas relevante de los COMMIT
```
git log --oneline
```
- Vuelve a un COMMIT anterior. El ID del COMMIT se puede ver en el comando anterior. No es necesario escribir todo el ID, con unos 3 o 4 caracteres iniciales es suficiente.
```
git checkout <id commit>
```
