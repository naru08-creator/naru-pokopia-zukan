<img width="300" alt="スクリーンショット 2026-05-23 220812" src="https://github.com/user-attachments/assets/177debc6-bf46-4fc0-a5aa-759c59be20e1" />
<img width="300" alt="スクリーンショット 2026-05-23 220827" src="https://github.com/user-attachments/assets/5cab4b85-9283-40e3-8b2e-f900c93ac3c1" />

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

## Why I Made This

ゲーム内では「好きな環境」や「好きなもの」を検索しづらく、
もっと探しやすい図鑑が欲しいと思ったことがきっかけです。

そして、ポケモンたちに「すみごこち最高！」と言ってもらえる空間づくりを、
もっと楽しめるようにしたいと思って制作しました。

最初は個人用に作り始めたツールですが、
少しずつ公開用のデータ図鑑として整えていっています。

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

## Feedback

使ってみた感想や、
「こんなふうに使ったよ！」などあればぜひ教えてください。

改善アイデアや不具合報告も歓迎です。

## Notes

このサイトは「ぽこあポケモン」の非公式ファンサイトです。  
公式情報ではなく、個人が整理したデータ・メモをもとに制作しています。

## About the Creator

AIやUI設計を使って、情報を見やすく・使いやすく整理する個人クリエイターとして活動しています。  
制作物やブログはポータルにまとめています。

👉 [活動ポータルを見る](https://naru08-creator.github.io/narunikki_portal/)

---
<img width="300" alt="ぽこあポケモンデータ図鑑 英語版" src="https://github.com/user-attachments/assets/bd8a644a-6016-456d-aa7e-c0803980e93c" />
<img width="300" alt="ぽこあポケモンデータ図鑑 英語版 ボタン" src="https://github.com/user-attachments/assets/609ad2ad-fbc7-4de6-a912-0676b0e7b178" />

# Pokémon Pokopia Data Guide

An unofficial data guide for **Pokémon Pokopia**, designed primarily for comfortable use on smartphones.

This tool turns data organized in Google Sheets into a lightweight web app where users can search and filter Pokémon by specialties, ideal habitats, favorite things, and littered items.

## Links

- **Live Demo:** [Pokémon Pokopia Data Guide](https://naru08-creator.github.io/naru-pokopia-zukan/)
- **How to Use:** [Guide article](https://narunikki.hatenablog.com/entry/pokopiazukan)
- **Creator Portal:** [Yurutto My Pace ni Oshigoto-chu Portal](https://naru08-creator.github.io/narunikki_portal/)
- **Related Articles:** [Pokémon Pokopia article list](https://narunikki.hatenablog.com/archive/category/%E3%81%BD%E3%81%93%E3%81%82%E3%83%9D%E3%82%B1%E3%83%A2%E3%83%B3)

## What This Tool Does

- Search by Pokémon name or keywords
- Filter data with selectable tags
- Switch between AND / OR search
- Switch between Japanese and English display
- Load data from Google Sheets as CSV
- Show results in a mobile-friendly card layout
- Display announcements in a marquee-style news banner

## Design Focus

The main goal of this tool is to make a growing amount of data easy to search and understand on a smartphone.

- Keep the search area fixed near the top for quick access
- Show active filters as tags so the current search conditions are visible
- Use card-style results on mobile instead of a dense table
- Use lightweight CSS inspired by the bright sky, grass, and wooden signboard feeling of the game
- Avoid heavy visual effects so the tool stays simple and fast on GitHub Pages

## Why I Made This

In Pokémon Pokopia, it can be difficult to search for information such as favorite environments and favorite items directly inside the game.

I wanted a simpler and more comfortable way to organize that information.

I also wanted to help players create spaces where Pokémon would happily say:
“Perfect comfort!”

This project started as a personal fan tool and gradually evolved into a public data guide for other players as well.

## Data Flow

```text
Google Spreadsheet
        -> CSV
index.html
        ->
Search / Filter / Language Switch
        ->
GitHub Pages
```

## Tech

- HTML
- CSS
- JavaScript
- Google Sheets CSV
- GitHub Pages

## Feedback

If you tried this tool, I’d love to hear how you used it.

What worked well?
What was difficult to use?
What features would you like to see next?

Feedback, bug reports, and ideas are always welcome.

## Notes

This is an unofficial fan site for **Pokémon Pokopia**.  
It is based on personally organized data and notes, not official data.

## About the Creator

I create small web tools and content using AI, UI design, and information organization.  
My works and blog are collected on my portal site.

👉 [Visit the creator portal](https://naru08-creator.github.io/narunikki_portal/)
