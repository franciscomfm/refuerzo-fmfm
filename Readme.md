Ejercicio 1y2 lo que hice fue coger mi otro repositorio anterior llamado fm_fm-Proyecto-GIT renombrarlo a refuerzo-fmfm y desconectarlo de github con el siguiente comando "git remote remove origin", seguidamente lo conecte al que habia creado nuevo en github llamado refuerzo-fmfm con el comando "git remote add origin https://github.com/franciscomfm/refuerzo-fmfm.git" y subir todos los arcivos con el comando "git push origin master", en las siguientes imagenes podemos ver todo sus archivos en github, luego mas tarde borre el repositorio en local y lo clone desde github copiando la url del proyecto a mi escritorio con el siguiente comando "git clone y su url".


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/Captura%20de%20pantalla%202021-02-16%20153218.png)


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/Captura%20de%20pantalla%202021-02-16%20131349.png)


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/1.png)

![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/2.jpg)



Ejercicio 3 aquí podemos ver el README creado en local en visual estudio code.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/3.png)


Ejercicio 4 y 5, con los comnandos "git add ." para añadirlo al stage area y git commit -m "commit inicial" para crear una version y haciendo un "git push" estara repositorio en github


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/7.png)

Ejercicio 6 cree un archivo privado.txt y una carpeta privada/ para ignorar esto archivos cree un archivo llamado .gitignore y dentro especifique los tipos de archivos que queria ignorar como por ejemplo privada/ y privado.txt luego añadi con el comando "git add ." el archivo .gitignore al stagearea y hice un commit llamdado "He añadido el .gitignore" con el comando "git commit -m "".... así ignore esto archivos.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/11.png)


Ejercicio 7 cree en local, visual estudio code el archivo 1.txt y luego lo añadi al stage area con "git add ." y le hice un git commit -m "He añadido 1.txt".


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/12.png)


Ejercicio 8 y 9 cree el tag v0.1 con el comando "git tag v0.1 -m "Primera version"" y lo subi a github con el comnado git push --tags y con el comando "git show" podemos ver a que commit hace referencia cada tags y su información]



![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/13.png)


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/Captura%20de%20pantalla%202021-02-16%20132228.png)


Ejercicio 10 me puse foto de perfil en github.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/16.jpg)


Ejercicio 11 puse mi usuario de github en mi grupo "3" de discord para que me siguieran mis compañeros, luego segui a mis compañeros en github y despues les añadi una estrella a cada uno.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/17.jpg)


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/18.jpg)



![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%204.%20Refuerzo%20github/19.png)



Nombre | GITHUB
------ | ------
Jesús Manuel Espinar Ocaña | https://github.com/jesus-eo
Juan Diego Jurado Pimentel | https://github.com/juandiegojp
Miguel Gutiérrez | https://github.com/MiguelGutierrezParejo



Aqui empieza la tarea 5 de refuerzo.


Ejercicio 1 para crear una rama con el comando "git branch y el nombre de la rama en este caso "v0.2" y para saber el listado de rama el siguiente comando te puede ayudar "git branch", luego te posicionas en la rama que quieras en este momento queremos irnos a la rama v0.2 con el comnando "git  checkout v0.2".


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/0.png)


Ejercicio 2 creamos el archivo 2.txt en la rama v0.2 con los comando "git add ." y le hacemos un commit.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/2.png)


Ejercicio 3 con el comando "git push -u origin v0.2 creamos y subimos los archivos a la rama remota en github.


Ejercicio 4 y 5 6 y 7 solucione el conflicto aceptando ambos cambios, primero en la rama master le añadi Hola al archovo 1.txt y le hice un commit con "git commit -m..." despues cambie de rama con el comando "git checkout v0.2" y le añadi a 1.txt Adios y le añadi un commit a esta modificacion luego me volvi a la rama master y fusione la rama v0.2 con la master con el comando "git merge v0.2" desde la rama master claramente y me salio conflicto por haber tocado la misma linea de codigo en el mismo archivo en las dos rama diferentes, estudio visual code te da la oportunidad de elegir la modificacion que quieras oportuna, para listar los conmmit de cada rama para saber los mege con el comando "git log --oneline" en la rama que quieras.


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/8.png)

![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/5.jpg)


Ejercicio 8 crea el segundo tag con el comando "git tag v0.2 -m "segunda version" y lo subi a github con el comando git push --tags y si queremos borrar la rama v0.2 con el comando "git branch -d y el nombre de la rama si no tenemos commit pendiente que fusionar y si tenemos commit pendientes que fusionar forzaremos la eliminación con el comando "git branch -D v0.2".


![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/13.png)


Ejercicio 9 lista de distintos commit con sus ramas y sus tags con el comando "git log --oneline".

![](https://github.com/franciscomfm/refuerzo-fmfm/blob/master/imagenes%20para%20tarea%204y5%20refurzo/Tarea%205.%20Refuerzo%20github/Captura%20de%20pantalla%202021-02-18%20135254.png)