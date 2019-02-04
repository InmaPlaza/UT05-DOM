# UT05-DOM

Sobre la práctica del ERP de la unidad anterior, debes utilizarla para mostrar su contenido en una página HTML utilizando el API de DOM. Para ello deberás realizar los siguientes pasos:

    1. Crear un esqueleto de página HTML sin contenido. Podrás utilizar una API como bootstrap para que tu página quede más vistosa, o utilizar una plantilla que hayas encontrado en Internet, aunque se tendrá en cuenta si haces tu propio desarrollo.

    2. Crea una función initPopulate donde puedas añadir a tu VideoSystem todos los objetos que necesite, es decir, en esta función deberás instanciar los personas, las categorías, recursos, producciones, etc, que tendrá la aplicación como carga inicial de datos, así como la relación entre ellos en el objeto de sistema. Ejecútala en el evento onload de la página. En esta ocasión ya no es necesario la función de testeo de la galería. (0,5 puntos). Obligatorio.

    3. Deberás crear diferentes funciones cuyo cometido será generar el contenido de los objetos almacenados en el ERP para mostrarlos en la página mediante el api de DOM. Las funciones populate tienen que ser las siguientes:

        a. showHomePage: se utilizará para crear la página de inicio. Esta función tiene que crear en la zona central la distribución de todas las categorías disponibles en el sistema.
        Puedes mostrar algunas producciones de cada una de las categorías para mejorar el resultado.
        Esta función tiene que ser invocada en el enlace de inicio de la página. (0,5 puntos)

        b. categoriesMenuPopulate: Tiene que crear la estructura de menú que permita navegar entre categorías. (0,5 puntos)

        c. showActors: Muestra un listado con los actores del sistema. (0,5 puntos)

        d. showDirectors: Muestra un listado con los actores del sistema. (0,5 puntos)

        e. showActor: Dado un actor muestra toda su información relacionada, incluida sus producciones. (0,5 puntos)

        f. showDirector: Dado un director, muestra toda su información relacionada, incluida sus producciones. (0,5 puntos)

        g. showProductions: Dado una categoría, director o actor, muestra el listado de sus producciones. (0,5 puntos)

        h. showProduction: Muestra la información de una producción, incluida su director y sus actores participantes. (0,5 puntos)

        i. showResource: Muestra los recursos relacionados con una producción. (0,5 puntos)
        
    4. Relaciones entre vistas. En cada una de las vistas tendrá que estar relacionada con la siguiente sin realizar una recarga de la página. (1 punto)
        a. De actores o directores a producciones.
        b. De producciones a actores o directores.
    c. Desde la página inicial a una producción o a su categoría.

El evento onload de la página, deberá ser una función que invoque a:
    • InitPopulate. Para realiazar la carga inicial de datos.
    • ShowHomePage. Para mostrar los datos en la zona central de la página.
    • CategoriesMenuPopulate. Para cargar un menú con las respectivas categorías.

Se valorará:
    1. Funcionalidad
    2. Robustez
    3. Diseño y maquetación

También se tendrá en cuenta implementación de funcionalidad extra, así como buenas prácticas con objetos.
La nota máxima de la práctica será 10 puntos.

## Version 1.0.0
 - Creacion del fichero DOM.js
 - Añadir funcionalidad al fichero DOM.js

## Version 1.0.1
 - Correcion de errores