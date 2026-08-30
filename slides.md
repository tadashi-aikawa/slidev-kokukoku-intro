---
title: KOKUKOKU — 刻一刻と時を見守る
colorSchema: dark
canvasWidth: 1280
routerMode: hash
transition: fade-out
fonts:
  provider: none
  sans: ["Zen Old Mincho", "Hiragino Mincho ProN"]
  serif: ["Zen Old Mincho", "Hiragino Mincho ProN"]
layout: cover
class: mk-scroll kokukoku-cover
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-cover">
<div class="d-cover-cols">
<div class="d-gaidai">
<span class="d-gaidai-ja">刻刻</span>
<span class="d-gaidai-en">KOKUKOKU</span>
<span class="d-gaidai-sub">刻一刻と時を見守る</span>
</div>
<div class="d-cover-meta" style="--d:0.76s">macOS 用・自作の常駐パネル</div>
</div>
<img class="d-cover-logo" src="./public/media/kokukoku.webp" alt="KOKUKOKU" />
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>

<style>
.kokukoku-cover .d-cover {
  justify-content: center;
  align-items: center;
}
.kokukoku-cover .d-cover-cols {
  display: flex;
  flex-direction: row-reverse;
  align-items: center;
}
.kokukoku-cover .d-gaidai {
  display: flex;
  flex-direction: row-reverse;
  align-items: flex-start;
  justify-content: center;
  box-sizing: border-box;
  width: 196px;
  height: 300px;
  margin-left: 52px;
  padding: 30px 20px 0;
  background: #f5edd7;
  border: 1px solid rgba(60, 48, 26, 0.5);
  box-shadow:
    0 6px 16px rgba(90, 66, 28, 0.22),
    inset 0 0 0 5px #f5edd7,
    inset 0 0 0 6px rgba(60, 48, 26, 0.28);
  opacity: 0;
  animation: d-in 0.5s 0.56s ease-out forwards;
}
.kokukoku-cover .d-gaidai-ja {
  writing-mode: vertical-rl;
  font-size: 62px;
  font-weight: 500;
  letter-spacing: 0.16em;
  color: #241d13;
}
.kokukoku-cover .d-gaidai-en {
  writing-mode: vertical-rl;
  text-orientation: upright;
  margin-right: 12px;
  padding-top: 6px;
  font-size: 13px;
  letter-spacing: 0.34em;
  color: #7a6e58;
}
.kokukoku-cover .d-gaidai-sub {
  writing-mode: vertical-rl;
  margin-right: 26px;
  padding-top: 4px;
  font-size: 21px;
  letter-spacing: 0.2em;
  color: #3b3123;
}
.kokukoku-cover .d-cover-meta {
  writing-mode: vertical-rl;
  padding-top: 44px;
  font-size: 15px;
  letter-spacing: 0.2em;
  color: #6e6353;
  opacity: 0;
  animation: d-in 0.5s var(--d) ease-out forwards;
}
.kokukoku-cover .d-cover-logo {
  position: absolute;
  left: 42px;
  bottom: 28px;
  width: 92px;
  height: 92px;
  object-fit: contain;
  opacity: 0;
  mix-blend-mode: multiply;
  animation: d-in 0.42s 0.98s ease-out forwards;
}
</style>

