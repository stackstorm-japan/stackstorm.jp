## このリポジトリについて

[日本 StackStorm ユーザ会オフィシャルページ](https://stackstorm.jp) のコンテンツを管理しているリポジトリです。

## 公式ページについて

公式ページは [Hugo](https://gohugo.io/) によって作成されています。

以下では Hugo によるコンテンツ操作の方法を解説します。これらに従ってコンテンツの操作を行う場合は、
[Hugo インストールマニュアル](https://gohugo.io/getting-started/installing/) に従って環境構築を行ってください。

ページを追加・更新する場合には、以下の情報を参考に [PR (Pull Request)](https://help.github.com/articles/about-pull-requests/) を作成してください。

### 参考情報：ブログページの作成

新たなブログページ (「新機能 hoge に関する解説」) の作成方法を説明します。

まずはオフィシャルページのリポジトリを [Fork](https://help.github.com/articles/fork-a-repo/) した後、`git clone` でローカルリポジトリを作成します（ユーザ `userlocalhost` のローカルリポジトリを作成する場合）
```Bash
$ git clone git@github.com:stackstorm-japan/official-page.git
```

取得したローカルリポジトリのトップディレクトリに移動し、`[hugo new]` コマンドによって [コンテンツファイル](https://gohugo.io/content-management/organization/) を生成します。
```Bash
$ cd official-page
$ hugo new post/about_a_new_function_hoge.md
```

生成されたファイルに本文を記載します。本文は [Markdown 形式](https://guides.github.com/features/mastering-markdown/) で記述します。またコンテンツファイルの構成は [公式動画](https://www.youtube.com/watch?time_continue=82&v=0GZxidrlaRM) をご参照ください。
```Markdown
---
title: "新機能 hoge に関する解説"
date: 2017-12-30T18:22:55+09:00
tags:
  - 技術情報
  - hoge
---

## hoge とは
hoge は XXX を YYY する機能

## 背景
...
```

最後に作成したファイルをコミットした後、リモートリポジトリに `push` します。
```Bash
$ git add .
$ git commit -m "Wrote a new content about new functional feature about hoge"
$ git push origin master
```
