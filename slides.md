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

# <span class="text-white drop-shadow-xl text-6xl font-bold italic tracking-tighter">台南公園輕社交平台</span>
<p class="text-white/80 tracking-widest mt-4 block font-light text-2xl">從行為觀察到「反思型社交」的設計實踐</p>

<div class="pt-12">
  <div class="inline-block backdrop-blur-md bg-white/10 border border-white/20 px-8 py-4 rounded-2xl shadow-2xl">
    <p class="font-mono text-sm">UX 設計個案研究</p>
  </div>
</div>

<!--
大家好，我們是第Ｘ組，今天要報告的主題是「台南公園輕社交平台」。這是一個關於如何透過數位設計，幫助害羞或慢熟的年輕人，在他們感到舒適的步調下，重新與公共空間建立連結的專案。我們的報告將會從最初的田野觀察開始，一路帶大家看到我們如何定義問題、發展人物誌，並最終設計出一個以「反思型社交」為核心的數位平台。
-->

---

<Toc class="text-left mt-8" />

<!--
這是我們今天的報告大綱，主要會分成三個部分：第一部分是「設計問題探索」，我們會說明如何從零開始，透過觀察與研究來界定核心問題。第二部分是「設計解答探索」，這裡會展示我們的設計概念、原型以及如何透過測試來優化它。最後，我們會總結這個專案的價值與我們的反思。
-->

---
layout: section
---

# PART I
## 設計問題探索

<!--
好的，讓我們進入第一部分：設計問題探索。這個章節的核心目標，不是急著找答案，而是專注於「問對問題」。我們會展示如何從一片廣泛的現象中，逐步收斂，最終找到那個最值得我們解決的痛點。
-->

---

# 場域評選：為何是台南公園？

<div class="grid grid-cols-3 gap-4 text-left pt-4">
  <div>
    <h3 class="font-bold text-lg mb-2 flex items-center gap-2"><div class="i-carbon-market w-6 h-6 text-orange-400"></div>大東夜市</h3>
    <p class="text-xs text-white/80">目標在於解決「效率」與「便利性」，但社交行為多限於商業交易，環境壓力高。</p>
  </div>
  <div>
    <h3 class="font-bold text-lg mb-2 flex items-center gap-2"><div class="i-carbon-tree w-6 h-6 text-teal-400"></div><span class="bg-teal-400/20 px-2 py-1 rounded">台南公園 (決選)</span></h3>
    <p class="text-xs text-white/80">一個完全去目的化的開放空間，存在「數位孤島」現象。其低壓力特質，是實驗「心理模型」的最佳場所。</p>
  </div>
  <div>
    <h3 class="font-bold text-lg mb-2 flex items-center gap-2"><div class="i-carbon-building w-6 h-6 text-sky-400"></div>銀同社區</h3>
    <p class="text-xs text-white/80">目標在於「紀錄」與「傳承」，但互動多為單向聆聽，缺乏雙向社交潛力。</p>
  </div>
</div>

<div class="text-left mt-8 backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
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
      <td class="p-2 font-bold">解決「行為與心理斷層」</td>
    </tr>
    <tr class="border-t border-white/10">
      <td class="p-2 font-bold">研究價值</td>
      <td class="p-2">偏向功能性優化</td>
      <td class="p-2">偏向社會設計</td>
      <td class="p-2 font-bold">偏向 UX 行為深度分析</td>
    </tr>
  </tbody>
</table>
</div>

<!--
在專案初期，我們評估了三個潛在場域。我們發現台南公園的研究價值最高，因為它的問題核心是關於「人的行為與心理斷層」。我們觀察到一個非常有趣的現象，我們稱之為「數位孤島」——人們身處在一個開放的公共空間，卻選擇退回到手機的個人世界裡。這個矛盾的現象，讓我們決定把台南公園當作我們深入研究的對象。
-->

---
layout: two-cols
---

# 田野觀察 (原始數據)

我們在台南公園進行了長時間的質化觀察，紀錄了 12 組不同使用者的行為故事。這些看似零碎的片段，是我們後續所有分析的根基。

<br>
<br>

**資料來源: `data/field_study.csv`**

::right::

<div class="space-y-4 text-sm">
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-yellow-300">(U7) 剛放學的南二中同學</p>
    <p class="text-white/80">「和他的朋友們一邊過馬路一邊看手機... 的同學時不時會模仿手機上短片內容，引三人大笑... 到公車站後自成一小群一起等公車。」</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-teal-300">(U8) 穿便服的大學生</p>
    <p class="text-white/80">「自己一個人在人行道上行走，似乎很專注在自己的手機上... 的手機畫面似乎是遊戲... 開始在聊天軟體與遊戲畫面之間來回切換。」</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 text-left">
    <p class="font-bold text-red-300">(U9) 在對向等公車的人</p>
    <p class="text-white/80">「旁觀的人很多，似乎感到一些焦慮，每隔幾分鐘會一邊張望一邊東西望... 臉上明顯透露出不耐煩，並且手機上開啟大台南公車app。」</p>
  </div>
