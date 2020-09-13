
# TFG Aprendizaje Automático en el sector hotelero

* Alumno: Don Alien Embarec Riadi <alu0101035406@ull.edu.es>
* Director del proyecto: Don Pedro Antonio Toledo Delgado <petode@ull.edu.es>
* Curso: 2019/2020
* Institución: Universidad de La Laguna, Escuela Superior de Ingeniería y Tecnología, Santa Cruz de Tenerife, España.
* Titulación: Grado en Ingeniería Informática

## Sinopsis

El objetivo de este trabajo ha sido estudiar el fenómeno de la ocupación en
la industria hotelera. Concretamente, disponemos de dos fuentes de datos
[1], representativas de la actividad de reservas en dos hoteles ubicados en
Portugal. Esta información viene complementada con una serie de variables
adicionales que ayudan a entender cómo varía la demanda en los dos
hoteles.
La información disponible, pues, cubre información de reservas,
cancelaciones, edades de los clientes, tarifa diaria abonada por el
alojamiento, categoría de habitaciones contratadas, etc.

El objetivo de este proyecto es, aprovechando las herramientas del
Aprendizaje Automático, estudiar varios problemas comunes de la industria,
como predecir el precio diario de alojamiento dadas unas variables que
influyen como la antelación, el número de noches contratadas, la probabilidad
de cancelación de una reserva, entre otras.

Otra de las metas de este proyecto es crear un modelo que prediga las
reservas donde es más plausible la cancelación. El repositorio de datos
cuenta con una variable is_canceled que indica si la reserva ha sido
cancelada o no.

Esta variable, cotejada con otros datos de los que depende, como los
recargos aplicados a algunas habitaciones, las peticiones especiales de los
clientes, el efecto de las reservas hechas con mucha antelación, entre otros
factores, puede contribuir a construir un modelo clasificador con un alto grado
de fiabilidad, que dado un conjunto de datos de entrada, etiquete los registros
más propensos a cambios y anulaciones.

**Palabras clave**: predicción precio alojamiento, cancelaciones reservas, regresión,
clasificación, ciencia de datos, aprendizaje automático, aprendizaje supervisado,
tarifa diaria de alojamiento.

[1] N. Antonio, A. de Almeida y L. Nunes, «Hotel booking demand datasets,»
Science Direct, vol. 22, nº ISSN 2352-3409, pp. 41-49, 2019. 