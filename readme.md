# Ejercicios de git 1
1.__Crea un directorio llamado repo01 en local (desde tu máquina) e
ejecuta el comando pertinente
para que dicho directorio para que se transforme el repositorio en local ¿Cómo
podemos identificar que el repositorio se ha inicializado?__  
Para convertir un directorio en un repositorio tenemos que ejecutar el comando de git init, de esta forma tendremos una carpeta oculta en ese repositorio que se llama .git y hará de enlace entre el repositorio remoto y el local.  
![Error al cargar la imagen](https://github.com/eamargant/exercici1git/blob/main/FOTOS/1.PNG?raw=true "Captura proces init")  
******************  
2.__Añade un documento llamado readme.md dentro del repositorio (recuerda
que MD es la extensión de los ficheros Markdown) y documenta en su interior todos
los pasos que vas realizando para crear un repositorio, etc. Puedes añadir
fotos o lo que creas conveniente__  
***********
3.__Añade el fichero que acabamos de añadir al repositorio al staging area, visualiza el estado del
repositorio (con git status) y haz un snapshot (commit) del fichero hacía nuestro
repositorio local. ¿En que “file status lifecycle” se encuentra el fichero?__ 

Una vez hemos hecho el add y el commit del fichero, significa que se han actualizado todos los cambios hecho en ese fichero, y se han actualizado en el repositorio local. Una vez hagamos el ___git push___ el fichero que acabamos de actualizar y guardar en nuestro repositorio local se va a "enviar" al repositorio remoto.

4.__Intenta subir los ficheros al repositorio remoto mediante al comando git
push
¿Se te ocurre que está pasando? (si no lo sabes aún no te preocupes)__  
Como aún no tenemos enlazado el servidor remoto con el local, el ___git push___ no hace nada por que no tiene ningun servidor remoto al que enviarlo.  
5.__Ejecuta el comando git remote –v e investiga porque no nos aparece nada__  
Igual que antes, al no tener servidor remoto no aparece nada.  
6.__Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local__  
7.__Vuelve a ejecutar el comando git remote –v nuevamente y explica el porque
ahora si que aparece__  
Al tenerlo enlazado, el comando que antes no funcionaba, ahora hace su función y nos muestra info del servidor remoto.
![Error al cargar la imagen](https://github.com/eamargant/exercici1git/blob/main/FOTOS/3.PNG?raw=true "Captura proces")    
8.__Sube los cambios que hemos subido al snapshot local (commit) hacía al repositorio remoto__
![Error al cargar la imagen](https://github.com/eamargant/exercici1git/blob/main/FOTOS/4.PNG?raw=true "Captura proces")  
9.__Ves al repositorio remoto (en este caso GitHub) y comprueba que se haya
realizado el commit correctamente y observa que pasa
en el repositorio ¿Observas algo peculiar?__  
Tengo los mismos documentos que en mi repositorio local y el en caso del Readme puedo ver su contenido sin tener que abrirlo.  
![Error al cargar la imagen](https://github.com/eamargant/exercici1git/blob/main/FOTOS/5.PNG?raw=true "Captura proces") 