---
theme: default
background: 'https://images.unsplash.com/photo-1525383547365-11f33578ba4c?q=80&w=2070&auto=format&fit=crop'
class: 'text-center'
css: unocss
transition: slide-left
title: '台南公園輕社交平台：UX 設計個案研究'
info: 一份關於如何透過數位平台，幫助害羞的青少年在台南公園進行低壓力社交的 UX 個案研究。
toc: true
speaker: true
---

# <span class="text-white drop-shadow-xl text-6xl font-bold">台南公園輕社交平台</span>
<p class="text-white/80 tracking-widest mt-4 block font-light text-2xl">從行為觀察到「反思型社交」的設計實踐</p>

<div class="pt-12">
  <div class="inline-block backdrop-blur-md bg-white/10 border border-white/20 px-8 py-4 rounded-2xl shadow-2xl">
    <p class="font-mono text-sm">使用者經驗設計個案研究</p>
  </div>
</div>

<!--
大家好，我們是第Ｘ組，今天要報告的主題是「台南公園輕社交平台」。這是一個關於如何透過數位設計，幫助害羞或慢熟的年輕人，在他們感到舒適的步調下，重新與公共空間建立連結的專案。我們的報告將會從最初的田野觀察開始，一路帶大家看到我們如何定義問題、發展人物誌，並最終設計出一個以「反思型社交」為核心的數位平台。
-->

---

<Toc />

<!--
這是我們今天的報告大綱，主要會分成三個部分：第一部分是「專案介紹」，我們會說明本專案的目標與核心價值。第二部分是「設計方法」，這裡會詳細展示我們的研究流程與數據分析過程。第三部分則是「UX 設計解答」，我們會展示最終的網站原型是如何解決我們發現的問題。
-->

---
layout: section
---

# PART I
## 專案介紹 (INTRODUCTION)

<!--
好的，讓我們進入第一部分：專案介紹。這個章節的核心目標是讓大家快速了解，我們這個專案到底在做什麼、想解決什麼問題，以及它的核心價值主張。
-->

---

## 專案目標與價值主張

<div class="grid grid-cols-2 gap-8 text-left items-center">
  <div>
    <h3 class="font-bold text-2xl mb-4">專案目標</h3>
    <p class="text-white/80">本專案旨在探索如何透過一個數位平台，幫助青少年在一個感覺<b>低壓力、舒適、且忠於自我個性</b>的環境中進行社交。</p>
    <p class="text-white/80 mt-4">我們選擇以**台南公園**為中心，設計一個讓青少年可以發起或參與小型、「氛圍導向」活動的平台。</p>
  </div>
  <div class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <h3 class="font-bold text-2xl mb-4">價值主張</h3>
    <p class="text-white/80">與其推廣大型、吵雜或高度社交的活動，我們的設計更專注於：</p>
    <p class="text-teal-300 font-bold mt-4 text-lg">「幫助害羞或慢熟的使用者，在他們自己的步調下，安全地邁出社交的第一步，將公園變成一個友善、可及的連結場所。」</p>
  </div>
</div>

<!--
我們的專案目標非常明確：我們想知道，一個數位平台要如何幫助那些害羞的青少年，舒服地交朋友。我們不做那種強迫大家 high 起來的活動，而是專注在「降低社交門檻」，讓使用者可以自己決定互動的強度，把公園變成一個沒有壓力的地方。
-->

---

## 核心概念：反思型社交

<div class="text-left">
  <p v-click>傳統社交 App 的問題在於，它們假設所有使用者都已準備好、且渴望社交。它們的設計往往是：</p>
  <p v-click class="text-center my-4 text-xl font-mono text-red-300">活動內容 → 人員湊齊 → 強制社交</p>
  <p v-click>這種模式對害羞的使用者來說，是一場災難。他們在加入前無法預期氛圍，加入後又被迫快速破冰。</p>
  <br>
  <div v-click class="p-4 rounded-lg bg-teal-500/10 border-teal-500/50 border">
    <p>我們的核心概念——「反思型社交」——翻轉了這個流程：</p>
    <p class="text-center my-4 text-xl font-mono text-teal-300">社交強度篩選 → 低壓共同任務 → 自然連結</p>
    <p>使用者可以先「反思」自己當下的社交能量，選擇最舒適的互動方式，然後才參與活動。我們相信，這才能帶來真正有品質的連結。</p>
  </div>
</div>

<!--
我們提出的核心概念，叫做「反思型社交」。傳統的社交模式是把人湊在一起，然後期待他們能自然聊起來，但這對害羞的人來說壓力很大。我們的模式是反過來的：讓使用者先「向內看」，思考自己現在的狀態，是想多聊幾句，還是只想安靜地待著。根據這個「反思」的結果，平台再推薦給他最適合的活動。我們認為，這樣才能創造真正舒適的社交體驗。
-->

---
layout: section
---

# PART II
## 設計方法 (DESIGN METHODS)

<!--
接下來是第二部分，我們將詳細說明整個專案的研究與設計流程。我們遵循一個嚴謹的設計流程，從廣泛的探索，到逐步收斂問題，再到發想解決方案。
-->

---

## 設計流程概覽

本專案遵循「設計思考」的雙鑽石模型 (Double Diamond)，分為兩個主要階段。

