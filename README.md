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
| `mockup.md` | 見た目の型の比較(3案 × 2枚)。**型が決まったら削除する** |

`mockup.md` は本編とは別ファイル・別ポートで動かす捨てる前提の比較物。選ばれなかった案は消すだけで戻せる。

## デザインの型(mockup.md)

| ページ | 案 | 性格 |
| --- | --- | --- |
| p.2 / p.3 | 案一 行灯 | 闇に一点の灯り。静。文字が主役 |
| p.4 / p.5 | 案二 金屏風 | 黒地に金と朱。艶。円相と箔 |
| p.6 / p.7 | 案三 刻 | プロダクトの文法そのまま。動 |

素材はどの案も同じ2枚(骨子の2枚目「3つの困りごと」/ 6枚目「溶ける和ろうそく」)。動画はまだ無いので同サイズのプレースホルダー。

配色は KOKUKOKU 本体のパレット(`PanelElements.swift` の `Colors`)から採っている。

- 墨 `#16160F` 〜 `#0A0907`
- 生成り `#F8ECD8`
- 金茶 `#AB8A55` / 金 `#D9B45C`
- 朱 `#DA5932`(面で使わず点で置く)
- 炎色 `#FFF5D1` → `#FFA847` → グロー `#F25420`

## PDF出力

Playwrightが必要だが依存には入れていない。出すときだけ追加する。

```bash
bun add -D --exact playwright-chromium
bun run export
```
