---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: トラックボールマウスとトラックパッドの使用感比較
hideInToc: true
---

# トラックボールマウスとトラックパッドの比較

テックソリューション室 SI事業部 フロントエンド開発G<br>
福西俊介

<style>
  h1 {
    font-size: 20px;
  }
</style>
---
transition: fade-out
hideInToc: true
level: 1
---

# 目次

<Toc />
<br>
<br>

---
layout: default
---

# はじめに

<div class="outline">
  <p class="outline-text">
    トラックボールマウスとトラックパッドに関してネットで調べたメリットとデメリット、<br>
    そして実際両方を使用してみて感じたことなどを話そうと思います。
  </p>
</div>
<div class="links">
  <a href="https://www.amazon.co.jp/gp/aw/d/B0B19W7YRV/ref=ya_aw_od_pi?ie=UTF8&psc=1" target="_blank" rel="noopener noreferrer">https://www.amazon.co.jp/gp/aw/d/B0B19W7YRV/ref=ya_aw_od_pi?ie=UTF8&psc=1</a><br>
  <a href="https://www.apple.com/jp/shop/product/MK2D3ZA/A/magic-trackpad-%E3%83%9B%E3%83%AF%E3%82%A4%E3%83%88multi-touch%E5%AF%BE%E5%BF%9C" target="_blank" rel="noopener noreferrer">https://www.apple.com/jp/shop/product/MK2D3ZA/A/magic-trackpad-%E3%83%9B%E3%83%AF%E3%82%A4%E3%83%88multi-touch%E5%AF%BE%E5%BF%9C</a>
</div>


<style>
.outline {
  margin-top: 90px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 21px;
  outline-style: none;
}
.outline-text {
  line-height: 2.5rem;
}
.links {
  margin-left: 20px;
}
</style>
---
transition: fade-out

level: 1
---

# トラックボールマウス、トラックパッドとは

<section class="wrapper">
  <div class="column1">
    <h2>トラックボールマウス</h2>
    <div class="explanation">
      指で球体（トラックボール）を回転させることでカーソルを制御するタイプのマウス。<br />
      これは親指でボールを回転させるタイプ。
    </div>
    <img src="/public/IMG_9229.jpeg" />
  </div>
  <div class="column2">
    <h2>トラックパッド</h2>
    <div class="explanation">
      ノートパソコンなどによくついている、指の動きでカーソルを制御するデバイス。
    </div>
    <br />
    <img src="/public/IMG_9228.jpeg" />
  </div>
</section>


<style>
  .wrapper {
    margin-top: 40px;
    display: flex;
    gap: 100px;
  }
  .explanation {
    margin: 12px 0px 16px;
  }
  .column1 {
    width: 50%;
  }
  .column2 {
    width: 50%
  }
  img {
    max-width: 280px;
  }
</style>
---
---

# トラックボールマウスのメリット

<div class="image-container">
  <div class="column1">
    <p>- 長い距離のカーソル移動が楽にできる</p>
    <p>- スペースはマウスが置けるだけの広さがあればいい</p>
    <p>- マウスパッドが必要ない</p>
    <p>- マウスの左側にあるボタンでページを戻ったり進んだりできる</p>
  </div>
  <div class="column2">
    <img src="/public/IMG_9229.jpeg" />
  </div>
</div>

<style>
.image-container {
  display: flex;
  align-items: center;
  margin-top: 80px;
}
.column1 {
  margin-right: 20px;
}
.column2 {
  width: 36%;
  height: auto;
}
img {
  width: 100%;
  height: 100%;
}
</style>
---
---

# トラックボールマウスのデメリット

<div class="image-container">
  <div class="column1">
    <p>- 扱いに慣れる必要がある</p>
    <p>- 掃除などのメンテナンスが必要になる</p>
    <p>- 細かい操作をするのが難しい</p>
    <p>- 自分に合うボールの位置を考える必要がある</p>
    <p>- ワイヤレス、Bluetoothは価格が高め</p>
    <table>
      <tbody>
        <tr>
          <td>有線：</td>
          <td>2000円台</td>
        </tr>
        <tr>
          <td>ワイヤレス：</td>
          <td>4000円~</td>
        </tr>
        <tr>
          <td>Bluetooth：</td>
          <td>6000円~</td>
        </tr>
      </tbody>
    </table>
    <a href="https://kakaku.com/pc/trackball/" target="_blank" rel="noopener noreferrer">https://kakaku.com/pc/trackball/</a>
  </div>
  <div class="column2">
    <img src="/public/IMG_9229.jpeg" />
  </div>
</div>

<style>
.image-container {
  display: flex;
  align-items: center;
  margin-top: 40px;
}
.column1 {
  margin-right: 20px;
}
.column2 {
  width: 50%;
  height: auto;
}
img {
  width: 100%;
  height: 100%;
}
table {
  margin-bottom: 20px
}
</style>

---

# トラックパッドのメリット

<div class="image-container">
  <div class="column1">
    <p>- スワイプやズームなど様々なジェスチャーが使える</p>
    <p>- スマホ操作と似ており、直感的に操作ができる</p>
    <p>- トラックパッドが置けるだけの広さがあればいい</p>
    <p>- 手首が痛くなりにくい</p>
    <p>- 横スクロールが簡単にできる</p>
  </div>
  <div class="column2">
    <img src="/public/IMG_9228.jpeg" />
  </div>
</div>

<style>
.image-container {
  display: flex;
  align-items: center;
  margin-top: 60px;
}
.column1 {
  margin-right: 20px;
}
.column2 {
  width: 50%;
  height: auto;
}
img {
  width: 100%;
  height: 100%;
}
</style>

---
class: px-20
---

# トラックパッドのデメリット

<div class="image-container">
  <div class="column1">
    <p>- 長い距離のドラッグがやりにくい</p>
    <p>- ゲームやOffice系ソフトなど細かな作業がしにくい</p>
    <p>- 指が少し疲れる場合がある</p>
    <p>- 価格が高め</p>
    <table>
      <tbody>
        <tr>
          <td>独立型:</td>
          <td>6000円~</td>
        </tr>
        <tr>
          <td>キーボード一体型：</td>
          <td>5000円~</td>
        </tr>
      </tbody>
    </table>
    <a href="https://my-best.com/1508#ranking" target="_blank" rel="noopener noreferrer">https://my-best.com/1508#ranking</a>
  </div>
  <div class="column2">
    <img src="/public/IMG_9228.jpeg" />
  </div>
</div>

<style>
.image-container {
  display: flex;
  align-items: center;
  margin-top: 40px;
}
.column1 {
  margin-right: 20px;
}
.column2 {
  width: 44%;
  height: auto;
}
img {
  width: 100%;
  height: 100%;
}
table {
  margin-bottom: 20px
}
</style>
---
preload: false
---


# どちらも使ってみてわかったこと

<div class="wrapper">
<h3>トラックパッドの方が使いやすい</h3>
<ul>
<li>横スクルールが簡単にできる</li>
<li>ウィンドウのサイズを変える時操作しやすい</li>
<li>充電が長持ちする</li>
<li>掃除する必要があまりない</li>
<li>持ち運ぶ際に幅を取らない</li>
</ul>
</div>

<style>
  .wrapper {
    margin-top: 40px;
  }
  ul {
    margin-top: 20px;
  }
  h3 {
    text-decoration: underline;
  }
</style>
---

<h2>
  ご静聴ありがとうございました!
</h2>

<style>
  div {
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

