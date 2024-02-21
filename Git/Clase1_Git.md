## Configuración inicial
### Configurando Git por primera vez
- git --version

- git config --global user.name "Mafer Vásquez"

- git config --global user.email fvag0702@gmail.com

- git config --global user.ui true

- git config --global init.defaultBranch main

- git config --list

- (asignando visual studio code como editor de configuración de git)-
git config --global core.editor "code --wait"

- git config --global -e

- (para estandarizar los saltos de línea en windows)
git config --global core.autocrlf true

- (para estandarizar los saltos de línea en linux/mac)-
git config --global core.autocrlf input

- (ver todas las opciones de la configuración en la terminal)-
git config -h

- (ver todas las opciones de la configuración en el navegador)-
git help config

## Repositorio nuevo
git init (ver que archivos están actvos trackeados (A) o no lo están (U))

git add archivo/directorio (agregar los cambios de un archivo al staged)

git add . (para trackear todos los archivos de tu carpeta)(agregar todos los cambios de todos los archivos al staged)

git commit -m "Primer commit" (primer mensaje de cambio que quieras subir en el repositorio)

git remote add origin _agregas enlace_
(esto agregará el origen remoto de tu repositoria de github, pasa de local al que esta en la aplicación)

git push -u origin main (primera vez que vinculas el repositorio remoto con el local)

git push (para las próximas actualizaciones que quieras subir)