</div>

<!--
這是我們在現場觀察到的幾個真實案例。我們看到，學生群體即使聚在一起，注意力仍在手機上；也有獨自一人的大學生，在遊戲和聊天軟體之間頻繁切換。更有趣的是，一位等車的民眾，因為人多而感到焦慮，並頻繁查看公車App。這些都顯示了人們在公共空間中，對數位設備的高度依賴與複雜的心理狀態。
-->

---

# 行為分析 (1/3)：數據準備

為了從質化觀察中找出規律，我們首先將 12 組使用者的行為，量化到 9 個不同的心理與行為維度上。

<br>

**資料來源: `data/user_behavior_dimension_analysis.ipynb`**

````md magic-move
```python {all|1-12|14-22}
# Data as defined previously
data = {
    'Scale': [
        'Negative vs Positive Emotion', 'No Tech vs Using Tech', 'Alone vs Group',
        'Stationary vs Fast Moving', 'Distracted vs Focused', 'Uncomfortable vs Comfortable',
        'Short vs Long Stay', 'Aimless vs Purposeful', 'No vs Yes Facility Interaction'
    ],
    '1': [5.0, 4.1, 2.5, 9.1, 4.8, 5.4, 2.0, 0.7, 7.7],
    '2': [8.8, 8.9, 9.5, 4.1, 3.7, 9.2, 2.5, 3.5, 3.1],
    # ... (data for 3-11 omitted for brevity)
    '12': [6.7, 2.3, 0.0, 10.0, 9.9, 6.8, 4.3, 10.0, 7.0]
}

# Transpose the data so rows are Points (1-12) and columns are Scales
import pandas as pd
df_orig = pd.DataFrame(data)
df_transposed = df_orig.set_index('Scale').transpose()

# Standardize the data
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
X_scaled = scaler.fit_transform(df_transposed)
```
````
<!--
我們分析的第一步，是將觀察紀錄數據化。我們定義了九個維度，例如情緒、科技使用、獨處或群體等等，並為 12 組使用者打分數。為了讓每個維度的權重相同，我們接著使用 StandardScaler 對數據進行標準化，消除單位的影響。這一步是後續聚類分析的基礎。
-->

---

# 行為分析 (2/3)：聚類演算法

接著，我們使用 `DBSCAN` 演算法來對標準化後的數據進行分群。DBSCAN 的優點是不需要預設分群數量，能自動找出相似的數據點，並將離群值標記出來。

<br>

**資料來源: `data/user_behavior_dimension_analysis.ipynb`**

````md magic-move
```python {all|2|6|7}
from sklearn.cluster import DBSCAN

# We need to determine the `eps` (epsilon) value,
# which defines the neighborhood radius for a point.
# After several tests, we found eps=3.0 to be optimal.
dbscan = DBSCAN(eps=3.0, min_samples=2)
dbscan_labels = dbscan.fit_predict(X_scaled)

# Example Output: [ 0  1  2  3  3  0  1  0 -1 -1  2  0]
# where -1 represents an outlier.
```
````

<div v-click class="mt-4 text-sm text-left backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
  <p>我們對 `eps` 參數進行了多次實驗 (`eps` 決定了鄰近點的搜索半徑)。</p>
  <p class="text-white/80">`eps=2.5` 時，群體過於分散；`eps=3.5` 時，則過於集中。最終 `eps=3.0` 產出了最有意義的四個群體與兩個離群值。</p>
</div>

<!--
數據準備好後，我們選擇了 DBSCAN 演算法來分群。選擇它的原因，是因為它不需要我們先猜測要分成幾群。演算法會自動根據數據的密集程度來找出群體。經過反覆測試 `eps` 這個關鍵參數後，我們在 `eps=3.0` 時，得到了最穩定且最具有解釋力的分群結果。
-->

---

# 行為分析 (3/3)：聚類結果

演算法最終將 12 組使用者分為 4 個核心群體與 2 個離群值。這讓我們清晰地看到公園中不同使用者的「存在狀態」。

<div class="grid grid-cols-2 gap-4 text-left text-sm mt-4">
  <div class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 space-y-2">
    <h3 class="font-bold text-red-300">A組: 高頻流動者 (U1, U6, U8, U12)</h3>
    <p class="text-white/80 text-xs">通常處於移動狀態，社交窗口極短，互動必須是非侵入式的。</p>
    <h3 class="font-bold text-blue-300">B組: 封閉社交者 (U2, U7)</h3>
    <p class="text-white/80 text-xs">身體在場，心理在別處 (手機或夥伴)，對外部干擾防禦心強。</p>
  </div>
  <div class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10 space-y-2">
    <h3 class="font-bold text-yellow-300">C組: 靜態停留者 (U3, U11)</h3>
    <p class="text-white/80 text-xs">有穩定停留基礎，是發展「微任務」或「共同興趣」社交的潛力股。</p>
    <h3 class="font-bold text-purple-300">D組: 場域佔有者 (U4, U5)</h3>
    <p class="text-white/80 text-xs">舒適度極高，社交圈已固化，對數位平台介入需求最低。</p>
  </div>
