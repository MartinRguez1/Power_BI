# VENTAS SUPERSTORE

## Contexto

¿Recuerdas los datos de ventas que analizaste en el módulo de Tableau? Bueno, volveremos a trabajar con ellos pero, desde un punto de vista distinto. Recordemos que en
la clase de Power BI aprendimos que un dashboard debe ser una experiencia para el cliente. Donde el diseño, el número de visualizaciones, el tipo de visualización, las
imágenes, los filtros, y los botones deben tener un propósito… ¡Conocer los datos!

## Objetivo

Crear un dashboard de ventas en **Power BI Desktop** utilizando el archivo _"Sample - Superstore - Orders Only.csv"_.
  
  El archivo contiene datos de venta donde algunas columnas clave son:
    
    ● Category y Sub-category- Categoría y subcategoría del producto.
    ● Country/Region y Estado - País y Estado de venta.
    ● Segment - Segmento del cliente.

## Desarollo de la actividad

1. Se importa la base de datos _"Sample - Superstore - Orders Only.csv"_ en __Power BI__.
2. Se crea una columna con una Medida llamada _Ventas_ donde se calcula el monto total de la venta.
3. Se crean 3 pestañas, dos visisbles y una oculta.
   * En primer página llamada _“General”_, el usuario puede tener un vistazo general de sus ventas desde puntos de vista Sub-Categoria, por estado, por provincia, ademas 2 tarjetas donde se visualiza el monto total de la venta y las ciudades donde tenemos presencia.
   * En la segunda página llamada _“Resumen”_, se muestra un resumen por mes y año y otro por sub categoria y venta por año.
   * La página oculta llamada _“Detalle por Cliente”_, tiene el detalle de Ventas por Cliente a la cual se pueda acceder por medio de la opción de _“Obtener detalles”_, para el caso de que el cliente necesite saber quiénes son sus mejores compradores

