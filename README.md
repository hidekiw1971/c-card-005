# compornent（共通部品）

## 概要

- 三角バッジ(New)、画像、タイトル、説明、カテゴリ、日付
- レスポンシブ対応済
- コンポーネント（共通部品）として使用可能。

## 仕様

- margin は使用してません。
- padding は必要最低限に使用してます。
- tabletはpcサイズが縮小されて表示されます。
- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。

## 注意事項

- レイアウトを設定する場合は、class を追加してそちらで設定して下さい。
- そうしないと共通部品として使えなくなります。
- クラス「card\_\_badge」で、inlin-block にすると上に隙間ができる。丸バッジの位置によって使い分けが必要？

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## イメージ画像
<img width="404" alt="image" src="https://user-images.githubusercontent.com/99580997/157425662-97502aa8-dbc3-49a9-b924-293766905a93.png">
<img width="784" alt="image" src="https://user-images.githubusercontent.com/99580997/157425716-3ad1d86c-c77b-46b9-9cd9-a3c8e8193b7f.png">
<img width="1244" alt="image" src="https://user-images.githubusercontent.com/99580997/157425794-4aada1a3-c4f9-4b23-a5bc-72981eac4342.png">


## portfolio url:

- https://css-md-0020.wtb.cfbx.jp/

## 参考にしたサイト

- 【CSS】 border-width を学ぶ【三角形で国旗を作る】
- https://sunsukeblog.com/css-border-width

## 更新履歴

- 2022/3/9 初版 作成完了（レスポンシブ対応済）
- 2022/3/9 初版 作成中

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考


