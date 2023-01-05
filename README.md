# <h1 align=center> **PROYECTO INDIVIDUAL Nº3** </h1>

## **Introducción al proyecto.**
El objetivo de este proyecto es realizar un analisis integral del sistema que brinda acceso a internet en Argentina. Para hacerlo contamos con un conjunto de datos que fueron descargados de la pagina Enacon por medio de un conjunto de archivos en formato .csv.

#### **Analisis Exploratorio de Datos (EDA)**

Lo primero que cabe mencionar es que nuestros datos provienen de dieciseis archivos diferentes y se encuentran disponibles en la carpeta Datasets. Precisamente la diversificación que existe de la información contenida en los diferentes datasets fue el primer reto con el que nos encontramos. Para superarlo se procedió a hacer un exámen individual de cada uno ellos y, dado el breve tiempo que disponemos para la realización del presente trabajo, se procedió a normalizar los datos también en esta instancia.

Lo relativo al analisis exploratorio  lo podemos encontrar en el archivo EDA.ipynb. Se eligió utilizar Jupyter Notebook por que nos permitió relizar un analisis mas sencillo y segmentado.

El primer paso, luego de convertir los achivos a formato dataframe, fue analizar cada uno por separado. Se concluyó que los archivos podían clasificarse en base a su tamaño y contenido en tres grandes grupos, los relativos a la nación, a la provincia y a las localidades.

También, se buscaron duplicados, valores faltantes, errores de carga y en los tipos de los datos, haciendo las correcciones que fueran necesarias.

Por último, teniendo en cuenta los Kpis escogidos se concatenaron los dataframe para realizar dos archivos .csv uno provincial y otro nacional. Solo se incluyeron los que contenían información relativa a los accesos de internet por hogares, velocidad de bajada de datos, tecnologías e ingresos. 


#### **Creación del dashborad**

Por último, se escogió Power By como la opción ideal para la realización del dashboard debido a su simpleza, estética y la posibilidad de poder realizar gráficos interactivos sobre las bases de datos que le son suministradas.

El mismo cuenta con una portada y cuatro paginas mas. En cada una de ellas se desarrolla los kpis propuestos facilitando una amplía gama de material visual que permite la fácil comprensión de la información solicitada por nuestro cliente.

Asi las cosas, podremos conocer como se distribuye los accesos de internet cada 100 habitantes sobre el territorio nacional , cual es la composición y la media de la velocidad de bajada en el sistema de dsitribución de internet argentino y en consecuencia, ¿si nuestro cliente cuenta con un servicio competitivo?, cuales son las tecnologías imperantes en sector y los ingresos y posibilidades que brinda este negocio en nuestro país. Además, cabe destacar que no se trata de un análisis estáctico, sino que por el contrario nos permite ver la evolución de todos los aspectos mencionados desde el 2014 a la fecha. 

## **Herramientas utilizadas.**

* Vs Code.
* Python( pandas, numpy).
* Jupyter Notebook.
* Power By


