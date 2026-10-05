<!-- ELUCENIA technical documentation · teste-de-fagerstrom · fr · no clinical/professional/rights approval -->

# Test de Fagerström

[conditions, sources et autorisations](https://elucenia.org/fr/outils/teste-de-fagerstrom)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Combien de temps après le réveil fumez-vous votre première cigarette ?

`q1`

- `0` — Plus de 60 minutes
- `1` — De 31 à 60 minutes
- `2` — De 6 à 30 minutes
- `3` — Dans les 5 premières minutes

### Trouvez-vous difficile de ne pas fumer dans les lieux où c’est interdit ?

`q2`

- `0` — Non
- `1` — Oui

### Quelle cigarette de la journée vous satisfait le plus (ou serait la plus difficile à abandonner) ?

`q3`

- `0` — N’importe quelle autre
- `1` — La première du matin

### Combien de cigarettes fumez-vous par jour ?

`q4`

- `0` — 10 ou moins
- `1` — 11 à 20
- `2` — 21 à 30
- `3` — 31 ou plus

### Fumez-vous plus souvent dans les premières heures après le réveil que pendant le reste de la journée ?

`q5`

- `0` — Non
- `1` — Oui

### Fumez-vous même lorsque vous êtes malade au point de rester au lit la plupart du temps ?

`q6`

- `0` — Non
- `1` — Oui

## Édition de la méthode

FTND/Heatherton 1991:6 items, total 0–10 ; pas Tolerance Questionnaire original ; protocole brésilien 2020

## Formule documentée

Six questions. Délai avant première cigarette: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. Cigarettes par jour: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. Les quatre autres valent 1 pour oui (ou «première du matin»). Total 0–10.

## Limites et population

L’édition FTND révise le FTQ et a été étudiée chez des fumeurs de cigarettes. Ne présumez pas une équivalence de cotation pour tous les produits nicotiniques ou dispositifs électroniques. Le protocole brésilien cité et les rubriques intégrales nécessitent encore une vérification primaire dans cette revue.

## Références

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
