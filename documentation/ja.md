<!-- ELUCENIA technical documentation · classificacao-de-forrest · ja · no clinical/professional/rights approval -->

# Forrest分類

[条件・出典・許諾](https://elucenia.org/ja/tools/classificacao-de-forrest)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 内視鏡での潰瘍所見

`classe`

- `Ia` — Ia – 噴出性の活動性出血
- `Ib` — Ib – 湧出性の活動性出血
- `IIa` — IIa – 出血のない露出血管
- `IIb` — IIb – 付着凝血塊
- `IIc` — IIc – 平坦な色素斑（ヘマチン）
- `III` — III – 清浄な潰瘍底（フィブリン）

## 方法の版

Forrest 1974：Ia/Ib/IIa/IIb/IIc/III；ESGE 2021の文脈

## 記載された計算式

Forrest I (活動性出血): Ia噴出性、Ib滲出性。 Forrest II (最近の出血徴候): IIa露出血管、IIb付着血餅、IIc平坦なヘマチン付着。 Forrest III: 清浄な潰瘍底.

## 限界・対象集団

Forrest分類は出血性消化性潰瘍の内視鏡所見を分類し、消化管出血のすべてを対象とするものではありません。検査所見に基づいて分類を選択してください。このツールは画像解析や出血原因の特定を行いません。2021年ESGEガイドラインは観察者間の一致に限界があるとしています。分類や表示される過去の割合だけで、個人の再出血を予測したり、退院や治療を決定したりすることはできません。

## 参考文献

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

Forrest Ia（噴出性出血）：内視鏡的止血が適応

| 結果の詳細 | |
| --- | --- |
| 内視鏡治療なしの再出血 | 55%（活動性出血） |


### 2

Forrest IIa（露出血管）：内視鏡的止血が適応

| 結果の詳細 | |
| --- | --- |
| 内視鏡治療なしの再出血 | 43% |


### 3

Forrest IIb（付着血栓）：血栓の除去と基礎病変の治療を考慮する

| 結果の詳細 | |
| --- | --- |
| 内視鏡治療なしの再出血 | 22% |


### 4

Forrest III（きれいな潰瘍底）：内視鏡治療は適応外

| 結果の詳細 | |
| --- | --- |
| 内視鏡治療なしの再出血 | 5% |

