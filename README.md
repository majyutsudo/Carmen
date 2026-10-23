CARMEN / OPERA v2.8.34

- iPhone表示検証用: Write / Focusの本文textareaを、スマホ幅でPreviewと同じフォント優先順位に変更。
- 金星・火星のU+FE0E追加を取り消し、通常のUnicode記号へ戻しました。
- デスクトップ・Preview・記号入力ロジックは変更なし。

CARMEN / OPERA v2.8.33

- ASTROLOGYの金星・火星にテキスト表示指定子 U+FE0E を付与。iPhoneの編集欄での表示改善を試験する小規模変更です。
- 既存の文字盤配置、入力・削除動作は変更していません。

CARMEN / OPERA v2.8.15-final.1

- 作品集から単一作品への変換時、作品境界の区切り線・タイトル・副題・クレジットを作品集プレビューに合わせて表示。
- 章見出しの「なし／小／標準／大／特大」の余白をプレビューへ反映。
- 作品集の作品情報が空欄でも変換可能。
- v2.8.15の読み込みダイアログは維持。

CARMEN / OPERA v2.8.15

更新: Word Oracleは再入場時に結果をクリアしMy Wordsに戻ります。スマートフォンの入力欄は16px以上の文字サイズに統一し、iOS Safariの自動ズームを抑制します。

## v2.8.9 — CARMEN QUICK GUIDE

メインメニューに「? ヘルプ」を追加。17項目の画面構成図と簡潔な機能説明を備えた全画面のクイックガイドです。スクロールは本文の1領域のみ。閲覧専用でユーザーデータには触れません。

## v2.8.9

COLLECTION EDITORでは画面下部の「作品を削除」を非表示にしました。作品の編集画面では引き続き使用できます。既存のデータは変更しません。

# CARMEN / OPERA

*An Instrument for Poetic Composition*

**CARMEN / OPERA** is a browser-based writing studio for poetry and lyrics, created by **Majyutsudo**. Write, revise, and organize your work in a quiet workspace designed for poetic composition.

Version **2.7.0**

## Launch the app

Open the published GitHub Pages website for this repository. The public app URL will be added here after deployment.

The app can also run from the included `index.html` file. Installing as a Progressive Web App (PWA) and service-worker-based offline use require HTTPS or localhost.

## Features

- Writing editor for poetry and lyrics, with preview and collections
- **Rhyme Book** and built-in Japanese/English dictionary and rhyme tools
- **Focus Mode** for distraction-free writing
- **Word Oracle**, with My Words, Tarot (one or three cards), and I Ching
- Five visual themes, including **Passion**
- Local storage and export/import tools for preserving your work

## Your work and privacy

CARMEN / OPERA requires no account. Works and personal dictionaries are stored in your browser, not automatically uploaded to GitHub or the app author. Data saved on one device, browser profile, or site origin is not automatically synchronized with another.

**Back up your work regularly** using the app's export features. Clearing browser data, using private browsing, or losing a device can remove locally stored work. When switching from a local `file://` copy to the hosted version, export your data from the old copy and import it into the new one.

After a successful first online load and service worker installation, the app may be available offline on supported browsers. Offline availability depends on the browser retaining the cache.

## License and credits

Free to use for personal or commercial writing. The poems, lyrics, and other works you create remain yours. Personal modifications to the application are permitted; redistribution, publication, or sale of the application or modified copies generally requires permission. This is **not an open-source software license**.

See [LICENSE](LICENSE) for the full terms and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for the separate licenses applying to embedded dictionary data. Third-party dictionary licenses are not restricted by the application's proprietary terms.

**Created by Majyutsudo**  
© 2026 Majyutsudo. All rights reserved, except as otherwise noted for third-party materials.

## v2.7.2

- Rhyme Finder: English / CMUdict 完全韻検索を追加。日本語検索は従来どおり。
- `.carmen` の作品・作品集読み込みで Ensemble ブロックとパートの関連を保持するよう修正。



## v2.7.2
選択テキストの近くに韻検索ツールを表示。Ensembleの表示スタイル（Ensemble／Parallel／Stacked）を追加。既存データは従来のEnsemble表示を維持します。Parallelは画面幅620px以下で縦1列になります。

## v2.7.8

