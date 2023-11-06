
# Dashboard Call Center Anonymous Bank

<image src="Archivos\CallCenter.jpg">


Este dashboard muestra, a través de Power BI, las operaciones del Call Center de Anonymous Bank en el año 1999.
Con tal fin, se utilizó el Dataset proporcionado por Henry dentro del bootcamp de Data Science y que formó parte de la serie de proyectos integradores del módulo Data Analytics. El mismo consta de 444.448 filas y 18 columnas.

## Objetivo

Medir los niveles de calidad de servicio, eficiencia y productividad del Call Center.

Para ello, se propone que definamos los KPIs adecuados para poder medir los objetivos propuestos, y definir nuevos niveles objetivos de manera de ofrecer esos niveles de SLA a terceras partes, o generar un nuevo servicio Premium para los clientes mas importantes del Banco, contemplando proponer mejoras en:

* Eficiencia operativa, proponiendo mejoras operativas.
* Mejorar la satisfacción del cliente, cumpliendo los SLA comprometidos.
* Brindar una herramienta para la gestión y la toma de decisiones a los managers del Call Center.

### Temas a abordar
* ¿Cuál es el nivel de servicio para los clientes Prioritarios?
* ¿Damos un mejor servicio que a los clientes normales?
* ¿Qué volumen de llamadas atendemos?
* ¿Cuáles son los cuellos de botella? ¿En qué días? ¿En qué bandas horarias?
* ¿Cómo es la eficiencia y productividad de nuestros agentes?
* ¿Hay clientes recurrentes en el uso del servicio?
* ¿Cuáles son los tipos de servicio más recurrentes?
* ¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada? Ejemplo: si quiero que mi tiempo promedio de espera sea menor a 60 segundos?
  

## ETL - Limpieza, transformación y carga de Datos

Realizamos este proceso tanto en Power BI, a través de Power Query,  como en Python para arribar al mismo resultado del dataset transformado para la futura visualización y muestreo de datos.
No realizamos un modelado sobre la el Dataset brindado dado que todo las tablas se relacionaban entre sí a traves del ID del Cliente.


## Visualización
### Portada

<image src="Archivos\Portada.jpeg">

La portada utiliza el fondo y tonalidad de Anonymous Bank, con el logo identificador de la firma y una barra de navegación que permite acceder a las distintas solicitudes de la Empresa, en base al dataset del Call Center para el año informado.


### Vista General

En esta vista elegimos la posibilidad de filtrar las llamadas, tanto por Prioridad de Cliente como por tipo de Servicio brindado, obteniendo datos básicos del dataset para poder segmentar de la mejor manera, la información que requiera Anonymous Bank.

<image src="Archivos\General.jpeg">


### Eficacia y Productividad

En este caso, accedimos a información más específica que nos permiten los datos, y rankeamos a aquellos Clientes con mayor recurrencia, a los Agentes con mayor productividad en cuanto a cantidad de llamadas atendidas, y la eficacia de los mismos respecto al tiempo promedio de resolucíon del Servicio.

<image src="Archivos\Eficacia_Productividad.jpeg">


### Llamadas Recibidas

Este análisis resulta orientado a la proyección del Servicio del Call Center.
Identificamos los cuello de Botella, y además, permite recorrer el historial de las llamadas.


<image src="Archivos\Cantidad_Llamadas.jpeg">

## CONCLUSIÓN

En conclusión, tras el análisis detallado del funcionamiento del call center de Anonymous Bank, se ha evidenciado de manera clara que la cantidad de agentes destinados a atender las llamadas no es suficiente para garantizar un servicio eficiente. La insuficiencia de personal ha llevado a tiempos de espera prolongados, frustración de los clientes y una disminución en la calidad de atención, lo que finalmente puede afectar la satisfacción del cliente y la reputación de la institución financiera. Es crucial que el banco considere aumentar su personal de call center o implementar estrategias de gestión que permitan una distribución más eficiente de las tareas para garantizar un servicio de alta calidad y la satisfacción del cliente.
En adición, es fundamental destacar que la insuficiencia de agentes en el call center no solo afecta la atención general, sino que también pone en riesgo la atención de los clientes prioritarios. Estos clientes, que pueden ser titulares de cuentas significativas o tener necesidades especiales, requieren una atención primordial y personalizada. La falta de agentes disponibles puede resultar en una atención insatisfactoria para estos clientes, lo que a su vez podría poner en peligro relaciones comerciales valiosas.
Por lo tanto, la mejora en la atención de los clientes prioritarios debería ser una prioridad para el banco. Esto puede lograrse a través de la asignación de agentes específicos para atender a esta categoría de clientes, la implementación de un sistema de priorización de llamadas o la inversión en tecnología que agilice la gestión de consultas y necesidades de clientes importantes. Al mejorar la atención de los clientes prioritarios, el banco puede fortalecer sus relaciones comerciales y mantener la satisfacción de este segmento clave de su clientela.




