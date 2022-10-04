# Proyecto Imprenta
Proyecto estructurado en bootstrap 5, tambien utilizamons node-sass, preprocesador css.
## Instalación
```sh
npm install -g node-sass
```
Despues de la instalacion de esta dependencia, en el directorio del proyecto inicializamos un package.json con el siguiente comando
```sh
npm init
```
En el archivo package.json, en el apartado scripts anexamos la siguien linea de codigo:
```sh
"scss": "node-sass --watch src/assets/scss -o src/assets/css"
```
Cabe recalcar que en el directorio debemos tener una carpeta llamada src donde estara otro documento llamado assets y dos mas, una llamada scss y otra css. con el fin de que al momento de ejecutar el comando npm run scss no genere error.
comando para correr scss. 
```sh
npm run scss
```
# Nota:
Siempre creo el archivo scss y css en sus carpetas correspondientes, los estilos los escribo en el primer archivo antes ya mencionado y ellos se almacenan automaticamente en el css, archivo reconocido por el navegador.








