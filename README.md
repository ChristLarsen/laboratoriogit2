## Laboratorio GIT 2

---

_Inicialización uso de Git_

1. Crear un repositorio en local

**mkdir laboratoriogit2**

**cd laboratoriogit2**

**git init**

![Imagen de lo realizado](imagenes/Captura1.png)

2. Subir el repositorio a GitHub

![Imagen de lo realizado](imagenes/Captura2.png)

**git remote add origin https://github.com/ChristLarsen/laboratoriogit2.git**

3. Hacer un commit y un push

He abierto mi repositorio nuevo con VSCode. Creo un nuevo fichero README.md :

![Imagen de lo realizado](imagenes/Captura3.png)

**git add .**

**git commit -m "Inicialización repositorio"**

**git push --set-upstream origin master**

![Imagen de lo realizado](imagenes/Captura4.png)

4. Crear una rama

**git branch development**

**git checkout development**

Creo ficheo fichero1.js en mi carpeta principal.

**git add .**

**git commit -am "Development"**

**git push -set-upstream origin development**

![Imagen de lo realizado](imagenes/Captura5.png)

5. Hago un merge

**git checkout master**

**git merge development -m "Merge con development"**

**git push**