<div class="grid grid-cols-2 gap-8 text-left text-sm mt-8">
  <div class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <h3 class="font-bold text-lg mb-2">💎 第一階段：設計問題探索 (Discovery & Define)</h3>
    <ul class="list-disc list-inside space-y-1 text-white/80">
      <li>基礎導入與研究 (Desk Research)</li>
      <li>場域研究與訪談 (Field Study)</li>
      <li>人物誌發展 (Persona)</li>
      <li>核心問題確立 (Problem Definition)</li>
    </ul>
  </div>
  <div class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <h3 class="font-bold text-lg mb-2">💎 第二階段：設計解答探索 (Develop & Deliver)</h3>
    <ul class="list-disc list-inside space-y-1 text-white/80">
      <li>創意開展與劇本規劃 (Storyboarding)</li>
      <li>原型開發與 MVP 實作 (Prototyping)</li>
      <li>原型測試與角色扮演 (Role-play Testing)</li>
      <li>最終迭代與成果發表 (Final Delivery)</li>
    </ul>
  </div>
</div>

<p class="text-xs text-white/60 mt-8">資料來源: `data/presentation_guide.md`</p>

<!--
我們的流程，基本上遵循設計思考的雙鑽石模型。第一個鑽石是「探索問題」，包含桌面研究、田野調查、人物誌建立與問題定義。我們的目標是「做對的事」。第二個鑽石是「探索解答」，包含腳本規劃、原型開發與測試。我們的目標是「把事做對」。接下來，我們會逐一介紹每個環節的細節。
-->

---

## 場域評選：為何是台南公園？

<div class="text-left mt-4 backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
<h3 class="font-bold">決策對比矩陣 (Site Comparison Matrix)</h3>
<table class="w-full text-xs text-left mt-2">
  <thead class="text-white/70">
    <tr>
      <th class="p-2">維度</th>
      <th class="p-2">大東夜市</th>
      <th class="p-2">銀同社區</th>
      <th class="p-2 text-teal-300">台南公園 (決選)</th>
    </tr>
  </thead>
  <tbody class="text-white/90">
    <tr class="border-t border-white/10">
      <td class="p-2 font-bold">數位化目標</td>
      <td class="p-2">解決「便利與效率」</td>
      <td class="p-2">解決「紀錄與傳承」</td>
      <td class="p-2 font-bold text-teal-300">解決「行為與心理斷層」</td>
    </tr>
    <tr class="border-t border-white/10">
      <td class="p-2 font-bold">社交互動性</td>
      <td class="p-2">高（但僅限商業交易）</td>
      <td class="p-2">低（多為單向聆聽）</td>
      <td class="p-2 font-bold text-teal-300">高（潛在社交需求巨大）</td>
    </tr>
    <tr class="border-t border-white/10">
      <td class="p-2 font-bold">環境壓力</td>
      <td class="p-2">高（擁擠、吵雜）</td>
      <td class="p-2">中（需尊重私領域）</td>
      <td class="p-2 font-bold text-teal-300">極低（無壓力中介空間）</td>
    </tr>
    <tr class="border-t border-white/10">
      <td class="p-2 font-bold">研究價值</td>
      <td class="p-2">偏向功能性優化</td>
      <td class="p-2">偏向社會設計</td>
      <td class="p-2 font-bold text-teal-300">偏向 UX 行為深度分析</td>
    </tr>
  </tbody>
</table>
</div>

<p class="text-xs text-white/60 mt-4 text-left">資料來源: `data/research.md`</p>

<!--
在專案初期，我們評估了三個潛在場域。我們發現台南公園的研究價值最高，因為它的問題核心是關於「人的行為與心理斷層」。我們觀察到一個非常有趣的現象，我們稱之為「數位孤島」——人們身處在一個開放的公共空間，卻選擇退回到手機的個人世界裡。這個矛盾的現象，讓我們決定把台南公園當作我們深入研究的對象。
-->

---
layout: two-cols
---

## 田野觀察 (原始數據)

我們紀錄了 12 組使用者的行為。這些第一手資料揭示了使用者在公園中的真實狀態。

<br>

**資料來源: `data/field_study.csv`**

::right::

<div class="space-y-4 text-xs">
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-yellow-300 mb-1">(U7) 剛放學的南二中同學</p>
    <p class="text-white/80 italic">「和他的朋友們一邊過馬路一邊看手機... 的同學時不時會模仿手機上短片內容，引三人大笑... 到公車站後自成一小群一起等公車。」</p>
    <p class="text-white/50 mt-1">-> 身體在場，但社交焦點在手機內容。</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-teal-300 mb-1">(U8) 穿便服的大學生</p>
    <p class="text-white/80 italic">「自己一個人在人行道上行走，似乎很專注在自己的手機上... 的手機畫面似乎是遊戲... 開始在聊天軟體與遊戲畫面之間來回切換。」</p>
    <p class="text-white/50 mt-1">-> 利用數位裝置建立個人結界。</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-red-300 mb-1">(U9) 在對向等公車的人</p>
    <p class="text-white/80 italic">「旁觀的人很多，似乎感到一些焦慮，每隔幾分鐘會一邊張望一邊東西望... 臉上明顯透露出不耐煩，並且手機上開啟大台南公車app。」</p>
    <p class="text-white/50 mt-1">-> 在人群中感到焦慮，手機成為緩解工具。</p>
  </div>
</div>

<!--
這是我們在現場觀察到的幾個真實案例。我們看到，學生群體即使聚在一起，注意力仍在手機上；也有獨自一人的大學生，在遊戲和聊天軟體之間頻繁切換。更有趣的是，一位等車的民眾，因為人多而感到焦慮，並頻繁查看公車App。這些都顯示了人們在公共空間中，對數位設備的高度依賴與複雜的心理狀態。
-->

---

## 行為分析 (1/3)：數據準備程式碼

