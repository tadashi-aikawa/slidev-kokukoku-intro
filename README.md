# slidev-kokukoku-intro

社内LT「KOKUKOKU」紹介(5分・2026-09-14)のスライド。[slidev-sandbox](https://github.com/tadashi-aikawa/slidev-sandbox) を原本に作成。

## 起動

```bash
bun install
bun dev      # 本編 slides.md → http://localhost:3030
bun mockup   # デザインの型の比較 mockup.md → http://localhost:3050
```

## ファイル

| ファイル | 中身 |
| --- | --- |
| `slides.md` | 本編。骨子(9枚)をもとに展開する |
| `mockup.md` | 見た目の型の比較(4案 × 2枚)。**型が決まったら削除する** |
| `public/media/` | デモ動画A・B・C |
| `public/fonts/` | 同梱フォント(下記) |

`mockup.md` は本編とは別ファイル・別ポートで動かす捨てる前提の比較物。選ばれなかった案は消すだけで戻せる。

## デザインの型(mockup.md)

| ページ | 案 | 性格 |
| --- | --- | --- |
| p.2 / p.3 | 案一 行灯 | 闇に一点の灯り。静。文字が主役 |
| p.4 / p.5 | 案二 金屏風 | 黒地に金と朱。艶。円相と箔。**選定済み** |
| p.6 / p.7 | 案三 刻 | プロダクトの文法そのまま。動 |
| p.8 / p.9 | 案四 巻物 | 紙に墨と朱。書。横へ繰り出し、縦組み |

素材はどの案も同じ2枚(骨子の2枚目「3つの困りごと」/ 6枚目「溶ける和ろうそく」)。動画枠は案二 p.5 と案四 p.9 だけ実物(動画C)に差し替え済みで、案一・案三はプレースホルダーのまま。

配色は KOKUKOKU 本体のパレット(`PanelElements.swift` の `Colors`)から採っている。

- 墨 `#16160F` 〜 `#0A0907`
- 生成り `#F8ECD8`
- 金茶 `#AB8A55` / 金 `#D9B45C`
- 朱 `#DA5932`(面で使わず点で置く)
- 炎色 `#FFF5D1` → `#FFA847` → グロー `#F25420`

案四は同じ絵の具のまま地を「黒」から「紙」へ裏返した派生。**金は黒の世界、墨と朱は紙の世界**と持ち場を分けてある。

- 紙 `#F1E6C9` → `#CBB78D`(古色の和紙)
- 墨 `#2C2419` / 淡墨 `#6E6353`
- 朱 `#B23F26`(番号)/ 落款 `#C4432A` を `mix-blend-mode: multiply` で紙に沈める
- 金は軸頭と黒地の金泥だけに残す

## 動画(public/media/)

| ファイル | 中身 | 寸法 | 尺 |
| --- | --- | --- | --- |
| `demo-a-invoke-and-track.mp4` | 呼び出して計測する | 1440×900 | 5.0秒 |
| `demo-b-calendar-notification.mp4` | カレンダー通知 | 1440×814 | 9.0秒 |
| `demo-c-candle-burnout.mp4` | 和ろうそくの燃え尽き | 1440×800 | 11.3秒 |

**16:9ではない**ので、枠は `aspect-ratio: 1440 / 800` のように実寸で書く。音声なしなので `autoplay muted loop playsinline` で置く。

markdownのHTMLから参照するときのパスは `./public/media/...`(`slides.md` のパス早見表に従う)。

## 同梱フォント(public/fonts/)

| フォント | ウェイト | ライセンス |
| --- | --- | --- |
| [Zen Old Mincho](https://github.com/googlefonts/zen-oldmincho) | 400 / 500 | SIL Open Font License 1.1 |

ライセンス全文は `public/fonts/ZenOldMincho-OFL.txt`。`@font-face` は `styles/index.css` の先頭で宣言している(スライド内の `<style>` は1枚ごとにスコープされるため、そこには置けない)。

`mockup.md` のheadmatterは `provider: none` にしてあり、**選ばれた案二・案四はネットワークなしで正しく出る**。案一(Shippori Mincho B1)・案三(Zen Kaku Gothic New)は選外なので同梱せず、macOS同梱のヒラギノへフォールバックする。

**本編を組むときの宿題**: `styles/index.css` の先頭に原本(slidev-sandbox)から引き継いだ外部 `@import`(Noto Sans JP / Nerd Fonts)が残っている。会場のネットワークが不安なら、本編の書体を決めるのと同時に外す。

## PDF出力

Playwrightが必要だが依存には入れていない。出すときだけ追加する。

```bash
bun add -D --exact playwright-chromium
bun run export
```
