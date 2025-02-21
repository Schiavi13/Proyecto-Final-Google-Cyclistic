# Análisis de Viajes Cyclistic Junio 2023 - Mayo 2024



## Tabla de Contenido
- [Introducción](#introducción)
- [Objetivo](#objetivo)
- [Fuentes de Datos](#fuentes-de-datos)
- [Herramientas](#herramientas)
- [Análisis de Datos](#análisis-de-datos)
  - [Estadísticas Anuales](#estadísticas-anuales)
    - [Totales](#totales)
    - [Usuarios Miembros](#usuarios-miembros)
    - [Usuarios Casuales](#usuarios-casuales)
  - [Uso Anual del Servicio](#uso-anual-del-servicio)
  - [Promedio de Viajes por Día](#promedio-de-viajes-por-día)
  - [Promedio de Duración de Viajes](#promedio-de-duración-de-viajes)
- [Hallazgos](#hallazgos)
- [Recomendaciones](#recomendaciones)

## Introducción
En 2016, Cyclistic lanzó una exitosa oferta de bicicletas compartidas, que creció hasta contar con 5,824 bicicletas georreferenciadas en 692 estaciones en Chicago. El sistema permite desbloquear bicicletas en una estación y devolverlas en cualquier otra. Su estrategia de marketing se ha enfocado en el reconocimiento de marca y atraer a diversos consumidores mediante planes de precios flexibles, como pases de un solo viaje, de día completo y membresías anuales. Los analistas de Cyclistic concluyeron que los miembros anuales son más rentables que los ciclistas ocasionales, quienes usan los pases de un solo viaje o de día completo.

## Objetivo
Identificar en qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic.
## Fuentes de Datos
Los datos serán proporcionados por Motivate International Inc. en el enlace [Fuente de datos](https://divvy-tripdata.s3.amazonaws.com/index.html).
En el sitio de descarga, se buscan los archivos comprimidos con la convención de nombre “aaaamm-divvy-tripdata.zip”, cada comprimido contiene un archivo .csv y una carpeta con archivos para macOS, en este caso se usarán los .csv, cada comprimido corresponde a la información de viajes de un solo mes.

## Herramientas
- Excel - Procesamiento de datos
- BigQuery - Procesamiento de datos, análisis de datos
- Google Sheets - Análisis de datos
- Tableau - [Visualización de datos](https://public.tableau.com/app/profile/luis.mart.nez1450/viz/GooglecapstoneprojectCyclistic/Dashboard1)

## Análisis de Datos

### Estadísticas Anuales

#### Totales
![kpi_total](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_kpi_total.png)
<br/>
![bar_plot_totales](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_cantiad_total_viajes_tipo_usuario.png)
<br/>
<br/>
Aproximadamente 1/3 del total de viajes los realizaron usuarios casuales.

#### Usuarios Miembros
![kpi_miembros](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_kpi_miembros.png)

#### Usuarios Casuales
![kpi_csuales](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_kpi_casuales.png)
<br/>
<br/>
En promedio, los viajes de usuarios casuales fueron el doble de extensos que los viajes de los usuarios miembros.

### Uso Anual del Servicio
![uso_anual](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_cantidad_viajes_fecha_tipo_usuario.png)
<br/>
<br/>
El 50.9% de los viajes de los usuarios casuales se realizaron durante el verano (Norteamérica).

### Promedio de Viajes por Día
![promedio_viajes_dia](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_promedio_viajes_dia_tipo_usuario.png)
<br/>
<br/>
Los usuarios miembros utilizaron más el servicio los días martes, miércoles y jueves.
<br/>
Los usuarios casuales utilizaron más el servicio los fines de semana.

### Promedio de Duración de Viajes
![promedio_duracion_dia](https://github.com/Schiavi13/Proyecto-Final-Google-Cyclistic/blob/main/Assets/Imagenes/viz_duracion_promedio_dia_tipo_usuario.png)
<br/>
<br/>
La duración de los viajes realizados por usuarios miembros fueron más cortas que los usuarios casuales.
<br/>
La duración de los viajes de usuarios casuales aumentó significativamente los fines de semana.

## Hallazgos
- Los usuarios casuales Hacen mayor uso del servicio durante el verano y los días cercanos.
- Los usuarios casuales utilizan más el servicio los fines de semana.
- La duración de los viajes de los usuarios casuales es más extensa que la de los usuarios miembros.
- La duración de los viajes de todos los usuarios aumenta los fines de semana, en especial para los usuarios casuales.

## Recomendaciones
De acuerdo a los hallazgos encontrados en el periodo junio de 2023 - mayo de 2024 se recomiendan las siguientes acciones:
- Promocionar las suscripciones anuales en mayo con alguna oferta de descuento, aprovechando el aumento en viajes de usuarios casuales en verano.
- Aumentar ligeramente el precio de los alquileres los días sábado y domingo, apuntar a un precio que motive a los usuarios casuales a adquirir la membresía y que no desmotive el uso completo del servicio.

