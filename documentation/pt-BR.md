<!-- ELUCENIA technical documentation · classificacao-de-forrest · pt-BR · no clinical/professional/rights approval -->

# Classificação de Forrest

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/classificacao-de-forrest)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Aspecto da úlcera na endoscopia

`classe`

- `Ia` — Ia – sangramento ativo em jato
- `Ib` — Ib – sangramento ativo em babação (porejamento)
- `IIa` — IIa – vaso visível sem sangramento
- `IIb` — IIb – coágulo aderido
- `IIc` — IIc – mancha plana pigmentada (hematina)
- `III` — III – base limpa (fibrina)

## Edição do método

Forrest 1974:Ia/Ib/IIa/IIb/IIc/III; contexto ESGE 2021

## Fórmula documentada

Forrest I (sangramento ativo): Ia em jato, Ib em babação. Forrest II (estigmas de sangramento recente): IIa vaso visível, IIb coágulo aderido, IIc hematina plana. Forrest III: base limpa.

## Limites e população

Forrest classifica o aspecto endoscópico da úlcera péptica com sangramento, não toda hemorragia digestiva. Selecione a classe a partir do exame; a ferramenta não analisa imagens nem identifica a causa do sangramento. A diretriz ESGE 2021 reconhece limitações de concordância entre observadores. A classe e eventuais percentuais históricos não fornecem, sozinhos, uma previsão individual de ressangramento nem determinam alta ou tratamento.

## Referências

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Forrest Ia (sangramento em jato): hemostasia endoscópica indicada

| Detalhes do resultado | |
| --- | --- |
| Ressangramento sem terapia endoscópica | 55% (sangramento ativo) |


### 2

Forrest IIa (vaso visível): hemostasia endoscópica indicada

| Detalhes do resultado | |
| --- | --- |
| Ressangramento sem terapia endoscópica | 43% |


### 3

Forrest IIb (coágulo aderido): considerar remover o coágulo e tratar a lesão subjacente

| Detalhes do resultado | |
| --- | --- |
| Ressangramento sem terapia endoscópica | 22% |


### 4

Forrest III (base limpa): terapia endoscópica não indicada

| Detalhes do resultado | |
| --- | --- |
| Ressangramento sem terapia endoscópica | 5% |

