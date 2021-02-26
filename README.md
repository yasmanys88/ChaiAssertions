# ChaiAssertions
Algunos de los temas que tratare de realizar en este repositorio: <br>
<ul>
<li>Instalar Chai desde la terminal o la interfaz de línea de comandos.</li>
<li>Ver los diferentes estilos de aseveración proporcionadas por Chai, que son <b>assert</b>, <b>expect</b> y <b>should</b>.</li>
<li>cubrire diferencias, extras y configuraciones.</li>
</ul><br>
<h2>Las interfaces de Chai se clasifican ampliamente en dos: estilos TDD y estilos BDD </h2>
<p>BDD, también conocido como lenguaje de desarrollo impulsado por el comportamiento, proporciona un lenguaje expresivo y un estilo legible, mientras que TDD, también conocido como desarrollo impulsado por pruebas, proporciona una sensación más clásica.<br>
Veamos ahora las interfaces - que son <b>expect</b>, <b>should</b> y <b>assert</b>.<br>
Los dos primeros, es decir <b>expect</b> y <b>should</b>, son estilos BDD, y <b>assert</b> es una biblioteca de afirmaciones de estilo TDD.<br>
</p>
<h2>Adición de la biblioteca de afirmaciones de Chai</h2>
<p> Ingrese el comando: <b>npm install chai -save-dev</b><br>
Esto instalará Chai en el proyecto y hará una entrada en el archivo package.json.<br>
Entonces, ya tenemos a Chai, y ahora podemos comenzar a usarlo.<br>
Tengo una carpeta de prueba en este proyecto.Para obtener las interfaces de Chai, necesitamos importar Chai al archivo de prueba, lo que se puede hacer creando una variable:<br>
<b>const chai = require('chai');</b><br>
</p>