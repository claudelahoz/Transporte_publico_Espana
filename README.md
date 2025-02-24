# Análisis de Datos de Transporte Público
Power BI PostgreSQL Python Pandas Matplotlib Seaborn Scikit-learn GitHub
Este proyecto realiza un análisis exhaustivo de los datos de transporte público en España, proporcionando insights sobre patrones de viaje, retrasos, número de pasajeros. El conjunto de datos incluye información detallada sobre cada viaje, como la fecha y hora, rutas, tipos de transporte, número de pasajeros y retrasos.
Informes

Informe interactivo en Power BI

### [Dasboard Transporte Público en España](https://app.powerbi.com/links/DKmfGKumDy?ctid=5fd5460a-b425-49de-9bd0-fcd26270d30c&pbi_source=linkShare).

## Estructura del proyecto

EDA_TRANSPORTE_PUBLICO_ESPANA/


        ├── README.md
        
        ├── data
        
        │   ├── Transporte_Publico_Espana_transformado.xlsx
        
        │   └── Transporte_Publico_Espana.csv
        
        ├── notebooks
        
        │   ├── .env
        
        │   ├── 01_EDA.ipynb
        
        │   └── 02_SQL.ipynb
        
        ├── reports
        
        │   ├── Boxplot_Duracion_Viaje_Minutos.png
        
        │   ├── Boxplot_Numero_Pasajeros.png
        
        │   ├── Boxplot_Retraso_Minutos.png
        
        │   ├── Boxplot_tipo transporte.png
        
        │   ├── Cantidad_Usuarios_por_Dia_Semana.png
        
        │   ├── Cantidad_Usuarios_por_Region.png
        
        │   ├── Cantidad_Usuarios_por_Ruta.png
        
        │   ├── Cantidad_Usuarios_por_Tipo_Transporte.png
        
        │   ├── distribucion duracion del viaje y retraso por tipo de transporte.png
        
        │   ├── Distribucion_MICE_Duracion_Viaje_Minutos.png
        
        │   ├── Distribucion_MICE_Numero_Pasajeros.png
        
        │   ├── efecto_winsorizado.png
        
        │   ├── histogramas.png
        
        │   ├── Matriz de correlacion.png
        
        │   ├── numero de viajes por dia de la semana.png
        
        │   ├── Pasajeros por hora.png
        
        │   ├── Pasajeros por region.png
        
        │   ├── retraso por dia de semana y tipo de transporte.png
        
        │   ├── Rutas más frecuentes.png
        
        │   ├── Transporte_Publico_Espana.pbix

        │   └── Winsorizado.png
        
        └── scripts
        
            └── utils.py
    
## Descripción general del conjunto de datos
El conjunto de datos contiene información valiosa que puede ayudar a optimizar las operaciones de transporte público y mejorar la eficiencia. Incluye:

Fecha y hora: Registros detallados de cada viaje, permitiendo análisis de patrones temporales.
Detalles del viaje: Información sobre rutas, tipos de transporte, número de pasajeros y duración del viaje.
Retrasos: Datos sobre retrasos, permitiendo identificar áreas problemáticas.

## Análisis

Análisis de patrones de viaje: Descubre cuántos pasajeros utilizan el transporte cada día y explora si hay horas pico de uso.
Rutas más utilizadas: Analizamos los datos para determinar las rutas más populares y frecuentes.
Eficiencia y retrasos: Calculamos los tiempos promedio de viaje y retrasos para identificar áreas de mejora.
Optimización de rutas y horarios: Uso de los datos para identificar rutas con bajo rendimiento o que necesitan ajustes.

## Autor
- <ins><b>©2024 Claudia De la hoz. Todos los derechos reservados</b></ins>
