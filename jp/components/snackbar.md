﻿---
title: Snackbar - デザイン システム コンポーネント
_description: Snackbar コンポーネント シンボルは、短い通知やユーザーの最近の操作を示すことができます。
_keywords: デザイン システム, Sketch, Ignite UI for Angular, コンポーネント, UI ライブラリ, ウィジェット
_language: ja
---

## Snackbar (スナックバー)

Snackbar コンポーネント シンボルは、短い通知の表示やリストの記録の追加または削除など最近の操作の表示するためのオプションを提供します。オプションは、元に戻すなどのシンプルな追加操作をトリガーします。Snackbar は、[Ignite UI for Angular Snackbar コンポーネント](https://jp.infragistics.com/products/ignite-ui-angular/angular/components/snackbar.html)と視覚的に同じものです。

### Snackbar デモ

<img class="responsive-img" src="../images/snackbar_demo.png" srcset="../images/snackbar_demo@2x.png 2x" />

### スタイル設定

Snackbar は、スタイル設定に制限があり操作ボタンのテキスト色のみ変更できます。

<img class="responsive-img" src="../images/snackbar_styling.png" srcset="../images/snackbar_styling@2x.png 2x" />

## 使用方法

Snackbar は、その他のコンテンツの一番上に表示されるため、アプリケーションのメイン ナビゲーション上には配置しないでください。メッセージとコントラストがある操作ボタンを強調するためのスタイルを選択し、最新のボタンのみ表示して列に複数の Snackbars を積み重ねないようにします。

| 良い例                              | 悪い例                             |
| ------------------------------- | --------------------------------- |
| <img class="responsive-img" src="../images/snackbar_do1.png" srcset="../images/snackbar_do1@2x.png 2x" /> | <img class="responsive-img" src="../images/snackbar_dont1.png" srcset="../images/snackbar_dont1@2x.png 2x" /> |
| <img class="responsive-img" src="../images/snackbar_do2.png" srcset="../images/snackbar_do2@2x.png 2x" /> | <img class="responsive-img" src="../images/snackbar_dont2.png" srcset="../images/snackbar_dont2@2x.png 2x" /> |
| <img class="responsive-img" src="../images/snackbar_do3.png" srcset="../images/snackbar_do3@2x.png 2x" /> | <img class="responsive-img" src="../images/snackbar_dont3.png" srcset="../images/snackbar_dont3@2x.png 2x" /> |

## コードの生成

Snackbar の色を指定した場合、Snackbar HTML 要素は div でラップされます。ブラウザーによってネスト コンポーネント (他のコンポーネント内のコンポーネント) のスタイル設定が要求されます。

> [!WARNING]
> デザインの Snackbar のインスタンスで `Detach from Symbol` をトリガーすると、ほとんどの場合で Snackbar のためのコード生成機能が失われます。

### Event プロパティ

`🕹️Event` プロパティは、コンポーネント TypeScript のメソッドを作成するために使用し、Snackbar の HTML に onAction シグネチャーを追加します。イベントが波括弧構文 ({onEventName}) を使用して指定する必要があります。

### テキスト

Message と Button に Text プロパティがあります。このプロパティにテキスト、[バインディング](../codegen/data-binding.md)、または両方を含むことができます。例:

- 設定
- {settingsLabel}
- 重要な {labelText}

## その他のリソース

関連トピック:

- [データ バインディング](../codegen/data-binding.md)
  <div class="divider--half"></div>
  
コミュニティに参加して新しいアイデアをご提案ください。


