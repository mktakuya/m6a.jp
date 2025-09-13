m6a.jp
=====

mktakuya のWebサイト


## 開発ガイド

### 前提

- `.ruby-version` ファイルに合致したバージョンの Ruby がインストールされていること
- `.node-version` ファイルに合致したバージョンの Node.js がインストールされていること


### 依存ライブラリのインストール

```
$ bundle install
$ npm install
```


### Jekyll と Tailwind CLI の起動

```
$ bundle exec jekyll serve
$ npx @tailwindcss/cli -i ./assets/main.css -o ./dist/main.css --watch 
```


### ブラウザで確認

```
$ open http://localhost:4000
```
