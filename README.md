# 電気通信大学 情報・ネットワーク工学専攻 大学院試験解答

## 掲載している年度と問題番号

### 必須問題
* 2023

### 選択問題

|年度| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|---|---|---|---|---|---|---|---|---|
|2023|   |   |   |   |   |   | ◯ |   |
|2022|   |   |   |   |   |   |   |   |
|2021|   |   |   |   |   |   |   |   |
|2020|   |   |   |   |   |   |   |   |
|2019|   |   |   |   |   |   |   |   |
|2018|   |   |   |   |   |   |   |   |
|2017|   |   |   |   |   |   |   |   |
|2016|   |   |   |   |   |   |   |   |

## 解答作成の手順

まず、対応する年度のディレクトリを作成する。（例：`2023`）

### 必須問題

`_required.tex`を作成する年度のディレクトリにコピーする。そのとき、ファイル名の先頭に年度の数をいれる。（例：`2023/2023_required.tex`）

### 選択問題

`_mcq.tex`を作成する年度のディレクトリにコピーする。そのとき、ファイル名の先頭に年度の数をいれる。（例：`2023/2023_mcq.tex`）

### その後の手順

```tex
\newcommand{\examYear}{20**}
\newcommand{\answerCreater}{}
```

の欄に、取り組んだ問題の（実施）年度と、自分の名前（本名じゃなくていいが、このレポジトリでは一貫したものにする）を記入する。

### 解答作成ルール

* 大問ごとに`\newpage`する
* 各小問は`enumerate`で並べる