為了從質化觀察中找出規律，我們編寫 Python 程式碼，將 12 組使用者的行為量化到 9 個維度上。

**資料來源: `data/user_behavior_dimension_analysis.ipynb`**

```python {all|5-9|10-12}
# Data Definition (Quantifying qualitative observations)
data = {
    'Scale': [
        'Negative vs Positive Emotion', 'No Tech vs Using Tech', 'Alone vs Group',
        'Stationary vs Fast Moving', 'Distracted vs Focused', 'Uncomfortable vs Comfortable',
        'Short vs Long Stay', 'Aimless vs Purposeful', 'No vs Yes Facility Interaction'
    ],
    # Example Data Point (U1: Child Biking)
    '1': [5.0, 4.1, 2.5, 9.1, 4.8, 5.4, 2.0, 0.7, 7.7],
    # ... (Data for U2-U12)
}

# Transpose and Standardize
import pandas as pd
from sklearn.preprocessing import StandardScaler

df_orig = pd.DataFrame(data)
df_transposed = df_orig.set_index('Scale').transpose()
scaler = StandardScaler()
X_scaled = scaler.fit_transform(df_transposed)
```

<!--
我們分析的第一步，是將觀察紀錄數據化。我們定義了九個維度，例如情緒、科技使用、獨處或群體等等，並為 12 組使用者打分數。為了讓每個維度的權重相同，我們接著使用 StandardScaler 對數據進行標準化，消除單位的影響。這一步是後續聚類分析的基礎。
-->

---

## 行為分析 (2/3)：聚類演算法

接著，我們使用 `DBSCAN` 演算法來對標準化後的數據進行分群。DBSCAN 的優點是不需要預設分群數量，能自動找出相似的數據點，並將離群值標記出來。

**資料來源: `data/user_behavior_dimension_analysis.ipynb`**

```python {all|6-7|9-13}
from sklearn.cluster import DBSCAN

# We need to determine the `eps` (epsilon) value,
# which defines the neighborhood radius for a point.
# After several tests, we found eps=3.0 to be optimal.
dbscan = DBSCAN(eps=3.0, min_samples=2)
dbscan_labels = dbscan.fit_predict(X_scaled)

# Results analysis
# The output `dbscan_labels` groups users with similar behavior patterns.
# [ 0  1  2  3  3  0  1  0 -1 -1  2  0]
# where -1 represents an outlier.
```

<div v-click class="mt-4 text-sm text-left backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
  <p>我們對 `eps` 參數進行了多次實驗 (`eps` 決定了鄰近點的搜索半徑)。</p>
  <p class="text-white/80">`eps=2.5` 時，群體過於分散；`eps=3.5` 時，則過於集中。最終 `eps=3.0` 產出了最有意義的四個群體與兩個離群值。</p>
</div>

<!--
數據準備好後，我們選擇了 DBSCAN 演算法來分群。選擇它的原因，是因為它不需要我們先猜測要分成幾群。演算法會自動根據數據的密集程度來找出群體。經過反覆測試 `eps` 這個關鍵參數後，我們在 `eps=3.0` 時，得到了最穩定且最具有解釋力的分群結果。
-->

---

## 行為分析 (3/3)：聚類結果與洞察

演算法最終將 12 組使用者分為 4 個核心群體與 2 個離群值。這讓我們清晰地看到公園中不同使用者的「存在狀態」。

**資料來源: `data/user_behavior_dimension_analysis_summary.md`**

<div class="grid grid-cols-2 gap-4 text-left text-sm mt-4">
  <div class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 space-y-2">
    <h3 class="font-bold text-red-300">Group A: 高頻流動者 (U1, U6, U8, U12)</h3>
    <p class="text-white/80 text-xs">通常處於移動狀態，社交窗口極短，互動必須是非侵入式的。</p>
    <h3 class="font-bold text-blue-300">Group B: 封閉社交者 (U2, U7)</h3>
    <p class="text-white/80 text-xs">身體在場，心理在別處 (手機或夥伴)，對外部干擾防禦心強。</p>
  </div>
  <div class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 space-y-2">
    <h3 class="font-bold text-yellow-300">Group C: 靜態停留者 (U3, U11)</h3>
    <p class="text-white/80 text-xs">有穩定停留基礎，是發展「微任務」或「共同興趣」社交的潛力股。</p>
    <h3 class="font-bold text-purple-300">Group D: 場域佔有者 (U4, U5)</h3>
    <p class="text-white/80 text-xs">舒適度極高，社交圈已固化，對數位平台介入需求最低。</p>
  </div>
</div>

<p v-click class="text-sm font-bold text-teal-300 mt-6 text-left">💡 核心洞察：不同群體間存在著「社交真空地帶」，這是我們設計介入的機會點。</p>

<!--
這是我們的最終分群結果。我們可以看到，公園裡的使用者並非鐵板一塊。有像A組這樣快速移動的，也有像D組那樣長期待著不動的。這個分析最重要的發現，是我們看到了群體之間的「社交真空地帶」——也就是那些既不完全封閉、也不完全開放的潛在社交機會，這也成為我們後續設計的切入點。
-->

---

## 人物誌 (Persona)：楊子萱

基於觀察數據，我們建立了核心人物誌：一位渴望社交但受限於環境的害羞高中生。

