Aquí encontrarás la implementación de una prueba técnica que utiliza el lenguaje de programación Go para cargar datos en ZincSearch y luego visualizarlos mediante Vue.js.

<p>La base de datos necesaria se puede obtener a través del siguiente enlace: <a href="http://www.cs.cmu.edu/~enron/enron_mail_20110402.tgz">Enron Mail Dataset</a>.</p>

<h2>Estructura del Repositorio</h2>

<ul>
    <li><strong>/backend:</strong> Contiene el código fuente del backend.</li>
    <ul>
        <li><strong>/Indexer:</strong> El código para cargar la base de datos en ZincSearch.</li>
        <li><strong>/Api_code:</strong> El código de la API utilizando chi.</li>
    </ul>
    <li><strong>/frontend:</strong> Aquí encontrarás el código fuente del frontend implementado con Vue.js 3.</li>
</ul>

<h2>Configuración y Ejecución</h2>

<h3>Carga de la Base de Datos en ZincSearch</h3>

<ol>
    <li>Ve a la carpeta <code>backend/Indexer</code>.</li>
    <li>Abre el archivo <code>main.go</code>.</li>
    <li>Cambia la ruta de la base de datos en la constante <code>pathDataBase</code> (línea 22) con la ubicación de tus datos descargados.</li>
    <li>Ejecuta el archivo para cargar la base de datos en ZincSearch.</li>
</ol>

<h3>Ejecución de la API</h3>

<ol>
    <li>Navega a la carpeta <code>backend/Api_code</code>.</li>
    <li>Abre el archivo <code>api.go</code>.</li>
    <li>Inicia la API ejecutando el archivo.</li>
</ol>



