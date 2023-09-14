Samuel Gutierrez Sanchez

**Lenguajes interpretados**: de el maestro Jonathan Mircha, nos enseña a como usar git en consola y nube

**Sistemas Operativos**: de el maestro osiel morales, nos enseña a como limpiar el almacenamiento

**composicion y diseño**: de el maestro Roberto melo, nos enseña a usar photoshop

**diseño de videojuegos**: de el maestro Hector guerrero, nos enseña a como hacer un juego

**proyecto app**: de el maestro sebastian mejia, nos enseña a crear documentos estructurados


Creando la version v1.0.0

///////////////////////////////////////////////////////////////////////////////////////////

**¿Como se inicializa un repositorio en Git?**
se inicializa abriendo la terminal del visual studio code y ingresas los siguientes comandos

```
git --version
``` 
```
git config --local user.name "Tu nombre"``` 
```git config --local user.email tucorreo@gmail.com
``` 
```
git config --local user.ui true
``` 
```
git config --local init.defaultBranch main
``` 
```
git config --list
``` 

```
git config --global core.editor "code --wait"
``` 
```
git config --local -e
``` 

**¿Como creas un repositorio en github?**
Primero te tienes que crear una cuenta de github si no tienes, luego simplemente ya iniciado del lado izquierdo de bajo dellogo de git, esta la opcion crear un nuevo repositorio, ahi tu decides el nombre y si hacerlo publico o privado

**¿Como vinculas un repositorio local de git con uno remoto en github?**
para vincularlo necesitas los siguientes comandos

```
git remote add origin https://github.com/usuario/repositorio.git
```
```
git push -u origin master
```
```
git push
```

Estos tres comandos te los da tu propio repositorio a la hora de crearlo

**¿Cual es el flujo basico de trabajo en git y github?**
el flujo de trabajo es crear nuevos cambios en tu repositorio local, guardar y subir los cambios a traves de los comandos a tu repositorio de github
