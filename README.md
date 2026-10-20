## v2.7.9

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
