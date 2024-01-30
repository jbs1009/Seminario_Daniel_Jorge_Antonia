### Seminario_Practica_Daniel-Jorge-Antonia
# Proyecto de investigación y análisis estadístico sobre relación entre sedentarismo y uso de audífonos y/o gafas.
![escudo_ubu_blanco](https://github.com/jbs1009/Seminario_Daniel_Jorge_Antonia/assets/144683429/bd62233a-f5a1-4102-81a7-9735eb3ac68d)

## Autores: Antonia Añazco, Jorge Bermejo, Daniel Marrón


En este repositorio de GitHub se presenta un trabajo en el que se analiza la posible influencia de un estilo de vida sedentario en el desarrollo de problemas de tipo visual y/o auditivo, extrapolados a partir de estadísticas reales extraídas de la base de datos oficial de datos del gobierno de España acerca de utilización de, respectivamente, gafas y/o audífono. El análisis estadístico consecuente ha sido llevado a cabo con el lenguaje de programación R, en particular, utilizando el software de R Studio como entorno para dicho objetivo. Además de funciones disponibles en R de base, se han hecho uso, para ello, de las siguientes librerías:
- library(tidyjson)
- library(rjson)
- library(tidyverse)
- library(readr)
- library(readxl)
- library(dplyr)
- library(ggplot2)
- library(tidyr)
- library(ggborderline)
- library(ggdark)
  
Todo el código, metodología, resultados, conclusiones del estudio... están disponibles en este repositorio de GitHub.

# Introducción 

El sedentarismo representa un serio problema para la salud pública, especialmente en Occidente. 

Algunos efectos son: 

Hipertensión 

Diabetes tipo II 

Obesidad 

Ahora bien, ¿alguna vez os habéis planteado cómo afecta al sedentarismo a otros aspectos acerca de nuestra salud no tan obvios? 

En el siguiente trabajo vamos a tratar de encontrar, o en su defecto descartar, la existencia de una correlación directa entre un estilo de vida sedentario y el desarrollo de problemas de visión y/o auditivos valiéndonos para ello de sendos estudios expuestos más adelante acerca de la distribución de dichos problemas y el estilo de vida a lo largo del territorio español teniendo además en cuenta otros factores como edad o sexo. 


# Objetivos: 

1 – Estudiar la relación entre el sedentarismo y el uso de audífonos en funcion de los grupos de edad 

2 – Estudiar la relación entre el sedentarismo y el uso de audífonos según el sexo 

3 – Estudiar la relación entre el sedentarismo y el uso de gafas en función de los grupos de edad 

4 – Estudiar la relación entre el sedentarismo y el uso de gafas según el sexo 
