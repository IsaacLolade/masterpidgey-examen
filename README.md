# Exámen Entonos de desarrollo

## Creación de repositrio

![Creación](/ExamenGit/crearrepositorio.png)

## Clonar repositorio

Para realizar la clonación de mi respositorio en local he realizado un git clone https://github.com/IsaacLolade/masterpidgey-examen.git
![clonación](C:\Users\issssiiiiii\masterpidgey-examen\ExamenGit\Clonar repositorio local.png)

## Crear README

Para crear el README, primeramente me he dirigido a la ruta en la que se encuentra mi repositorio local con el comando cd masterpidegey-examen y una vez dentro he hecho uso del comando nano README.md
![Creación README](/ExamenGit/crearREADME.png)

## Commit inicial

Una vez guardado y editado nuestro archivo de markdown hare un git add README.md para añadir el archivo para realizar el commit.

Utilizaremos el comando git commit -m "commit inicial" cargar los cambios realizados

![Git add](/ExamenGit/gitadd.png)
![Commit](/ExamenGit/gitcommit.png)

## Push inicial

Para realizar el push inicial haremos uso del comando git push origin main

![Push inicial](/ExamenGit/gitpush.png)

### Colaborador

![Collab](/ExamenGit/collab.png)

## Ignorar archivos

### Crear en el repositorio local un fichero llamado privado.txt.

Haremos uso del comando nano privado.txt para crear el archivo.txt y realizaremos los mismos pasos que antes git add del archivo, commit
y el push
![Creación archivo](/ExamenGit/creacionprivado.txtydirectorioprivada.png)

### Crear en el repositorio local una carpeta llamada privada.

Haremos uso del comando mkdir privada para crear el directorio y realizaremos los mismos pasos que antes git add del directorio, commit y el push

![Creación carpeta](/ExamenGit/creacionprivado.txtydirectorioprivada.png)

### Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.

Haremos uso del comando nano .gitignore y una vez dentro pondremos el nombre de los archivos que queremos. Al igual que antes deberemos de realizar tanto el git add como el commit, en micaso he decidido subir el commit juntado los dos pasos anteriores.

![Creacion de gitignore](/ExamenGit/gitignore.png)

### Añadir fichero 1.txt en el repositorio local

Haremos uso del comando nano 1.txt para crear el archivo.txt.

![Crear archivo 1.txt](/ExamenGit/creacion1.txt.png)

### Crear tag

Utilizaremos el siguiente comando para poder crear un tag git tag v0.1

![Crear tag](/ExamenGit/Creaciongittag.png)

### Subir tag

Para subir el tag haremos uso el comando de git push origin v0.1

![Subir tag](/ExamenGit/subirtag.png)

### Visualizar los commits realizados

Para poder ver cuáles son los commits que hemos realizadohasta el momento solo haremos uso de del comando git log

![Visualizar commits](/ExamenGit/Visualizarcommits.png)

### Crear una tabla

| NOMBRE                 | GITHUB                                                       |
| ---------------------- | ------------------------------------------------------------ |
| Máximo Fernández Riera | [enlace a github 1](https://github.com/maximofernandezriera) |

## Pull request

### Creación y clonacion del fork

Para ello nos vamos a dirigir a al repoositorio de Github al cual queremos realizar el fork y una vez allí buscaremos en la parte superior a la derecha donde nos aparecerá una opción para poder realizar el fork. Seguiremos los pasos necesarios para crear el fork y una vez finalizado ya tendriamos nuestra propia bifurcación ahora para poder realizar los cambios que creamos necesarios. A continuación haremos un git clone https://github.com/IsaacLolade/first-contributions.git para poder hacer uso de este repositorio en la terminal de git bash.

![Creación fork](/ExamenGit/CrearFork.png)

![Clonación fork](/ExamenGit/clonaciondefork.png)

### Crear una rama

Para crear una nueva rama, he utilizado el comando git branch isaac-bifurcacion.

![Crea rama](/ExamenGit/creacionderama.png)

### Cambiar a la rama creada

Luego he utilizado el comando git checkout isaac-bifurcacion para poder cambiar del main a mi rama previamente creada.

![Cambiar de rama](/ExamenGit/cambioamiramaycreaciondearchivopararealizarpullrequest.png)

### Crear un archivo para realizar pull request

A continuación he creado un archivo llamado isaac_pullrequest.txt donde añadiré un comentario para poder hacer uso de el y relizar la pull request.

![Creación archivo para realizar pull request](/ExamenGit/cambioamiramaycreaciondearchivopararealizarpullrequest.png)

### Observar que repositorios tenemos sincronizados

Haremos uso del git remote -v el cual nos mostrará los repositorios con los cualés estamos sincronizados ahora mismo en mi caso me aparece :
origin https://github.com/IsaacLolade/first-contributions.git (fetch)
origin https://github.com/IsaacLolade/first-contributions.git (push)

![Repos sincronizados](/ExamenGit/observarrepositoriossincronizados.png)

### Añadir repositorio el cual sinconizaremoscon nuestro fork

Para ello haremos uso de añadir más repositorios en remoto utilizaremos el comando git remote add upstream https://github.com/maximofernandezriera/first-contributions.git y si volvemos a realizar el git remote -v veremos que nos aparece :
origin https://github.com/IsaacLolade/first-contributions.git (fetch)
origin https://github.com/IsaacLolade/first-contributions.git (push)
usptream https://github.com/maximofernandezriera/first-contributions.git (fetch)
usptream https://github.com/maximofernandezriera/first-contributions.git (push)

![Ver repos remotos](/ExamenGit/observarrepositoriossincronizados2.png.png)

### Sincronización repositorios

Para sincronizar los repositorios en remoto haremos uso del comando git fetch upstream

![Fetch](/ExamenGit/sincronizacionderepositorios.png)

### Realizar merge

Para realizar el merge utilizar primeramente haremos un git checkout main para dirigirnos al repositorio local y una vez allí haremos un git merge upstream/main.

![merge](/ExamenGit/merge.png)

### Fotos de pullrquest

![Petición de pullrequest](/ExamenGit/pullrquest.png)

![Aceptado](/ExamenGit/pullrequestmergeado.png)

## Conclusión

Gracias a este exámen he adquirido conocimientos los cuáles me van a servir para poder mis futuros proyectos a una de las plataformas mas conocidas por desarrolladores llamada Github, los comandos que he aprendido me ayudarán a agilizar mi trabajo de manera que sea mas optimo por decirlo de alguna manera.