<div class="grid grid-cols-[1fr_2fr] gap-8 text-left items-center">
  <div class="flex flex-col items-center">
    <!-- <img src="/data/user_persona.png" class="w-48 h-48 rounded-full object-cover border-4 border-white/20 shadow-lg"> -->
    <p class="text-white/50 italic text-sm">（此處應放置人物誌照片）</p>
    <h3 class="font-bold text-2xl mt-4">楊子萱</h3>
    <p class="text-white/80">16歲，高一學生</p>
    <p class="text-white/70 mt-1">害羞、慢熟、觀察型</p>
  </div>
  <div>
    <div class="mb-4">
      <h4 class="font-bold text-lg flex items-center gap-2 text-red-400">❌ 痛點 (Pain Points)</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>學校社交圈已固化，難以融入。</li>
        <li>大型或吵鬧的活動讓她倍感壓力。</li>
        <li>害怕一個人參加活動會很奇怪。</li>
        <li>不知道如何自然地開啟對話。</li>
      </ul>
    </div>
    <div>
      <h4 class="font-bold text-lg flex items-center gap-2 text-green-400">🎯 需求 (Needs)</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>一個能「自然融入」的契機。</li>
        <li>低壓力、不需要強勢社交的活動。</li>
        <li>能預先知道活動氛圍，建立安全感。</li>
        <li>找到步調相似、不必假裝外向的朋友。</li>
      </ul>
    </div>
  </div>
</div>

<p class="text-xs text-white/60 mt-4 text-left">資料來源: `data/user_persona.md`</p>

<!--
基於我們的研究，我們建立了我們的核心使用者人物誌——楊子萱。她是一位16歲的高一學生，個性害羞、慢熟，習慣先觀察再行動。她渴望交朋友，但學校的社交圈已經固定，而傳統的社交活動又讓她壓力很大。她的核心需求是找到一個「安全的、低壓力的、能自然融入」的社交機會。子萱是我們後續所有設計思考的中心。
-->

---

## 利害關係人地圖 (Stakeholder Map)

<div class="text-left text-sm">
  <p>我們繪製了一個以楊子萱為核心的網狀地圖，分析影響她行為的各種力量。</p>
</div>

<div class="mt-4 scale-90 origin-top">
    ```mermaid
    graph TD
    %% 核心角色
    Main((楊子萱<br/>16歲高中生))

    %% 核心圈層：壓力與社交依賴
    Main --- |抱怨對象/同儕| Friends[學校同學]
    Main --- |共同等待/競爭| Classmates[補習班同學]
    Main --- |學業壓力源| CramTeacher[補習班老師]
    Main --- |依賴與安全感| Family[很少溝通的父母]
    Main --- |虛擬社交| Followers[Threads/IG上的網友]

    %% 中間圈層：場域互動與心理干擾
    Main -.-> |感到被盯著看/不自在| Elders[涼亭玩牌的長者]
    Main -.-> |羨慕/覺得吵鬧| Children[遊樂區的小孩]
    Main -.-> |想避開眼神接觸| Passersby[路過的慢跑者]
    Main -.-> |數位逃避| Shorts[短影音Reels/TikTok]
    Main -.-> |獲取資訊| BusApp[公車動態App]
    Main -.-> |視覺重疊/焦慮來源| Crowds[公車站等車的陌生人群]

    %% 外圍圈層：環境與間接影響
    Friends --- |師生關係| SchoolTeacher[學校老師]
    Elders --- |抱怨菸灰與垃圾| Cleaner[公園清潔員]
    Cleaner --- |回報環境狀況| Manager[公園管理處人員]
    Manager --- |主管機關| TCG_Gov[台南市政府工務局]
    TCG_Gov --- TCG[台南市政府]

    BusApp --- |數據來源| BusSystem[公車交通系統]
    BusSystem --- |延遲造成焦慮| Main

    Shorts --- |演算法決定內容| TechCorp[社群媒體演算法]
    TechCorp --- |影響專注力與審美| Main

    %% 空間與社會互動
    Elders --- |主動搭話造成壓力| Main
    LocalShop[公園旁便利商店] --- |買晚餐/飲料| Main
    LocalShop --- |空間提供| Clerk[店員]
    Resident[公園附近居民] -.-> |抱怨噪音/治安| Police[警察]
    Police -.-> |例行巡邏觀看| Main

    %% 關係備註
    style Main fill:#ff9999,stroke:#333,stroke-width:4px
    ```
</div>

<div class="text-left text-xs mt-2">
  <ul class="list-disc list-inside space-y-1 text-white/80">
    <li>**數位島嶼**：**演算法（TechCorp）** 與 **短影音（Shorts）** 是她躲避現實社交的盾牌，但也是造成她分心與焦慮的間接推手。</li>
    <li>**跨世代衝突**：**玩牌長者（Elders）** 與子萱之間的關係是「空間重疊但心理排斥」。長輩的「主動詢問（如：今天沒上課？）」對她而言是微侵略。</li>
  </ul>
</div>

<p class="text-xs text-white/60 mt-4 text-left">資料來源: `data/stakeholder_map.md`</p>

<!--
利害關係人地圖顯示，子萱的問題不僅僅是沒有朋友，而是被多重壓力包圍。補習班、學校給予學業壓力；長輩的關心對她來說是社交壓力；而手機裡的短影音則是她逃避這些壓力的避風港。我們的設計必須在這個複雜的網絡中，為她創造一個喘息與連結的空間。
-->

---

## 核心問題定義：Jobs-To-Be-Done (JTBD)

我們使用 JTBD 框架，將子萱模糊的「想交朋友」需求，轉化為 10 個具體的「待辦任務」。

**資料來源: `data/jobs_to_be_done.md`**

