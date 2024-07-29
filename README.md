# Adventure Works - Analisis de Ventas
[![Blue-Geometric-Technology-General-Professional-Linked-In-Banner.png](https://i.postimg.cc/WzTWnhmj/Blue-Geometric-Technology-General-Professional-Linked-In-Banner.png)](https://postimg.cc/BL7BZZww)

El propósito de este proyecto se basó en el desarrollo de un Dashboard pasando por las etapas de obtención de datos desde un archivó SQL, procesos de ETL para  asegurar la calidad de los datos y deshabilitaciones de carga para hacerlo estrellado, con el fin de obtener indicadores que logren satisfacer la necesidades de información.

## Análisis general del tablero

### Portada

<p align="center">
  <a href="https://postimg.cc/Xr6cYzQ3">
    <img src="https://i.postimg.cc/RZNPXrt3/Portada.png" alt="Portada">
  </a>
</p>

Se realizó acorde al core de la empresa con el logo de la misma y un título alusivo a lo que contiene, así mismo se colocaron botones para que se pueda navegar a través de las páginas, al encontrarse en la interfaz de Power Bi, se debe realizar un ctrl + click para poder pasar de páginas. 

### General

<p align="center">
  <a href="https://postimg.cc/d7q28Zbx">
    <img src="https://i.postimg.cc/nLm3fv0p/Mercado.png" alt="Mercado">
  </a>
</p>
<p align="justify">
Se comienza con el título y la vista de tarjetas con indicadores clave para pasar a los tacómetros que muestran indicadores del negocio el cual fue realizado a través de un parámetro de campo, esta misma funcionalidad se empleó para el gráfico de utilidades neta y bruta por categoría y subcategoría para poder visualizar dos gráficos en un solo espacio. Se destaca el mapa, el cual al igual que la gráfica de la izquierda funciona tanto con el filtro de indicadores como con el de país, en este último, se optó por trabajar con el código del país por que es el que realiza cambios en la tarjeta de cantidad de clientes; este tablero se culmina con un comparativo de la distribución de ingresos. 
</p>

### Mercado Estados Unidos

<p align="center">
  <a href="https://postimg.cc/DJN1kj89">
    <img src="https://i.postimg.cc/zvz7h45G/Mercado-USA.png" alt="Mercado USA">
  </a>
</p>
<p align="justify">
Como primera medida se aplicó un filtro a toda la página por país, para evitar tener que hacerlo en todas las gráficas, se procuró que los gráficos presentarán un tamaño similar, pero por orden de lectura las las tarjetas y la tabla se destacan ante los otros, así mismo se colocaron los filtros año y categoría de producto solicitados por el usuario y como complemento se agregó el filtro de provincia para poder acceder a la información de la tabla de manera general.  Debido a la cantidad de data de las ciudades, se estableció un filtro de T0P N por las 10 ciudades con un % COGS alto respecto a la utilidad bruta, este top varía respecto al filtro de provincia donde se muestran las ciudades de la misma con el %COGS alto. Respecto al filtro de provincia,también se deshabilitó la interacción con el gráfico de líneas de ingresos del periodo actual y anterior.
</p>

## Resultados principales y líneas futuras de análisis

### General
<p align="justify">
Se observa un aumento en los ingresos totales, respecto al periodo anterior, presentando un crecimiento de 0,17%, si bien es un número positivo, es importante analizar a través de este dashboard las oportunidades de negocio que se podrían presentar para aumentar esta cifra en los próximos periodos que se vayan a analizar. 
En cuanto a la cantidad de clientes por mercados, Canadá presenta las cifras más bajas con 1517 clientes, se recomienda implementar campañas de promoción mediante correos directos y redes sociales con el fin de captar clientes, teniendo en cuenta que este país posee la segunda tasa más alta de propiedad de bicicletas per cápita después de los países bajos. También se observa una oportunidad de negocio respecto a la ventas, ya que se estima que las personas gastan una cantidad de dinero considerable en bicicletas y equipos cada año. 
En cuanto a las categorías de producto se marca una alta diferencia tanto en la Utilidad Neta como Utilidad Bruta de bicicletas, respecto a accesorios y ropa. Por lo cual se recomienda hacer un estudio de mercado para poder confirmar la baja de ventas en estos artículos, teniendo en cuenta factores como calidad, precio y competencia, para así poder impulsar este segmento que representa importancia en el posicionamiento de la marca; además de ser necesarios para poder desempeñar la actividad de ciclismo de forma cómoda y segura. 
Respecto a los accesorios también es importante iterar si los que se están ofreciendo hasta el momento están acordes a la demanda de los usuarios y comparar los precios de los mismos con la competencia, también sería importante reforzar estrategias de fidelidad de los clientes, enfocadas en la posventa para acercar al usuario con las diferentes opciones de productos que presenta la marca. 


En cuanto al segmento de categoría de componentes, no se tiene información al respecto por lo cual se dio inicio a un proceso de iteración de la base de datos para confirmar si los datos están debidamente relacionados y cargados. 
</p>
<p align="justify">
Los argumentos anteriormente mencionados, respaldan las utilidades por subcategoría en la cual las bicicletas de carretera y montaña presentan las cifras más altas, respecto a los cascos y otros accesorios; así mismo se identificó que estos usuarios en la mayoría de ocasiones ruedan en grupo y requieren de accesorios para poder montar bicicleta con comodidad durante varias horas, por lo cual se debe analizar con el equipo de marketing cómo aumentar la venta de los mismos en estos espacios. 
Referente a la distribución de ingresos, COGS y utilidad bruta por mes, en el gráfico se puede observar que los ingresos son más altos respecto a las otras métricas, esto puede indicar un alto volumen de ventas ya que respecto al periodo anterior tuvo un incremento, referente a la utilidad bruta baja en comparación con los otros indicadores, esto se puede deber a la diferencia entre ingresos y COGS, también puede ser el resultado de una  alta competencia del mercado de bicicletas y accesorios, se debe confirmar con el área de ventas la fluctuación de precios y si estos se encuentran bajos para ser competitivos, de ser así, con el área de marketing se deberían implementar estrategias de comunicación enfocadas en la calidad del producto como sustento a un precio elevado respecto a la competencia.
</p>

### Mercado Estadounidense

<p align="justify">
En cuanto a los ingresos, se han aumentado respecto al periodo anterior, siendo una señal positiva para indicar que el mercado está creciendo y generando más ganancias; en términos generales se está progresando en la dirección correcta. 
Respecto a cantidad de clientes, es el que más aporta en comparación con otros mercados donde la compañía tiene presencia, destacándose la provincia de California como la que más ingresos aporta en sus diferentes ciudades, influyendo en el posicionamiento de la marca. Se debe prestar especial atención a las ciudades que representan ingresos bajos que ni siquiera son acordes a la compra de bicicletas, por lo cual se deben implementar estrategias segmentadas por ubicación de publicidad por redes sociales y correo directo  para poder impulsar las ventas. 
La venta de bicicletas en este mercado sigue marcando una tendencia alta, por lo cual se sugiere implementar estrategias de correo directo a las personas que compraron las mismas para promocionar accesorios y ropa con el incentivo de descuento, a fin de generar no solo ventas sino posicionamiento de marca.
Referente al  %COGS, se puede observar en el tablero a  simple vista una tendencia alta en la mayoría de las ciudades analizadas, lo cual es un indicador negativo debido a que la compañía está presentando un margen de ganancia bruto bajo, por lo cual se debe analizar y confirmar si se están presentando ineficiencias en la cadena de suministros, precios altos por parte de los proveedores, mezcla de productos o competencia intensa. 
</p>

## Líneas futuras de análisis

- Mercados con ingresos bajos respecto al líder, como proceso de identificación problemas referentes no solo a las ventas si no a las cadenas de suministro, precios altos y competencia. 

- Accesorios y ropa como complemento a la compra de bicicletas, iterar acerca de la calidad y precios de los productos respecto a la competencia para detectar oportunidades de negocio en miras de aumentar las ventas en estos segmentos.

- Implementación de campañas de fidelización de clientes para ampliar el segmento de compra de los mismos.  


