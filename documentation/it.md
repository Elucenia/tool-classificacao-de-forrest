<!-- ELUCENIA technical documentation · classificacao-de-forrest · it · no clinical/professional/rights approval -->

# Classificazione di Forrest

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/classificacao-de-forrest)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Aspetto endoscopico dell’ulcera

`classe`

- `Ia` — Ia – sanguinamento attivo a getto
- `Ib` — Ib – sanguinamento attivo a nappo
- `IIa` — IIa – vaso visibile non sanguinante
- `IIb` — IIb – coagulo adeso
- `IIc` — IIc – macchia piatta pigmentata (ematina)
- `III` — III – base pulita (fibrina)

## Edizione del metodo

Forrest 1974: Ia/Ib/IIa/IIb/IIc/III; contesto ESGE 2021

## Formula documentata

Forrest I (sanguinamento attivo): Ia a getto, Ib a nappo. Forrest II (stigmate di sanguinamento recente): IIa vaso visibile, IIb coagulo aderente, IIc ematina piatta. Forrest III: fondo pulito.

## Limiti e popolazione

Forrest classifica l’aspetto endoscopico dell’ulcera peptica sanguinante, non ogni emorragia digestiva. Selezionare la classe in base all’esame; lo strumento non analizza immagini né identifica la causa del sanguinamento. La linea guida ESGE del 2021 riconosce limiti nella concordanza tra osservatori. La classe e le eventuali percentuali storiche non forniscono, da sole, una previsione individuale di risanguinamento né determinano la dimissione o il trattamento.

## Riferimenti

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

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

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Forrest Ia (sanguinamento a getto): emostasi endoscopica indicata

| Dettagli del risultato | |
| --- | --- |
| Re-sanguinamento senza terapia endoscopica | 55% (sanguinamento attivo) |


### 2

Forrest IIa (vaso visibile): emostasi endoscopica indicata

| Dettagli del risultato | |
| --- | --- |
| Re-sanguinamento senza terapia endoscopica | 43% |


### 3

Forrest IIb (coagulo adeso): considerare la rimozione del coagulo e il trattamento della lesione sottostante

| Dettagli del risultato | |
| --- | --- |
| Re-sanguinamento senza terapia endoscopica | 22% |


### 4

Forrest III (base pulita): terapia endoscopica non indicata

| Dettagli del risultato | |
| --- | --- |
| Re-sanguinamento senza terapia endoscopica | 5% |

