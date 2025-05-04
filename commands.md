# COMANDOS GIT

**Inicializando nuestro repositorio**
git init

**Verificar el estado de los archivos**
git status
git status -s

**Agregando los archivos al repositorio**
git add <nombre archivo>
git add .
git add --all

**Agregamos los cambios al repositorio LOCAL y un comentario del cambio**
git commit -m <"comentario">

**Subiendo los cambios al repositorio remoto**
git push origin <rama principal>

### Comandos adicionales
**Configuración de usuario**
git config user.name
git config user.email
git config user.name <usuario github>
git config user.email <correo github>

**Verificando el repositorio remoto**
git remote -v

**Agregando repositorio remoto**
git remote add origin <enlace repositorio github>

### Comando sobre ramas

git branch


git branch <nueva-rama>

**Creando una nueva rama y accediendo a ella**
git checkout -b <nueva-rama>


git checkout -b

hola