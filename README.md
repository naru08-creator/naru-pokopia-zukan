# ぽこあポケモンデータ図鑑

**Pokémon Pokopia Data Guide**  
スマホで使いやすい、ぽこあポケモン向けの非公式データ図鑑です。

Googleスプレッドシートで整理したデータをもとに、ポケモンの「得意なこと」「好きな環境」「好きなもの」「ちらかすアイテム」から検索・絞り込みできるWebツールとして公開しています。

## Links

- **実際に使う:** [ぽこあポケモンデータ図鑑](https://naru08-creator.github.io/naru-pokopia-zukan/)
- **使い方・解説:** [このツールの解説記事](https://narunikki.hatenablog.com/entry/pokopiazukan)
- **活動ポータル:** [ゆるっとマイペースに推しごとチュウ ポータル](https://naru08-creator.github.io/narunikki_portal/)
- **関連記事一覧:** [ぽこあポケモン記事一覧](https://narunikki.hatenablog.com/archive/category/%E3%81%BD%E3%81%93%E3%81%82%E3%83%9D%E3%82%B1%E3%83%A2%E3%83%B3)

## What This Tool Does

- ポケモン名やキーワードで検索
- タグを使った絞り込み検索
- AND / OR 検索の切り替え
- 日本語 / English 表示の切り替え
- GoogleスプレッドシートのデータをCSVとして読み込み
- スマホで見やすいカード型表示
- お知らせを電光掲示板風に表示

## Design Focus

このツールでは、データ量が増えてもスマホで迷わず探せることを重視しています。

- 検索欄を画面上部に固定し、すぐ検索できるようにする
- 絞り込み条件をタグとして表示し、現在の条件が分かるようにする
- スマホでは表ではなくカード表示にして、ポケモン名を見つけやすくする
- ゲームの明るい雰囲気に合わせて、空・草・木の看板をイメージした軽量なCSSデザインにする
- 画像や重い演出に頼らず、GitHub Pages上で軽く動く構成にする

## Data Flow

```text
Google Spreadsheet
        ↓ CSV
index.html
        ↓
Search / Filter / Language Switch
        ↓
GitHub Pages
```

## Tech

- HTML
- CSS
- JavaScript
- Google Sheets CSV
- GitHub Pages

## Notes

このサイトは「ぽこあポケモン」の非公式ファンサイトです。  
公式情報ではなく、個人が整理したデータ・メモをもとに制作しています。

## About the Creator

AIやUI設計を使って、情報を見やすく・使いやすく整理する個人クリエイターとして活動しています。  
制作物やブログはポータルにまとめています。

👉 [活動ポータルを見る](https://naru08-creator.github.io/narunikki_portal/)
