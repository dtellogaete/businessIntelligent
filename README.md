# Proyecto Business Intelligent
## Introducción
Existen tres fuentes de datos en una plantilla excel “Dummy-Data.xls”, la cual contiene tres hojas:
- Dummy-Data: contiene datos de Razón Social, Folio de documento de ventas, fecha y monto.
- Compra: contiene datos de la Razón Social, Folio de documento de compras, fecha y monto.
- RUT: contiene datos de las empresas: Razón social y Rut.

Se solicita la siguiente información:
- Gráfico de Ingresos debe ser en formato ($MM)
- Gráfico de Egresos ($MM)
- Gráfico Margen Bruto (Ingresos menos Egresos) ($MM)

## Proceso de transformación de datos:
En las hojas Dummy-Data y Compra, existen datos que es necesario transformar, esta actividad se realiza de manera manual en la plantilla excel y es para los formatos de fecha y monto.

## Visualización de datos

Para la visualización de los datos se utilizan dos herramientas Power BI y [Fleshdashboard](https://rmarkdown.rstudio.com/flexdashboard/) 

### Power BI

![Power BI](https://github.com/dtellogaete/businessIntelligent/blob/master/imagenes/2.PNG)

El input de los datos se realiza directamente por CSV y se proceden a realizar los gráficos.

En el siguiente link se puede acceder al dashboard en
[Power BI](https://app.powerbi.com/view?r=eyJrIjoiZjk0ZDRlMGMtZmUwYy00NTViLTk0MmYtOWNlMWY5MjJiOWQ4IiwidCI6ImExMmI3MGM5LTUzY2MtNDFmNi05Y2U2LWYwMWNiYmRlZjllMSIsImMiOjR9)

### FleshDashboard

![Power BI](https://github.com/dtellogaete/businessIntelligent/blob/master/imagenes/1.PNG)

El input de los datos se realiza a partir de una base de datos en PostgreSQL, esta base de datos se construye a partir de los CSV entregados anteriormente.

En el siguiente link se puede acceder al dashboard en
[FleshDashboard](https://danielbusiness.shinyapps.io/apps/)
