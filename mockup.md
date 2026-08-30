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
<p class="idx-lead">同じ2枚(2枚目「3つの困りごと」/ 6枚目「溶ける和ろうそく」)を、4つの型で作り分けました。<br/>違うのは <b>光の質</b> と <b>動きの量</b>。文章ではなく、めくって体感してください。</p>
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
<div class="idx-page">p.8 / p.9</div>
</div>
</div>
<div class="idx-foot">案二を選定済み。<b>案四は案二と同じ絵の具・同じ書体</b>で、地を「黒」から「紙」へ裏返した派生です。混ぜるなら<b>案二を地</b>にして、<b>紙で語る枚(2・7枚目)だけ案四</b>。金は黒の世界、墨と朱は紙の世界と持ち場を分けてあるので、続けて出しても喧嘩しません。</div>
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
.idx-card-new::after { content: "追加"; }
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
  position: relative; aspect-ratio: 1440 / 800; width: 100%;
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
title: 案四 巻物 / 三つの困りごと
class: mk-d8
transition: fade-out
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner">
<div class="d-cols">
<div class="d-daisen">困 り ご と</div>
<div class="d-col d-col-title" style="--d:1.5s"><h1>三つの困りごと</h1></div>
<div class="d-col" style="--d:1.75s"><span class="d-no">一</span>何に時間を使ったか分からない</div>
<div class="d-col" style="--d:1.95s"><span class="d-no">二</span>次の予定まで、あと何分か<em>知りたいのは予定と予定の「間」</em></div>
<div class="d-col" style="--d:2.15s"><span class="d-no">三</span>集中すると休憩を忘れる</div>
<div class="d-col d-col-close" style="--d:2.4s">いま何をするかの材料。ひとつのパネルに</div>
<div class="d-seal-col"><span class="d-seal">刻々</span></div>
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
.slidev-layout.mk-d8 {
  padding: 0; color: #F8ECD8; overflow: hidden; position: relative;
  background: radial-gradient(120% 100% at 22% 18%, #171209 0%, #0A0806 66%);
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", "Yu Mincho", serif;
}
.d-grain {
  position: absolute; inset: 0; pointer-events: none; opacity: 0.45;
  background-image:
    radial-gradient(circle at 9% 82%, rgba(217,180,92,0.5) 0 1.4px, transparent 1.9px),
    radial-gradient(circle at 21% 12%, rgba(217,180,92,0.42) 0 1.8px, transparent 2.3px),
    radial-gradient(circle at 74% 92%, rgba(217,180,92,0.45) 0 1.1px, transparent 1.6px),
    radial-gradient(circle at 90% 22%, rgba(217,180,92,0.4) 0 2px, transparent 2.6px),
    radial-gradient(circle at 52% 6%, rgba(217,180,92,0.36) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 96% 70%, rgba(217,180,92,0.42) 0 1.5px, transparent 2px);
}
.d-lamp {
  position: absolute; right: 2%; top: 50%; width: 52%; height: 150%; transform: translateY(-50%);
  background: radial-gradient(32% 30% at 50% 50%, rgba(255,199,92,0.13) 0%, rgba(218,138,50,0.04) 48%, rgba(0,0,0,0) 78%);
  animation: d-breathe 7s ease-in-out infinite;
}
@keyframes d-breathe { 0%,100% { opacity: .78 } 50% { opacity: 1 } }
.d-scroll { position: absolute; left: 64px; right: 64px; top: 92px; height: 510px; --span: 1112px; }
.d-rod {
  position: absolute; top: -18px; bottom: -18px; width: 20px; border-radius: 3px;
  background: linear-gradient(90deg, #12100A 0%, #3E3220 26%, #6E5832 50%, #352B1B 78%, #100E09 100%);
}
.d-rod::before, .d-rod::after {
  content: ""; position: absolute; left: -5px; width: 30px; height: 15px; border-radius: 3px;
  background: linear-gradient(160deg, #EBD79A, #A98A52 55%, #6B551F);
  box-shadow: 0 2px 8px rgba(0,0,0,0.55);
}
.d-rod::before { top: -7px; }
.d-rod::after { bottom: -7px; }
.d-rod-r { right: 0; box-shadow: -10px 0 26px rgba(0,0,0,0.6); }
.d-rod-l {
  left: var(--span); box-shadow: 10px 0 26px rgba(0,0,0,0.6); z-index: 3;
  animation: d-roll 1.5s .25s cubic-bezier(.2,.78,.24,1) forwards;
}
/* clip-path と同じメインスレッドの時計で動かすため transform ではなく left を使う */
@keyframes d-roll { to { left: 0; } }
.d-paper {
  position: absolute; left: 20px; right: 20px; top: 14px; bottom: 14px;
  isolation: isolate; overflow: hidden;
  background:
    repeating-linear-gradient(90deg, rgba(112,84,40,0) 0 78px, rgba(112,84,40,0.05) 104px, rgba(112,84,40,0) 132px),
    radial-gradient(150% 130% at 84% 16%, #F1E6C9 0%, #E6D8B6 44%, #D8C69D 78%, #CBB78D 100%);
  box-shadow:
    inset 0 14px 24px -16px rgba(84,60,24,0.55), inset 0 -14px 24px -16px rgba(84,60,24,0.55),
    0 26px 60px rgba(0,0,0,0.6);
  clip-path: inset(0 0 0 100%);
  animation: d-unroll 1.5s .25s cubic-bezier(.2,.78,.24,1) forwards;
}
@keyframes d-unroll { to { clip-path: inset(0 0 0 0); } }
.d-fiber {
  position: absolute; inset: 0; pointer-events: none; opacity: .55;
  background-image:
    repeating-linear-gradient(94deg, rgba(120,96,52,0.055) 0 1px, transparent 1px 6px),
    repeating-linear-gradient(3deg, rgba(120,96,52,0.04) 0 1px, transparent 1px 5px);
}
.d-stain {
  position: absolute; inset: 0; pointer-events: none; mix-blend-mode: multiply; opacity: .34;
  background-image:
    radial-gradient(ellipse 120px 60px at 11% 84%, rgba(150,112,52,0.3), transparent 70%),
    radial-gradient(ellipse 90px 70px at 44% 8%, rgba(150,112,52,0.22), transparent 72%),
    radial-gradient(ellipse 150px 80px at 92% 90%, rgba(150,112,52,0.26), transparent 74%);
}
.d-inner {
  position: relative; height: 100%; padding: 38px 46px;
  display: flex; flex-direction: row-reverse; align-items: stretch; justify-content: space-between;
}
.d-cols { display: flex; flex-direction: row-reverse; align-items: stretch; }
.d-daisen {
  align-self: flex-start; writing-mode: vertical-rl; margin: 2px 2px 0 34px;
  background: #F0E7CF; border: 1px solid rgba(60,48,26,0.45); padding: 14px 5px;
  font-size: 13px; letter-spacing: 0.24em; color: #4A4032;
  box-shadow: 0 3px 7px rgba(90,66,28,0.2);
  opacity: 0; animation: d-in .8s 1.5s ease-out forwards;
}
.d-col {
  writing-mode: vertical-rl; height: 100%; color: #2C2419; font-size: 24px; line-height: 1.5;
  letter-spacing: 0.08em; font-weight: 400;
  opacity: 0; animation: d-in 1s var(--d) ease-out forwards;
}
.d-col + .d-col { border-right: 1px solid rgba(60,48,26,0.15); padding-right: 21px; margin-right: 21px; }
.slidev-layout.mk-d8 .d-col-title h1 {
  writing-mode: vertical-rl; font-size: 38px; font-weight: 500; letter-spacing: 0.13em;
  color: #241D13; margin: 0; line-height: 1.2;
}
.d-no { display: inline-block; color: #B23F26; font-size: 19px; letter-spacing: 0; margin-inline-end: 18px; }
.d-col em {
  display: block; font-style: normal; font-size: 16px; color: #6E6353; letter-spacing: 0.06em;
  margin-right: 6px;
}
.d-col-close { font-size: 17px; color: #6E6353; letter-spacing: 0.12em; }
.d-seal-col { align-self: flex-end; margin-right: 30px; padding-bottom: 6px; opacity: 0; animation: d-in .9s 2.6s ease-out forwards; }
.d-seal {
  display: grid; place-items: center; width: 54px; height: 54px;
  writing-mode: vertical-rl; background: #C4432A; color: #F2E8CE;
  font-size: 21px; letter-spacing: 0.08em; mix-blend-mode: multiply;
  box-shadow: inset 0 0 0 1px rgba(242,232,206,0.5);
}
@keyframes d-in { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }
.d-art { flex: 1 1 auto; display: flex; align-items: center; justify-content: center; }
.d-clock { width: 288px; height: 288px; fill: none; }
.d-ring {
  stroke: #2C2419; stroke-width: 2.6; stroke-linecap: round; opacity: .82;
  stroke-dasharray: 100 100; stroke-dashoffset: 100;
  animation: d-draw 1.5s 1.6s cubic-bezier(.26,.7,.3,1) forwards;
}
@keyframes d-draw { to { stroke-dashoffset: 0; } }
.d-ring2 { stroke: rgba(44,36,25,0.22); stroke-width: 1; opacity: 0; animation: d-fade .9s 2.5s ease-out forwards; }
.d-tick line { stroke: rgba(44,36,25,0.5); stroke-width: 1.6; stroke-linecap: round; }
.d-tick { opacity: 0; animation: d-fade .9s 2.6s ease-out forwards; }
.d-hands { opacity: 0; animation: d-fade .9s 2.85s ease-out forwards; }
@keyframes d-fade { to { opacity: 1; } }
.d-hand-h { stroke: #2C2419; stroke-width: 4; stroke-linecap: round; transform-origin: 120px 120px; transform: rotate(-58deg); }
.d-hand-m { stroke: #2C2419; stroke-width: 2.4; stroke-linecap: round; transform-origin: 120px 120px; animation: d-spin 24s linear infinite; }
@keyframes d-spin { from { transform: rotate(58deg); } to { transform: rotate(418deg); } }
.d-pivot { fill: #B23F26; stroke: none; }
.d-tag { position: absolute; left: 64px; bottom: 34px; font-size: 13px; letter-spacing: 0.3em; color: #5C5340; }
</style>

---
title: 案四 巻物 / 溶ける和ろうそく
class: mk-d9
transition: fade-out
---

<div class="d-grain"></div>
<div class="d-lamp"></div>
<div class="d-scroll">
<div class="d-paper">
<div class="d-fiber"></div>
<div class="d-stain"></div>
<div class="d-inner">
<div class="d-cols">
<div class="d-daisen">和 ろ う そ く</div>
<div class="d-col d-col-title" style="--d:1.5s"><h1>溶ける和ろうそく</h1></div>
<div class="d-col" style="--d:1.75s"><span class="d-no">一</span>溜まるバーではなく、減る蝋燭</div>
<div class="d-col" style="--d:1.95s"><span class="d-no">二</span>満ちたら休め。バーは逆だった</div>
<div class="d-col" style="--d:2.15s"><span class="d-no">三</span>数字は出さない<em>そろそろか否かだけ</em></div>
<div class="d-seal-col"><span class="d-seal">刻々</span></div>
</div>
<div class="d-art">
<div class="d-fig">
<video class="d-video" autoplay muted loop playsinline>
<source src="./public/media/demo-c-candle-burnout.mp4" type="video/mp4" />
</video>
<div class="d-fast">早回し</div>
</div>
<div class="d-figcap">図 ― 燃え尽きて、また灯るまで</div>
</div>
</div>
</div>
<div class="d-rod d-rod-l"></div>
<div class="d-rod d-rod-r"></div>
</div>
<div class="d-tag">案四 巻物</div>

<style>
.slidev-layout.mk-d9 {
  padding: 0; color: #F8ECD8; overflow: hidden; position: relative;
  background: radial-gradient(120% 100% at 22% 18%, #171209 0%, #0A0806 66%);
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", "Yu Mincho", serif;
}
.d-grain {
  position: absolute; inset: 0; pointer-events: none; opacity: 0.45;
  background-image:
    radial-gradient(circle at 9% 82%, rgba(217,180,92,0.5) 0 1.4px, transparent 1.9px),
    radial-gradient(circle at 21% 12%, rgba(217,180,92,0.42) 0 1.8px, transparent 2.3px),
    radial-gradient(circle at 74% 92%, rgba(217,180,92,0.45) 0 1.1px, transparent 1.6px),
    radial-gradient(circle at 90% 22%, rgba(217,180,92,0.4) 0 2px, transparent 2.6px),
    radial-gradient(circle at 52% 6%, rgba(217,180,92,0.36) 0 1.3px, transparent 1.8px),
    radial-gradient(circle at 96% 70%, rgba(217,180,92,0.42) 0 1.5px, transparent 2px);
}
.d-lamp {
  position: absolute; right: 2%; top: 50%; width: 52%; height: 150%; transform: translateY(-50%);
  background: radial-gradient(32% 30% at 50% 50%, rgba(255,199,92,0.13) 0%, rgba(218,138,50,0.04) 48%, rgba(0,0,0,0) 78%);
  animation: d-breathe 7s ease-in-out infinite;
}
@keyframes d-breathe { 0%,100% { opacity: .78 } 50% { opacity: 1 } }
.d-scroll { position: absolute; left: 64px; right: 64px; top: 92px; height: 510px; --span: 1112px; }
.d-rod {
  position: absolute; top: -18px; bottom: -18px; width: 20px; border-radius: 3px;
  background: linear-gradient(90deg, #12100A 0%, #3E3220 26%, #6E5832 50%, #352B1B 78%, #100E09 100%);
}
.d-rod::before, .d-rod::after {
  content: ""; position: absolute; left: -5px; width: 30px; height: 15px; border-radius: 3px;
  background: linear-gradient(160deg, #EBD79A, #A98A52 55%, #6B551F);
  box-shadow: 0 2px 8px rgba(0,0,0,0.55);
}
.d-rod::before { top: -7px; }
.d-rod::after { bottom: -7px; }
.d-rod-r { right: 0; box-shadow: -10px 0 26px rgba(0,0,0,0.6); }
.d-rod-l {
  left: var(--span); box-shadow: 10px 0 26px rgba(0,0,0,0.6); z-index: 3;
  animation: d-roll 1.5s .25s cubic-bezier(.2,.78,.24,1) forwards;
}
/* clip-path と同じメインスレッドの時計で動かすため transform ではなく left を使う */
@keyframes d-roll { to { left: 0; } }
.d-paper {
  position: absolute; left: 20px; right: 20px; top: 14px; bottom: 14px;
  isolation: isolate; overflow: hidden;
  background:
    repeating-linear-gradient(90deg, rgba(112,84,40,0) 0 78px, rgba(112,84,40,0.05) 104px, rgba(112,84,40,0) 132px),
    radial-gradient(150% 130% at 84% 16%, #F1E6C9 0%, #E6D8B6 44%, #D8C69D 78%, #CBB78D 100%);
  box-shadow:
    inset 0 14px 24px -16px rgba(84,60,24,0.55), inset 0 -14px 24px -16px rgba(84,60,24,0.55),
    0 26px 60px rgba(0,0,0,0.6);
  clip-path: inset(0 0 0 100%);
  animation: d-unroll 1.5s .25s cubic-bezier(.2,.78,.24,1) forwards;
}
@keyframes d-unroll { to { clip-path: inset(0 0 0 0); } }
.d-fiber {
  position: absolute; inset: 0; pointer-events: none; opacity: .55;
  background-image:
    repeating-linear-gradient(94deg, rgba(120,96,52,0.055) 0 1px, transparent 1px 6px),
    repeating-linear-gradient(3deg, rgba(120,96,52,0.04) 0 1px, transparent 1px 5px);
}
.d-stain {
  position: absolute; inset: 0; pointer-events: none; mix-blend-mode: multiply; opacity: .34;
  background-image:
    radial-gradient(ellipse 120px 60px at 11% 84%, rgba(150,112,52,0.3), transparent 70%),
    radial-gradient(ellipse 90px 70px at 44% 8%, rgba(150,112,52,0.22), transparent 72%),
    radial-gradient(ellipse 150px 80px at 92% 90%, rgba(150,112,52,0.26), transparent 74%);
}
.d-inner {
  position: relative; height: 100%; padding: 38px 46px;
  display: flex; flex-direction: row-reverse; align-items: stretch; justify-content: space-between;
}
.d-cols { display: flex; flex-direction: row-reverse; align-items: stretch; }
.d-daisen {
  align-self: flex-start; writing-mode: vertical-rl; margin: 2px 2px 0 34px;
  background: #F0E7CF; border: 1px solid rgba(60,48,26,0.45); padding: 14px 5px;
  font-size: 13px; letter-spacing: 0.24em; color: #4A4032;
  box-shadow: 0 3px 7px rgba(90,66,28,0.2);
  opacity: 0; animation: d-in .8s 1.5s ease-out forwards;
}
.d-col {
  writing-mode: vertical-rl; height: 100%; color: #2C2419; font-size: 24px; line-height: 1.5;
  letter-spacing: 0.08em; font-weight: 400;
  opacity: 0; animation: d-in 1s var(--d) ease-out forwards;
}
.d-col + .d-col { border-right: 1px solid rgba(60,48,26,0.15); padding-right: 21px; margin-right: 21px; }
.slidev-layout.mk-d9 .d-col-title h1 {
  writing-mode: vertical-rl; font-size: 38px; font-weight: 500; letter-spacing: 0.13em;
  color: #241D13; margin: 0; line-height: 1.2;
}
.d-no { display: inline-block; color: #B23F26; font-size: 19px; letter-spacing: 0; margin-inline-end: 18px; }
.d-col em {
  display: block; font-style: normal; font-size: 16px; color: #6E6353; letter-spacing: 0.06em;
  margin-right: 6px;
}
.d-seal-col { align-self: flex-end; margin-right: 30px; padding-bottom: 6px; opacity: 0; animation: d-in .9s 2.6s ease-out forwards; }
.d-seal {
  display: grid; place-items: center; width: 54px; height: 54px;
  writing-mode: vertical-rl; background: #C4432A; color: #F2E8CE;
  font-size: 21px; letter-spacing: 0.08em; mix-blend-mode: multiply;
  box-shadow: inset 0 0 0 1px rgba(242,232,206,0.5);
}
@keyframes d-in { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }
.d-art {
  flex: 0 0 520px; display: flex; flex-direction: column; justify-content: center;
  opacity: 0; animation: d-in 1s 1.7s ease-out forwards;
}
.d-fig {
  position: relative; width: 100%; aspect-ratio: 1440 / 800; overflow: hidden;
  border: 1px solid rgba(44,36,25,0.75); outline: 1px solid rgba(44,36,25,0.2); outline-offset: 4px;
  background: #100E0A; box-shadow: 0 14px 30px rgba(70,50,20,0.35);
}
.d-video { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; display: block; }
.d-fast {
  position: absolute; right: 10px; bottom: 8px; font-size: 13px; letter-spacing: 0.2em; color: #E4DAC4;
  padding: 2px 8px 3px; background: rgba(10,9,7,0.55); backdrop-filter: blur(2px);
}
.d-figcap { margin-top: 16px; font-size: 14px; letter-spacing: 0.16em; color: #6E6353; text-align: center; }
.d-tag { position: absolute; left: 64px; bottom: 34px; font-size: 13px; letter-spacing: 0.3em; color: #5C5340; }
</style>
