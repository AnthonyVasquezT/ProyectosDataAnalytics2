# ProyectosDataAnalytics2
Desarrollo de proyecto que abarca el análisis inmobiliario en Iowa
Este dashboard en Power BI analiza el comportamiento de ventas inmobiliarias a partir de variables de la vivienda, su ubicación, su calidad constructiva y el periodo de venta.
## Objetivo del proyecto
Explorar cómo diferentes características de una propiedad influyen en su precio de venta y en el comportamiento general del mercado inmobiliario, con el fin de identificar patrones útiles para la toma de decisiones.
## Contexto del negocio
En el sector inmobiliario, el precio de una vivienda no depende solo del tamaño o la ubicación. También influyen factores como:
calidad general de la construcción,
tipo de vivienda,
estado de remodelación,
presencia de garaje,
área habitable,
barrio o vecindario,
condición de venta y fecha de transacción.
Este proyecto busca transformar ese conjunto de datos en información visual clara y útil para análisis de negocio.
Dataset
El proyecto se basa en un dataset de viviendas de Ames, Iowa, con múltiples atributos estructurales y contextuales de cada propiedad. Entre las variables utilizadas destacan:
`SalePrice`
`LotArea`
`GrLivArea`
`OverallQual`
`OverallCond`
`YearBuilt`
`YearRemodAdd`
`Neighborhood`
`HouseStyle`
`BldgType`
`GarageCars`
`TotalBsmtSF`
`KitchenQual`
`YrSold`
`SaleType`
`SaleCondition`
## KPIs principales
El dashboard incluye indicadores como:
precio promedio de venta,
precio mínimo de venta,
precio máximo de venta,
cantidad de viviendas vendidas,
área promedio habitable,
promedio de precio de venta por año,
objetivos de venta mensual y anual.
## Páginas del reporte
### 1. Análisis Ventas
Página principal con una visión ejecutiva del comportamiento general del mercado.  
Incluye tarjetas, KPI, medidor, gráficos de columnas, línea, área y gráfico combinado para revisar evolución, distribución y objetivos.
### 2. Análisis Ventas 2
Página enfocada en segmentación y comparación de variables.  
Permite analizar el peso de cada barrio, la relación entre calidad y precio, la distribución por tipo de vivienda y el desempeño anual.
### 3. Análisis Ventas 3
Página orientada a correlaciones y comportamiento multivariable.  
Contiene un gráfico de dispersión y un gráfico de bandas para identificar relaciones entre área de lote, precio de venta y otras dimensiones relevantes.
## Hallazgos que permite explorar
Este reporte ayuda a responder preguntas como:
¿Qué barrios concentran mayor valor de venta?
¿La calidad general de la casa impacta el precio?
¿Las viviendas más amplias tienden a venderse a mejor precio?
¿Cómo varía el comportamiento de ventas por año?
¿Qué tipo de vivienda aparece con mayor frecuencia?
¿Qué relación existe entre área habitable y precio de venta?
## Herramientas utilizadas
- Power BI
- Power Query
- DAX
- Modelado de datos
- Visualización de datos
## Estructura del repositorio
```bash
├── README.md
├── Analisis Inmobiliaria.pbix
└── descripción_dataset.txt
```
## Enfoque técnico
Durante el desarrollo del proyecto se trabajó con:
- limpieza y preparación de datos,
- análisis exploratorio,
- modelado para visualización,
- construcción de medidas y objetivos,
- diseño de dashboard orientado a negocio.
## Perfil del proyecto
Este proyecto está diseñado para reforzar competencias típicas de un practicante de analista de datos, como:
- interpretación de datos,
- análisis de indicadores,
- visualización ejecutiva,
- identificación de patrones,
comunicación de hallazgos,
soporte a decisiones basadas en datos.
