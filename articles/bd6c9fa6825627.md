---
title: "flutterを用いて初めてアプリを作るまで"
emoji: "💻"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["flutter", "dart", "VSCode"]
published: true
---

# はじめに

今回は flutter を用いてエンジニアのためのマッチングアプリ「Team」を作る上で学んだことをアウトプットしていこうと思います。

# 執筆者の経歴

- エンジニア歴は１年
- 仕事では SQL を使ってデータベースの構築などをしている
- flutter を用いて１人でアプリを作るのは初めて
- でも知り合いのエンジニアと flutter でマッチングアプリ制作・リリース済み
- 参考までにアプリのリンク →[WinWin（男女のグループマッチングアプリ）](https://winwin-fukuoka.com/)

# 今回のゴール

flutter を使って初期アプリ（カウントアプリ）を画面で動作確認ができるようになる。

# それでは早速やっていこう！

# まずはアプリを格納するフォルダの作成

自分の場合はユーザーの直下に「flutter_app」というフォルダを作りました。
![新規フォルダの画像](https://live.staticflickr.com/65535/51314454077_91a2bc930e_z.jpg =500x)

# コマンドプロンプトの起動

![コマンドプロンプトの画像](https://live.staticflickr.com/65535/51316231840_f5325d9fc9_z.jpg =500x)

# 先程作ったフォルダへ移動

```dart: コマンドプロンプト
$ cd flutter_app
```

# アプリを Create する

```dart: コマンドプロンプト
$ flutter create team
```

自分の場合は「team」という名前のアプリを作りました。

# コマンドがエラーなく実施されれば成功

All done!というメッセージを確認できれば OK です。

![Fluttercreateの画像](https://live.staticflickr.com/65535/51332332939_987327d974_z.jpg =500x)

# 早速 VSCode でアプリを開いてみよう！

アプリフォルダの中の lib 配下の「main.dart」を開いてみましょう。
中身はこんな感じ。

![VSCodeの画像](https://live.staticflickr.com/65535/51332362519_0f5dcc6668_z.jpg =500x)

# シミュレーターを起動してflutter run

```dart: コマンドプロンプト(team)
team$ flutter run
```

アプリフォルダの直下でコマンドを流しましょう。

# 画面でアプリを確認できればOK！

簡単なカウントアプリで右下のボタンを押すとカウントがプラスされていきます。

![カウントアプリの画像](https://live.staticflickr.com/65535/51331640686_4ef39b93b1_z.jpg =296x)

# まとめ

さぁということで今回はFlutterを用いて初めてのアプリ作成から画面確認までしてみました。
Flutterはまだまだ日本語の記事が少ないので少しでも皆さんのお役に立てればと思います！！