---
title: 三つの困りごと
class: mk-scroll kokukoku-problems
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-text">
<div class="d-cols">
<div class="d-daisen">困 り ご と</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>三つの困りごと</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>何に時間を使ったか分からない</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>次の予定まで、あと何分か<em>知りたいのは予定と予定の「間」</em></div>
<div class="d-col" style="--d:0.86s"><span class="d-no">三</span>集中すると休憩を忘れる</div>
<div class="d-col d-col-close" style="--d:0.94s">三つとも判断の材料。ひとつのパネルに</div>
</div>
<div class="d-art">
<svg class="d-clock" viewBox="0 0 240 240" aria-hidden="true">
<circle class="d-ring" cx="120" cy="120" r="104" pathLength="100"/>
<circle class="d-ring2" cx="120" cy="120" r="86"/>
<g class="d-tick">
<line x1="120" y1="26" x2="120" y2="40"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(30 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(60 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(90 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(120 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(150 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(180 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(210 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(240 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(270 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(300 120 120)"/>
<line x1="120" y1="26" x2="120" y2="40" transform="rotate(330 120 120)"/>
</g>
<g class="d-hands">
<line class="d-hand-h" x1="120" y1="120" x2="120" y2="66"/>
<line class="d-hand-m" x1="120" y1="120" x2="120" y2="44"/>
<circle class="d-pivot" cx="120" cy="120" r="4.5"/>
</g>
</svg>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">2 / 9</div>

<style>
.kokukoku-problems .d-clock {
  width: 314px;
  height: 314px;
  fill: none;
}
.kokukoku-problems .d-ring {
  stroke: #2c2419;
  stroke-width: 2.6;
  stroke-linecap: round;
  opacity: 0.82;
  stroke-dasharray: 100 100;
  stroke-dashoffset: 100;
  animation: problems-draw 0.55s 0.58s cubic-bezier(0.26, 0.7, 0.3, 1) forwards;
}
@keyframes problems-draw {
  to { stroke-dashoffset: 0; }
}
.kokukoku-problems .d-ring2 {
  stroke: rgba(44, 36, 25, 0.22);
  stroke-width: 1;
  opacity: 0;
  animation: d-fade 0.28s 1.05s ease-out forwards;
}
.kokukoku-problems .d-tick line {
  stroke: rgba(44, 36, 25, 0.5);
  stroke-width: 1.6;
  stroke-linecap: round;
}
.kokukoku-problems .d-tick,
.kokukoku-problems .d-hands {
  opacity: 0;
  animation: d-fade 0.28s 1.12s ease-out forwards;
}
.kokukoku-problems .d-hand-h {
  stroke: #2c2419;
  stroke-width: 4;
  stroke-linecap: round;
  transform-origin: 120px 120px;
  transform: rotate(-58deg);
}
.kokukoku-problems .d-hand-m {
  stroke: #2c2419;
  stroke-width: 2.4;
  stroke-linecap: round;
  transform-origin: 120px 120px;
  animation: problems-spin 24s linear infinite;
}
@keyframes problems-spin {
  from { transform: rotate(58deg); }
  to { transform: rotate(418deg); }
}
.kokukoku-problems .d-pivot {
  fill: #b23f26;
  stroke: none;
}
</style>

---
title: 呼び出して、計測する
class: mk-scroll kokukoku-demo
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">計 測</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>呼び出して、計測する</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>ホットキーで画面中央へ</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>数字キーで計測、<span class="d-upright">q</span>で消す</div>
</div>
<div class="d-art">
<div class="d-figbox">
<div class="d-fig">
<SlidevVideo autoplay="once" autoreset="slide" muted playsinline>
<source src="./public/media/demo-a-invoke-and-track-tight.mp4" type="video/mp4" />
</SlidevVideo>
</div>
<div class="d-figcap">図<span class="d-cap-no">一</span> ― マウスに触れず、数秒で計測</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">3 / 9</div>

<style>
.kokukoku-demo .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-demo .d-fig {
  width: 448px;
  aspect-ratio: 864 / 896;
}
</style>

---
title: パネルの中身
class: mk-scroll kokukoku-anatomy
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">一 枚 の 中</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>パネルの中身</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>上から、計測・予定・和ろうそく</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>結果と予定は、日報へそのままコピー</div>
</div>
<div class="d-art">
<div class="d-figbox">
<div class="d-fig"><img src="./public/media/still-panel.png" alt="KOKUKOKUのパネル全体" /></div>
<div class="d-figcap">図<span class="d-cap-no">一</span> ― 計測・今日の予定・連続作業を一枚に</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">4 / 9</div>

<style>
.kokukoku-anatomy .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-anatomy .d-fig {
  width: 438px;
  aspect-ratio: 890 / 934;
}
.kokukoku-anatomy .d-fig img {
  object-fit: contain;
}
</style>

---
title: 予定は「間隔」で見る
class: mk-scroll kokukoku-intervals
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">間 隔</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>予定は「間隔」で見る</h1></div>
<div class="d-col" style="--d:0.70s">知りたいのは、予定と予定の「間」</div>
</div>
<div class="d-art">
<div class="d-figpair">
<div class="d-figbox d-figbox-still">
<div class="d-fig d-fig-still"><img src="./public/media/still-timeline-rails-crop.png" alt="空き・連続・重複を示す予定レール" /></div>
<div class="d-figcap">図<span class="d-cap-no">一</span> ― 空き・連続・重複を色で</div>
</div>
<div class="d-figbox d-figbox-video">
<div class="d-fig d-fig-video">
<SlidevVideo autoplay="once" autoreset="slide" muted playsinline>
<source src="./public/media/demo-b-calendar-notification-tight.mp4" type="video/mp4" />
</SlidevVideo>
</div>
<div class="d-figcap">図<span class="d-cap-no">二</span> ― 触らず通知。フォーカスは奪わない</div>
</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">5 / 9</div>

<style>
.kokukoku-intervals .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-intervals .d-figpair {
  align-items: flex-start;
  gap: 20px;
}
.kokukoku-intervals .d-figbox-still {
  flex: 0 0 226px;
}
.kokukoku-intervals .d-fig-still {
  width: 100%;
  aspect-ratio: 436 / 294;
}
.kokukoku-intervals .d-figbox-video {
  flex: 1 1 auto;
}
.kokukoku-intervals .d-fig-video {
  width: 100%;
  aspect-ratio: 2220 / 930;
}
.kokukoku-intervals .d-figcap {
  max-width: 430px;
  font-size: 12px;
  letter-spacing: 0.1em;
}
</style>

---
title: 溶ける和ろうそく
class: mk-scroll kokukoku-candle
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">連 続 作 業</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>溶ける和ろうそく</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>溜まるバーではなく、減る蝋燭</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>数字は出さない<em>「そろそろ」だけを伝える</em></div>
</div>
<div class="d-art">
<div class="d-figbox">
<div class="d-fig">
<SlidevVideo autoplay="once" autoreset="slide" muted playsinline>
<source src="./public/media/demo-c-candle-burnout.mp4" type="video/mp4" />
</SlidevVideo>
</div>
<div class="d-figcap">図<span class="d-cap-no">一</span> ― 燃え尽きたら煙。休憩で、新しい一本</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">6 / 9</div>

<style>
.kokukoku-candle .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-candle .d-fig {
  width: 408px;
  aspect-ratio: 864 / 944;
}
</style>

---
title: 和の意匠は全部、機能
class: mk-scroll kokukoku-motifs
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">意 匠 と 機 能</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>和の意匠は全部、機能</h1></div>
<div class="d-col" style="--d:0.70s">意味と形が一致するから、覚えなくていい</div>
</div>
<div class="d-art">
<div class="d-icon-grid">
<div class="d-icon-card" style="--d:0.68s">
<img src="./public/media/icon-candle.svg" alt="和ろうそく" />
<div><b>和ろうそく</b><span>連続作業の残り</span></div>
</div>
<div class="d-icon-card" style="--d:0.76s">
<img src="./public/media/icon-kanzashi-pinned.svg" alt="玉簪" />
<div><b>玉簪</b><span>パネルを固定</span></div>
</div>
<div class="d-icon-card" style="--d:0.84s">
<img src="./public/media/icon-soroban.svg" alt="そろばん" />
<div><b>そろばん</b><span>計測をご破算</span></div>
</div>
<div class="d-icon-card" style="--d:0.92s">
<img src="./public/media/icon-clock.svg" alt="和紙の丸窓" />
<div><b>和紙の丸窓</b><span>いまの時刻</span></div>
</div>
<div class="d-icon-note">図<span class="d-cap-no">一</span> ― パネルの和の意匠は、すべてコードで描いたSVG</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">7 / 9</div>

<style>
.kokukoku-motifs .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-motifs .d-icon-grid {
  display: grid;
  grid-template-columns: repeat(2, 250px);
  gap: 20px 22px;
  align-content: center;
}
.kokukoku-motifs .d-icon-card {
  display: grid;
  grid-template-columns: 82px 1fr;
  align-items: center;
  min-height: 118px;
  padding: 14px 16px;
  background: rgba(247, 240, 220, 0.7);
  border: 1px solid rgba(60, 48, 26, 0.28);
  box-shadow: 0 8px 18px rgba(90, 66, 28, 0.16);
  opacity: 0;
  animation: d-in 0.45s var(--d) ease-out forwards;
}
.kokukoku-motifs .d-icon-card img {
  width: 68px;
  max-height: 76px;
  object-fit: contain;
  justify-self: center;
}
.kokukoku-motifs .d-icon-card:nth-child(3) img {
  filter: brightness(0) saturate(100%);
  opacity: 0.78;
}
.kokukoku-motifs .d-icon-card b,
.kokukoku-motifs .d-icon-card span {
  display: block;
}
.kokukoku-motifs .d-icon-card b {
  color: #2c2419;
  font-size: 20px;
  font-weight: 500;
  letter-spacing: 0.08em;
}
.kokukoku-motifs .d-icon-card span {
  margin-top: 6px;
  color: #6e6353;
  font-size: 14px;
  letter-spacing: 0.08em;
}
.kokukoku-motifs .d-icon-note {
  grid-column: 1 / -1;
  color: #6e6353;
  font-size: 13px;
  letter-spacing: 0.12em;
  text-align: center;
  opacity: 0;
  animation: d-in 0.45s 1s ease-out forwards;
}
</style>

---
title: 使い始め方
class: mk-scroll kokukoku-install
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-art">
<div class="d-cols">
<div class="d-daisen">使 い 始 め 方</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>使い始め方</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>一行で入れる</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>設定は一枚だけ</div>
</div>
<div class="d-art">
<div class="d-figbox d-figbox-paste">
<div class="d-paste d-paste-cmd">
<pre class="d-cmd"><span class="d-prompt">$</span>brew install --cask tadashi-aikawa/tap/kokukoku</pre>
</div>
<div class="d-paste d-paste-conf">
<div class="d-paste-label">設定</div>
<div class="d-paste-note">~/.config/kokukoku/config.toml</div>
</div>
<div class="d-figcap">貼紙 ― Homebrew の一行と、TOML 一枚</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-page-number">8 / 9</div>

<style>
.kokukoku-install .d-art {
  flex: 1 1 auto;
  width: 0;
}
.kokukoku-install .d-figbox-paste {
  flex: 0 0 auto;
}
.kokukoku-install .d-paste-cmd {
  padding: 34px 34px 30px;
}
.kokukoku-install .d-cmd {
  font-size: 18px;
  line-height: 1.8;
}
.kokukoku-install .d-paste-conf {
  align-self: flex-start;
  display: flex;
  align-items: baseline;
  gap: 18px;
  margin: 26px 0 0 52px;
  padding: 17px 26px;
  transform: rotate(0.7deg);
}
.kokukoku-install .d-paste-label {
  color: #b23f26;
  font-size: 14px;
  letter-spacing: 0.18em;
}
.kokukoku-install .d-paste-note {
  color: #5e5443;
  font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace;
  font-size: 15px;
  letter-spacing: 0.02em;
}
</style>

---
title: 刻一刻と時を見守る
layout: cover
class: mk-scroll kokukoku-closing
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-closing">
<div class="d-closing-copy">
<div class="d-closing-title">刻一刻と時を見守る</div>
<div class="d-closing-name">KOKUKOKU・刻刻</div>
</div>
<div class="d-repo-url">github.com/tadashi-aikawa/kokukoku</div>
<img class="d-closing-logo" src="./public/media/kokukoku.webp" alt="KOKUKOKU" />
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>

<style>
.kokukoku-closing .d-closing {
  align-items: center;
  justify-content: center;
}
.kokukoku-closing .d-closing-copy {
  display: flex;
  flex-direction: row-reverse;
  align-items: flex-start;
  opacity: 0;
  animation: d-in 0.5s 0.58s ease-out forwards;
}
.kokukoku-closing .d-closing-title {
  writing-mode: vertical-rl;
  color: #241d13;
  font-size: 42px;
  font-weight: 500;
  letter-spacing: 0.16em;
}
.kokukoku-closing .d-closing-name {
  writing-mode: vertical-rl;
  text-orientation: upright;
  margin-right: 24px;
  padding-top: 6px;
  color: #6e6353;
  font-size: 14px;
  letter-spacing: 0.24em;
}
.kokukoku-closing .d-repo-url {
  position: absolute;
  left: 50%;
  bottom: 35px;
  transform: translateX(-50%);
  color: #6e6353;
  font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace;
  font-size: 15px;
  letter-spacing: 0.03em;
  opacity: 0;
  animation: closing-url-in 0.42s 0.9s ease-out forwards;
}
@keyframes closing-url-in {
  from { opacity: 0; transform: translate(-50%, 8px); }
  to { opacity: 1; transform: translate(-50%, 0); }
}
.kokukoku-closing .d-closing-logo {
  position: absolute;
  left: 42px;
  bottom: 28px;
  width: 92px;
  height: 92px;
  object-fit: contain;
  opacity: 0;
  mix-blend-mode: multiply;
  animation: d-in 0.42s 0.98s ease-out forwards;
}
</style>
