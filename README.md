# compornent（共通部品）

## 概要

- バッジ(New)、画像、タイトル、説明、カテゴリ、日付
- レスポンシブ対応済
- コンポーネント（共通部品）として使用可能。

## 仕様

- margin は使用してません。
- padding は必要最低限に使用してます。

## 注意事項

- レイアウトを設定する場合は、class を追加してそちらで設定して下さい。
- そうしないと共通部品として使えなくなります。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## イメージ画像

<img width="415" alt="image" src="https://user-images.githubusercontent.com/99580997/157412356-72f00b70-1300-4bbf-a269-8a51767faae7.png">
<img width="781" alt="image" src="https://user-images.githubusercontent.com/99580997/157412450-4f3b7cd9-bd7f-4229-91e2-5d3e9262fe31.png">
<img width="1237" alt="image" src="https://user-images.githubusercontent.com/99580997/157412539-dcc3cb21-fdd9-435f-b60c-aeda24417cd5.png">


## portfolio url:

- https://css-md-0019.wtb.cfbx.jp/

## 参考にしたサイト

- 【CSS】 border-width を学ぶ【三角形で国旗を作る】
- https://sunsukeblog.com/css-border-width

## 更新履歴

- 2022/3/9 初版 完成（レスポンス対応済。表示崩れ解消。）
- 2022/3/9 初版 完成（レスポンス時のバッジの表示崩れがきになる）
- 2022/3/9 初版 作成中

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