<div class="overflow-x-auto mt-4">
<table class="text-xs text-left w-full border-collapse">
  <thead>
    <tr class="border-b border-white/20 text-teal-300">
      <th class="p-2 w-1/4">情境 (When)</th>
      <th class="p-2 w-1/3">需求 (I want to)</th>
      <th class="p-2 w-1/3">目標 (So I can)</th>
    </tr>
  </thead>
  <tbody class="text-white/80">
    <tr class="border-b border-white/10">
      <td class="p-2">在瀏覽校外活動時</td>
      <td class="p-2">能看到不需要強勢社交的活動</td>
      <td class="p-2">安心踏出第一步，不會一開始就尷尬。</td>
    </tr>
    <tr class="border-b border-white/10">
      <td class="p-2">覺得學校社交機會固定</td>
      <td class="p-2">找到能重新開始的人際空間</td>
      <td class="p-2">不再被學校的小圈圈綁住。</td>
    </tr>
    <tr class="border-b border-white/10">
      <td class="p-2">考慮要不要參加一個陌生活動</td>
      <td class="p-2">先看到活動風格、預計人數、參加者年齡</td>
      <td class="p-2">降低焦慮、心理有底，願意前往。</td>
    </tr>
    <tr class="border-b border-white/10">
      <td class="p-2">在挑選活動</td>
      <td class="p-2">有明確的「適合新手／適合安靜的人」標籤</td>
      <td class="p-2">不會去到現場覺得自己格格不入。</td>
    </tr>
    <tr class="border-b border-white/10">
      <td class="p-2">剛到現場</td>
      <td class="p-2">有明確的流程指引或「先從自己做」的緩衝</td>
      <td class="p-2">慢慢適應，不被大場面嚇退。</td>
    </tr>
  </tbody>
</table>
</div>

<!--
為了更精準地定義問題，我們採用了 Jobs-To-Be-Done 框架。我們問自己：子萱到底想「雇用」我們的產品來完成什麼「工作」？如表格所示，這些工作非常具體，例如「預知活動氛圍以建立自信」、「避免格格不入的恐懼」。這個框架幫助我們從使用者的目標出發，而不是從功能出發來思考設計。
-->

---

## 核心問題定義：How Might We (HMW)

基於 JTBD，我們發想了 12 個設計機會點 (HMW)，引導我們進入解決方案的發想。

**資料來源: `data/how_might_we.csv`**

<div class="grid grid-cols-2 gap-4 text-left text-sm mt-4">
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
    <p class="font-bold text-yellow-300">HMW 3 (社交與隱私)</p>
    <p class="text-white/80 mt-1">朋友群訊息爆量時，我們如何設計能讓人短暫停下回訊息、不影響人流、又不造成視線壓力的小節點？</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
    <p class="font-bold text-teal-300">HMW 5 (環境心理)</p>
    <p class="text-white/80 mt-1">附近有人經過、視線不舒服時，如何以座位角度、背靠與微邊界，給她一個隱私？</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
    <p class="font-bold text-red-300">HMW 11 (空間控制感)</p>
    <p class="text-white/80 mt-1">對空間使用沒有可控性時，如何讓她在不與人交談的情況下，能預約公園中隱蔽且有充電的特定座椅或小空間？</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
    <p class="font-bold text-purple-300">HMW 12 (氛圍維持)</p>
    <p class="text-white/80 mt-1">在認真的時候，看要怎麼鼓勵所有進入該區域的人維持低語或靜默，避免不當的打擾？</p>
  </div>
</div>

<!--
有了 JTBD 後，我們進一步轉化為「我們該如何 (How Might We)」的問句。例如 HMW 11，我們思考如何讓使用者在不需與人交談的情況下，就能預約到一個讓她安心的空間。這些問題直接啟發了我們後來在 App 中設計的「預約」與「狀態顯示」功能。
-->

---
layout: section
---

# PART III
## UX 設計解答 (UX DESIGN SOLUTION)

<!--
現在進入第三部分：UX 設計解答。在這個章節，我們會展示最終的 App 設計是如何回應前面定義出的種種問題，並透過一個完整的使用者故事與實際程式碼，帶大家體驗我們的解決方案。
-->

---

## 解決方案概覽：網站架構

我們的解決方案是一個基於 React 的網頁應用程式 (Web App)，專為行動裝置優化。

**資料來源: `data/website/App.tsx`**

```tsx {all|17|24-30|36-46}
// App.tsx: 應用程式主架構
function Nav() {
  const navItems = [
    { path: "/", label: "首頁" },
    { path: "/activities", label: "探索活動" }, // 核心功能：尋找適合的活動
    { path: "/host", label: "發起活動" },       // 核心功能：成為主辦者
    { path: "/my-activities", label: "我的活動" },
    { path: "/friends", label: "我的朋友" },    // 社交資產累積
    { path: "/safety", label: "安全與導航" },   // 安全感設計
    { path: "/profile", label: "個人檔案" },    // 自我展現
  ];
  // ... (Rendering logic)
}

export default function App() {
  return (
    <Router>
      <ThemeProvider defaultTheme="dark">
        <div className="bg-gray-950 text-white">
          <Nav />
          {/* 背景動態 Blob 設計，營造柔和氛圍 */}
          <div className="fixed inset-0 z-0 overflow-hidden pointer-events-none">
             <div className="bg-pink-500 opacity-5 ... animate-blob" />
             <div className="bg-blue-500 opacity-5 ... animate-blob" />
             <div className="bg-green-500 opacity-5 ... animate-blob" />
          </div>
          <Routes>
            <Route path="/" element={<Welcome />} />
            <Route path="/activities" element={<Activities />} />
            {/* ... other routes */}
          </Routes>
        </div>
      </ThemeProvider>
    </Router>
  );
}
```

