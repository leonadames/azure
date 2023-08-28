# azure
Creado por Lorena Leon:

Proyecto final bootcampo Azure desarrollado en Data Factory en Datapath para la implementación de una etl con arquitectura Bronze/Silver/Gold


Etapa Bronze: Traer del equipo local (on premise) hacía la nube (carpeta bronce en el datalake) los archivos en su estado inicial.
Etapa Silver: Pasar los registros de los archivos en la etapa bronce e iniciar la limpieza de los datos por medio de filtros y depuración de columnas no requeridas para dejarlo en un dataset intermedio en la etapa silver.
Etapa Gold: Pasar los registros de los archivos en la etapa silver y realizar la integración de los datos por medio de cruce de llaves (Joins) para generar un archivo Json final
