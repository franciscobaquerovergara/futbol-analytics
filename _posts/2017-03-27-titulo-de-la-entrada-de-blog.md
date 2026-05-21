---
layout: post
title: "Querido José Néstor"
date: 2017-03-27
excerpt: "Este es un extracto de una entrada de marcador de posición. Haz clic en el enlace Editar para modificarla o eliminarla, o bien crea una entrada nueva."
---

Estimado José:

Le dirijo a manera de carta la primera entrada de mi blog. Era un proyecto que venía gestando en mi cabeza desde hace bastante, alimentado por perlas como (http://www.futbolred.com/seleccion-colombia/sequia-de-los-delanteros-en-la-seleccion-colombia-el-ultimo-gol-fue-contra-ecuador+16843960) en donde brilla por su ausencia la falta absoluta de rigor científico y más específicamente estadístico. Hay otros casos en donde las cifras sin contexto tienden a desinformar (http://www.futbolred.com/seleccion-colombia/colombia-20-anos-sin-ganarle-a-ecuador-en-el-atahualpa-de-quito+16843826) pues decir que "desde hace 20 años no gana Colombia en el Atahualpa" suena mucho más dramático que  "hace 5 partidos". Además, no veo por qué sería estadísticamente significativo para un pronóstico del resultado de mañana lo que hicieron Alex Aguinaga, "El Pibe" y "El Tino" hace 20 años. Tampoco lo es un estimador basado en una muestra de 6 observaciones. Mi sueño sería lograr el rigor y la calidad de Five Thirty Eight (https://fivethirtyeight.com/), pero por el momento me conformo con darle algo más de sofisticación al análisis de cifras en el fútbol colombiano.  Como bien nos lo mostró la fantástica Moneyball , el poder de las cifras puede ayudar mucho a entender el deporte.

## El modelo

Quedan cinco fechas de la eliminatoria, con cinco partidos en cada una de ellas. A cada uno de los partidos le asigno SUBJETIVAMENTE Y A MI CRITERIO las probabilidades de que gane el local, el visitante o de que haya un empate. Esto, por supuesto, es más que discutible y acogeré con gusto cualquier observación al respecto, pero creo haber asignado probabilidades sensatas a cada uno de los resultados. Con mucho más tiempo, podría también buscar una forma menos arbitraria de estimar estas probabilidades con base en un modelo estadístico. Espero profundizar este aspecto en futuras publicaciones.

Mis supuestos son los siguientes:

![Probabilidades eliminatorias](https://patcheau.wordpress.com/wp-content/uploads/2017/03/probabilidades-eliminatorias.jpg?w=476)

Con base en estas probabilidades genero aleatoriamente 16,384 escenarios, haciendo el supuesto -FUERTE Y DISCUTIBLE- que todos los partidos son eventos independientes y que la probabilidad de cada uno de los resultados no está condicionada por el resultado de otros partidos. Nótese que cada uno de estos 25 partidos tiene tres resultados posibles (gana visitante, gana local o empate) por lo que hay ![3 a la 25](https://patcheau.wordpress.com/wp-content/uploads/2017/03/3-a-la-25.jpg)tablas de posiciones finales posibles (que incluyen escenarios en donde Venezuela y Bolivia ganan y Brasil y Uruguay pierden todos los partidos restantes).

Con estos supuestos, es perfectamente posible que haya empate en puntos. Como criterio de desempate, uso la diferencia de gol actual. Nuevamente, como todos los supuestos anteriores, esto es más que discutible y podría perfeccionarse.

## Los resultados

Al correr las simulaciones descritas en el párrafo anterior, obtengo la siguiente proyección final de puntos para cada uno de los equipos:

|
 Equipo |
 Proyección final puntos |

|
 Brasil |
 38,79 |

|
 Uruguay |
 31,55 |

|
 Argentina |
 29,96 |

|
 Colombia |
 28,37 |

|
 Ecuador |
 27,35 |

|
 Chile |
 28,21 |

|
 Paraguay |
 24,04 |

|
 Perú |
 22,03 |

|
 Bolivia |
 12,07 |

|
 Venezuela |
 9,86 |

Según lo anterior, clasificarían Brasil, Uruguay, Argentina y Colombia directamente y Chile iría a repechaje. Sin embargo, no hay suficiente evidencia estadística como para afirmar que los totales de puntos de Chile, Ecuador y Colombia son significativamente distintos, por lo que habría lo que en las encuestas electorales llaman los comentaristas políticos "un empate técnico".

## ¿Qué pasa si Colombia le gana a Ecuador?

Como mi modelo anterior sugiere que los hinchas de Ecuador, Chile y Colombia vamos a estar al borde de un infarto hasta el final de la eliminatoria, quise también averiguar cómo se ven las proyecciones suponiendo que Colombia le gana a Ecuador y dejando el resto de supuestos igual. Este es el resultado:

|
 Equipo |
 Proyección final puntos |

|
 Brasil |
 38,79 |

|
 Uruguay |
 31,58 |

|
 Argentina |
 29,92 |

|
 Colombia |
 30,59 |

|
 Ecuador |
 25,35 |

|
 Chile |
 28,25 |

|
 Paraguay |
 23,99 |

|
 Perú |
 21,99 |

|
 Bolivia |
 12,03 |

|
 Venezuela |
 9,86 |

En este escenario, Colombia terminaría tercera, dejando a Ecuador con muy pocas opciones de pelear la clasificación.

## ¿Qué pasa si Ecuador le gana a Colombia?

De la misma forma, incluyo dentro de los supuestos que Ecuador le gana a Colombia, dejando todo lo demás igual. Así se ven las proyecciones en este caso:

|
 Equipo |
 Proyección final puntos |

|
 Brasil |
 38,77 |

|
 Uruguay |
 31,52 |

|
 Argentina |
 29,97 |

|
 Colombia |
 27,56 |

|
 Ecuador |
 28,29 |

|
 Chile |
 28,18 |

|
 Paraguay |
 24,01 |

|
 Perú |
 22,02 |

|
 Bolivia |
 12,02 |

|
 Venezuela |
 9,87 |

En este caso, al igual que en las proyecciones originales, no hay evidencia estadística suficiente para afirmar que los totales de puntos de Chile, Ecuador y Colombia son distintos.

En resumen, querido José, puede permitirse una derrota mañana en el Atahualpa pero esto reduciría su margen de maniobra sustancialmente. En cambio, una victoria lo dejaría ya pensando en Rusia.

Espero que esta información sea de utilidad.

Saludos,

Patcheau

PD: Completamente de acuerdo con esta columna: https://www.publimetro.co/co/columnas/2017/03/27/invitacion-publica-andrea-guerrero.html. En este caso no hay duda: es impresentable que Pablo Armero esté en la Selección.