- Writerで選択した語から韻検索へ移動する際、Rhyme Finderの先頭へスクロールします。
- 「Writeへ戻る」で元のWriterのスクロール位置を復元します。


## v2.7.8 — CARMENへの招待
「作品集を開く」ダイアログ右上に、読み取り専用の6幕ガイドツアーを追加。各幕のTRY ITから練習用作品を複製してWriterで編集できます。公式ガイドはユーザーのライブラリに追加されません。


v2.7.8: 「CARMENへの招待」を通常の作品集構造（章見出し・自由テキスト・作品）による読み物に改訂。練習ファイル作成機能を廃止し、閲覧だけで完結するガイドに変更。


### v2.8.9 小修正
- LIBRARYに.carmenの共通読み込み口を復帰し、作品・作品集とも読み込み前に確認します。
- 作品情報・クレジットはPCでも初期状態で折りたたみます。
- 作品集削除のチェックボックス配置を修正しました。
- 作品集の「＋下」と「差し替え」で既存作品を検索・選択できます。
- Rhyme BookとRhyme Finderの検索対象を説明文で明示しました。


## v2.8.9 試験機能
Rhyme Bookに辞書セットを追加。既存語は「マイライムブック」に属し、辞書セットごとに登録、検索、改名、削除、有効切替が可能です。CSVは従来5列に dictionary 列を追加（旧CSVも読み込み可能）。読み込み時に新規セット・既存セット・CSV記載のセットを選べます。DATAからセットごとにCSVを書き出せます。Rhyme Finderでは対象セットを指定できます。JMdictの外部辞書は「内蔵辞書に戻す」で解除できます。公開前の試験版です。


## v2.8.17
作品集を単一作品として読み込む際、最初の収録作品の前にも作品集プレビューと同じ区切り線を追加します。各作品の本文ブロックとその表示設定は変更せず引き継ぎます。


## v2.8.32
スクロール中に Write / Preview / Focus / 辞書（Rhyme Finder）へ移動できるコンパクトな固定ナビゲーションを追加。


## v2.8.32
スクロール中のナビゲーションを「作品／辞書／Preview／Focus」に整理。作品と辞書はドロップダウンで既存の各機能へ移動します。Writeから他の画面へ移動する際は表示中のブロックを記憶し、戻るとそのブロック付近へ復帰します。


v2.8.32: フロートバーを Write｜Preview｜作品▼（Structure / Characters / Focus）｜辞書▼ に変更。既存の画面遷移・編集位置復帰は維持。


## v2.8.32
通常の主要メニューの順序を「作品｜辞書｜管理｜作品集」に変更しました。機能・サブメニューは変更していません。


### v2.8.32
- 作品・辞書・管理・作品集で、作品名、作品情報・クレジット、版を保存の共通ヘッダーを表示します。
- Write専用の案内文はWrite画面だけに表示します。
- メニューや機能の切り替え処理は変更していません。


### v2.8.32
- 作品のサブメニューから重複した Preview を削除（独立ボタンは維持）。
- Title/Heading の余白「なし」で直前ブロックの既定の下余白を抑え、作品単体と作品集プレビューの双方に適用。
- Word Harvester を開く際、スマートフォンでもパネルの先頭を表示するよう移動位置を明示。Write の編集位置復帰は維持。


## v2.8.32
辞書6画面へのナビゲーション時に各画面の見出しを表示するようスクロール位置を統一。Writeのブロック位置復元は維持。

- v2.8.32: Global runic keyboard (Elder Futhark, insert into last selected text field or copy).


## v2.8.32

記号キーボードをRUNES / ASTROLOGY / SYMBOLSの3面（各24文字・6列×4段）に拡張。入力位置の記憶、1文字削除、クリア、コピーを維持。


### v2.8.32
- スマートフォンの記号キーボードのみ省スペース化（見出し・説明の省略、余白とキー高さを調整）。PC版と入力・削除の処理は変更なし。
- iPhoneの標準ソフトウェアキーボードは従来どおり閉じてから記号パネルを開く仕様。


v2.8.32: iPhone向けにVisual Viewportに合わせて記号キーボード起動ボタンを移動し、起動時は入力位置を保持したまま標準キーボードを閉じる試験的改修。PC版の配置と記号配列は変更なし。
