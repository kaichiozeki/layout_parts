修正内容をまとめたマークダウン形式のファイルを添付しますので、添付ファイルをダウンロードし、エディタで開いて修正内容を確認してください！
修正指示に対して、 *どのように修正したか* を確認したいので修正指示のすぐ下に直接 *修正内容を書き込み* 、再レビュー依頼の時に `review.md` ファイルを併せて添付してください！
マークダウンについて詳しく知りたい方は[こちら](https://giztech.gizumo-inc.work/lesson/40)にまとめてありますので読んでみてください。
以上、よろしくお願いします！

## レイアウトパーツ
--- 例 ---
1. 修正指示を記載します(メンター)
   - 修正内容を記載してください(研修生)
     例) 〇〇クラスに××を指定して△△になるようにしました。
----------676px

## 全体

## 1
- clearfixの使い方が合ってないため、floatが解除しきれていない状況になっています。まずはclearfixについて調べてどこが間違っている箇所を修正してみましょう！

  clearfixの位置を <div class="q1_box">の親要素に移動させました。

## 2
- テーブルを構成するタグの中にはtheadやtbodyというタグがあります。テーブルはこれらのタグを組み合わせるとHTMLの役割が明確になってより読みやすいコードになるので使用してみてください！

  htmlにthead,tbody,tfootを追記しました。

- tabelタグに直接スタイルを当ててしまっているので、適切なクラス名をつけるようにしてみましょう！

  クラス名を変更しました。

- htmlに不要なインデントがあります

　<h2 class="layout_main_section_title">2.テーブル</h2>のインデントを消しました。

- 背景色が青のセルは縦も横も見出しの役割になっているので、thタグを使用しましょう！

  thのタグを使用し、cssのtable td:first-childのfont-sizeは18pxを削除しました。

## 3
- 背景色や文字の太さなどが見本と異なるので見直してみましょう！

   font-weight: bold;をq3_boxに追加しました。
   box-9の背景色を変更しました。

- 数字の中央配置をするのにdisplay:gridを使用していますが、これはグリッドレイアウトを作成するためのプロパティで、中央寄せに使うには少しコードが複雑になってしまうため、もっとシンプルな中央寄せを探して使ってみましょう！

  display:gridを削除し、line-height、text-align: center;を追加して中央寄せしました。

- 各ボックスで共通な部分と固有の部分を分けれていて良いですね！ただ、ボックスのサイズなどまだ共通と固有の部分で効率のいい分け方があるので考えて実装してみましょう！

  position: absolute;、 height: 100px;、width: 100px;をまとめました。


## 4
- position固定とposition可変の文字が左によってしまっています

  text-align: center;を追加しました。