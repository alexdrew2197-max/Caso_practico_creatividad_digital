# Reporte de Analisis - Creatividad Digital

## 1. Contexto
- **Objetivo del analisis:** Desarrollar un dataset de campañas de creatividad digital y checar cuales de ellas tienen resultados más favorables, todo esto con tal de desarrollar las habilidades necesarias para poder manegar y manipular los datos.
- **Fuente de datos:** Se obtuvieron los datos a partir de 180 campañas creadas a partir de cinco clientes, 'LumaAds', 'FrameHouse', 'PixelForge', 'NeoStudio', 'CromaLab', obteniendo datos como: el formato en que se hizo la campaña, en que plataforma se hizo, su objetivo general, presupuesto en dolares, etc.
- **Periodo analizado:** Se analizo el periodo de los meses de Enero a Junio, del año 2025.

## 2. Limpieza y preparacion
- Variables derivadas creadas:
    1. **Tasa de clicks (CTR):** Porcentaje de impresiones que resultaron en un click.
    2. **Tasa de conversion (CVR):** Porcentajes de click que terminaron en una conversion.
    3. **Costo por click (CPC):** Costo por cada click obtenido en dolares.
    4. **Costo por mil impresiones (CPM):** Costo por cada 1000 veces que se mostro el anuncio, en dolares.
    5. **Retorno sobre inversion (ROI):** Granancia neta como fraccion del costo invertido.
- Supuestos y decisiones: 
1. Se presume que, la mayoria de Tiktok, Instragram o Youtube tengan mejores estadisticas que las plataformas de Facebook o X. Se planea hacer esto obteniendo el promedio de los datos de cada una de las plataformas, verificando si nuestras presunciones son correctas.
2. Se presume que la mayoria de las campañas van a tener un ROI positivo o igual a cero (que recuperan lo invertido). Se planea hacer esto sacando el ROI de cada una de las campañas y verificando cuantas de ellas tienen un retorno mayor o igual a cero.

## 3. Hallazgos estadisticos
- **KPI 1: Hallazgos de tendencia central.** La moda nos dice que una de las plataformas más usadas fue instragam, igual con el formato de Reel siendo uno de los más creados. Sin embargo, la moda del ROI es negativa, siendo de -0.95, diciendonos que, la mayoria de las campañas pierden dinero, que en promedio, cada campaña cuesta alrededor de 1552 dolares, y que, la mayoria de las campañas solo generan un ingreso de alrededor 26 dolares.
- **KPI 2: Hallazgos de dispersion** El ROI tiene un rango de 34.37 y una desviación de 6.32, lo que nos dice que hay campañas que apenas y recuperan lo invertido, mientras que otras tienen campañas altamente exitosas.
- **KPI 3: Outliers identificados** La campaña con ID 158 tiene un CTR mucho menor que las campañas con ID 93 y 108, sin embargo, genero 84,100 dolares en ingresos, somparadas a las otras que solo generaron ingresos de 506 y 83 dolares respectivamente. Asimismo, la campaña 108 tuvo una clasificación creativa de 89, comparado a la campaña 158, sin embargo, fue la campaña que genero menos ingresos de todas.

## 4. Filtros y segmentos relevantes
- **Segmento A:** Se obtuvo que hubo 90 campañas con un ROI negativo, cuyo costo en dolares esta por encima de la mediana. 
- **Segmento B:** Se encontro que en las plataformas de Instagram y Tiktok el gasto para la campaña es mayor que la media, siendo en plataformas como X donde es más raro que se vea esto.
- **Segmento C:** Del top 10 campañas por ROI unicamente en TikTok e Instragram, Instagram es la plataforma que domina el top 10, teniendo todas ellas el objetivo de vender algo. Asimismo el formato preferido para estas campañas fue la creaacion de Story y Reels.

## 5. Graficas e interpretacion
1. **Grafica 1:**La grafica nos muestra que, un gran numero de campañas han resultado en un ROI demasiado bajo, solo siendo algunas de ellas las que han podido ser exitosas y regresar más del doble de lo invertido en ellas.
2. **Grafica 2:** La grafica nos muestra que plataformas como instagram y tiktok tuvieron casos de outliers de bajo rendimiento, mientras que plataformas como Facebook tuvieron casos de outliers positivos.
3. **Grafica 3:** La grafica nos muestra que, el contenido de reels y story, tienen un mejor CTR, comparado con otras formas de contenido. Esto significa que el contenido de reels y story es más relevante para las audiencias.
4. **Grafica 4:** La grafica nos muestra como en los dos primeros meses del 2025 se tuvieron unos ingresos mensuales positivos, sin embargo, en el 3 y 4 mes los ingresos tuvieron un pequeño declive, pero a pesar de eso, en los meses 5 y 6 se lograron recuperar los ingresos perdidos e incluso crear una ganancia mucho mayor que la de los primeros 2 meses.

## 6. Insights accionables
1. Una mejor clasificación creativa no significa que la campaña vaya a generar un mayor numero de ingresos.
2. El objetivo que tiene la campaña es importante, siendo aquellas campañas enfocadas en ventas las que mejores ROI tienen.
3. Los reels son los formatos que tienen un CTR mucho más alto que los otros formatos.

## 7. Recomendaciones
1. Los reels son los formatos más ideales para el crecimiento de una empresa, siendo uno de los formatos con menor costo y con mayores impresiones, CTR, CVR, CPC, CPM y ROI.
2. La plataforma que crea mayores ingresos y mejores oportunidades es Tiktok, que a pesar de ser uno de los segundos costos más altos, tambien es una que tiene mejores oportunidades para la creacion de ingresos.

## 8. Anexo
- Limitaciones de los datos: Los datos no especifican el tema o de que tratan las campañas, solo simplificandolas a los objetivos de 'Traffic', 'Ventas', 'Awareness' y 'Leads'. Objetivos más detallados permitiria un analisis más extenso de la base de datos.
- Siguientes pasos: Lo ideal sería crear y expandir en los objetivos que tienen las campañas de manera más detallada, por ejemplo, si el objetivo era hacer una venta, lo ideal sería definir si se vendia un servicio o un producto.