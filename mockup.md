---
title: KOKUKOKU 紹介LT デザインの型 比較
colorSchema: dark
canvasWidth: 1280
routerMode: hash
transition: fade
fonts:
  provider: none
  sans: ["Hiragino Sans", "Noto Sans JP"]
  serif: ["Zen Old Mincho", "Hiragino Mincho ProN"]
class: mk-index
---

<div class="idx">
<div class="idx-kicker">KOKUKOKU 紹介LT(5分)</div>
<h1>見た目の型・4案</h1>
<p class="idx-lead">同じ2枚(2枚目「3つの困りごと」/ 6枚目「溶ける和ろうそく」)を、4つの型で作り分けました。<br/>違うのは <b>光の質</b> と <b>動きの量</b>。案四だけ、<b>全9枚を通すための枚</b>を足してあります。</p>
<div class="idx-grid">
<div class="idx-card">
<div class="idx-no">案 一</div>
<div class="idx-name">行灯 <span>あんどん</span></div>
<div class="idx-note">闇に一点の灯り。<b>静</b>。<br/>文字が主役で、動きは滲みだけ。</div>
<div class="idx-page">p.2 / p.3</div>
</div>
<div class="idx-card idx-card-picked">
<div class="idx-no">案 二</div>
<div class="idx-name">金屏風 <span>きんびょうぶ</span></div>
<div class="idx-note">黒地に金と朱。<b>艶</b>。<br/>円相が描かれ、箔がきらめく。</div>
<div class="idx-page">p.4 / p.5</div>
</div>
<div class="idx-card">
<div class="idx-no">案 三</div>
<div class="idx-name">刻 <span>こく</span></div>
<div class="idx-note">プロダクトの文法そのまま。<b>動</b>。<br/>行が灯り、蝋燭が本当に溶ける。</div>
<div class="idx-page">p.6 / p.7</div>
</div>
<div class="idx-card idx-card-new">
<div class="idx-no">案 四</div>
<div class="idx-name">巻物 <span>まきもの</span></div>
<div class="idx-note">紙に墨と朱。<b>書</b>。<br/>横へ繰り出され、縦組みで読む。</div>
<div class="idx-page">p.8 〜 p.12</div>
</div>
</div>
<div class="idx-foot"><b>全9枚を案四で通せるか</b>を確かめる枚を足しました。紙を高くし(510→600px)、繰り出しを <b>1.5秒 → 0.75秒</b>・出揃いを <b>2.6秒 → 1.4秒</b>へ。型は2変奏 ── <b>詞書が主</b>(p.8 / p.9)と<b>絵が主</b>(p.11 / p.12)。難所の3枚が p.10 表紙(題箋だけ)・p.11 予定は「間隔」で見る(絵2点)・p.12 使い始め方(横書きのコマンドを貼紙で)です。</div>
</div>

