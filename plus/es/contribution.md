---
layout: default
ident: contribution
lang: es
title: Colabora
---

<div style="position: relative;" align="center">
<p style="font-size: 40px;">Colabora</p>
</div>

<div class="plus">

    ¿Quieres colaborar? Aquí encontrarás instrucciones <br><br>

    <div>
        <div class="bcblue boxdissap">
        Los primeros pasos
        </div>

        <div class="dissap" style="margin-left: 50px">

            <div>
                <div class="bcgreen boxdissap">
                Contacto
                </div>

                <div class="dissap" style="margin-left: 50px">
                ¡Estaremos encantados de saber que te gusta Mathifold! Nos puedes contactar a través de nuestro correo <code>mathifold@gmail.com</code>. Podremos asesorarte sobre el mejor modo en que contribuir con nosotros y podrás conocer nuestro equipo.
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Fork en GitHub
                </div>

                <div class="dissap" style="margin-left: 50px">
                Si conoces GitHub, el modo en que más directamente puedes ayudarnos es haciendo una copia personal (<code>fork</code>) del repositorio <a href="https://github.com/mathifold/mathifold" target="_blank">https://github.com/mathifold/mathifold</a> desde el cual construir y enviar contribuciones.<br><br>

                Si no stás familiarizado con GitHub, te aconsejamos hacer el curso de <a href="https://www.udacity.com/course/how-to-use-git-and-github--ud775" target="_blank">Git/GitHub en Udacity</a>. ¡Te encantará!
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Otros modos de colaborar
                </div>

                <div class="dissap" style="margin-left: 50px">
                También hay otros modos de colaborar que no involucran directamente el código o la programación: asesoría pedagógica, diseño, difusión... ¡cualquier idea es bien recibida!
                </div>
            </div>
        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        Palabras clave
        </div>

        <div class="dissap" style="margin-left: 50px">

            <div>
                <div class="bcgreen boxdissap">
                GitHub
                </div>

                <div class="dissap" style="margin-left: 50px">
                El material con el que se construye la página web está alojado en el repositorio <b>mathifold/mathifold</b> en <code>GitHub</code>: <a href="https://github.com/mathifold/mathifold" target="_blank">https://github.com/mathifold/mathifold</a>. De este modo, todo el contenido es de libre acceso. <code>GitHub</code> también ofrece una apropiada plataforma para gestionar las distintas contribuciones.
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                jekyll
                </div>

                <div class="dissap" style="margin-left: 50px">
                Mathifold se construye con el generador de páginas web estáticas <a href="https://jekyllrb.com/" target="_blank"><code>jekyll</code></a>
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                MathJax
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="http://cdn.mathjax.org/" target="_blank"><code>MathJax</code></a> permite insertar fórmulas <code>LaTeX</code> dentro de la página web
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                SageMath
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="https://www.sagemath.org/" target="_blank"><code>SageMath</code></a> ofrece un lenguaje apropiado con el que hacer multitud de applets de matemáticas
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Geogebra
                </div>

                <div class="dissap" style="margin-left: 50px">

                <a href="https://www.geogebra.org" target="_blank"><code>Geogebra</code></a> está siendo utilizado en la construcción de algunos applets, generalmente de geometría plana y tridimensional.
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                IPE Drawing Editor
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="http://ipe.otfried.org/" target="_blank"><code>IPE Drawing Editor</code></a> es el software con el que se hacen la mayoría de los dibujos.
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Blender
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="https://www.blender.org" target="_blank"><code>Blender</code></a> permite el renderizado de animaciones matemáticas.
                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        La creación de nuevos posts
        </div>

        <div class="dissap" style="margin-left: 50px">

        La mayor parte del trabajo en la realización de la página web es la creación de nuevos posts, los "paquetes de conocimiento"

            <div>
                <div class="bcgreen boxdissap">
                ¿Dónde se encuentran?
                </div>

                <div class="dissap" style="margin-left: 50px">
                Los posts son archivos <code>.md</code> (lenguaje <code>markdown</code>), y deben colocarse en la carpeta <code>_posts</code> dentro del idioma correspondiente con el siguiente formato: <code>yyyy-mm-dd- ....... .md</code>. Dentro de cada capítulo, <code>jekyll</code> ordena los posts lexicográficamente, por lo que en ocasiones puede ser necesario hacer referencia a una fecha de creación fictícia en la creación de post.
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Encabezados
                </div>

                <div class="dissap" style="margin-left: 50px">
                    Cada post cuenta con un encabezado, que es la "ficha técnica" del post. Ésta consta de

                    <ul>
                        <li><code>title</code>: Título del post</li>
                        <li><code>lang</code> y <code>category</code>: en ambos el código del idioma del post</li>
                        <li><code>permalink</code>: <code>código-de-idioma/ident</code></li>
                        <li><code>ident</code>: un identificador que debe ser distinto para cada post y que intente sintetizar el contenido de éste. Suele comenzar con el tipo de post</li>
                        <li><code>parent</code>: el identificador del capítulo al cual pertenece, según <code>_data/nav.yml</code></li>
                        <li><code>kind</code>: el código de tipo de post</li>
                        <li><code>mathjax</code> y <code>sage</code>: <code>true</code> o <code>false</code> según si la página necesita utilizar <code>mathjax</code> o <code>sage</code></li>
                        <li><code>geogebratube</code>: en caso de embeber un applet de Geogebratube, indicar el número identificativo</li>
                        <li><code>layout</code> y <code>type</code>: se dejan con <code>post</code></li>
                    </ul>
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Contenido
                </div>

                <div class="dissap" style="margin-left: 50px">
                El contenido se escribe en <code>markdown</code>, y puede incluir <code>mathjax</code> u otros complementos.<br>

                Se puede enlazar a otros posts incluyendo<br>

                {% raw %}

                <code>{% cite ident %}</code>

                {% endraw %}<br>

                y se pueden incluir imágenes mediante <br>

                {% raw %}

                <code>{% resource name.ext %}</code>

                {% endraw %}<br>

                (ver la sección <code>_plugins</code> abajo para más información)

                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        Los archivos del repositorio
        </div>

        <div class="dissap" style="margin-left: 50px">

        Todas las carpetas del repositorio <code>mathifold/mathifold</code> contribuyen a la construcción de la página web:

            <div>
                <div class="bcgreen boxdissap">
                <code>_data</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Esta carpeta contiene archivos con información relevante, generalmente en forma de listas o diccionarios

                <ul>
                    <li>
                        <code>languages.yml</code>: Describe la lista de idiomas que soporta la página
                    </li>
                    <li>
                        <code>nav.yml</code>: Describe, por medio de diccionarios anidados, la estructura arbórea de la página en sus tres primeros órdenes: <em>Temas</em>, <em>Asignaturas</em> y <em>Capítulos</em>. Cada item debe tener un identificador <code>ident</code>, una traducción en cada uno de los idiomas listados en <code>languages.yml</code> y, para los dos primeros, un subdiccionario <code>children</code>.
                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_includes</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Cada archivo de esta carpeta contiene un fragmento de código que se repite en todas las páginas creadas

                <ul>
                    <li>
                        <code>footer.html</code> contiene el pie de página, que incluye los botones informativos
                    </li>
                    <li>
                        <code>head.html</code> contiene parte del <code>head</code> previo a <code>body</code>, donde se cargan las hojas de estilo y los distintos scripts, que pueden variar de página a página (<code>mathjax</code>, <code>sage</code>, <code>geogebra</code>)
                    </li>
                    <li>
                        <code>header.html</code> contiene el encabezado: los enlaces a niveles superiores a la izquierda, el buscador y los idiomas a la derecha
                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_layouts</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Cada layout describe el contenido y diseño de cada página. <code>default</code> es el contenido estándar del cual están después las especificaciones <code>home</code>, <code>topic</code>, <code>subject</code>, <code>chapter</code>, <code>post</code> y <code>search</code>.

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_plugins</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Hay dos tipos de plugins implementados, que podemos llamar <em>generadores</em> y <em>funcionales</em>

                <ul>
                    <li>
                        Los plugins generadores son <code>generate_home.rb</code>, <code>generate_topic.rb</code>, <code>generate_subject.rb</code> <code>generate_chapter.rb</code> y <code>generate_search.rb</code>, que generan las páginas descritas por <code>_data/nav.yml</code> (junto con la página de búsqueda), una vez por cada idioma
                    </li>
                    <li>
                        Los plugins funcionales son <code>cite.rb</code> y <code>resource.rb</code>, e implementan distintas funciones que pueden ser ejecutadas al redactar un post. Las funciones implementadas son<br><br>

                        {% raw %}

                        <code>{% cite ident %}</code>

                        {% endraw %}<br><br>

                        que enlaza al post del <code>ident</code> correspondiente (del mismo idioma, si lo hay) y <br><br>

                        {% raw %}

                        <code>{% resource name.ext %}</code>

                        {% endraw %}<br><br>

                        que busca la imagen <code>name.ext</code> dentro de la carpeta <code>/images/images</code>, la coloca e inserta un enlace de descarga de la fuente si se encuentra un archivo <code>name</code> (con distinta extensión) en la carpeta <code>/images/codes</code>

                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_posts</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Contiene los posts, cuya estructura se ha descrito anteriormente. Están divididos en carpetas según el idioma, pero esta separación es sólo para la logística de traducción, pues esta ordenación es indistinta para <code>jekyll</code>, que ordena todos los posts en <code>_posts</code> de acuerdo con la información de sus encabezados.

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_site</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Este es el directorio en el que <code>jekyll</code> guarda la página web estática generada que después se sube al servidor. En principio, en esta carpeta no se hacen modificaciones directamente

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>css</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Contiene las hojas de estilo. <code>custom.css</code> es la hoja que genuinamente se encarga de la apariencia de la página, mientras que <code>subject_images.css</code>, <code>topic_images.css</code> y <code>symb.css</code> tratan la asignación de imágenes representativas y deberían poderse implementar con cierto código.

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>images</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Contiene las imágenes de toda la página web. Las carpetas <code>topics</code>, <code>subjects</code>, <code>symb</code> y <code>others</code> contienen las imágenes exteriores al contenido de los posts. Las carpetas <code>images</code> y <code>codes</code> contienen las imágenes que se utilizarán en los posts (preferiblemente en formato SVG) junto con sus códigos fuente, que se incluyen en la página mediante el plugin <code>resource</code>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>js</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Contiene los archivos de script. <code>lunr.min.js</code> y <code>search.js</code> implementan la búsqueda de posts en páginas generadas con <code>jekyll</code> usando <a href="http://jekyll.tips/jekyll-casts/jekyll-search-using-lunr-js/" target="_blank"><code>lunr.js</code></a>. <code>script.js</code> almacena el resto de script.

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>plus</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Contiene los archivos de la información contenida en los botones de la parte inferior izquierda: <em>Sobre Mathifold</em>, <em>Manual</em> y <em>Colabora</em> en distintos idiomas

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>templates</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Varias plantillas que incorporan ciertos scripts (<code>mathjax</code> y <code>sage</code>) con los que realizar pruebas de código sin necesidad de correr <code>jekyll</code>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>xtras</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Cualquier otro material relacionado con la construcción de Mathifold que se quiera guardar

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                otros archivos
                </div>

                <div class="dissap" style="margin-left: 50px">
                Fuera de las carpetas anteriores se encuentran los archivos <code>_config.yml</code>, <code>404.md</code>, <code>app.yaml</code>, <code>favicon.ico</code>, <code>index.html</code>, <code>LICENSE.txt</code> y <code>README.md</code>

                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        Tareas y retos
        </div>

        <div class="dissap" style="margin-left: 50px">

        He aquí un pequeño listado de implementaciones que se quieren llevar a cabo en Mathifold y para los cuales se requiere de colaboradores entusiastas y experimentados

            <div>
                <div class="bcgreen boxdissap">
                Cuentas
                </div>

                <div class="dissap" style="margin-left: 50px">
                Creación de cuentas personales, en las que cada usuario pueda personalizar su estudio de las matemáticas dentro de Mathifold
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                App
                </div>

                <div class="dissap" style="margin-left: 50px">
                Asociada a la página web, la creación de una aplicación (en <code>Android</code> y <code>iOS</code>) que permita y adapte el uso de Mathifold en tablets y dispositivos móviles, de tal modo que en un futuro cualquier usuario pueda tener en su dispositivo algo similar a la imagen

                {% resource mathifold_app.png %}

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Traducción
                </div>

                <div class="dissap" style="margin-left: 50px">

                Traducción a todos los idiomas posibles, especialmente aquellos de más uso, y comenzando por aquellos contenidos más estables dentro de la página

                </div>
            </div>

        </div>
    </div>


</div>