</div>

<p v-click class="text-sm font-bold text-white/90 mt-6">核心洞察：不同群體間存在著「社交真空地帶」，這是我們設計介入的機會點。</p>

<!--
這是我們的最終分群結果。我們可以看到，公園裡的使用者並非鐵板一塊。有像A組這樣快速移動的，也有像D組那樣長期待著不動的。這個分析最重要的發現，是我們看到了群體之間的「社交真空地帶」——也就是那些既不完全封閉、也不完全開放的潛在社交機會，這也成為我們後續設計的切入點。
-->

---

# 人物誌：楊子萱

<div class="grid grid-cols-[1fr_2fr] gap-8 text-left items-center">
  <div class="flex flex-col items-center">
    <!-- <img src="/data/user_persona.png" class="w-48 h-48 rounded-full object-cover border-4 border-white/20 shadow-lg"> -->
    <p class="text-white/50 italic text-sm">（此處應放置人物誌照片）</p>
    <h3 class="font-bold text-2xl mt-4">楊子萱</h3>
    <p class="text-white/80">16歲，高一</p>
    <p class="text-white/70 mt-1">害羞、慢熟、觀察型</p>
  </div>
  <div>
    <div class="mb-4">
      <h4 class="font-bold text-lg flex items-center gap-2"><div class="i-carbon-pain w-6 h-6 text-red-400"></div>痛點</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>學校社交圈已固化，難以融入</li>
        <li>大型或吵鬧的活動讓她倍感壓力</li>
        <li>害怕一個人參加活動會很奇怪</li>
        <li>不知道如何自然地開啟對話</li>
      </ul>
    </div>
    <div>
      <h4 class="font-bold text-lg flex items-center gap-2"><div class="i-carbon-intent-request-create w-6 h-6 text-green-400"></div>需求</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>一個能「自然融入」的契機</li>
        <li>低壓力、不需要強勢社交的活動</li>
        <li>能預先知道活動氛圍，建立安全感</li>
        <li>找到步調相似、不必假裝外向的朋友</li>
      </ul>
    </div>
  </div>
</div>

<!--
基於我們的研究，我們建立了我們的核心使用者人物誌——楊子萱。她是一位16歲的高一學生，個性害羞、慢熟，習慣先觀察再行動。她渴望交朋友，但學校的社交圈已經固定，而傳統的社交活動又讓她壓力很大。她的核心需求是找到一個「安全的、低壓力的、能自然融入」的社交機會。子萱是我們後續所有設計思考的中心。
-->

---

# 問題定義：JTBD (原始數據)

我們使用 Jobs-To-Be-Done 框架，將子萱模糊的「想交朋友」需求，轉化為具體的「待辦任務」。

**資料來源: `data/jobs_to_be_done.md`**

<div class="text-left mt-4 text-xs">
| 情境 (When) | 需求 (I want to) | 目標 (So I can) |
|---|---|---|
| 在瀏覽校外活動時 | 能看到不需要強勢社交的活動 | 安心踏出第一步，不會一開始就尷尬或被迫聊天。 |
| 覺得學校社交機會固定、難以突破 | 找到能重新開始的人際空間 | 不再被學校的小圈圈綁住，有新機會建立友誼。 |
| 考慮要不要參加一個陌生活動 | 先看到活動風格、預計人數、參加者年齡 | 降低焦慮、心理有底，願意前往。 |
| 在挑選活動 | 有明確的「適合新手／適合安靜的人」標籤 | 不會去到現場覺得自己格格不入。 |
| 剛到現場 | 有明確的流程指引或「先從自己做」的緩衝 | 慢慢適應，不被大場面嚇退。 |
</div>

<!--
為了更精準地定義問題，我們採用了 Jobs-To-Be-Done 框架。我們問自己：子萱到底想「雇用」我們的產品來完成什麼「工作」？如表格所示，這些工作非常具體，例如「預知活動氛圍以建立自信」、「避免格格不入的恐懼」。這個框架幫助我們從使用者的目標出發，而不是從功能出發來思考設計。
-->

---
layout: section
---

# PART II
## 設計解答探索

<!--
現在進入第二部分：設計解答探索。在這個章節，我們會展示如何回應前面定義出的問題，從概念發想、原型製作，到最終的測試與迭代。
-->

---

# 使用者故事：子萱的一天

