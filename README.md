# Proyecto Coder

**Alumnos:** Maria Florencia Di Primo, Pablo Zorrilla, Marcos Perafan

## Pasos para abrir el proyecto
1. Descargar el repositorio y abrir la carpeta con Visual Studio Code
2. En la terminal, posicionarse en la carpeta del proyecto y utilizar los siguientes comandos: `python manage.py runserver`
3. Navegar hacia **http://localhost:8000/tienda

> En la página de inicio se puede acceder a las distintas categorías (Remeras, Pantalones y Camisas) desde la barra de navegación o desde el botón de cada una en el carrousel.

### Modelos y rutas de navegación
Cada categoría de producto tiene una página donde se visualizan todos los productos de ese modelo/clase. 
> Por ejemplo, la clase Remeras tiene una vista en http://localhost:8000/tienda/remeras donde se pueden visualizar todos los productos

En cada vista, se puede acceder al buscador, que busca productos por marca, o crear productos, a través del botón debajo de las tarjetas de producto que lo indica.

 - El botón **Buscar Remeras** lleva a la vista http://localhost:8000/tienda/buscar-remera, por ejemplo.
 - El botón **+ Crear Remeras** lleva a la vista http://localhost:8000/tienda/crear-remera