<!--
這是我們網站的主程式架構。我們使用了 React Router 來管理頁面，並透過 Tailwind CSS 與 UnoCSS 來打造一個深色模式、帶有柔和動態背景 (Blobs) 的視覺風格，目的是為了在第一眼就給使用者一種「放鬆」、「不刺眼」的感覺，降低社交焦慮。
-->

---
layout: two-cols
---

## 使用者故事：子萱的旅程 (1/4)

**場景：孤單與渴望**

故事從子萱在房間滑著社群軟體開始。看著國中好友們都交了新朋友，她感到一陣孤單，也想建立自己的高中社交圈。但是，班上的小圈圈已經形成，硬要加入只會讓她感到說不出的尷尬。

<br>

> 「某天，她在 IG 限時動態上看到國中好友們與新同學打成一片的照片。她愣住了...『如果我也有自己的小圈圈就好了。』她心裡這麼想，卻不知道該如何開始。」

<p class="text-xs text-white/60 mt-2">資料來源: `data/design_scenario.md`</p>

::right::

<div class="p-4 mt-8">
  <!-- <img src="/user_story_1.png" class="rounded-xl shadow-lg border border-white/10"> -->
  <div class="w-full h-64 bg-gray-800/50 rounded-xl flex items-center justify-center border border-white/10">
    <p class="text-white/50 italic">（示意圖：子萱在房間看著手機，神情落寞）</p>
  </div>
</div>

<!--
為了讓大家更有感，我們將透過子萱的故事來展示 App 的功能。故事的開始，是大家都很熟悉的場景：滑著 IG，看著別人的精彩生活，感到自己的孤單。這是我們設計的出發點——回應這份渴望。
-->

---
layout: two-cols
---

## 使用者故事：子萱的旅程 (2/4)

**場景：發現與篩選**

她發現了我們的平台，並被「探索活動」頁面的篩選器吸引。不同於傳統活動網，她可以先選擇自己能接受的**社交強度**。

<br>

> 「首頁不像其他活動網站那樣擠滿吵雜的宣傳圖，而是先詢問她『今天想用什麼步調參加活動』。她可以依照 vibe 進行微調... 社交強度也不是奇怪的硬性分類，而是用很輕鬆的語氣呈現。」

<p class="text-xs text-white/60 mt-2">資料來源: `data/design_scenario.md`</p>

::right::

<div class="p-4 mt-8">
  <!-- <img src="/user_story_filter.png" class="rounded-xl shadow-lg border border-white/10"> -->
  <div class="w-full h-64 bg-gray-800/50 rounded-xl flex items-center justify-center border border-white/10">
    <p class="text-white/50 italic">（示意圖：App 探索頁面，子萱正在調整社交強度拉桿）</p>
  </div>
</div>

<!--
子萱進入了我們的平台。她最喜歡的功能是這個篩選器。她不需要先決定「要做什麼」，而是先決定「要怎麼社交」。這種把主控權交還給使用者的設計，讓她感到安心。
-->

---

## 解決方案：活動篩選邏輯 (Activities Page)

我們在 `Activities.tsx` 中實作了強大的篩選邏輯，確保子萱能精確找到符合她心理預期的活動。

**資料來源: `data/website/pages/Activities.tsx`**

```tsx {all|10-12|14-16|20-22}
// Activities.tsx: 篩選邏輯
const filteredActivities = mockActivities.filter((activity) => {
  // 1. 搜尋關鍵字
  const nameMatch = activity.name.toLowerCase().includes(search.toLowerCase());
  
  // 2. 核心功能：社交強度篩選 (Social Level Filter)
  // 將滑桿數值 (1-5) 對應到活動的社交等級
  const levelMatch = (activity.socialLevel + 1) >= socialLevel[0] && 
                   (activity.socialLevel + 1) <= socialLevel[1];

  // 3. 興趣標籤篩選
  const tagsMatch = selectedTags.length === 0 || 
                  selectedTags.every((tag) => activity.tags.includes(tag));

  // 4. 群體大小與日期篩選
  const groupSizeMatch = /* ... logic ... */;
  const dateMatch = /* ... logic ... */;

  return nameMatch && levelMatch && tagsMatch && groupSizeMatch && dateMatch;
});
```

<div class="mt-4 text-left text-sm backdrop-blur-sm bg-white/5 p-3 rounded-lg">
  <p class="font-bold text-teal-300">對應設計理念：</p>
  <p>透過 `levelMatch` 變數，我們讓使用者能過濾掉那些「太過熱情」或「太過冷漠」的活動，確保每一次的曝光都是精準的。</p>
</div>

<!--
這是「探索活動」頁面背後的程式碼。我們可以看到 `filteredActivities` 函式中，最關鍵的就是 `levelMatch` 這一段。它將使用者設定的社交強度範圍，與資料庫中的活動屬性進行比對。這確保了子萱永遠不會看到那些會讓她壓力山大的大型聯誼活動。
-->

---
layout: two-cols
---

## 使用者故事：子萱的旅程 (3/4)

**場景：參與及安心**

在報名參加前，她需要建立個人檔案。不同於寫自我介紹的焦慮，這裡提供了「個性滑桿」和「標籤」，讓她能輕鬆定義自己。

<br>

> 「興趣標籤更是貼心地拆得很細：手機攝影、植物觀察、輕散步... 每一項都像是替她量身設計。平台呈現出一種柔和的節奏，彷彿在告訴她：『你不用急，我們一步一步來。』」