我們將所有研究與設計概念，串連成一個完整的使用者故事，來模擬子萱如何透過我們的平台，完成一次成功的社交體驗。

<br>
<div class="text-left p-4 rounded-lg bg-white/5 backdrop-blur-sm border border-white/10">
<p class="font-bold text-teal-300">開場：孤單與渴望</p>
<p class="text-sm text-white/80">「新學期過了兩個月，班上的小圈圈都已經穩固。體育課大家都三三兩兩聊天打鬧，而子萱常站在隊伍邊緣，想加入但又不知道從哪裡插話... 某天放學，她滑 IG 看到國中好友們正在他們的高中班上大笑合照，突然覺得胸口悶了一下：『如果我也有自己的小圈圈就好了。』」</p>
<p class="text-xs text-white/60 mt-2">Source: `data/design_scenario.md`</p>
</div>

<!--
我們的設計情境，完整地描繪了子萱的心路歷程。故事從她在房間感到孤單開始，她渴望社交，卻又害怕被拒絕。她嘗試過從學校社團開始，但資訊的不透明讓她充滿焦慮，最終還是放棄了。
-->

---

# 核心設計：心理舒適度優先

<div class="grid grid-cols-2 gap-8 items-center">
  <div class="text-left">
    <h3 class="font-bold text-2xl mb-4">社交強度過濾器</h3>
    <p class="text-white/80 mb-4">這是我們設計的核心。使用者不是先選「活動內容」，而是先選「想要的社交方式」。平台用輕鬆的語氣呈現選項：</p>
    <ul class="space-y-2 text-sm">
      <li v-click>「<span class="text-teal-300">只需要點頭微笑的程度</span>」</li>
      <li v-click>「<span class="text-teal-300">會聊幾句但不會強迫互動</span>」</li>
      <li v-click>「<span class="text-teal-300">適合慢熟的人</span>」</li>
    </ul>
    <p class="text-white/80 mt-4">這給予了慢熟使用者「選擇的權利」，讓他們能待在自己的舒適圈內進行社交。</p>
  </div>
  <div>
    <!-- <img src="/data/website/activities_filter.png" class="rounded-2xl shadow-xl" alt="Activity Filter UI"> -->
    <p class="text-white/50 italic">（示意圖：App 篩選器介面）</p>
  </div>
</div>

<!--
我們設計的核心，就是這個「社交強度過濾器」。傳統的活動平台，你只能選「爬山」或「看電影」。但在我們的平台上，你可以先決定你今天想要的「社交方式」。這個設計翻轉了傳統的邏輯，把「心理舒適度」放在第一位，真正賦予了像子萱這樣的慢熟使用者「選擇的權利」。
-->

---

# 原型驗證 (原始數據)

我們透過角色扮演的方式，讓受訪者化身為「楊子萱」來對我們的設計進行驗證。

**資料來源: `data/persona_verification.md`**

<div class="grid grid-cols-2 gap-4 mt-4 text-sm text-left">
  <div v-click class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <p class="text-sky-300 font-bold mb-2">Q: 你會主動發起活動嗎？</p>
    <p class="italic">「一開始我應該不會... 因為會擔心沒有人加入怎麼辦... 但如果我已經參加幾次，覺得氣氛很舒服，我可能會嘗試發起那種很簡單的活動... 但一定要是『有人一起才開始』的功能，我不想一個人站在那裡等人來。」</p>
    <p class="text-green-400 mt-2">➡️ <span class="font-bold">優化方向：</span> 在 2.0 版本加入「最低成團人數」的設定。</p>
  </div>
  <div v-click class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
    <p class="text-amber-300 font-bold mb-2">Q: 什麼樣的活動對你來說壓力很大？</p>
    <p class="italic">「長篇自我介紹... 競爭激烈... 需要上台表演... 人數過多... 還有那種大家都已經很熟了的小圈子氛圍。簡單來說，如果一個活動讓我覺得『要表現得很好』或『會被注意、被比較』，我就會覺得壓力太大。」</p>
    <p class="text-green-400 mt-2">➡️ <span class="font-bold">驗證：</span> 我們的「低壓力」、「小群體」、「有共同任務」的設計方向是正確的。</p>
  </div>
</div>

<!--
設計完成後，我們進行了原型驗證。我們邀請受訪者扮演楊子萱，來測試我們的想法。結果非常成功。例如，當問到是否會主動發起活動，她們表示一開始會害怕，但如果平台有「最低成團人數」的功能，她們就願意嘗試。這給了我們明確的優化方向。同時，她們對高壓力活動的描述，也反過來驗證了我們主打「低壓力、小群體」的設計是正確的。
-->

---
layout: section
---

# PART III
## 專案價值與結論

<!--
最後，來到我們的結論部分。我們將總結這個專案的價值，以及我們從中學到的事情。
-->

---

# 專案價值

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
