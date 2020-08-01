# nothingパッケージ
RでGitHubからパッケージをインストールするデモのための、「何もしない」パッケージです。

## インストール

先に `remotes` パッケージをCRANからインストールしておく必要があります。

```
install.packages("remotes")
```

また、Windows環境では[RTools](https://cran.ism.ac.jp/bin/windows/Rtools/)もインストールする必要があります。

準備が整ったら、以下のように nothing パッケージをインストールします。

```
remotes::install_github("ltl-manabi/nothing")
```

## 使い方

このパッケージは何の機能も提供しませんが、以下のようにして読み込みます。

```
library(nothing)
```

いちおう、RStudioでパッケージ用のプロジェクトを作成するとデフォルトで格納される、`hello.R` をそのまま置いているので、以下の `hello()` 関数で動作の確認ができます。

```
hello()
```
