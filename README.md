# environment-200913

2020/09/13(日): 環境構築の練習

## anyenv, nodenv を用意

9/13 時点では、Node.js の LTS(Long Term Support: 推奨版)は 12.18.3

### 参考

[Node.js](https://nodejs.org/ja/)

[Node.js のバージョンを自動で切り替えられる nodenv が超便利](https://qiita.com/tonkotsuboy_com/items/5322d226b6783d25b5df)

### package.json を作成

```
npm init -y
```

## Gulp.js を導入

### 参考

[絶対つまずかない Gulp 4 入門(2019 年版)
インストールと Sass を使うまでの手順](https://ics.media/entry/3290/)

### gulp 本体をローカルにインストール

```
npm install -D gulp
```

### gulp-sass を導入

Sass ファイルをコンパイルする為のプラグイン gulp-sass

```
npm install -D gulp gulp-sass
```
