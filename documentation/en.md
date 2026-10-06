<!-- ELUCENIA technical documentation · teste-de-fagerstrom · en · no clinical/professional/rights approval -->

# Fagerström test

[conditions, sources and permissions](https://elucenia.org/en/tools/teste-de-fagerstrom)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### How soon after waking do you smoke your first cigarette?

`q1`

- `0` — More than 60 minutes
- `1` — From 31 to 60 minutes
- `2` — From 6 to 30 minutes
- `3` — Within the first 5 minutes

### Do you find it difficult not to smoke where smoking is prohibited?

`q2`

- `0` — No
- `1` — Yes

### Which cigarette of the day is most satisfying (or would be hardest to give up)?

`q3`

- `0` — Any other
- `1` — The first in the morning

### How many cigarettes do you smoke per day?

`q4`

- `0` — 10 or fewer
- `1` — 11 to 20
- `2` — 21 to 30
- `3` — 31 or more

### Do you smoke more frequently in the first hours after waking than during the rest of the day?

`q5`

- `0` — No
- `1` — Yes

### Do you smoke even when you are so ill that you spend most of the time in bed?

`q6`

- `0` — No
- `1` — Yes

## Method edition

FTND/Heatherton 1991:6 items, total 0–10; not original Tolerance Questionnaire; Brazil smoking protocol 2020

## Documented formula

Six questions. Time to first cigarette: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. Cigarettes daily: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. Other four questions score 1 for yes (or “the first in the morning”). Total 0–10.

## Limits and population

The FTND edition revises FTQ and was studied in cigarette smokers. Do not presume equivalent scoring for every nicotine product or electronic device. The cited Brazilian protocol and full rubrics still require primary-source checking in this review.

## References

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Very low dependence (0 to 2 points)

A cognitive-behavioral approach may be sufficient; pharmacotherapy according to individual assessment.


### 2

Low dependence (3 to 4 points)

According to the PCDT, Fagerström ≤ 4 is one of the criteria for prioritizing behavioral treatment alone.


### 3

Moderate dependence (5 points)

Combining cognitive-behavioral treatment and pharmacotherapy is usually indicated.


### 4

Very high dependence (8 to 10 points)

Higher likelihood of withdrawal syndrome: combine pharmacotherapy with behavioral treatment.

