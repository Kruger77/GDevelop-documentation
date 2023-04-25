---
title: グローバル変数
---
# グローバル変数

グローバル変数とは、次のような変数です。

- ゲームを実行しているあいだ、ずっとメモリー上に存在する
- ゲームのどのシーンからもアクセスできる

プレイヤーのスコアのような、ゲーム全体を通して常にアクセスされるデータを格納するのに向いています。グローバル変数は、ゲームを終了したときにはじめてメモリーから削除されます。

## グローバル変数の作成

1. [project manager](/ja/gdevelop5/interface/project-manager)を開きます。
2. **ゲーム設定**パネルを展開します。
3. **グローバル変数**を選択します。
4. **追加**をクリックします。
5. 変数の名前を入力します。
6. （オプションで）変数の既定値を入力します。
7. **適用**を選択します。

!!! tip

    変数の名前にはドット/ピリオド（.）とカンマ（,）を使えません。変数名には英数字のみを使うことをおすすめします。

## グローバル変数を式の中で使う

グローバル変数は[式](/ja/gdevelop5/all-features/expressions)の中で使うことができます。構文は変数のデータ型によって異なります。以下に例を示しますが、山括弧でくくられたプレースホルダーは実際に使う値に読み替えてください。

### 数値

```
GlobalVariable(＜変数名＞)
```

### テキスト

```
GlobalVariableString(＜変数名＞)
```

### 構造体

```
GlobalVariable(＜親変数＞.＜子変数＞)
GlobalVariableString(＜親変数＞.＜子変数＞)
```