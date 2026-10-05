<!-- ELUCENIA technical documentation · teste-de-fagerstrom · ja · no clinical/professional/rights approval -->

# Fagerströmテスト

[条件・出典・許諾](https://elucenia.org/ja/tools/teste-de-fagerstrom)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 起床後どのくらいで最初のたばこを吸いますか？

`q1`

- `0` — 60 分 超
- `1` — 31～60分
- `2` — 6～30分
- `3` — 最初の5分以内

### 禁煙の場所で吸わずにいることが難しいですか？

`q2`

- `0` — いいえ
- `1` — はい

### 1日のうちどのたばこが最も満足できますか（またはやめにくいですか）？

`q3`

- `0` — その他のどれでも
- `1` — 朝の最初の1本

### 1日に何本たばこを吸いますか？

`q4`

- `0` — 10以下
- `1` — 11 ～ 20
- `2` — 21 ～ 30
- `3` — 31以上

### 起床後の数時間は他の時間より頻繁に吸いますか？

`q5`

- `0` — いいえ
- `1` — はい

### 病気でほとんど寝ていてもたばこを吸いますか？

`q6`

- `0` — いいえ
- `1` — はい

## 方法の版

FTND/Heatherton 1991：6項目0～10、原Tolerance Questionnaireとは別、ブラジル喫煙指針2020

## 記載された計算式

6問。 最初の喫煙まで: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. 1日の本数: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. 残り4問は「はい」（または「朝最初」）で1点。合計0～10。

## 限界・対象集団

FTND版はFTQを改訂し、紙巻きたばこを吸う人で研究されました。あらゆるニコチン製品や電子機器で採点が同等であると仮定してはいけません。引用されたブラジルのプロトコルと完全な採点基準は、このレビューで一次文献を確認する必要がまだあります。

## 参考文献

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

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
