<!-- ELUCENIA technical documentation · teste-de-fagerstrom · pt-BR · no clinical/professional/rights approval -->

# Teste de Fagerström

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/teste-de-fagerstrom)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Quanto tempo após acordar você fuma o primeiro cigarro?

`q1`

- `0` — Mais de 60 minutos
- `1` — De 31 a 60 minutos
- `2` — De 6 a 30 minutos
- `3` — Nos primeiros 5 minutos

### Você acha difícil não fumar em lugares proibidos?

`q2`

- `0` — Não
- `1` — Sim

### Qual cigarro do dia traz mais satisfação (ou seria o mais difícil de largar)?

`q3`

- `0` — Qualquer outro
- `1` — O primeiro da manhã

### Quantos cigarros você fuma por dia?

`q4`

- `0` — 10 ou menos
- `1` — 11 a 20
- `2` — 21 a 30
- `3` — 31 ou mais

### Você fuma mais frequentemente nas primeiras horas após acordar do que no resto do dia?

`q5`

- `0` — Não
- `1` — Sim

### Você fuma mesmo quando está doente a ponto de ficar acamado a maior parte do tempo?

`q6`

- `0` — Não
- `1` — Sim

## Edição do método

FTND/Heatherton 1991:6 itens, total 0–10; sem Tolerance Questionnaireoriginal; PCDTtabagismo 2020

## Fórmula documentada

Seis perguntas. Tempo até o primeiro cigarro: ≤ 5 min 3, 6 a 30 min 2, 31 a 60 min 1, \> 60 min 0. Cigarros por dia: ≤ 10 0, 11 a 20 1, 21 a 30 2, ≥ 31 3. As outras quatro perguntas valem 1 ponto se a resposta for sim (ou "o primeiro da manhã"). Total de 0 a 10.

## Limites e população

A edição FTND revisa o FTQ e foi estudada em fumantes de cigarros. Não presumir equivalência de pontuação para todo produto de nicotina ou dispositivo eletrônico. O protocolo brasileiro citado e as rubricas integrais ainda precisam de conferência primária nesta revisão.

## Referências

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
