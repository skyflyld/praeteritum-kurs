---
theme: default
title: Präteritum — Die Zeit der Geschichten
author: Ariste
transition: slide-left
mdc: true
highlighter: shiki
fonts:
  sans: Inter
  serif: Georgia
  mono: Fira Code
css: unocss
---

<style>
.slidev-layout {
  background: #f5f0e8 !important;
  color: #1a1a1a !important;
}
.slidev-layout h1, .slidev-layout h2 {
  font-family: Georgia, serif !important;
}
.red-accent { color: #c41e3a; }
.gold-accent { color: #b8860b; }
.zh-note { font-size: 0.8em; color: #6b6b6b; }
.news-badge {
  font-family: Georgia, serif;
  font-size: 0.75em;
  color: #c41e3a;
  letter-spacing: 3px;
  text-transform: uppercase;
  border: 1px solid #c41e3a;
  padding: 4px 20px;
  display: inline-block;
}
.flash-card {
  background: #fafaf5;
  border: 2px solid #d4c9b8;
  border-radius: 8px;
  padding: 20px;
  text-align: center;
  transition: all 0.3s;
}
.flash-card:hover {
  border-color: #c41e3a;
  transform: translateY(-4px);
}
.verb-card {
  display: inline-block;
  background: #fff;
  border: 2px solid #d4c9b8;
  border-radius: 8px;
  padding: 12px 20px;
  margin: 6px;
  font-family: Georgia, serif;
  font-size: 1.1em;
  cursor: pointer;
  transition: all 0.3s;
}
.verb-card:hover {
  border-color: #c41e3a;
  background: #fef5f5;
}
.trap-box {
  border: 3px dashed #d4c9b8;
  border-radius: 12px;
  padding: 30px;
  text-align: center;
  cursor: pointer;
  transition: all 0.3s;
}
.trap-box:hover {
  border-color: #c41e3a;
  background: #fef5f5;
}
.step-box {
  background: #fff8e1;
  border-left: 4px solid #b8860b;
  padding: 16px;
  border-radius: 0 8px 8px 0;
  margin: 12px 0;
}
.rescue-card {
  display: inline-block;
  background: linear-gradient(135deg, #fff 0%, #fff5f5 100%);
  border: 2px solid #d4c9b8;
  border-radius: 8px;
  padding: 16px 20px;
  margin: 6px;
  text-align: center;
  font-family: Georgia, serif;
  min-width: 100px;
}
.rescue-card .inf { font-weight: 700; font-size: 1.1em; }
.rescue-card .past { color: #c41e3a; font-size: 1.2em; font-weight: 700; margin-top: 4px; }
.ticket-card {
  background: linear-gradient(135deg, #fffef9 0%, #fff9e6 100%);
  border: 1px solid #e8dca0;
  border-radius: 8px;
  padding: 20px;
  position: relative;
}
.ticket-card::before {
  content: '';
  position: absolute;
  top: 0; left: 50%;
  transform: translateX(-50%);
  width: 16px; height: 8px;
  background: #f5f0e8;
  border-radius: 0 0 50% 50%;
}
</style>

---
layout: center
class: text-center
---

<div class="news-badge mb-8">📰 DIE ZEITUNG</div>

# Präteritum
## <span class="red-accent">Die Zeit der Geschichten</span>

<span class="zh-note">过去时 — 讲故事时态</span>

<div class="mt-12 text-lg">
  <span class="red-accent">Sei ein Reporter!</span>
  <span class="zh-note ml-4">当一回记者</span>
</div>

---
layout: image-right
image: https://images.unsplash.com/photo-1504711434969-e33886168d6c?w=400
---

# Zwei Sprachen, zwei Welten

<span class="zh-note">两种语言，两个世界</span>

<div class="mt-8">

<div class="flash-card mb-4">
  <div style="color:#6b6b6b;font-size:0.85em">🗣️ <strong>Alltag · 口语</strong></div>
  <div class="text-xl my-2"><strong>Perfekt</strong></div>
  <div>Der Kanzler <em>hat</em> gestern Hangzhou <em>besucht</em>.</div>
</div>

<div class="flash-card" style="border-color:#c41e3a;background:#fef5f5">
  <div style="color:#c41e3a;font-size:0.85em">📰 <strong>Nachrichten · 新闻</strong></div>
  <div class="text-xl my-2"><strong>Präteritum</strong></div>
  <div>Der Kanzler <em style="color:#c41e3a">besuchte</em> gestern Hangzhou.</div>
</div>

</div>

---
layout: two-cols
---

# Perfekt

<v-clicks>

- <strong>haben / sein</strong> + Partizip II
- Der Kanzler <em>hat</em> … <em>besucht</em>
- Ich <em>habe</em> … <em>gelernt</em>
- Er <em>ist</em> … <em>gefahren</em>
- <span class="zh-note">需要记住助动词 + 二分词</span>

</v-clicks>

::right::

# Präteritum

<v-clicks>

- <strong>动词本身变形</strong>
- Der Kanzler <em style="color:#c41e3a">besuchte</em> …
- Ich <em style="color:#c41e3a">lernte</em> …
- Er <em style="color:#c41e3a">fuhr</em> …
- <span class="zh-note">不需要助动词！不需要 ge-！</span>

</v-clicks>

---
layout: center
---

# 🔍 Entdecke das Muster!

<span class="zh-note">自己发现规律</span>

<div class="mt-8 grid grid-cols-2 gap-4">
  <div class="verb-card" v-click="1">machen → mach<span style="color:#c41e3a;font-weight:700">te</span></div>
  <div class="verb-card" v-click="2">lernen → lern<span style="color:#c41e3a;font-weight:700">te</span></div>
  <div class="verb-card" v-click="3">wohnen → wohn<span style="color:#c41e3a;font-weight:700">te</span></div>
  <div class="verb-card" v-click="4">spielen → spiel<span style="color:#c41e3a;font-weight:700">te</span></div>
  <div class="verb-card" v-click="5">fragen → frag<span style="color:#c41e3a;font-weight:700">te</span></div>
</div>

<div v-click="6" class="mt-8 step-box">
  <h3 class="gold-accent">🎉 Die 3-Schritte-Regel</h3>
  <ol>
    <li><strong>Stamm finden:</strong> 不定式去掉 -en <span class="zh-note">找词干</span></li>
    <li><strong>-te anhängen:</strong> 词干 + te <span class="zh-note">加 -te</span></li>
    <li><strong>Kein -ge-!</strong> Kein Hilfsverb! <span class="zh-note">不用 ge-，不用助动词</span></li>
  </ol>
</div>

---
layout: center
---

# ⚠️ Achtung, Falle!

<span class="zh-note">小心陷阱</span>

<div class="trap-box" v-click="1">
  <div class="zh-note">Stamm = arbeit- → arbeit + te = ???</div>
  <div class="text-3xl font-serif my-4">arbeit-te ❓</div>
  <div class="zh-note">👆 对吗？</div>
</div>

<div v-click="2" class="mt-8">
  <div class="text-3xl font-serif red-accent">arbeit<span style="border-bottom:3px solid #b8860b">ete</span> ✅</div>
  <div class="step-box mt-4">
    <strong>🔑 Regel:</strong> 词干以 <strong>-t</strong> 或 <strong>-d</strong> 结尾 → 加 <strong>-ete</strong><br>
    <span class="zh-note">arbeiten → arbeit<b>ete</b> &nbsp;|&nbsp; reden → red<b>ete</b> &nbsp;|&nbsp; warten → wart<b>ete</b></span>
  </div>
</div>

---
layout: center
---

# 🩹 Notfall-Karten

<span class="zh-note">不规则动词急救卡 — 只记15个最常用的！</span>

<div class="mt-6 grid grid-cols-5 gap-3 text-sm">
  <div class="rescue-card"><div class="inf">gehen</div><div class="past">ging</div></div>
  <div class="rescue-card"><div class="inf">essen</div><div class="past">aß</div></div>
  <div class="rescue-card"><div class="inf">sehen</div><div class="past">sah</div></div>
  <div class="rescue-card"><div class="inf">kommen</div><div class="past">kam</div></div>
  <div class="rescue-card"><div class="inf">fahren</div><div class="past">fuhr</div></div>
  <div class="rescue-card"><div class="inf">geben</div><div class="past">gab</div></div>
  <div class="rescue-card"><div class="inf">finden</div><div class="past">fand</div></div>
  <div class="rescue-card"><div class="inf">nehmen</div><div class="past">nahm</div></div>
  <div class="rescue-card"><div class="inf">schreiben</div><div class="past">schrieb</div></div>
  <div class="rescue-card"><div class="inf">bleiben</div><div class="past">blieb</div></div>
  <div class="rescue-card"><div class="inf">sprechen</div><div class="past">sprach</div></div>
  <div class="rescue-card"><div class="inf">liegen</div><div class="past">lag</div></div>
  <div class="rescue-card"><div class="inf">stehen</div><div class="past">stand</div></div>
  <div class="rescue-card"><div class="inf">tun</div><div class="past">tat</div></div>
  <div class="rescue-card"><div class="inf">wissen</div><div class="past">wusste</div></div>
</div>

---
layout: center
---

# 📝 Ein Tag im Leben eines Reporters

<span class="zh-note">记者的一天 — 用急救卡里的动词写一段故事</span>

<div class="flash-card mt-8 text-left">
  <strong>📰 Beispiel:</strong><br>
  Der Reporter <em style="color:#c41e3a">kam</em> um 7 Uhr ins Büro. 
  Er <em style="color:#c41e3a">aß</em> ein Sandwich und <em style="color:#c41e3a">trank</em> einen Kaffee. 
  Dann <em style="color:#c41e3a">schrieb</em> er einen Artikel. 
  Um 12 Uhr <em style="color:#c41e3a">fuhr</em> er zum Rathaus und <em style="color:#c41e3a">sprach</em> mit dem Pressesprecher.
</div>

<div class="mt-6 zh-note">
  💡 使用了: kam, aß, trank, schrieb, fuhr, sprach
</div>

---
layout: two-cols
---

# 🎫 Exit-Ticket

<div class="ticket-card mt-4">
  <h4 class="gold-accent">✅ Heute habe ich gelernt…</h4>
  <p class="zh-note text-sm mb-2">今天我学到了……</p>
  <div style="border:1px dashed #d4c9b8;border-radius:4px;height:80px"></div>
</div>

::right::

<div class="mt-16"></div>

<div class="ticket-card">
  <h4 class="gold-accent">❓ Ich bin noch nicht sicher bei…</h4>
  <p class="zh-note text-sm mb-2">我还不太确定……</p>
  <div style="border:1px dashed #d4c9b8;border-radius:4px;height:80px"></div>
</div>

---
layout: center
class: text-center
---

# <span class="red-accent">二分词忘了？<br>那就用过去时！</span>

<div class="mt-8 text-xl">
  Präteritum = Die Zeit der Geschichten
</div>

<div class="mt-12 flex flex-wrap gap-2 justify-center">
  <span v-for="v in ['ging','aß','sah','kam','fuhr','gab','fand','nahm','schrieb','blieb','sprach','lag','stand','tat','wusste']" class="px-3 py-1 rounded-full text-sm" style="background:rgba(196,30,58,0.1);color:#c41e3a;font-family:Georgia,serif">{{ v }}</span>
</div>

<div class="mt-12">
  <span class="text-lg red-accent">Gut gemacht, Reporter!</span>
  <span class="zh-note ml-2">做得好，记者！</span>
</div>
