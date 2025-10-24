# Prueba-Inicio-Repo
Así armamos un repositorio
Hemos comenzado con el repositorio , les voy a dejar los comndos que utilice:<br>
* Vimos como he creado el repositorio en la nube de Github
* Es impoprtante saber que antes de todo esto se debe tener todos los pasos de ingreso y seguridad.
* Cuando hablo de seguridad y conectividad se trata de la ssh, es la clave pública y privada.
* Copiamos el enlace ssh.
* Abrimos la terminal Git Bash como administrador.
* Ingresamos al área de trabajo donde queremos agregar el repo
* Yo ingrese a la carpeta Documents.

```sh
cd Documents
mkdir Proyectos
cd Proyectos
git clone git@github.com:valeriaPinaya/Prueba-Inicio-Repo.git
cd Pueba-Inicio-Repo
git pull origin main
git fetch
git branch #Veran la rama main por defecto
touch Readme.md #Creamos el readme
git status
git add .
git commit -m"Creamos el readme .md"
git status
git push origin main
``` 

##Agregamos este trabajo al Readme online
> ¿Cómo hacemos esto?
Ingresamos al repositorio y luego solo presionamos punto <br>

```sh
     .
```
Ingresamos toda esta información y terminamos. 