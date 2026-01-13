---
marp: true
size: A4
paginate: false
theme: default
---

<!-- _class: lead -->

# Flow Garden
### Generative / Interactive / Physics

---

<!--
以下は1スライド完結型ポスター
-->

<style>
section {
  display: grid;
  grid-template-rows: auto 1fr auto auto auto;
  row-gap: 16px;
}
.poster-image {
  border: 2px dashed #999;
  height: 320px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #666;
  font-size: 18px;
}
.grid-2 {
  display: grid;
  grid-template-columns: 1fr 1fr;
  column-gap: 20px;
}
.footer {
  display: grid;
  grid-template-columns: 2fr 1fr;
  column-gap: 20px;
  align-items: center;
}
.qr {
  border: 1px solid #999;
  height: 90px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 14px;
  color: #666;
}
</style>

<div class="poster-image">
  Processing 実行画面のスクリーンショット
</div>

<div class="grid-2">

<div>

## ■ コンセプト
この作品は「自然の流れ」をテーマに，  
ランダム性と秩序が共存する動きを  
Processingで表現した作品です。

</div>

<div>

## ■ 技術ポイント
**使用した技術**
- for文による多数オブジェクト制御  
- ベクトルによる移動計算  
- noise() を用いた滑らかな変化  

**工夫した点**
- 粒子同士が重なりすぎないように調整  
- 時間経過で色が変化する仕組みを追加  

</div>

</div>

## ■ 操作方法・見どころ
**操作方法**
- マウス移動：流れの方向が変化  
- クリック：粒子の数が増加  

**見どころ**
- 流れが自然に切り替わる瞬間  
- 全体として一つの形に見える動き  

<div class="footer">

<div>
**3班**  
メンバー：Aさん，Bさん，Cさん
</div>

<div class="qr">
QRコード
</div>

</div>