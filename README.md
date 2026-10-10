# kouminiku-9900.github.io

アルケミス松田エンジニアリング（Alchemis Matsuda Engineering）の公開サイト。`main` がそのまま GitHub Pages で配信される。

## 構成

| パス | 内容 |
| --- | --- |
| `/alchemis/` | 事業者サイト。Home（`index.html`）/ About（`about.html`）/ Works（`works.html`）の3ページ構成で、英語版は `en.html` / `about-en.html` / `works-en.html`。運営・販売者情報（代表者名・所在地・連絡先）は About だけに載せ、全アプリページのフッターの「運営・販売者情報」は `about.html` / `about-en.html` に張っている。Works にはストア公開済みのアプリだけを出す（未公開分はHTMLコメントで伏せてある） |
| `/five-disc-changer/` | 5連ディスクチェンジャーポータブル（iOS）。`android/` に Android 版 |
| `/local-shuffle/` | ローカル動画シャッフルくん。直下が Android、`ios/` が iOS、`mac/` が Mac 版 |
| `/screentime-roast/` | スクリーンタイム煽り |

## 旧URL（消さないこと）

ルート直下の HTML は、ストアやアプリ内に登録済みの旧URLを生かすための転送ページ。

| 旧URL | 転送先 |
| --- | --- |
| `/` | `/local-shuffle/ios/privacy-ja.html`（iOS版ローカル動画シャッフルくんのプライバシーポリシーURL・サポートURLとしてApp Storeに登録済み。次のバージョン提出時にURLを差し替えたら `/alchemis/` に変えてよい） |
| `/en.html` | `/local-shuffle/ios/privacy.html` |
| `/privacy(-ja).html` `/support(-ja).html` `/terms(-ja).html` | `/local-shuffle/mac/` の同名ファイル |

`googlef34a15efe1ff6756.html` は Google Search Console の確認用。