<p class="text-xs text-white/60 mt-2">資料來源: `data/design_scenario.md`</p>

::right::

<div class="p-4 mt-8">
  <!-- <img src="/user_story_profile.png" class="rounded-xl shadow-lg border border-white/10"> -->
  <div class="w-full h-64 bg-gray-800/50 rounded-xl flex items-center justify-center border border-white/10">
    <p class="text-white/50 italic">（示意圖：個人檔案頁面，個性滑桿介面）</p>
  </div>
</div>

<!--
決定報名後，子萱需要建立檔案。我們知道寫「自我介紹」是很難的，所以我們設計了「個性滑桿」和豐富的「標籤系統」。她只需要動動手指，選幾個標籤，拉一拉滑桿，就能完成一個既真實、又具備個人特色的檔案。
-->

---

## 解決方案：個人檔案設計 (Profile Page)

在 `Profile.tsx` 中，我們設計了「個性風格滑桿」，讓使用者能以非文字的方式展現自我。

**資料來源: `data/website/pages/Profile.tsx`**

```tsx {all|17-21|26-30}
// Profile.tsx: 個性風格滑桿元件
<Card className="bg-white/5 ...">
  <h3 class="font-semibold text-lg">個性風格</h3>
  <div class="space-y-4">
    <div>
      <div class="flex justify-between text-sm text-gray-400 mb-1">
        <span>獨處充電</span>
        <span>和人互動充電</span>
      </div>
      <Slider defaultValue={[initialPersonalitySliders.socialEnergy]} />
    </div>
    <div>
      <div class="flex justify-between text-sm text-gray-400 mb-1">
        <span>比較常聽</span>
        <span>比較常說</span>
      </div>
      <Slider defaultValue={[initialPersonalitySliders.talkativeness]} />
    </div>
    {/* 其他維度: 慢節奏/快節奏, 偏觀察/偏主動, 隨性/規劃 */}
  </div>
</Card>
```

<div class="mt-4 text-left text-sm backdrop-blur-sm bg-white/5 p-3 rounded-lg">
  <p class="font-bold text-teal-300">對應設計理念：</p>
  <p>這五個維度（能量來源、對話頻率、節奏、參與風格、規劃性）直接對應了我們在人物誌中發現的痛點，幫助使用者找到「同頻率」的夥伴。</p>
</div>

<!--
這是個人檔案頁面的程式碼片段。我們使用了 Radix UI 的 Slider 元件，創造了五個維度的個性量表。例如「獨處充電 vs 互動充電」，這直接反映了內向與外向的差異。這讓子萱不需要寫長篇大論，別人也能一眼看出她是一個「喜歡安靜、習慣傾聽」的人。
-->

---
layout: two-cols
---

## 使用者故事：子萱的旅程 (4/4)

**場景：連結與歸屬**

活動當天，子萱依約前往公園。因為平台已經建立了足夠的信任感與預期，她不再那麼害怕。

<br>

> 「抵達指定地點附近，她看到主揪先微笑揮手：『妳是子萱嗎？我們剛在等妳耶。』... 活動開始後，每個人都拿著手機拍天色變化，一邊散步、一邊自然地聊起影集... 夕陽映在樹影上時，她第一次覺得自己不是局外人，而是這群人中的一份子。」

<p class="text-xs text-white/60 mt-2">資料來源: `data/design_scenario.md`</p>

::right::

<div class="p-4 mt-8">
  <!-- <img src="/user_story_meetup.png" class="rounded-xl shadow-lg border border-white/10"> -->
  <div class="w-full h-64 bg-gray-800/50 rounded-xl flex items-center justify-center border border-white/10">
    <p class="text-white/50 italic">（示意圖：子萱在公園與新朋友一起拍照）</p>
  </div>
</div>

<!--
故事的最後，子萱成功參加了活動。因為之前的鋪陳，她知道會遇到什麼樣的人、做什麼樣的事，這消除了她的恐懼。在公園裡，她透過「拍照」這個共同興趣，自然而然地融入了群體，找到了她一直渴望的歸屬感。
-->

---

## 解決方案：安全感與信任機制

為了確保線下見面的安全，我們在 `MyActivities.tsx` 與 `Safety.tsx` 中實作了驗證與安全功能。

<div class="grid grid-cols-2 gap-4 text-left">
<div>

**資料來源: `data/website/pages/MyActivities.tsx`**
```tsx
// 活動審核狀態 (Stepper)
const statusToStep = (status) => {
  switch (status) {
    case "pending": return 1;
    case "reviewing": return 2;
    case "verified": return 3;
  }
};
// ... Stepper UI Component ...
```
<p class="text-xs text-white/70 mt-2">讓發起者清楚知道活動審核進度，建立平台公信力。</p>

</div>
<div>

**資料來源: `data/website/pages/Safety.tsx`**
```tsx
// 緊急應變指南
<Card>
  <h3 class="...">緊急應變指南</h3>
  <p>【快速脫身指南】</p>
  <ul>
    <li>「我突然想到家裡有事，得先走一步。」</li>
    <li>「我突然有點頭暈，想找個地方休息。」</li>
  </ul>
  <Button variant="destructive">舉報問題</Button>
</Card>
```
<p class="text-xs text-white/70 mt-2">提供具體的「脫身話術」，降低使用者對未知狀況的恐懼。</p>

</div>
</div>

<!--
除了媒合，我們更重視安全。左邊的程式碼展示了我們的活動審核機制，確保平台上的活動都是經過過濾的。右邊則是我們獨創的「安全頁面」，裡面甚至包含了「快速脫身指南」，教使用者如果覺得不舒服，可以怎麼禮貌地離開。這些細節，都是為了給予使用者最大的安全感。
-->

