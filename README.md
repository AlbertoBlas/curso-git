curso-git
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