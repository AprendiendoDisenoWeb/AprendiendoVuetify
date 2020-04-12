# AprendiendoVuetify
Repositorio donde iré subiendo mi aprendizaje con vuetify

Una de las cosas que hemos de tener en cuenta es que estoy usando como fuente ubuntu mono, por lo que he ido a https://fonts.google.com/specimen/Ubuntu+Mono?query=ubuntu+mono&selection.family=Ubuntu+Mono&sidebar.open. He buscado la fuente en concreto que quería poner en la página web y he copiado el código que en esta página se muestra. En el index.html he puesto <link href="https://fonts.googleapis.com/css2?family=Ubuntu+Mono&display=swap" rel="stylesheet">. Este archivo se encuentra en carpeta>public>index.html
Mientras que en el css o style de Home.vue he puesto:
<style>
    .myfont{
        font-family: 'Ubuntu Mono', monospace;
    }
</style>
He probado, sin hacer ningún cambio, a poner dentro de /botones un class="myfont" y atuomáticamente se me ha puesto en la tipografía Ubuntu mono, no parece ser necesario referenciarla de ninguna otra forma.
Además, a diferencia de lo que pasaba al intentar cambiar el tamaño dentro de una etiqueta <v-> mediante display-1, por ejemplo, al poner dentro de class="myfont" white--text de esta forma class="myfont white--text" ha funcionado

Hay ciertos botones que, al poner un texto concreto, adoptan formas de iconos. Por ejemplo con favorite adopta forma de corazón (Siempre y cuando dentro del v-button tengamos un v-icon)
También se pueden hacer botones redondos.

Hay que tener en cuenta que ciertos componentes cambian haciendo una especie de animación, cosa que podría aprovecharse