---

## 解決方案：我的朋友 (CRM)

在 `Friends.tsx` 中，我們設計了一個輕量化的關係管理系統，讓子萱能延續活動中的連結。

**資料來源: `data/website/pages/Friends.tsx`**

```tsx {all|12-16|25-29}
// Friends.tsx: 朋友列表與筆記功能
const friends = [
  {
    name: "teamtaro",
    metAt: "公園小隊挑戰", // 記錄相遇場合
    notes: "上次的跳拍任務超好笑 😂", // 私人筆記功能
  },
  // ...
];

export default function FriendsPage() {
  return (
    // ...
    <div className="space-y-2">
      <h4 className="font-semibold text-white">關於 {friend.name} 的筆記:</h4>
      <Textarea
        defaultValue={friend.notes}
        placeholder={`關於 ${friend.name} 的一些筆記...`}
        className="bg-transparent border-dashed text-gray-300"
      />
    </div>
    // ...
  );
}
```

<!--
社交不應該止於活動結束。我們的「我的朋友」頁面，不僅僅是好友列表，更像是一個個人的社交筆記本。子萱可以記錄下她對每個朋友的印象，例如「他喜歡拍貓」、「上次一起聊了某部電影」。這能幫助她在下次見面時，更容易打開話題，延續這份得來不易的友誼。
-->

---

## 原型驗證與回饋

我們透過角色扮演 (Role-play) 的方式，驗證了我們的設計假設。以下是來自受測者的真實回饋。

**資料來源: `data/persona_verification.md`**

<div class="grid grid-cols-2 gap-4 mt-4 text-sm text-left">
  <div v-click class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <p class="text-sky-300 font-bold mb-2">Q: 為了讓你願意專程出門，什麼條件最關鍵？</p>
    <p class="italic text-white/80">「① 最重要：活動內容要“有魅力但不尷尬” (例如：手機攝影散步)。<br>② 很重要：時間一定要舒服 (下午 4 點後～晚上)。<br>③ 重要：地點要明確、好找。」</p>
    <p class="text-green-400 mt-2 text-xs">➡️ 驗證了我們以「黃昏」、「攝影/散步」、「明確地標」為主的活動設計。</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <p class="text-amber-300 font-bold mb-2">Q: 你會主動發起活動嗎？</p>
    <p class="italic text-white/80">「一開始我應該不會... 擔心沒有人加入怎麼辦... 但如果平台有『有人加入才成立』的功能，我會願意試試看。」</p>
    <p class="text-green-400 mt-2 text-xs">➡️ 啟發了我們在未來版本加入「最低成團人數」設定的想法。</p>
  </div>
</div>

<!--
最後，我們進行了原型驗證。受測者的回饋非常正面，特別是對於活動時間（黃昏）和內容（低尷尬）的偏好，完全印證了我們的設計方向。同時，她們對於「發起活動」的擔憂，也給了我們很好的優化方向，讓我們知道下一步該做什麼。
-->

---
layout: section
---

# PART IV
## 結論 (CONCLUSION)

<!--
最後，來到我們的結論部分。我們將總結這個專案的價值，以及我們從中學到的事情。
-->

---

## 專案價值

<div class="grid grid-cols-3 gap-8 text-left pt-8">
  <div>
    <div class="i-carbon-user-favorite w-12 h-12 text-green-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對使用者</h3>
    <p class="text-sm text-white/80">提供一個「社交新手村」。在這裡，犯錯是被允許的，沉默是沒關係的。它賦予了使用者在公共空間中「合法」獨處或進行輕社交的權利。</p>
  </div>
  <div>
    <div class="i-carbon-park w-12 h-12 text-teal-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對公園</h3>
    <p class="text-sm text-white/80">讓被忽視的青少年族群重新與公園產生連結。公園不再只是長輩的運動場或小孩的遊樂區，它也可以是年輕人建立歸屬感的第三空間。</p>
  </div>
  <div>
    <div class="i-carbon-connect w-12 h-12 text-sky-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對社會</h3>
    <p class="text-sm text-white/80">提出一個緩解現代人孤獨感的可能解方。它證明了，有時候我們需要的不是更多的連結，而是「更舒適的連結」。</p>
  </div>
</div>

<!--
總結來說，這個專案的價值體現在三個層面。對使用者而言，它是一個可以放心犯錯的「社交新手村」。對公園而言，它重新活化了被忽略的青少年族群。而對整個社會來說，它提供了一個緩解孤獨感的新模式——證明了「更舒適的連結」遠比「更多的連結」來得重要。
-->

---
layout: center
class: text-center
---

# <span class="bg-gradient-to-r from-blue-300 to-emerald-300 bg-clip-text text-transparent font-bold text-5xl italic tracking-tighter">認識朋友，可以是一種舒適的選擇。</span>

<p class="mt-20 text-white/40 font-mono text-xs tracking-[0.4em] uppercase font-light">Thank you</p>

<!--
我們相信，透過好的設計，認識朋友，可以是一種舒適的選擇。這就是我們今天的報告。謝謝大家。
-->

---
layout: default
---

# Q & A

<div class="h-full flex flex-col justify-center items-center opacity-30 italic">
  <p class="text-4xl text-white font-light">討論與反饋</p>
  <div class="mt-8 w-16 h-0.5 bg-white rounded-full"></div>
</div>

<!--
謝謝大家，接下來是問答時間。
-->
