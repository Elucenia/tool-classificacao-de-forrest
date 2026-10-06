<!-- ELUCENIA technical documentation · classificacao-de-forrest · fr · no clinical/professional/rights approval -->

# Classification de Forrest

[conditions, sources et autorisations](https://elucenia.org/fr/outils/classificacao-de-forrest)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Aspect de l’ulcère à l’endoscopie

`classe`

- `Ia` — Ia – saignement actif en jet
- `Ib` — Ib – saignement actif en nappe
- `IIa` — IIa – vaisseau visible non hémorragique
- `IIb` — IIb – caillot adhérent
- `IIc` — IIc – tache pigmentée plane (hématine)
- `III` — III – fond propre (fibrine)

## Édition de la méthode

Forrest 1974 : Ia/Ib/IIa/IIb/IIc/III ; contexte ESGE 2021

## Formule documentée

Forrest I (saignement actif): Ia en jet, Ib en nappe. Forrest II (stigmates de saignement récent): IIa vaisseau visible, IIb caillot adhérent, IIc hématine plane. Forrest III: fond propre.

## Limites et population

Forrest classe l’aspect endoscopique d’un ulcère peptique hémorragique, et non toute hémorragie digestive. Sélectionnez la classe à partir de l’examen ; l’outil n’analyse pas les images et n’identifie pas la cause du saignement. Les recommandations ESGE de 2021 reconnaissent les limites de la concordance entre observateurs. La classe et les éventuels pourcentages historiques ne fournissent pas, à eux seuls, une prédiction individuelle de récidive hémorragique et ne déterminent ni la sortie ni le traitement.

## Références

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

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

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Forrest Ia (saignement en jet) : hémostase endoscopique indiquée

| Détails du résultat | |
| --- | --- |
| Resaignement sans traitement endoscopique | 55 % (saignement actif) |


### 2

Forrest IIa (vaisseau visible) : hémostase endoscopique indiquée

| Détails du résultat | |
| --- | --- |
| Resaignement sans traitement endoscopique | 43% |


### 3

Forrest IIb (caillot adhérent) : envisager de retirer le caillot et de traiter la lésion sous-jacente

| Détails du résultat | |
| --- | --- |
| Resaignement sans traitement endoscopique | 22% |


### 4

Forrest III (base propre) : traitement endoscopique non indiqué

| Détails du résultat | |
| --- | --- |
| Resaignement sans traitement endoscopique | 5% |

