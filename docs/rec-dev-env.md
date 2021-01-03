# 開発環境

[gulp.js](https://gulpjs.com/) を利用して、 [Sass](https://sass-lang.com/) + [PostCSS](https://postcss.org/) で開発する。

ソースコードは `.sass` よりも `.scss` を推奨する。

## 目次

## 導入手順

1.  [Node.js](https://nodejs.org/ja/) と [git](https://git-scm.com/)をインストール
    （環境変数を通すのを忘れずに）
2.  リポジトリをクローン
    ```
    git clone https://github.com/KarasuTatehi/itsuki-no-miya.git
    ```
3.  パッケージをインストール
    ```
    npm i
    ```

## ビルド

1.  `src` ディレクトリでソースコードを書く
2.  ビルドスクリプトを実行
    ```
    npm run build
    ```
    `dest` ディレクトリにコンパイルされた `blob` が出力される