<style>
.slidev-layout.mk-index {
  padding: 44px 64px 30px;
  background: radial-gradient(120% 90% at 50% 0%, #17170F 0%, #0B0B09 62%);
  color: #F8ECD8;
  letter-spacing: 0.02em;
  font-family: "Hiragino Sans", "Noto Sans JP", sans-serif;
  display: flex; flex-direction: column;
}
.idx { display: flex; flex-direction: column; height: 100%; }
.idx-kicker { font-size: 17px; letter-spacing: 0.34em; color: #AB8A55; }
.slidev-layout.mk-index h1 {
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", serif;
  font-size: 48px; font-weight: 500; color: #F8ECD8; margin: 8px 0 14px; letter-spacing: 0.1em;
}
.idx-lead { font-size: 19px; line-height: 1.85; color: #C4B79E; margin: 0; }
.idx-lead b { color: #E7C878; font-weight: 500; }
.idx-grid { margin-top: 26px; display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; }
.idx-card { position: relative; border: 1px solid #3A3428; border-top: 2px solid #AB8A55; padding: 16px 18px 14px; background: rgba(255,255,255,0.015); }
.idx-card-picked { border-top-color: #D9B45C; background: rgba(217,180,92,0.05); }
.idx-card-new { border-top-color: #D9B45C; background: rgba(217,180,92,0.05); }
.idx-card-picked::after, .idx-card-new::after {
  position: absolute; right: 14px; top: 12px; font-size: 11px; letter-spacing: 0.18em; color: #DA5932;
}
.idx-card-picked::after { content: "選定"; }
.idx-card-new::after { content: "統一案"; }
.idx-no { font-family: "Zen Old Mincho", serif; font-size: 14px; letter-spacing: 0.3em; color: #AB8A55; }
.idx-name { font-family: "Zen Old Mincho", "Hiragino Mincho ProN", serif; font-size: 28px; margin: 5px 0 10px; letter-spacing: 0.06em; }
.idx-name span { display: block; font-size: 12px; color: #8A8069; letter-spacing: 0.2em; margin: 2px 0 0; }
.idx-note { font-size: 15px; line-height: 1.75; color: #C4B79E; }
.idx-note b { color: #E7C878; font-weight: 500; }
.idx-page { margin-top: 12px; font-size: 14px; color: #DA5932; letter-spacing: 0.14em; }
.idx-foot { margin-top: auto; font-size: 15px; line-height: 1.9; color: #8A8069; border-top: 1px solid #26241C; padding-top: 14px; }
.idx-foot b { color: #C4B79E; font-weight: 500; }
</style>

---
title: 案一 行灯 / 3つの困りごと
class: mk-a2
transition: fade
---

<div class="a-lamp"></div>
<div class="a-body">
<div class="a-eyebrow">困 り ご と</div>
<h1>3つの困りごと</h1>
<ul class="a-list">
<li style="--d:.75s">何にどれだけ時間を使ったか、<b>後から分からない</b></li>
<li style="--d:1.15s">次の予定まで<b>あと何分</b>か、カレンダーを開きに行く<em>予定そのものより、予定と予定の「間」が知りたい</em></li>
<li style="--d:1.55s">集中すると<b>休憩を忘れる</b>。気づいたら疲れている</li>
</ul>
<div class="a-close">どれも「いま何をするか」の材料。ひとつのパネルで済ませたかった</div>
</div>
<div class="a-tag">案一 行灯</div>

<style>
.slidev-layout.mk-a2 {
  padding: 0; background: #0B0B09; color: #F8ECD8;
  letter-spacing: 0.04em; overflow: hidden; position: relative;
  font-family: "Shippori Mincho B1", "Hiragino Mincho ProN", "Yu Mincho", serif;
  display: flex; align-items: flex-start; padding-top: 86px;
}
.a-lamp {
  position: absolute; right: -4%; top: 50%; width: 78%; height: 170%; transform: translateY(-50%);
  background:
    radial-gradient(30% 26% at 60% 50%, rgba(255,205,110,0.26) 0%, rgba(255,205,110,0) 100%),
    radial-gradient(54% 48% at 60% 50%, rgba(212,132,44,0.14) 0%, rgba(0,0,0,0) 100%);
  animation: a-breathe 7s ease-in-out infinite;
}
@keyframes a-breathe {
  0%, 100% { opacity: 0.78; transform: translateY(-50%) scale(1); }
  50%      { opacity: 1;    transform: translateY(-50%) scale(1.06); }
}
.a-body { position: relative; margin-left: 96px; width: 700px; }
.a-eyebrow { font-size: 15px; letter-spacing: 0.5em; color: #AB8A55; opacity: 0; animation: a-rise .9s .1s ease-out forwards; }
.slidev-layout.mk-a2 h1 {
  font-size: 46px; font-weight: 400; line-height: 1.4; color: #F8ECD8; margin: 14px 0 0;
  letter-spacing: 0.12em; opacity: 0; animation: a-rise 1.1s .25s ease-out forwards;
}
.slidev-layout.mk-a2 h1::after {
  content: ""; display: block; width: 0; height: 1px; margin-top: 24px;
  background: linear-gradient(90deg, #AB8A55, rgba(171,138,85,0));
  animation: a-rule 1.5s .55s ease-out forwards;
}
@keyframes a-rule { to { width: 100%; } }
.a-list { margin: 32px 0 0; padding: 0; list-style: none; }
.slidev-layout.mk-a2 .a-list li {
  position: relative; list-style: none; padding: 0 0 0 26px; margin: 0 0 24px;
  font-size: 23px; line-height: 1.7; color: #DCD2BE;
  opacity: 0; animation: a-rise 1.1s var(--d) ease-out forwards;
}
.slidev-layout.mk-a2 .a-list li::before {
  content: ""; position: absolute; left: 0; top: 0.4em; width: 1px; height: 0;
  background: #AB8A55; border-radius: 0;
  animation: a-stroke .8s calc(var(--d) + .3s) ease-out forwards;
}
@keyframes a-stroke { to { height: 1.1em; } }
.slidev-layout.mk-a2 .a-list li b { color: #F8ECD8; font-weight: 500; }
.slidev-layout.mk-a2 .a-list li em {
  display: block; font-style: normal; font-size: 18px; margin-top: 6px; color: #A2967E; letter-spacing: 0.06em;
}
.a-close {
  margin-top: 30px; font-size: 20px; color: #A2967E; letter-spacing: 0.1em;
  opacity: 0; animation: a-rise 1.2s 2.05s ease-out forwards;
}
@keyframes a-rise {
  from { opacity: 0; transform: translateY(10px); filter: blur(7px); }
  to   { opacity: 1; transform: translateY(0);    filter: blur(0); }
}
.a-tag { position: absolute; left: 96px; bottom: 36px; font-size: 13px; letter-spacing: 0.3em; color: #57503F; }
</style>

---
title: 案一 行灯 / 溶ける和ろうそく
class: mk-a3
transition: fade
---

<div class="a-lamp"></div>
<div class="a-grid">
<div class="a-body">
<div class="a-eyebrow">連 続 作 業 時 間</div>
<h1>溶ける和ろうそく</h1>
<ul class="a-list">
<li style="--d:.85s">溜まるバーではなく、<b>減る蝋燭</b></li>
<li style="--d:1.25s">満ちたら休め。<b>バーは満ちると嬉しい記号</b>で、逆さまだった</li>
<li style="--d:1.65s">数字は出さない。<b>そろそろか否か</b>しか語らない</li>
</ul>
</div>
<div class="a-media">
<div class="a-frame">
<div class="a-ph">動画C<span>約10秒</span></div>
<div class="a-fast">早回し</div>
</div>
<div class="a-cap">パネル下部・和ろうそくの拡大</div>
</div>
</div>
<div class="a-tag">案一 行灯</div>

<style>
.slidev-layout.mk-a3 {
  padding: 0; background: #0B0B09; color: #F8ECD8;
  letter-spacing: 0.04em; overflow: hidden; position: relative;
  font-family: "Shippori Mincho B1", "Hiragino Mincho ProN", "Yu Mincho", serif;
  display: flex; align-items: flex-start; padding-top: 86px;
}
.a-lamp {
  position: absolute; right: 8%; top: 50%; width: 66%; height: 170%; transform: translateY(-50%);
  background:
    radial-gradient(28% 24% at 50% 48%, rgba(255,205,110,0.24) 0%, rgba(255,205,110,0) 100%),
    radial-gradient(52% 46% at 50% 48%, rgba(212,132,44,0.13) 0%, rgba(0,0,0,0) 100%);
  animation: a-breathe 7s ease-in-out infinite;
}
@keyframes a-breathe {
  0%, 100% { opacity: 0.78; transform: translateY(-50%) scale(1); }
  50%      { opacity: 1;    transform: translateY(-50%) scale(1.06); }
}
.a-grid { position: relative; width: 100%; padding: 0 88px; display: grid; grid-template-columns: 1fr 520px; gap: 52px; align-items: start; }
.a-media { margin-top: 44px; }
.a-eyebrow { font-size: 15px; letter-spacing: 0.5em; color: #AB8A55; opacity: 0; animation: a-rise .9s .1s ease-out forwards; }
.slidev-layout.mk-a3 h1 {
  font-size: 40px; font-weight: 400; line-height: 1.4; color: #F8ECD8; margin: 14px 0 0;
  letter-spacing: 0.1em; opacity: 0; animation: a-rise 1.1s .25s ease-out forwards;
}
.slidev-layout.mk-a3 h1::after {
  content: ""; display: block; width: 0; height: 1px; margin-top: 20px;
  background: linear-gradient(90deg, #AB8A55, rgba(171,138,85,0));
  animation: a-rule 1.5s .55s ease-out forwards;
}
@keyframes a-rule { to { width: 100%; } }
.a-list { margin: 28px 0 0; padding: 0; list-style: none; }
.slidev-layout.mk-a3 .a-list li {
  position: relative; list-style: none; padding: 0 0 0 24px; margin: 0 0 20px;
  font-size: 21px; line-height: 1.7; color: #DCD2BE;
  opacity: 0; animation: a-rise 1.1s var(--d) ease-out forwards;
}
.slidev-layout.mk-a3 .a-list li::before {
  content: ""; position: absolute; left: 0; top: 0.4em; width: 1px; height: 0;
  background: #AB8A55; border-radius: 0;
  animation: a-stroke .8s calc(var(--d) + .3s) ease-out forwards;
}
@keyframes a-stroke { to { height: 1.1em; } }
.slidev-layout.mk-a3 .a-list li b { color: #F8ECD8; font-weight: 500; }
@keyframes a-rise {
  from { opacity: 0; transform: translateY(10px); filter: blur(7px); }
  to   { opacity: 1; transform: translateY(0);    filter: blur(0); }
}
.a-frame {
  position: relative; aspect-ratio: 16 / 9; width: 100%;
  border: 1px solid rgba(248,236,216,0.30); background: rgba(255,255,255,0.02);
  box-shadow: 0 0 80px rgba(255,190,90,0.12) inset, 0 24px 60px rgba(0,0,0,0.55);
  opacity: 0; animation: a-rise 1.3s .95s ease-out forwards;
}
.a-ph {
  position: absolute; inset: 0; display: flex; flex-direction: column;
  align-items: center; justify-content: center; gap: 8px;
  font-size: 22px; letter-spacing: 0.3em; color: #6E6553;
}
.a-ph span { font-size: 14px; letter-spacing: 0.24em; color: #4E4839; }
.a-fast { position: absolute; right: 12px; bottom: 10px; font-size: 13px; letter-spacing: 0.2em; color: #A2967E; }
.a-cap { margin-top: 14px; font-size: 14px; letter-spacing: 0.2em; color: #57503F; text-align: right;
  opacity: 0; animation: a-rise 1.2s 1.5s ease-out forwards; }
.a-tag { position: absolute; left: 88px; bottom: 36px; font-size: 13px; letter-spacing: 0.3em; color: #57503F; }
</style>

---
title: 案二 金屏風 / 3つの困りごと
class: mk-b4
transition: fade-out
---

<div class="b-grain"></div>
<svg class="b-enso" viewBox="0 0 200 200" aria-hidden="true">
<defs>
<linearGradient id="ensoA" x1="0" y1="0" x2="1" y2="1">
<stop offset="0" stop-color="#8E7134"/><stop offset="0.45" stop-color="#E8D28F"/><stop offset="1" stop-color="#6B551F"/>
</linearGradient>
</defs>
<path d="M143 34 A 82 82 0 1 0 168 118 A 82 82 0 0 1 128 168" pathLength="100"/>
</svg>
<div class="b-body">
<div class="b-eyebrow">困 り ご と</div>
<h1 class="b-title">3つの困りごと</h1>
<ol class="b-list">
<li style="--d:.75s"><i>一</i><span>何にどれだけ時間を使ったか、<b>後から分からない</b></span></li>
<li style="--d:1.05s"><i>二</i><span>次の予定まで<b>あと何分</b>か、カレンダーを開きに行く<em>予定そのものより、予定と予定の「間」が知りたい</em></span></li>
<li style="--d:1.35s"><i>三</i><span>集中すると<b>休憩を忘れる</b>。気づいたら疲れている</span></li>
</ol>
<div class="b-close"><span class="b-dot"></span>どれも「いま何をするか」の材料。ひとつのパネルで済ませたかった</div>
</div>
<div class="b-tag">案二 金屏風</div>

<style>
.slidev-layout.mk-b4 {
  padding: 0; color: #F8ECD8; letter-spacing: 0.05em; overflow: hidden; position: relative;
  background: radial-gradient(120% 100% at 20% 24%, #16130C 0%, #0A0907 62%);
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", "Yu Mincho", serif;
  display: flex; align-items: flex-start; padding-top: 86px;
}
.b-grain {
  position: absolute; inset: 0; pointer-events: none; opacity: 0.5;
  background-image:
    radial-gradient(circle at 12% 78%, rgba(217,180,92,0.55) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 24% 22%, rgba(217,180,92,0.45) 0 1.8px, transparent 2.3px),
    radial-gradient(circle at 68% 88%, rgba(217,180,92,0.5) 0 1.1px, transparent 1.6px),
    radial-gradient(circle at 86% 34%, rgba(217,180,92,0.42) 0 2px, transparent 2.6px),
    radial-gradient(circle at 45% 12%, rgba(217,180,92,0.4) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 92% 66%, rgba(217,180,92,0.45) 0 1.5px, transparent 2px),
    radial-gradient(circle at 58% 44%, rgba(217,180,92,0.3) 0 1.1px, transparent 1.6px),
    radial-gradient(circle at 34% 62%, rgba(217,180,92,0.28) 0 1.4px, transparent 1.9px);
}
.b-enso {
  position: absolute; right: -196px; top: 50%; width: 700px; height: 700px; transform: translateY(-50%) rotate(-18deg);
  fill: none; stroke: url(#ensoA); stroke-width: 7; stroke-linecap: round; opacity: 0.3;
  stroke-dasharray: 100 100; stroke-dashoffset: 100;
  mask-image: linear-gradient(160deg, rgba(0,0,0,1) 30%, rgba(0,0,0,0.25) 78%, rgba(0,0,0,0) 100%);
  animation: b-draw 1.6s .15s cubic-bezier(.24,.72,.3,1) forwards;
}
@keyframes b-draw { to { stroke-dashoffset: 0; } }
.b-body { position: relative; margin-left: 88px; width: 720px; }
.b-eyebrow { font-size: 15px; letter-spacing: 0.5em; color: #AB8A55; opacity: 0; animation: b-in .8s .1s ease-out forwards; }
.slidev-layout.mk-b4 h1.b-title {
  font-size: 48px; font-weight: 500; line-height: 1.35; margin: 12px 0 0; letter-spacing: 0.1em;
  background-image: linear-gradient(100deg, #B99A5E 0%, #F3E3B0 26%, #D9B45C 42%, #A8863F 70%, #E8D28F 100%);
  background-size: 300% 100%; background-position: 100% 0;
  -webkit-background-clip: text; background-clip: text; color: transparent;
  opacity: 0; animation: b-in 1s .3s ease-out forwards, b-shimmer 2.4s .9s ease-out 1 forwards;
}
@keyframes b-shimmer { to { background-position: 0 0; } }
.slidev-layout.mk-b4 h1.b-title::after {
  content: ""; display: block; height: 1px; width: 100%; margin-top: 22px;
  background: linear-gradient(90deg, #D9B45C 0%, rgba(171,138,85,0.35) 55%, rgba(171,138,85,0) 100%);
  transform-origin: left; transform: scaleX(0);
  animation: b-rule 1.1s .7s cubic-bezier(.22,.8,.28,1) forwards;
}
@keyframes b-rule { to { transform: scaleX(1); } }
.b-list { margin: 28px 0 0; padding: 0; }
.slidev-layout.mk-b4 .b-list li {
  list-style: none; display: flex; gap: 20px; align-items: baseline; margin: 0 0 22px; padding: 0;
  font-size: 23px; line-height: 1.7; color: #DCD2BE;
  opacity: 0; animation: b-slide 1s var(--d) cubic-bezier(.22,.8,.28,1) forwards;
}
.slidev-layout.mk-b4 .b-list li::before { content: none; }
.slidev-layout.mk-b4 .b-list li i {
  font-style: normal; flex: none; width: 44px; text-align: center; font-size: 20px; letter-spacing: 0;
  color: #0A0907; background: linear-gradient(160deg, #E8D28F, #AB8A55); padding: 3px 0 5px;
}
.slidev-layout.mk-b4 .b-list li b { color: #F3E3B0; font-weight: 500; }
.slidev-layout.mk-b4 .b-list li em {
  display: block; font-style: normal; font-size: 17px; margin-top: 6px; color: #9C907A;
}
@keyframes b-slide { from { opacity: 0; transform: translateX(22px); } to { opacity: 1; transform: translateX(0); } }
@keyframes b-in { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }
.b-close {
  margin-top: 26px; font-size: 20px; color: #C4B79E; letter-spacing: 0.1em;
  display: flex; align-items: center; gap: 12px;
  opacity: 0; animation: b-in 1s 1.75s ease-out forwards;
}
.b-dot { width: 7px; height: 7px; border-radius: 50%; background: #DA5932; box-shadow: 0 0 12px rgba(218,89,50,0.85); flex: none; }
.b-tag { position: absolute; left: 88px; bottom: 34px; font-size: 13px; letter-spacing: 0.3em; color: #5C5340; }
</style>

---
title: 案二 金屏風 / 溶ける和ろうそく
class: mk-b5
transition: fade-out
---

<div class="b-grain"></div>
<div class="b-glow"></div>
<div class="b-grid">
<div class="b-body">
<div class="b-eyebrow">連 続 作 業 時 間</div>
<h1 class="b-title">溶ける和ろうそく</h1>
<ol class="b-list">
<li style="--d:.85s"><i>一</i><span>溜まるバーではなく、<b>減る蝋燭</b></span></li>
<li style="--d:1.15s"><i>二</i><span>満ちたら休め。<b>バーは満ちると嬉しい記号</b>で、逆さまだった</span></li>
<li style="--d:1.45s"><i>三</i><span>数字は出さない。<b>そろそろか否か</b>しか語らない</span></li>
</ol>
</div>
<div class="b-media">
<div class="b-frame">
<span class="b-nail b-nail-tl"></span><span class="b-nail b-nail-tr"></span>
<span class="b-nail b-nail-bl"></span><span class="b-nail b-nail-br"></span>
<video class="b-video" autoplay muted loop playsinline>
<source src="./public/media/demo-c-candle-burnout.mp4" type="video/mp4" />
</video>
<div class="b-fast">早回し</div>
</div>
<div class="b-cap">動画C ― 燃え尽きて、また灯るまで</div>
</div>
</div>
<div class="b-tag">案二 金屏風</div>

<style>
.slidev-layout.mk-b5 {
  padding: 0; color: #F8ECD8; letter-spacing: 0.05em; overflow: hidden; position: relative;
  background: radial-gradient(120% 100% at 20% 24%, #16130C 0%, #0A0907 62%);
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", "Yu Mincho", serif;
  display: flex; align-items: flex-start; padding-top: 86px;
}
.b-grain {
  position: absolute; inset: 0; pointer-events: none; opacity: 0.5;
  background-image:
    radial-gradient(circle at 12% 78%, rgba(217,180,92,0.55) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 24% 22%, rgba(217,180,92,0.45) 0 1.8px, transparent 2.3px),
    radial-gradient(circle at 68% 88%, rgba(217,180,92,0.5) 0 1.1px, transparent 1.6px),
    radial-gradient(circle at 86% 34%, rgba(217,180,92,0.42) 0 2px, transparent 2.6px),
    radial-gradient(circle at 45% 12%, rgba(217,180,92,0.4) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 92% 66%, rgba(217,180,92,0.45) 0 1.5px, transparent 2px);
}
.b-glow {
  position: absolute; right: 4%; top: 50%; width: 56%; height: 150%; transform: translateY(-50%);
  background: radial-gradient(34% 32% at 50% 50%, rgba(255,199,92,0.17) 0%, rgba(218,138,50,0.05) 46%, rgba(0,0,0,0) 78%);
  animation: b-breathe 6s ease-in-out infinite;
}
@keyframes b-breathe { 0%,100% { opacity: .8 } 50% { opacity: 1 } }
.b-grid { position: relative; width: 100%; padding: 0 88px; display: grid; grid-template-columns: 1fr 500px; gap: 48px; align-items: start; }
.b-media { margin-top: 44px; }
.b-eyebrow { font-size: 15px; letter-spacing: 0.5em; color: #AB8A55; opacity: 0; animation: b-in .8s .1s ease-out forwards; }
.slidev-layout.mk-b5 h1.b-title {
  font-size: 40px; font-weight: 500; line-height: 1.35; margin: 12px 0 0; letter-spacing: 0.08em;
  background-image: linear-gradient(100deg, #B99A5E 0%, #F3E3B0 26%, #D9B45C 42%, #A8863F 70%, #E8D28F 100%);
  background-size: 300% 100%; background-position: 100% 0;
  -webkit-background-clip: text; background-clip: text; color: transparent;
  opacity: 0; animation: b-in 1s .3s ease-out forwards, b-shimmer 2.4s .9s ease-out 1 forwards;
}
@keyframes b-shimmer { to { background-position: 0 0; } }
.slidev-layout.mk-b5 h1.b-title::after {
  content: ""; display: block; height: 1px; width: 100%; margin-top: 18px;
  background: linear-gradient(90deg, #D9B45C 0%, rgba(171,138,85,0.35) 55%, rgba(171,138,85,0) 100%);
  transform-origin: left; transform: scaleX(0);
  animation: b-rule 1.1s .7s cubic-bezier(.22,.8,.28,1) forwards;
}
@keyframes b-rule { to { transform: scaleX(1); } }
.b-list { margin: 24px 0 0; padding: 0; }
.slidev-layout.mk-b5 .b-list li {
  list-style: none; display: flex; gap: 18px; align-items: baseline; margin: 0 0 18px; padding: 0;
  font-size: 20px; line-height: 1.7; color: #DCD2BE;
  opacity: 0; animation: b-slide 1s var(--d) cubic-bezier(.22,.8,.28,1) forwards;
}
.slidev-layout.mk-b5 .b-list li::before { content: none; }
.slidev-layout.mk-b5 .b-list li i {
  font-style: normal; flex: none; width: 38px; text-align: center; font-size: 17px; letter-spacing: 0;
  color: #0A0907; background: linear-gradient(160deg, #E8D28F, #AB8A55); padding: 3px 0 5px;
}
.slidev-layout.mk-b5 .b-list li b { color: #F3E3B0; font-weight: 500; }
@keyframes b-slide { from { opacity: 0; transform: translateX(22px); } to { opacity: 1; transform: translateX(0); } }
@keyframes b-in { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }
.b-frame {
  /* 動画Cは迅雷のクロップ後 864×944 の縦長。枠は実寸に合わせる */
  position: relative; aspect-ratio: 864 / 944; width: 400px; margin-left: auto;
  border: 2px solid transparent;
  background-image: linear-gradient(#100E0A, #100E0A), linear-gradient(150deg, #E8D28F, #8E7134 45%, #E8D28F 100%);
  background-origin: border-box; background-clip: padding-box, border-box;
  box-shadow: 0 26px 64px rgba(0,0,0,0.6);
  opacity: 0; animation: b-in 1.1s .95s ease-out forwards;
}
.b-nail { position: absolute; width: 7px; height: 7px; background: #E8D28F; border-radius: 50%; box-shadow: 0 0 8px rgba(232,210,143,0.6); }
.b-nail-tl { left: 8px; top: 8px } .b-nail-tr { right: 8px; top: 8px }
.b-nail-bl { left: 8px; bottom: 8px } .b-nail-br { right: 8px; bottom: 8px }
.b-video { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; display: block; }
.b-fast {
  position: absolute; right: 12px; bottom: 10px; font-size: 13px; letter-spacing: 0.2em; color: #E4DAC4;
  padding: 2px 8px 3px; background: rgba(10,9,7,0.55); backdrop-filter: blur(2px);
}
.b-cap { margin-top: 14px; font-size: 14px; letter-spacing: 0.2em; color: #5C5340; text-align: right;
  opacity: 0; animation: b-in 1s 1.45s ease-out forwards; }
.b-tag { position: absolute; left: 88px; bottom: 34px; font-size: 13px; letter-spacing: 0.3em; color: #5C5340; }
</style>

---
title: 案三 刻 / 3つの困りごと
class: mk-c6
transition: slide-up
---

<div class="c-inner">
<div class="c-head">
<span class="c-bar"></span>
<h1>3つの困りごと</h1>
<span class="c-key">1 / 2 / 3</span>
</div>
<div class="c-body">
<div class="c-rows">
<div class="c-row" style="--d:.35s"><span class="c-num">1</span><span class="c-label">何にどれだけ時間を使ったか、<b>後から分からない</b></span></div>
<div class="c-row" style="--d:.9s"><span class="c-num">2</span><span class="c-label">次の予定まで<b>あと何分</b>か、カレンダーを開きに行く<em>予定そのものより、予定と予定の「間」が知りたい</em></span></div>
<div class="c-row" style="--d:1.45s"><span class="c-num">3</span><span class="c-label">集中すると<b>休憩を忘れる</b>。気づいたら疲れている</span></div>
</div>
<div class="c-foot">どれも「いま何をするか」の材料。<b>ひとつのパネルで済ませたかった</b></div>
</div>
</div>
<div class="c-tag">案三 刻</div>

<style>
.slidev-layout.mk-c6 {
  padding: 0; background: #16160F; color: #F8ECD8; letter-spacing: 0.03em;
  overflow: hidden; position: relative; display: flex; align-items: stretch;
  font-family: "Zen Kaku Gothic New", "Hiragino Sans", sans-serif;
}
.c-inner { width: 100%; padding: 82px 84px 60px; display: flex; flex-direction: column; }
.c-body { flex: 1; display: flex; flex-direction: column; justify-content: center; }
.c-head { display: flex; align-items: center; gap: 18px; }
.c-bar { width: 5px; height: 42px; background: #DA5932; box-shadow: 0 0 14px rgba(218,89,50,0.7); flex: none;
  transform: scaleY(0); transform-origin: top; animation: c-bar .45s ease-out forwards; }
@keyframes c-bar { to { transform: scaleY(1); } }
.slidev-layout.mk-c6 h1 {
  font-size: 42px; font-weight: 500; color: #F8ECD8; margin: 0; letter-spacing: 0.06em;
  opacity: 0; animation: c-in .5s .12s ease-out forwards;
}
.c-key { margin-left: auto; font-size: 14px; letter-spacing: 0.34em; color: #6C6553;
  opacity: 0; animation: c-in .5s .3s ease-out forwards; }
.c-rows { margin-top: 44px; display: flex; flex-direction: column; gap: 20px; }
.c-row {
  position: relative; display: flex; align-items: center; gap: 24px; padding: 24px 32px; border-radius: 999px;
  border: 1.5px solid rgba(248,236,216,0.16);
  opacity: 0; animation: c-in .4s var(--d) ease-out forwards, c-light .8s calc(var(--d) + .18s) ease-out forwards;
}
@keyframes c-light {
  0%   { border-color: rgba(248,236,216,0.16); box-shadow: none; background-color: rgba(48,38,26,0); }
  55%  { border-color: #FFA847; box-shadow: 0 0 30px rgba(242,84,32,0.6), 0 0 10px rgba(255,245,209,0.5) inset; background-color: rgba(52,41,27,0.85); }
  100% { border-color: #E29A46; box-shadow: 0 0 16px rgba(242,84,32,0.3); background-color: rgba(48,38,26,0.6); }
}
.c-num {
  flex: none; width: 42px; height: 42px; border-radius: 50%; display: grid; place-items: center;
  font-size: 21px; font-weight: 700; color: #16160F; background: linear-gradient(180deg, #FFF5D1, #FFA847);
}
.c-label { font-size: 25px; line-height: 1.6; color: #E7DCC6; }
.c-label b { color: #FFC98A; font-weight: 700; }
.c-label em { display: block; font-style: normal; font-size: 17px; margin-top: 4px; color: #9A907C; }
.c-foot { margin-top: 36px; font-size: 20px; color: #9A907C; letter-spacing: 0.06em;
  opacity: 0; animation: c-in .6s 2.05s ease-out forwards; }
.c-foot b { color: #F8ECD8; font-weight: 500; }
@keyframes c-in { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
.c-tag { position: absolute; left: 84px; bottom: 28px; font-size: 13px; letter-spacing: 0.3em; color: #4F4A3C; }
</style>

---
title: 案三 刻 / 溶ける和ろうそく
class: mk-c7
transition: slide-up
---

<div class="c-inner">
<div class="c-head">
<span class="c-bar"></span>
<h1>溶ける和ろうそく</h1>
<span class="c-key">連 続 作 業 時 間</span>
</div>
<div class="c-body">
<div class="c-grid">
<div class="c-candle">
<svg viewBox="0 0 96 100" class="c-svg" aria-hidden="true">
<defs>
<linearGradient id="c7wax" x1="0" y1="0" x2="1" y2="0">
<stop offset="0" stop-color="#C7B89E"/><stop offset="0.32" stop-color="#F2E8D4"/><stop offset="1" stop-color="#C7B89E"/>
</linearGradient>
</defs>
<g class="c-smoke">
<path d="M48 26 q-4 -7 0 -14 q4 -7 0 -14 q-4 -7 0 -12" stroke="#A9A38A" stroke-width="2.4" fill="none" stroke-linecap="round"/>
</g>
<path class="c-wick" d="M48 24 L48 34" stroke="#4A3B29" stroke-width="3.4" stroke-linecap="round"/>
<path class="c-wax" d="M33 30 L63 30 C 61.5 48.36, 58.5 58.08, 58.5 63.48 C 58.5 77.52, 61 83, 61 84 L35 84 C 35 83, 37.5 77.52, 37.5 63.48 C 37.5 58.08, 34.5 48.36, 33 30 Z" fill="url(#c7wax)"/>
<ellipse class="c-cap" cx="48" cy="31" rx="13" ry="2.6" fill="#C7B89E" opacity="0.9"/>
<g class="c-flamewrap">
<g class="c-flame">
<path d="M48 24 C40.5 21.5, 37.5 13.5, 42 6.5 C44.5 2.5, 48 -0.5, 48 -4 C48 -0.5, 51.5 2.5, 54 6.5 C58.5 13.5, 55.5 21.5, 48 24 Z" fill="#FFC75C" opacity="0.38"/>
<path d="M48 24 C42 22, 39.5 15, 43 9 C45 5.5, 48 3, 48 0 C48 3, 51 5.5, 53 9 C56.5 15, 54 22, 48 24 Z" fill="#FFC75C"/>
<path d="M48 24 C45.5 22.5, 44.5 18, 46 14 C47 11.5, 48 10, 48 8 C48 10, 49 11.5, 50 14 C51.5 18, 50.5 22.5, 48 24 Z" fill="#FFF5D9" opacity="0.9"/>
</g>
</g>
<path d="M30 84 q18 -9 36 0 z" fill="#C7B89E"/>
<path d="M26 86 h44" stroke="#AB8A55" stroke-width="5" stroke-linecap="round"/>
</svg>
<div class="c-cap-text">コードで描いたSVG</div>
</div>
<div class="c-media">
<div class="c-frame">
<div class="c-ph">動画C<span>約10秒</span></div>
<div class="c-fast">早回し</div>
</div>
</div>
<div class="c-points">
<div class="c-p" style="--d:.5s">溜まるバーではなく、<b>減る蝋燭</b></div>
<div class="c-p" style="--d:.9s">満ちたら休め。バーは<b>満ちると嬉しい記号</b>で、逆さまだった</div>
<div class="c-p" style="--d:1.3s">燃え尽きたら煙。休憩キーで<b>新しい蝋燭がせり上がる</b></div>
</div>
</div>
</div>
</div>
<div class="c-tag">案三 刻</div>

<style>
.slidev-layout.mk-c7 {
  padding: 0; background: #16160F; color: #F8ECD8; letter-spacing: 0.03em;
  overflow: hidden; position: relative; display: flex; align-items: stretch;
  font-family: "Zen Kaku Gothic New", "Hiragino Sans", sans-serif;
}
.c-inner { width: 100%; padding: 82px 84px 60px; display: flex; flex-direction: column; }
.c-body { flex: 1; display: flex; flex-direction: column; justify-content: center; }
.c-head { display: flex; align-items: center; gap: 18px; }
.c-bar { width: 5px; height: 42px; background: #DA5932; box-shadow: 0 0 14px rgba(218,89,50,0.7); flex: none;
  transform: scaleY(0); transform-origin: top; animation: c-bar .45s ease-out forwards; }
@keyframes c-bar { to { transform: scaleY(1); } }
.slidev-layout.mk-c7 h1 {
  font-size: 42px; font-weight: 500; color: #F8ECD8; margin: 0; letter-spacing: 0.06em;
  opacity: 0; animation: c-in .5s .12s ease-out forwards;
}
.c-key { margin-left: auto; font-size: 14px; letter-spacing: 0.34em; color: #6C6553;
  opacity: 0; animation: c-in .5s .3s ease-out forwards; }
@keyframes c-in { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
.c-grid { display: grid; grid-template-columns: 226px 424px 1fr; gap: 30px; align-items: center; }
.c-candle { text-align: center; }
.c-svg { width: 224px; height: 233px; overflow: visible; filter: drop-shadow(0 0 38px rgba(255,168,71,0.34)); }
.c-wax { animation: c7-wax 9s linear infinite; }
@keyframes c7-wax {
  0%   { d: path("M33 30 L63 30 C 61.5 48.36, 58.5 58.08, 58.5 63.48 C 58.5 77.52, 61 83, 61 84 L35 84 C 35 83, 37.5 77.52, 37.5 63.48 C 37.5 58.08, 34.5 48.36, 33 30 Z"); }
  62%, 88% { d: path("M33 77.52 L63 77.52 C 61.5 79.72, 58.5 80.89, 58.5 81.54 C 58.5 83.22, 61 83, 61 84 L35 84 C 35 83, 37.5 83.22, 37.5 81.54 C 37.5 80.89, 34.5 79.72, 33 77.52 Z"); }
  95%, 100% { d: path("M33 30 L63 30 C 61.5 48.36, 58.5 58.08, 58.5 63.48 C 58.5 77.52, 61 83, 61 84 L35 84 C 35 83, 37.5 77.52, 37.5 63.48 C 37.5 58.08, 34.5 48.36, 33 30 Z"); }
}
.c-wick, .c-cap, .c-flamewrap { animation: c7-melt 9s linear infinite; }
@keyframes c7-melt {
  0%   { transform: translateY(0); }
  62%, 88% { transform: translateY(47.5px); }
  95%, 100% { transform: translateY(0); }
}
.c-flame {
  transform-box: fill-box; transform-origin: 50% 100%;
  animation: c7-flicker 1.1s ease-in-out infinite alternate, c7-out 9s linear infinite;
}
@keyframes c7-flicker {
  from { transform: scale(1, 1) skewX(0deg); }
  to   { transform: scale(0.93, 1.07) skewX(-3deg); }
}
@keyframes c7-out {
  0%, 60%   { opacity: 1; }
  64%, 90%  { opacity: 0; }
  96%, 100% { opacity: 1; }
}
.c-smoke { opacity: 0; animation: c7-smoke 9s linear infinite; }
@keyframes c7-smoke {
  0%, 62%  { opacity: 0; transform: translateY(50px); }
  70%      { opacity: 0.8; transform: translateY(42px); }
  87%      { opacity: 0; transform: translateY(20px); }
  100%     { opacity: 0; transform: translateY(20px); }
}
.c-cap-text { margin-top: 4px; font-size: 14px; letter-spacing: 0.12em; color: #6C6553; }
.c-frame {
  position: relative; aspect-ratio: 16 / 9; width: 100%; border-radius: 10px;
  border: 1.5px solid rgba(255,168,71,0.55); background: rgba(48,38,26,0.45);
  box-shadow: 0 0 24px rgba(242,84,32,0.28), 0 20px 46px rgba(0,0,0,0.55);
  opacity: 0; animation: c-in .5s .35s ease-out forwards;
}
.c-ph { position: absolute; inset: 0; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px;
  font-size: 21px; letter-spacing: 0.28em; color: #8A7E63; }
.c-ph span { font-size: 13px; letter-spacing: 0.22em; color: #635944; }
.c-fast { position: absolute; right: 12px; bottom: 9px; font-size: 13px; letter-spacing: 0.2em; color: #C4B79E; }
.c-points { display: flex; flex-direction: column; gap: 20px; }
.c-p { font-size: 19px; line-height: 1.65; color: #C9BFA9; padding-left: 16px; border-left: 2px solid #DA5932;
  opacity: 0; animation: c-in .5s var(--d) ease-out forwards; }
.c-p b { color: #FFC98A; font-weight: 700; }
.c-tag { position: absolute; left: 84px; bottom: 28px; font-size: 13px; letter-spacing: 0.3em; color: #4F4A3C; }
</style>

---
title: 案四 巻物 / 三つの困りごと(詞書が主)
class: mk-scroll mk-d8
transition: fade-out
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
<div class="d-col d-col-close" style="--d:0.94s">いま何をするかの材料。ひとつのパネルに</div>
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
<div class="d-tag">案四 巻物</div>

<style>
/* 型の基盤は styles/index.css の .mk-scroll。ここは丸窓の時計だけ */
.mk-d8 .d-clock { width: 344px; height: 344px; fill: none; }
.d-ring {
  stroke: #2C2419; stroke-width: 2.6; stroke-linecap: round; opacity: .82;
  stroke-dasharray: 100 100; stroke-dashoffset: 100;
  animation: d-draw .55s .58s cubic-bezier(.26,.7,.3,1) forwards;
}
@keyframes d-draw { to { stroke-dashoffset: 0; } }
.d-ring2 { stroke: rgba(44,36,25,0.22); stroke-width: 1; opacity: 0; animation: d-fade .28s 1.05s ease-out forwards; }
.d-tick line { stroke: rgba(44,36,25,0.5); stroke-width: 1.6; stroke-linecap: round; }
.d-tick { opacity: 0; animation: d-fade .28s 1.12s ease-out forwards; }
.d-hands { opacity: 0; animation: d-fade .28s 1.20s ease-out forwards; }
.d-hand-h { stroke: #2C2419; stroke-width: 4; stroke-linecap: round; transform-origin: 120px 120px; transform: rotate(-58deg); }
.d-hand-m { stroke: #2C2419; stroke-width: 2.4; stroke-linecap: round; transform-origin: 120px 120px; animation: d-spin 24s linear infinite; }
@keyframes d-spin { from { transform: rotate(58deg); } to { transform: rotate(418deg); } }
.d-pivot { fill: #B23F26; stroke: none; }
</style>

---
title: 案四 巻物 / 溶ける和ろうそく(詞書が主)
class: mk-scroll mk-d9
transition: fade-out
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner d-mode-text">
<div class="d-cols">
<div class="d-daisen">和 ろ う そ く</div>
<div class="d-col d-col-title" style="--d:0.60s"><h1>溶ける和ろうそく</h1></div>
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>溜まるバーではなく、減る蝋燭</div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>満ちたら休め。バーは逆だった</div>
<div class="d-col" style="--d:0.86s"><span class="d-no">三</span>数字は出さない<em>そろそろか否かだけ</em></div>
</div>
<div class="d-art">
<div class="d-figbox">
<div class="d-fig">
<video autoplay muted loop playsinline>
<source src="./public/media/demo-c-candle-burnout.mp4" type="video/mp4" />
</video>
<div class="d-fast">早回し</div>
</div>
<div class="d-figcap">図 ― 燃え尽きて、また灯るまで</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-tag">案四 巻物</div>

<style>
/* 型の基盤は styles/index.css の .mk-scroll。ここは動画Cの枠だけ */
/* 動画Cは迅雷のクロップ後 864×944 の縦長。紙が高くなったぶん天地いっぱいに置ける */
.mk-d9 .d-art { flex: 0 0 auto; }
.mk-d9 .d-fig { width: 412px; aspect-ratio: 864 / 944; }
</style>

---
title: 案四 巻物 / 表紙(題箋だけ)
class: mk-scroll mk-d10
transition: fade-out
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
<span class="d-gaidai-ja">刻々</span>
<span class="d-gaidai-en">KOKUKOKU</span>
<span class="d-gaidai-sub">刻一刻と時を見守る</span>
</div>
<div class="d-cover-meta" style="--d:0.76s">macOS 用・自作の常駐パネル</div>
</div>
<div class="d-seal-col d-seal-cover"><span class="d-seal">刻々</span></div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-tag">案四 巻物 ― 表紙</div>

<style>
/* 型の基盤は styles/index.css の .mk-scroll。表紙は題箋1枚と副題だけで成立させる */
.d-cover { justify-content: center; align-items: center; }
.d-cover-cols { display: flex; flex-direction: row-reverse; align-items: center; }

/* 外題(げだい)の題箋。中の枚の走り出しの題箋を、そのまま大きくしたもの */
/* 題名・読み・副題をすべてこの1枚に入れ、紙の上には他に何も置かない */
.d-gaidai {
  display: flex; flex-direction: row-reverse; align-items: flex-start; justify-content: center;
  box-sizing: border-box;
  width: 196px; height: 300px; margin-left: 52px; padding: 30px 20px 0;
  background: #F5EDD7; border: 1px solid rgba(60,48,26,0.5);
  box-shadow: 0 6px 16px rgba(90,66,28,0.22), inset 0 0 0 5px #F5EDD7, inset 0 0 0 6px rgba(60,48,26,0.28);
  opacity: 0; animation: d-in .5s .56s ease-out forwards;
}
.d-gaidai-ja {
  writing-mode: vertical-rl; font-size: 62px; font-weight: 500; letter-spacing: 0.16em;
  color: #241D13;
}
.d-gaidai-en {
  writing-mode: vertical-rl; text-orientation: upright;
  font-size: 13px; letter-spacing: 0.34em; color: #7A6E58; margin-right: 12px; padding-top: 6px;
}
.d-gaidai-sub {
  writing-mode: vertical-rl; font-size: 21px; letter-spacing: 0.2em; color: #3B3123;
  margin-right: 26px; padding-top: 4px;
}
.d-cover-meta {
  writing-mode: vertical-rl; font-size: 15px; letter-spacing: 0.2em; color: #6E6353;
  padding-top: 44px;
  opacity: 0; animation: d-in .5s var(--d) ease-out forwards;
}
/* 表紙の落款だけは版面の左下へ。中の枚では詞書の足元に付く */
.d-seal-cover { position: absolute; left: 46px; bottom: 34px; margin: 0; padding: 0; }
</style>

---
title: 案四 巻物 / 予定は「間隔」で見る(絵が主)
class: mk-scroll mk-d11
transition: fade-out
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
<div class="d-col" style="--d:0.70s">知りたいのは予定と予定の「間」</div>
</div>
<div class="d-art">
<div class="d-figpair">
<div class="d-figbox d-figbox-still">
<div class="d-fig d-fig-still"><img src="./public/media/still-timeline-rails.png" alt="三種のレール" /></div>
<div class="d-figcap">図<span class="d-cap-no">一</span> ― 空き・連続・重複を色で</div>
</div>
<div class="d-figbox d-figbox-video">
<div class="d-fig d-fig-video">
<video autoplay muted loop playsinline>
<source src="./public/media/demo-b-calendar-notification.mp4" type="video/mp4" />
</video>
</div>
<div class="d-figcap">図<span class="d-cap-no">二</span> ― 触らずに立ち上がる。フォーカスは奪わない</div>
</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-tag">案四 巻物 ― 絵が主</div>

<style>
/* 型の基盤は styles/index.css の .mk-scroll。ここは2枚の絵の配分だけ */
/* 右(先に読む)が静止画D、左が動画B。絵巻の場面の進みと語りの順序を合わせた */
/* width:0 + grow で「詞書の残り全部」を絵に渡す(内容幅で決まるのを避ける) */
.mk-d11 .d-art { flex: 1 1 auto; width: 0; }
/* 図の天を揃える。高さが違う2枚を中央で合わせると天がばらけて見える */
.mk-d11 .d-figpair { align-items: flex-start; }
.mk-d11 .d-figbox-still { flex: 0 0 272px; }
.mk-d11 .d-fig-still { width: 100%; aspect-ratio: 300 / 236; }
/* 静止画Dは830×390の横長。object-position で左の時系列側だけを見せる */
.mk-d11 .d-fig-still img { object-position: left center; }
.mk-d11 .d-figbox-video { flex: 1 1 auto; }
.mk-d11 .d-fig-video { width: 100%; aspect-ratio: 1440 / 814; }
.mk-d11 .d-figcap { font-size: 13px; }
</style>

---
title: 案四 巻物 / 使い始め方(貼紙)
class: mk-scroll mk-d12
transition: fade-out
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
<div class="d-col" style="--d:0.70s"><span class="d-no">一</span>入れて、開くだけ<em>Homebrew の cask</em></div>
<div class="d-col" style="--d:0.78s"><span class="d-no">二</span>設定は TOML 一枚<em>触らなくても動く</em></div>
</div>
<div class="d-art">
<div class="d-figbox d-figbox-paste">
<div class="d-paste d-paste-cmd">
<pre class="d-cmd"><span class="d-prompt">$</span>brew install --cask tadashi-aikawa/tap/kokukoku</pre>
<pre class="d-cmd"><span class="d-prompt">$</span>open -a KOKUKOKU</pre>
</div>
<div class="d-paste d-paste-conf">
<div class="d-paste-note">~/.config/kokukoku/config.toml</div>
</div>
<div class="d-figcap">貼紙 ― 端末に二行、設定に一枚</div>
</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-tag">案四 巻物 ― 貼紙</div>

<style>
/* 型の基盤は styles/index.css の .mk-scroll。ここは貼紙の寸法だけ */
/* 縦組みに入らない横書き(コマンド)は、紙に貼った別紙として置く */
.mk-d12 .d-art { flex: 1 1 auto; width: 0; }
.mk-d12 .d-figbox-paste { flex: 0 0 auto; }
.mk-d12 .d-paste-cmd { padding: 34px 36px 30px; }
.mk-d12 .d-cmd { font-size: 19px; line-height: 2.3; }
/* 2枚目の貼紙。傾きを逆に振って「別の紙を後から貼った」ことを見せる */
.mk-d12 .d-paste-conf {
  align-self: flex-start; margin: 24px 0 0 58px; padding: 16px 26px;
  transform: rotate(0.7deg);
}
.mk-d12 .d-paste-note {
  font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace;
  font-size: 15px; letter-spacing: 0.02em; color: #5E5443;
}
</style>
