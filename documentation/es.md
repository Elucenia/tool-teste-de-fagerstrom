<!-- ELUCENIA technical documentation · teste-de-fagerstrom · es · no clinical/professional/rights approval -->

# Test de Fagerström

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/teste-de-fagerstrom)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### ¿Cuánto tiempo después de despertarse fuma su primer cigarrillo?

`q1`

- `0` — Más de 60 minutos
- `1` — De 31 a 60 minutos
- `2` — De 6 a 30 minutos
- `3` — En los primeros 5 minutos

### ¿Le resulta difícil no fumar en lugares donde está prohibido?

`q2`

- `0` — No
- `1` — Sí

### ¿Qué cigarrillo del día le produce más satisfacción (o sería el más difícil de dejar)?

`q3`

- `0` — Cualquier otro
- `1` — El primero de la mañana

### ¿Cuántos cigarrillos fuma al día?

`q4`

- `0` — 10 o menos
- `1` — 11 a 20
- `2` — 21 a 30
- `3` — 31 o más

### ¿Fuma con más frecuencia en las primeras horas después de despertarse que durante el resto del día?

`q5`

- `0` — No
- `1` — Sí

### ¿Fuma incluso cuando está tan enfermo que permanece en cama la mayor parte del tiempo?

`q6`

- `0` — No
- `1` — Sí

## Edición del método

FTND/Heatherton 1991:6 ítems, total 0–10; no Tolerance Questionnaire original; protocolo brasileño 2020

## Fórmula documentada

Seis preguntas. Tiempo al primer cigarrillo: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. Cigarrillos diarios: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. Las otras cuatro valen 1 por sí (o “primero de la mañana”). Total 0–10.

## Límites y población

La edición FTND revisa el FTQ y se estudió en fumadores de cigarrillos. No suponga equivalencia de puntuación para todos los productos de nicotina ni dispositivos electrónicos. El protocolo brasileño citado y las rúbricas completas todavía necesitan comprobación primaria en esta revisión.

## Referencias

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Dependencia muy baja (0 a 2 puntos)

Un abordaje cognitivo-conductual puede ser suficiente; farmacoterapia según evaluación individual.


### 2

Dependencia baja (3 a 4 puntos)

Según el PCDT, Fagerström ≤ 4 es uno de los criterios para priorizar el abordaje conductual aislado.


### 3

Dependencia media (5 puntos)

Suele indicarse asociar el abordaje cognitivo-conductual y la farmacoterapia.


### 4

Dependencia muy elevada (8 a 10 puntos)

Mayor probabilidad de síndrome de abstinencia: asociar farmacoterapia al abordaje conductual.

