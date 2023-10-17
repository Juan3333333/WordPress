# WordPress
1. Para Instalar el WordPress primero tenemos que crear una carpeta.
```console
smx2b@turing-117: mkdir WordPress
smx2b@turing-117: cd WordPress
```
2. Creamos el fichero vagrantfile con el comando vagrant init.
```console
smx2b@turing-117: vagrant init ubuntu/jammy64
```
podemos utilizar el comando **ll** par comprobar todo los permisos y archivos.

3. Una vez hecho, ahora creamos la infraestructura con el siguiente comando
´´´console 
smx2b@turing-117: vagrant up --provider=virtualbox
´´´


