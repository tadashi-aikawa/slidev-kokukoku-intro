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
title: 3つの困りごと
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
<div class="d-col d-col-title" style="--d:0.60s"><h1>3つの困りごと</h1></div>
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
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>数字キーで計測、qで消す</div>
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
