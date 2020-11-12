# Bootstrap
## Introduccion
### Que es un framework frontend
Cuando realizamos una busqueda sobre frameworks frontend tambien podemos encontrar con el termino Framework CSS, en si mismo nos proveen organizacion, estructura a nuestras tecnologias frotend, HTML, CSS, JavaScript, y una base para inciar un proyecto web de manera flexible.

Su componenete principal es la *Grilla*, lo que nos permite ordenar el contenido de nuestra web y volverlo responsivo. asi mismo traen estilos de fuente y componente visuales preconfigurados que nos permiten ahorrar tiempo y que se rompa el codigo.

### Iniciar con bootstrap
Nos dirigimos a la pagina oficial de [Bootstrap](https://getbootstrap.com/) y vamos a la guia rapida *Get Started* podemos leer la documentacion oficial para entender mejor el framework

Copiamos el *Starter template*, dentr de nuestro directorio de trabajo creamos un archivo HTML y lo nombramos `index.html` y pegamos el codigo, podemos abrirlo en el navegador para explorarlo.

## Creando un sitio web
### La grilla de Bootstrap
Para iniciar a programar con bootstrap es necesario conocer su componente mas basico, los contenedores.

- En la pagina de boostrap nos ubicamos en el menu izquierdo y vamos a *layout*, aqui encontramos los containers, elegimos el deseado, copiamos el codigo y lo pegamos en el archivo HTML

- A continuacion vamos al menu *Grid*, esencialmente debemos entender que tendremos filas y columnas, dentro de los containers siempre debemos icluir filas `<div class="row">`, que por defecto tienen como maximo, 12 columnas`<div class="col-sm">`.

- El tamaño de cada columna se peude modificar cmabiado el `sm` por el tamaño deseado `<div class="col-2">`, si no se define el tamaño de cada columna, ellas se reparten el ancho de manera equitativa, si la suma de las filas supera de manera vertical mas de 12, bootstrap automaticamente la ubicara abajo de la anterior

