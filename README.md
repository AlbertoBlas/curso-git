curso-git en la rama mejorandola
=========

Una vez que instalas git debes configurarlo:

git config --global user.name "Alberto Blas"
git config --global user.email "xxx@gmail.com"

Generando el public Key SSH:

ssh-keygen

Leyendo tu clve para copiarla a Github

cat /.ssh/id_rsa.pub

Arrancando el proyecto

git init
touch README2
git add README2
git commit -m "Tu primer commit"
git push origin master


Clonar un proyecto

git init
git remote add origin git@github.com:flexeando/html5-boilerplate.git
git pull origin master


Crear Branches

git branch dev
git branch mejorandola

git checkout dev
-Switched to branch 'dev'


Subir todos los archivos

git commit add .

Para ver todos los branches
git branch

