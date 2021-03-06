# Análisis de la subocupación en Argentina 1er trimestre 2021
*Por Violeta Carrera Pereyra*

## Set de datos
El análisis es realizó sobre la base de la EPH (Encuesta Permanente de Hogares) del primer trimestre del 2021 realizada por el INDEC; que se puede descargar en el [siguiente link](https://www.indec.gob.ar/indec/web/Institucional-Indec-BasesDeDatos). 
Es una base que contiene dos sets de datos distintos: los referentes al hogar y los referentes a los individuos. En este trabajo se analiza nada más la base de individuos. 
La EPH es una encuesta con preguntas referidas al mercado laboral y a las condiciones de vida de las personas y familias, y se realiza con una frecuencia trimestral desde 1974.

## Requerimientos
Para el análisis se necesita la base de datos antes señalada e importar las librerias nunpy, pandas, seaborn y matplotlib.

## Contenido del repositorio
El repositorio tiene una carpeta llamada "DATA" con la base original (tanto la referida al hogar como la individual) y la base limpia con la que se trabaja para la presentación de los datos (los tres archivos en formato .xlsx) y una carpeta llamada "IMÁGENES" con las imágenes dispuestas en este resumen. También se encuentran este archivo y la notebook con la que se trabajó para el análisis.

## Conclusiones del análisis
Respecto al cruce que se hizo de los grupos por sexo, cabe mencionar que, si bien no sería extraño que las mujeres sean las más subocupadas (por discriminación y prejuicios a la hora de contratar y por la mayor cantidad de horas que le dedican a trabajos de cuidado no remunerados por fuera del mercado laboral), desde los 90' en Argentina se viene dando un fenómeno particular: el aumento de la subocupación, y de otro tipo de situaciones de precarización, entre grupos antes excentos de estas. Con la transformación del mercado laboral y de la estructura económica que se dió en los 90', y la consecuente caída de la demanda laboral, la subocupación pasó a ser un fenómeno que atañe también a los históricos "jefes de hogar" (Beccaria, 2003).  
  
Por otro lado, el gráfico del nivel educativo es tajante: en la composición de los ocupados plenos prevalecen los niveles educativos más altos por sobre los más bajos, y en la composición de subocupados se da la situación inversa.  

![Optional Text](IMÁGENES/25-11.png)

A su vez, los subocupados tienden a ser más jóvenes que los ocupados plenos: la distribución de los subocupados es una distribución más sesgada hacia la izquierda. Esto no es casual, como Castel (1997) señala, la inserción laboral de los jóvenes es cada vez más errática y dificil: las trayectorias contemplan, en sus inicios, cada vez más situaciones de precarización.
  
Sobre ingresos creo, sobre todo, interesante el boxplot que considera el ingreso familiar (porque era predecible que las personas que trabajan menos horas iban a tener ingresos individuales más bajos). Lo interesante de analizar el ingreso familiar es ver cómo esos ingresos más bajos no pueden ser compensados en el hogar por alguna otra persona que gané (y probablemente trabaje) más. Es decir, los subocupados suelen habitar hogares pobres, qué situación se da primero es un punto que excede este análsis pero una punta para seguir pensando ineludible: ¿las personas que habitan hogares pobres tienen más probabilidades de ser subocupadas? 
  
Como se mencionó en la presentación de los datos, si les descuentan o no jubilación fue elegido como indicador proxy de si están en una relación de dependencia formal o informal. En el grupo de subocupados solamente un 13,8% está, siguiendo la línea de análisis propuesta, en relación de dependencia formal, casi la mitad en informal y (detalle interesante) 42% de los preguntados no calificaban para responder la pregunta (es decir, no eran personas que tenían la posibilidad de que en su trabajo el empleador les descontara aportes para la jubilación).  
![Optional Text](IMÁGENES/jub.png)

Esto llevó al análisis de las categorías ocupacionales, ¿quiénes son los subocupados? Si bien muchos son obreros y empleados, el 40% (número alto en comparación con los ocupados plenos) son cuentapropistas. Ya lo advertía Villareal (1985), la transformación de la estructura productiva realizada durante la última dictadura militar, y continuada en décadas posteriores, trajo aparejada un aumento de los trabajadores independientes en detrimento del sector asalariado industrial formal. Este proceso produjo, como evidencia el último cuadro, una vinculación entre el trabajo cuentapropista independiente y la precarización laboral; los trabajadores independientes trabajan a pequeña escala, con escasos recursos (y muchos menos de 35 horas semanales).











