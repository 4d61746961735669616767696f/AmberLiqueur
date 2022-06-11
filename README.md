# AmberLiqueur
# Link del Figma con el prototipo: https://www.figma.com/file/NEeWJ1wFjvfOSGiRy9eqQs/Amber-Liqueur?node-id=0%3A1

# Cambios realizados en el commit 'Beta 0.0.1':

    - Incorporacion y modificacion de etiquetas en TODOS los html:

        • <navbar></navbar>: Cambio de nombre a <nav></nav> y correccion de href=''.

        • <header></header>: Se incorporo solo el contenido de titulos y subtitulos, asi como botones redireccionales si fuera necesario.

        • <main></main>: Incorporacion de esta etiqueta en el <body></body> donde se encuentran las distintas <section></section> con sus respectivos <div></div>

        • <section class='footer'></section>: Correccion de esta etiqueta a <footer></footer>.


    - Incorporacion de carpeta 'pages' donde se encuentran los templates o html de todas las paginas que no    son index.html.

    - Cambio de nombre del archivo 'GPS.html' a 'gps.html'.

# Cambios realizados en el commit 'Beta 0.0.2':

    Para esta entrega se pedia agregar recursos CSS al proyecto en 1(uno) archivo html. El archivo modificado es index.html.

    A continuacion se detallan los cambios:

        - Separacion en <header></header> / <main></main> / <locate></locate> / <footer></footer>.

            • <header></header>: Se agrego un boton redireccional a <main id="more"></main> con efecto en css.

            • <main></main>: Se agrego boton a store.html con efecto en css.

            • <locate></locate>: Se elimino gps.html y se incorporo el iframe en esta seccion del index.html.

            • <footer></footer>: Diseño nuevo de footer que contiene el logo de la marca y 5 tarjetas (con border) a redes   sociales (en construccion).

        - Incorporacios de Navbar funcional en <main></main> con adicion de efectos de seleccion (varios sitios estan en construccion, por eso no se dirige a ellos).

        - Cambio e incorporacion de fuentes mediante import de fonts.google.com y a traves de links en la seccion <head></head>.

        - Correccion de fondos background. 



    ===================================
        IMPORTANTE PARA CORRECCION
    ===================================
    Algunos puntos a aclarar:

        - Se conoce la posibilidad de que algunos vinculos esten fuera de servicio debido al proceso de construccion de los sitios.

        - Se estima el contenido en <p></p> dentro de <header></header> --> <aside></aside> deberian ser 
        <h1></h1>, no encontre forma de hacer que la fuente se haga mas 'fina', ya que el 'font-weight' no me realizaba ningun cambio dentro de la etiqueta <h1></h1>, asi que para llegar al resultado estetico esperado tuve que usar las etiquetas de parrafo.

        - Con respecto a la ultima devolucion, se me marco que pusiera el nav dentro del header, tuve la idea de incorporar el navbar recien en la seccion de main y dejar el header como pantalla principal. Fue una cuestion estetica que se me ocurrio, no se si es correcto poner el nav dentro de otra seccion que no sea el header.

        - Por ultimo, no se si es un error o algo que hice mal, pero cada vez de que recargo la pagina las fuentes estan todas en comic sans en el primer segundo, despues de eso si se aplican las que elegi. No se por que es y me pone muy nervioso.


