---
title: 技術ブログ始めました(VSCodeの設定編)
date: 2020-07-16T17:31:46+09:00
cover_index: /blog-test-mdui/covers/vscode_logo.jpeg
cover_detail: /tech-blog/covers/vscode_logo.jpeg
categories: ["blog"]
tags: 
  - "hexo"
  - "vscode"
---

VSCodeを使うとコンテナにアクセスできてビビる。。。

<!-- more -->

## 画像の貼り付け

{% asset_img 2020-07-17T100910.png %}


vscodeのエクステンションを使うと画像をコピペすると自動でフォルダ内に配置してくれる。

が、困ったことにリモート接続した場合、画像のクリップボードはコピーされない既知のバグ(仕様?)があるらしく、まだリモート先への画像コピペができないんですね。。。

なので、

1. リモート接続せずに執筆
2. 書き終わったらリモート接続してgithubにプッシュ

みたいな悲しい事態が起こる。。。