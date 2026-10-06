<!-- ELUCENIA technical documentation · classificacao-de-forrest · zh · no clinical/professional/rights approval -->

# Forrest 分级

[条件、来源与许可](https://elucenia.org/zh/tools/classificacao-de-forrest)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 内镜下溃疡表现

`classe`

- `Ia` — Ia – 活动性喷射出血
- `Ib` — Ib – 活动性渗血
- `IIa` — IIa – 可见血管但无出血
- `IIb` — IIb – 附着血凝块
- `IIc` — IIc – 平坦色素斑（正铁血红素）
- `III` — III – 清洁基底（纤维蛋白）

## 方法版本

Forrest 1974：Ia/Ib/IIa/IIb/IIc/III；ESGE 2021背景

## 已记录的公式

Forrest I (活动性出血): Ia喷射性，Ib渗血。 Forrest II (近期出血征象): IIa可见血管，IIb附着血凝块，IIc平坦含血色素斑。 Forrest III: 清洁基底.

## 限制与适用人群

Forrest分类描述出血性消化性溃疡的内镜表现，并不适用于所有消化道出血。请根据检查选择类别；工具不分析图像，也不识别出血原因。2021年ESGE指南指出观察者间一致性存在局限。类别及可能显示的历史百分比不能单独预测个人再出血风险，也不能决定出院或治疗。

## 参考文献

- [Forrest JA, Finlayson ND, Shearman DJ. Endoscopy in gastrointestinal bleeding. Lancet, 1974.](https://doi.org/10.1016/S0140-6736(74)91770-X)

- [Laine L, Peterson WL. Bleeding peptic ulcer. N Engl J Med, 1994.](https://doi.org/10.1056/NEJM199409153311107)

- [Gralnek IM et al. Endoscopic diagnosis and management of nonvariceal upper gastrointestinal hemorrhage (NVUGIH): European Society of Gastrointestinal Endoscopy (ESGE) Guideline – Update 2021. Endoscopy, 2021.](https://doi.org/10.1055/a-1369-5274)

- [ESGE2021](https://www.esge.com/assets/downloads/pdfs/guidelines/2021_a_1369_5274.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

Forrest Ia（喷射性出血）：有内镜止血指征

| 结果详情 | |
| --- | --- |
| 未行内镜治疗的再出血 | 55%（活动性出血） |


### 2

Forrest IIa（可见血管）：适用内镜止血

| 结果详情 | |
| --- | --- |
| 未行内镜治疗的再出血 | 43% |


### 3

Forrest IIb（附着血凝块）：考虑去除血凝块并处理潜在病灶

| 结果详情 | |
| --- | --- |
| 未行内镜治疗的再出血 | 22% |


### 4

Forrest III（清洁基底）：不适用内镜治疗

| 结果详情 | |
| --- | --- |
| 未行内镜治疗的再出血 | 5% |

