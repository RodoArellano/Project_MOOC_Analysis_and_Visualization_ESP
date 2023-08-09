# Proyecto_MOOC
Análisis y visualización de datos sobre 3 diferentes empresas: Coursera, edx y Udemy.

El análisis utiliza diferentes parámetros dependiendo le empresa, algunos son idioma, nivel del curso, cantidad de subscriptores, precios, temas y mas.

## Objetivo
Brindar recomendación para la creación de un una nueva empresa de plataforma virtual (MOOC) donde al igual que las mencionadas se puedan tomar cursos y certificaciones.

## ETL de los datasets utilizados
Dichos datasets se pueden encontrar en el repositorio con los nombres: 1.'udemy_courses.csv', 2.'edx_courses.csv', 3.''coursera_ratings.zip' y 4.'coursera_courses.zip'. Y el codigo de python para los ETL también se encuentra en este repositorio en una carpeta .zip con el nombre de 'ETL_datasets_MOOC.zip'.

### EDA
Una vez conocida y normalizada la información se procedió a realizar el EDA. Para facilitar la construcción del EDA este se realizó para cada empresa por separado, obteniendo así los archivos de Jupyter Notebook siguientes: 1.'EDA_udemy_courses', 2.'EDA_edx_courses' y 3.'EDA_coursera_courses'.

# Dashboard [Power BI]
Cada EDA se utilizó como base para la creación del dashboard en PowerBI. El darshboard se encuentra con el nombre de: 'proyecto_MOOC_dashboard.pbix'. Dicho esto a continuación de presentan un par de conclusiones junto con los KPIs considerados más relevantes (Durante la presentación se darán más conclusiones y recomendaciones).

Un par de comportamientos similares en los diferentes cursos son la preferencia por precios bajos y niveles introductorios. A continuación se presentan las tendencias en forma de gráficas:

Cantidad de subscriptores vs precio:

![subs_vs_price](https://github.com/RodoArellano/Proyecto_MOOC/assets/125421658/c0a3b664-ffae-4d05-b420-afd46befe171)

Cantidad de subscriptores vs nivel:

![subs_vs_level](https://github.com/RodoArellano/Proyecto_MOOC/assets/125421658/47ddd7dc-8b2f-4ce0-86ca-a2af2ed7d3ee)

Como se mencionó en renglones anteriores el comportamiento de las gráficas presentadas es similar en todos los cursos. Es decir que los subscriptores prefieren en su mayoría los cursos con niveles introductorios y con bajo costo.

Cabe mencionar que tanto en los EDAs como en el dashboard se presentan muchas más gráficas para explicar diferentes recomendaciones, pero por efectos de presentación y eficacia, estas se deben visualizar en power BI.

### KPIs:

Los KPIs que se consideraron más relevantes son: 1.Aumento de subscriptores al año, 2.Porcentaje de cursos gratuitos al año y 3.Rating promedio al año.

![KPIs](https://github.com/RodoArellano/Proyecto_MOOC/assets/125421658/63b8c116-fe9f-402f-a0b9-6a04cfd51c91)

Los KPIs mostrados se pueden filtrar con la columna a su izquierda que contiene los años de los cuales tenemos registro de información, además tienen metas esperadas para el siguiente año una vez dicha información se registre en el dataset.

Como información extra, se presenta un WordCloud obtenido de la empresa coursera para mostrar y dar una idea de la opinion de los subscriptores sobre los cursos y certificados que se ofertan:

![Wordcloud_coursera](https://github.com/RodoArellano/Proyecto_MOOC/assets/125421658/981b0ae7-b178-4c04-8686-a806c1e6e68d)

En los archivos EDA del repositorio se pueden encontrar más visualizaciones WordCloud de diferentes empresas. Algo que tienen en común las empresas es que todas muestran palabras positivas en sus WordClouds, lo que dá a entender de manera sencilla que a los subscriptores les ah satisfecho la oferta de cursos.

Gracias y para más detalle en información favor de revisar los documentos.

