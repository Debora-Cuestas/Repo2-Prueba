<img src="https://images.unsplash.com/photo-1618401479427-c8ef9465fbe1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2343&q=80">


$ git --version
Para ver la versión

clear
Para limpiar la pantalla

pwd (Print Working Directory)
Informa en qué carpeta estás parado

cd
Para moverte entre carpetas

$ git config --global user.name
Para consultar user.name 

*enter

$ git config --global user.name nombreporelquequiercambiar
Para cambiar nombre de usuario

$ git config --global user.email
Para consultar email.

$ git config --global core.editor
Para consultar editor predeterminado

mkdir Nombredelarchivoquequierocrear
Crea repositorio 

Devuelve: "D:\VSCode\Microsoft VS Code\bin\code" sino por defecto bin.

$ git config --global core.editor "code --wait"
Para configurar el editor

git commit -m ""
Guarda los cambios hasta ahí.

git init
Iniciar en una carpeta en un repositorio
NUNCA UN REPOSITORIO DENTRO DE OTRO

.gitignore
Que Git no les da seguimiento, los ignora.

git add 
Agrega al Staging area el material

git commit 
Hace el punto de restauración

git touch nombredearchivo
Crear un archivo

git .env
No comparte datos importantes o sensibles en el repositorio compartido

root
Usuario administrador de Linux

git commit -a -m "
git commit -am "
            agregá y comiteá (ambas son lo mismo)

Sólo se puede hacer a partir del segundo add. Si no hay un add primero no va a salir

git checkout nombredehash (ej: 79c884c) 
Para volver a cierto numero de commit

git checkout master
Volvé al commit actual

git log
Para ver los ultimos commiteos y hash

git log --oneline
Para que haga un log de una sola línea

rm nombre de archivo(remove)
Borra archivo OJO, NO PREGUNTA
