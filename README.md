# Estudio sobre los hábitos deportivos saludables de los españoles.
## Un análisis mediante correspondencias múltiples
### Pablo Barbero De La Orden

---
## Abstract

Los hábitos deportivos son un pilar fundamental en una vida saludable, sin embargo no existe una medición cuantificable y comparable con la que determinar la calidad de estos, visto desde un prisma de buena salud.

En este trabajo se desarrolla un indicador global que tiene como objetivo realizar una radiografía sobre los hábitos deportivos saludables de los españoles. Para ello se ha utilizado un conjunto de microdatos de la Encuesta sobre Hábitos deportivos en España realizada del 24 de marzo al 30 de abril de 2010 por el Centro de Investigaciones Sociológicas.

En ella se incluían preguntas relacionadas con el Vínculo personal con el deporte, Hábitos y prácticas deportivas, Salud y percepción de la forma física, Consumo de contenidos deportivos, Tiempo libre y su uso y Equipamiento deportivo en el hogar que corresponden con seis indicadores temáticos. A los que se les  aplica la técnica del Análisis de Correspondencias Múltiples para resumir su información y crear un indicador global.

Tras este procedimiento se concluyó que las mujeres españolas disponen de unos hábitos deportivos menos saludables en comparación a los hombres, a medida que avanza la edad se van desmejorando los hábitos deportivos saludables, cuanto mayor es el nivel de estudios de los españoles por lo general tendrá mejores hábitos deportivos. Las provincias con territorio montañoso disponen de hábitos deportivos más saludables, además que en las provincias donde no se consumen contenidos deportivos hace que los habitantes tengan menor vínculo con el deporte y por consiguiente unos peores hábitos deportivos.

#### Palabras clave

Deporte, Hábitos Deportivos, Análisis de Correspondencias Múltiples, España, Vínculo personal con el deporte, Hábitos y prácticas deportivas, Salud y percepción de la forma física, Consumo de contenidos deportivos, Tiempo libre, Equipamiento deportivo en el hogar.

---
## Datos

Este estudio ha sido elaborado en base a los datos que están disponibles de forma pública en [https://analisis.cis.es/formulario.jsp?dwld=/Microdatos/MD2833.zip].

---
## Metodología

- Construcción de 6 indicadores temáticos
- Aplicación de la técnica de Análisis de correspondencias múltiple
- Elaboración del indicador global mediante los pesos normalizados de la técnica

---
## Softwares y paquetes

Para nuestros análisis, utilizamos el paquete de Survey  (T, Analysis of Complex Survey Samples., 2004) y el paquete FactoMineR  (Lê, 2008) en R.
En cuanto a la visualización de gráficas y mapas se ha utilizado las librerías de Ggplot2  (H, 2016) y Sp  (Bivand RS, 2013).

---
## Conclusión

![Indicador_global](https://user-images.githubusercontent.com/107941870/214274688-c76d9a2b-d925-4e71-82a3-70eccec418f6.png)

![Indicador_global_provincia](https://user-images.githubusercontent.com/107941870/214274801-610393d8-cb7e-4504-b27e-2b0bb3f5ffd5.png)

