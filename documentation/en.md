<!-- ELUCENIA technical documentation · classificacao-de-forrest · en · no clinical/professional/rights approval -->

# Forrest classification

[conditions, sources and permissions](https://elucenia.org/en/tools/classificacao-de-forrest)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Endoscopic appearance of the ulcer

`classe`

- `Ia` — Ia – active spurting bleeding
- `Ib` — Ib – active oozing bleeding
- `IIa` — IIa – nonbleeding visible vessel
- `IIb` — IIb – adherent clot
- `IIc` — IIc – flat pigmented spot (hematin)
- `III` — III – clean base (fibrin)

## Method edition

Forrest 1974: Ia/Ib/IIa/IIb/IIc/III; ESGE 2021 context

## Documented formula

Forrest I (active bleeding): Ia spurting, Ib oozing. Forrest II (stigmata of recent bleeding): IIa visible vessel, IIb adherent clot, IIc flat haematin. Forrest III: clean base.

## Limits and population

Forrest classifies the endoscopic appearance of a bleeding peptic ulcer, not every gastrointestinal hemorrhage. Select the class from the examination; the tool does not analyze images or identify the cause of bleeding. The 2021 ESGE guideline recognizes limitations in agreement between observers. The class and any historical percentages alone do not provide an individual prediction of rebleeding or determine discharge or treatment.

## References

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

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

Forrest Ia (spurting bleeding): endoscopic hemostasis indicated

| Result details | |
| --- | --- |
| Rebleeding without endoscopic therapy | 55% (active bleeding) |


### 2

Forrest IIa (visible vessel): endoscopic hemostasis indicated

| Result details | |
| --- | --- |
| Rebleeding without endoscopic therapy | 43% |


### 3

Forrest IIb (adherent clot): consider removing the clot and treating the underlying lesion

| Result details | |
| --- | --- |
| Rebleeding without endoscopic therapy | 22% |


### 4

Forrest III (clean base): endoscopic therapy not indicated

| Result details | |
| --- | --- |
| Rebleeding without endoscopic therapy | 5% |

