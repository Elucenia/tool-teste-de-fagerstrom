<!-- ELUCENIA technical documentation · teste-de-fagerstrom · it · no clinical/professional/rights approval -->

# Test di Fagerström

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/teste-de-fagerstrom)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Quanto tempo dopo il risveglio fuma la prima sigaretta?

`q1`

- `0` — Più di 60 minuti
- `1` — Da 31 a 60 minuti
- `2` — Da 6 a 30 minuti
- `3` — Nei primi 5 minuti

### Trova difficile non fumare nei luoghi in cui è vietato?

`q2`

- `0` — No
- `1` — Sì

### Quale sigaretta della giornata dà più soddisfazione (o sarebbe la più difficile da eliminare)?

`q3`

- `0` — Qualsiasi altra
- `1` — La prima del mattino

### Quante sigarette fuma al giorno?

`q4`

- `0` — 10 o meno
- `1` — 11 a 20
- `2` — 21 a 30
- `3` — 31 o più

### Fuma più frequentemente nelle prime ore dopo il risveglio che nel resto della giornata?

`q5`

- `0` — No
- `1` — Sì

### Fuma anche quando è così malato da rimanere a letto per la maggior parte del tempo?

`q6`

- `0` — No
- `1` — Sì

## Edizione del metodo

FTND/Heatherton 1991:6 item, totale 0–10; non Tolerance Questionnaire originale; protocollo brasiliano 2020

## Formula documentata

Sei domande. Tempo alla prima sigaretta: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. Sigarette quotidiane: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. Altre quattro 1 per sì (o “prima mattutina”). Totale 0–10.

## Limiti e popolazione

L’edizione FTND rivede l’FTQ ed è stata studiata in fumatori di sigarette. Non presumere l’equivalenza del punteggio per ogni prodotto a base di nicotina o dispositivo elettronico. Il protocollo brasiliano citato e le rubriche complete richiedono ancora una verifica primaria in questa revisione.

## Riferimenti

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
