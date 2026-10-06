<!-- ELUCENIA technical documentation · teste-de-fagerstrom · zh · no clinical/professional/rights approval -->

# Fagerström 测试

[条件、来源与许可](https://elucenia.org/zh/tools/teste-de-fagerstrom)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 醒来后多久吸第一支烟？

`q1`

- `0` — 超过 60 分钟
- `1` — 31至60分钟
- `2` — 6至30分钟
- `3` — 最初5分钟内

### 在禁止吸烟的地方不吸烟是否困难？

`q2`

- `0` — 否
- `1` — 是

### 一天中哪支烟最满足您（或最难放弃）？

`q3`

- `0` — 任何其他一支
- `1` — 早晨第一支

### 您每天吸多少支烟？

`q4`

- `0` — 10或以下
- `1` — 11 至 20
- `2` — 21 至 30
- `3` — 31或以上

### 醒来后最初几小时是否比其余时间吸烟更频繁？

`q5`

- `0` — 否
- `1` — 是

### 即使病得大多数时间卧床，您仍吸烟吗？

`q6`

- `0` — 否
- `1` — 是

## 方法版本

FTND/Heatherton 1991：6项0–10；非原Tolerance Questionnaire；巴西吸烟方案2020

## 已记录的公式

六题。 第一支烟时间: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. 每日支数: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. 其余四题答是（或“晨起第一支”）各1分。总分0–10。

## 限制与适用人群

FTND版本修订了FTQ，并在卷烟吸烟者中研究。不能假定评分对所有尼古丁产品或电子装置均具有等效性。所引用的巴西方案和完整评分条目在本次评审中仍需核对原始文献。

## 参考文献

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

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

依赖性很低（0至2分）

认知行为方法可能已足够；药物治疗根据个体评估而定。


### 2

低度依赖（3至4分）

根据 PCDT，Fagerström ≤ 4 是优先采用单纯行为干预的标准之一。


### 3

中度依赖（5分）

通常建议联合认知行为治疗和药物治疗。


### 4

极高依赖（8至10分）

戒断综合征的可能性更高：将药物治疗与行为干预联合。

