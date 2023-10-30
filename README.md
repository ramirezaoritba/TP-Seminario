# TP-Seminario
Contenido del TP de SEminario ITBA

Obtetivos
---------
# tomar información de distintas fuentes y generar métricas y modelos predictivos
# El resultado debe ser guardado en postgres o parquet
# crear visualizaciones para ilustrar el análisis y los datos

Se tomaron 2 fuentes, una que contiene las reservas hoteleras, y otro que contiene los salarios básicos, publicados en el escalafón bancario público, desde enero 2021, únicamente en algunos meses con incremento. Para los meses que no existen en la segunda tabla (salarios), se toma el añó y mes inmediatamente anterior.
Se crearon dos visualizaciones
Se utilizó un árbol como algoritmo. Para la semilla de sepatación entre Train y Test, utilicé mi número de documento.
Se guardó la salida en un archivo parquet
