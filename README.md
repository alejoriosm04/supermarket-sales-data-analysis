<h1 align = "center">Supermarket Sales - Data Analysis</h1>

Proyecto desarrollado para una prueba técnica realizada para la ruta de Análisis de Datos de la Comunidad T.I. del [Grupo Estudiantil NOVA EAFIT](https://github.com/gruponovaeafit).


Se usó el conjunto de datos “Supermarket Sales” de la página Kaggle
relacionado con ventas del almacen Grupo Éxito.

Se buscó responder a dos preguntas importantes realizadas por el supuesto gerente del almacén para tomar correctas decisiones a partir de datos.

## Análisis Realizado

Se realizó un análisis preliminar de los datos datos y del respectivo dataset para responder correctamente los datos y saber que procedimiento seguir para obtener los resultados.

- Los datos fueron almacenados en un dataframe de `Pandas` para realizar diversas operaciones.

- Los datos fueron limpiados y se eliminaron los datos nulos. Los datos nulos se encontraban en la columna `Total` y fueron reemplzados por la suma de las columnas `Unit Price` y `Quantity`, y la multiplicación de la columna `Tax 5%`.

- Se eliminaron columnas que no aportaban información relevante para el análisis.

Las preguntas a responder fueron:

3. ¿Cuál tienda recomendaría cerrar ante una mala situación económica?
4. ¿Es viable implementar una estrategia cashless?

Para poder responder estas preguntas es necesario saber que datos podemos comparar, analizar y como podemos sacar conclusiones valiosas de estos datos.

### Pregunta 3

Para responder esta pregunta, la cual era bastante amplia, se decidió realizar un análisis frente al comportamiento de los clientes y sus compras en el almacén, y también se analizó el comportamiento financiero de cada tienda, en temas de ingresos, ganancias totales y productos vendidos.

En las diapositivas de presentación del análisis se encuentran las gráficas obtenidas con `matplotlib` y las respectivas conclusiones paso a paso del análisis.

Como principal conclusión, Éxito Wow Poblado presenta falencias. Es la mejor opción de tienda para cerrar, ya que es la que menos ingresos genera, la que menos ganancias totales tiene y la que menos productos vende. Del mismo modo, el comportamiento de clientes Miembros y No Miembros no es la más optima.

### Pregunta 4

Esta pregunta era bastante directa y tenia un punto de partida muy claro. Sin embargo, muy similar a la pregunta 3. Se realizó un análisis de los distintos métodos de pago utilizados en cada compra, y se comparó con el comportamiento de los clientes Miembros y No Miembros.

Se vió primoridal tomar en cuenta la opinión de los clientes Miembros, ya que, representan un flujo de entrada más puntual e importante que los clientes normales.

También se analizó que tanto dinero ingresó por cada método de pago. Es importante tener en cuenta el flujo de dinero representado en ingresos y ganancias para saber que tanto impacto tiene cada método de pago.

La principal conclusión respecto a esta pregunta es que es totalmente viable implementar una estrategia cashless. Ya que, el método de pago con tarjeta de crédito y débito representa más del 50% de los ingresos totales del almacén. Además, el comportamiento de los clientes Miembros es muy bueno, ya que, casi el 60% de los clientes Miembros utilizan este método de pago.

## Documentación

- En el repositorio se encuentran las respectivas librerias utilizadas para el análisis en el archivo `requirements.txt`.

- Se utilizó `Jupyter Notebook` para realizar el análisis y se encuentra en el archivo `main.ipynb`. Dentro del Notebook se encuentra el link para correr desde **Google Colab**.

- Los archivos compartidos por el líder de T.I., de guía, instrucciones y datos se encuentran en la carpeta `docs`.

- Las diapositivas utilizadas en la sustentación del análisis se encuentran en la carpeta `presentation`. Allí están a más detalle cada uno de los gráficos y conclusiones obtenidas.

## Autores

El proyecto y análisis fue desarrollado por [Alejandro Ríos](https://github.com/alejoriosm04/) con el apoyo del monitor y líder de T.I. del Grupo Estudiantil NOVA EAFIT, [Santiago Puerta](https://github.com/spuerta10/).