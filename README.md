# 前澤クリニック 全ページ完成版

**[完成版ZIPをダウンロード（約42MB）](https://github.com/kanaiyukimi/2026/raw/refs/heads/main/maezawa-responsive-final.zip)**

ZIPをすべて展開し、`maezawa-responsive/index.html` をブラウザで開いてください。差分の追加は不要です。

## title・description

全22ページにページ別のtitle・meta descriptionを設定しました。TOPは指定文そのまま、下層ページは「ページ名 | 武蔵境の内科・小児科【前澤クリニック】」と、ページの概要文＋指定の共通文です。

[全ページの設定一覧（CSV）](seo-metadata.csv)

ブラウザでも全22ページの設定を確認し、本文・レイアウトが変わっていないことを確認しました。

## 完成内容

- 確定したTOP：h1「武蔵境の内科・小児科」と案内ボタンを中央揃え。上部キャッチコピーを削除し、余白を調整。
- 共通ヘッダー：PCはロゴ横に「武蔵境駅南口より徒歩7分」。
- ナビは「ホーム・クリニック紹介・診療案内・診療日案内・院長だより・交通案内」の6項目を常時表示。バーガーメニューなし。
- 診療案内は13項目のメニューボタン。PC3列、スマホは画面幅に応じて2列・1列。
- 全22ページ（ご提供の20ページ＋診療案内＋PDF一覧）とPDF219点すべてを収録。
- PDF検索、電話ボタン、診療時間表の横スクロールに対応。元の本文とPDFの内容を保持。

## 表示例

![PC版トップ](preview/home-desktop.png)

![PC版診療案内](preview/services-desktop.png)

<img src="preview/home-mobile.png" alt="スマホ版トップ" width="300"> <img src="preview/services-mobile.png" alt="スマホ版診療案内" width="300">

## 確認結果

全22ページを320・390・768・1024・1440pxの5幅で確認（110通り）。ページ全体の横はみ出し、画像読込失敗、JavaScriptエラーなし。ローカルリンク・ページ内アンカー・PDF検索・診療案内13リンクの遷移を確認しました。PDF219点は読込成功と原本とのSHA-256一致を確認しています。

実機SafariおよびGoogle地図・カレンダー等の外部サービスの到達性は未検証です。

## 導入と対象範囲

静的HTML版です。WordPress管理画面やPHPテーマは含みません。本番のWordPressテーマへそのまま上書きせず、同梱の `README.txt` を確認してください。

未提供の「院内感染対策について」と地図画像2点は元サイトへのリンクです。住所・アクセス・駐車位置の説明文は収録しています。

過去の確認版・差分ZIPも履歴として残っています。今回使用するファイルは **`maezawa-responsive-final.zip`** です。`maezawa-responsive-all.zip` も同じ完成版へ更新しています。
