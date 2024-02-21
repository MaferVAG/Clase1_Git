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
git init
git add .
git commit -m "Primer commit"
git branch -M main
git remote add origin 
git push -u origin main
