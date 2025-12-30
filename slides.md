---
# Try to use 'default' theme for better experience
# See: https://sli.dev/themes/gallery.html
theme: default
# The background image is a URL.
background: 'https://images.unsplash.com/photo-1525383547365-11f33578ba4c?q=80&w=2070&auto=format&fit=crop'
# Class applies to all slides.
class: 'text-center'
# Or use UnoCSS to style it.
css: unocss
# Slide-level transition.
transition: slide-left
# Title in the HTML, for SEO.
title: 'Tainan Park Activity Platform: A UX Case Study'
# Information for the info-dialog.
info: This is a UX case study about a platform that can help shy teenagers socialize in Tainan Park.
# Enable table of contents.
toc: true
# Enable speaker notes.
speaker: true
---

# <span class="text-white drop-shadow-xl text-6xl font-bold italic tracking-tighter">台南公園輕社交平台</span>
# <span class="text-white drop-shadow-xl text-6xl font-bold italic tracking-tighter">Tainan Park Activity Platform</span>
<p class="text-white/80 tracking-widest mt-4 block font-light text-2xl">從行為觀察到「反思型社交」的設計實踐</p>
<p class="text-white/80 tracking-widest mt-2 block font-light text-2xl">From Behavioral Observation to "Reflective Socialization" Design Practice</p>

<div class="pt-12">
  <div class="inline-block backdrop-blur-md bg-white/10 border border-white/20 px-8 py-4 rounded-2xl shadow-2xl">
    <p class="font-mono text-sm">UX COMPLETE CASE STUDY</p>
  </div>
</div>

<!--
大家好，我們是第Ｘ組，今天要報告的主題是「台南公園輕社交平台」。這是一個關於如何透過數位設計，幫助害羞或慢熟的年輕人，在他們感到舒適的步調下，重新與公共空間建立連結的專案。我們的報告將會從最初的田野觀察開始，一路帶大家看到我們如何定義問題、發展人物誌，並最終設計出一個以「反思型社交」為核心的數位平台。
-->

---
layout: toc
---

<!--
這是我們今天的報告大綱，主要會分成三個部分：第一部分是「設計問題探索」，我們會說明如何從零開始，透過觀察與研究來界定核心問題。第二部分是「設計解答探索」，這裡會展示我們的設計概念、原型以及如何透過測試來優化它。最後，我們會總結這個專案的價值與我們的反思。
-->

---
layout: section
---

# PART I
## 設計問題探索
## Design Discovery

<!--
好的，讓我們進入第一部分：設計問題探索。這個章節的核心目標，不是急著找答案，而是專注於「問對問題」。我們會展示如何從一片廣泛的現象中，逐步收斂，最終找到那個最值得我們解決的痛點。
-->

---

# 場域評選
# Site Selection

<div class="grid grid-cols-3 gap-8 text-left">
  <div>
    <h3 class="font-bold text-xl mb-2 flex items-center gap-2"><div class="i-carbon-market w-6 h-6 text-orange-400"></div>大東夜市</h3>
    <p class="text-sm text-white/80">目標在於解決「效率」與「便利性」問題，例如排隊、點餐。但社交行為多限於商業交易，且環境壓力高。</p>
    <p class="text-sm text-white/80 mt-2">Focus on efficiency and convenience (queuing, ordering). Social interaction is limited to transactions in a high-pressure environment.</p>
  </div>
  <div>
    <h3 class="font-bold text-xl mb-2 flex items-center gap-2"><div class="i-carbon-tree w-6 h-6 text-teal-400"></div><span class="bg-teal-400/20 px-2 py-1 rounded">台南公園 (決選)</span></h3>
    <p class="text-sm text-white/80">一個完全去目的化的開放空間，存在嚴重的「數位孤島」現象。這裡的低壓力特質，是我們實驗「心理模型」的最佳場所。</p>
    <p class="text-sm text-white/80 mt-2">A non-purposed, open space exhibiting a "digital island" phenomenon. Its low-pressure nature makes it ideal for experimenting with psychological models.</p>
  </div>
  <div>
    <h3 class="font-bold text-xl mb-2 flex items-center gap-2"><div class="i-carbon-building w-6 h-6 text-sky-400"></div>銀同社區</h3>
    <p class="text-sm text-white/80">目標在於「紀錄」與「傳承」，將老街的記憶數位化。但互動多為單向聆聽，較缺乏雙向社交的潛力。</p>
    <p class="text-sm text-white/80 mt-2">Focus on documentation and preservation by digitizing historical narratives. Interaction is mostly one-way, lacking potential for reciprocal socializing.</p>
  </div>
</div>

<p class="mt-8 text-center text-lg font-bold">我們選擇台南公園，因為它提供了一個巨大的設計空白：<br>如何重新連結「身在公園，心在手機」的人們。</p>
<p class="mt-2 text-center text-lg font-bold text-white/80">We chose Tainan Park to address a design gap: reconnecting people who are physically present but mentally elsewhere.</p>

<!--
在專案初期，我們評估了三個潛在場域。夜市的核心是「效率」，社區的核心是「傳承」，但只有台南公園，它的核心問題是關於「人的行為與心理斷層」。我們觀察到一個非常有趣的現象，我們稱之為「數位孤島」——人們身處在一個開放的公共空間，卻選擇退回到手機的個人世界裡。這個矛盾的現象，讓我們決定把台南公園當作我們深入研究的對象。
-->

---

# 田野觀察與行為聚類
# Field Study & Behavioral Clustering

<div class="grid grid-cols-2 gap-4 text-left">
  <div>
    <h3 class="font-bold text-lg mb-2">U1-U12 使用者觀察 (User Observation)</h3>
    <p class="text-sm text-white/70">我們紀錄了 12 組在公園內的典型使用者，從獨自騎車的小孩、熱鬧成群的學生，到安靜玩牌的長者。這些第一手資料是我們後續分析的基礎。</p>
    <p class="text-sm text-white/70 mt-2">We documented 12 typical user groups in the park, from a child biking alone and lively students to quiet elderly card players. This firsthand data formed the basis of our analysis.</p>
    <!-- <img src="/data/recreated_plot.png" class="mt-4 rounded-lg shadow-lg" alt="Behavioral Analysis Plot"> -->
  </div>
  <div>
    <h3 class="font-bold text-lg mb-2">DBSCAN 聚類分析 (Clustering Analysis)</h3>
    <p class="text-sm text-white/70">透過演算法，我們將觀察數據歸納出四個核心群體：</p>
    <ul class="text-sm space-y-2 mt-4 text-white/90">
      <li><span class="bg-red-500/20 text-red-300 px-2 py-0.5 rounded">A組</span>: 高頻流動者 (Movers)</li>
      <li><span class="bg-blue-500/20 text-blue-300 px-2 py-0.5 rounded">B組</span>: 封閉社交者 (Closed Groups)</li>
      <li><span class="bg-yellow-500/20 text-yellow-300 px-2 py-0.5 rounded">C組</span>: 靜態停留者 (Observers)</li>
      <li><span class="bg-purple-500/20 text-purple-300 px-2 py-0.5 rounded">D組</span>: 場域佔有者 (Territorial)</li>
    </ul>
    <p class="text-sm text-white/70 mt-4">這個分析幫助我們發現了不同群體間的「社交真空地帶」，也就是那些既不完全封閉、也不完全開放的潛在社交機會。</p>
    <p class="text-sm text-white/70 mt-2">This analysis helped us identify a "social vacuum"—the untapped social potential between different user groups.</p>
  </div>
</div>

<!--
接著，我們在公園進行了深度的田野觀察，並將質化資料量化成九個維度。透過DBSCAN演算法，我們識別出了四種高度相似的行為群體。例如A組是慢跑者、騎車小孩這類「高頻流動者」，他們的社交機會非常短暫。B組則是情侶或好友，他們是「封閉社交者」，很難被外界打擾。這個分析最重要的發現，是我們看到了群體之間的「社交真空地帶」，這也成為我們後續設計的切入點。
-->

---

# 人物誌：楊子萱
# Persona: Yang Zixuan

<div class="grid grid-cols-[1fr_2fr] gap-8 text-left items-center">
  <div class="flex flex-col items-center">
    <!-- <img src="/data/user_persona.png" class="w-48 h-48 rounded-full object-cover border-4 border-white/20 shadow-lg"> -->
    <h3 class="font-bold text-2xl mt-4">楊子萱</h3>
    <p class="text-white/80">16歲，高一 (16, High School Student)</p>
    <p class="text-white/70 mt-1">害羞、慢熟、觀察型 (Shy, Slow to warm up, Observer)</p>
  </div>
  <div>
    <div class="mb-4">
      <h4 class="font-bold text-lg flex items-center gap-2"><div class="i-carbon-pain w-6 h-6 text-red-400"></div>痛點 (Pain Points)</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>學校社交圈已固化，難以融入 (School social circles are fixed and hard to join.)</li>
        <li>大型或吵鬧的活動讓她倍感壓力 (Large or noisy events are stressful.)</li>
        <li>害怕一個人參加活動會很奇怪 (Fears attending events alone will be awkward.)</li>
        <li>不知道如何自然地開啟對話 (Doesn't know how to start conversations naturally.)</li>
      </ul>
    </div>
    <div>
      <h4 class="font-bold text-lg flex items-center gap-2"><div class="i-carbon-intent-request-create w-6 h-6 text-green-400"></div>需求 (Needs)</h4>
      <ul class="list-disc list-inside text-sm text-white/80 pl-2 space-y-1 mt-1">
        <li>一個能「自然融入」的契機 (An opportunity to "fit in naturally.")</li>
        <li>低壓力、不需要強勢社交的活動 (Low-pressure events that don't require assertive socializing.)</li>
        <li>能預先知道活動氛圍，建立安全感 (Ability to know the event's vibe beforehand to feel secure.)</li>
        <li>找到步調相似、不必假裝外向的朋友 (To find like-minded friends without having to pretend to be extroverted.)</li>
      </ul>
    </div>
  </div>
</div>

<!--
基於我們的研究，我們建立了我們的核心使用者人物誌——楊子萱。她是一位16歲的高一學生，個性害羞、慢熟，習慣先觀察再行動。她渴望交朋友，但學校的社交圈已經固定，而傳統的社交活動又讓她壓力很大。她的核心需求是找到一個「安全的、低壓力的、能自然融入」的社交機會。子萱是我們後續所有設計思考的中心。
-->

---

# 核心問題定義
# Problem Definition

<div class="grid grid-cols-2 gap-8 text-left">
  <div>
    <h3 class="font-bold text-xl mb-4">Jobs-To-Be-Done (JTBD)</h3>
    <p class="text-sm text-white/80 mb-2">子萱想「雇用」一個產品來幫她完成什麼任務？</p>
    <p class="text-sm text-white/80 mb-2">What job would Zixuan "hire" a product to do for her?</p>
    <ul class="space-y-3 text-sm">
      <li class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
        <p class="font-bold">尋求低壓力參與</p><p>Seeking Low-Pressure Participation</p>
        <p class="text-white/70">讓她可以安心踏出第一步，不必被迫聊天。</p>
      </li>
      <li class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
        <p class="font-bold">預知活動氛圍</p><p>Previewing Event Atmosphere</p>
        <p class="text-white/70">讓她能降低焦慮，心理有底才願意前往。</p>
      </li>
    </ul>
  </div>
  <div>
    <h3 class="font-bold text-xl mb-4">How Might We...?</h3>
    <p class="text-sm text-white/80 mb-2">我們該如何將挑戰轉化為設計機會？</p>
    <p class="text-sm text-white/80 mb-2">How can we turn challenges into design opportunities?</p>
    <ul class="space-y-3 text-sm">
      <li class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
        <p class="font-bold">HMW... 提供一個讓她感到有隱私的角落？</p>
        <p>HMW... provide a corner that makes her feel private?</p>
      </li>
      <li class="backdrop-blur-sm bg-white/5 p-3 rounded-lg border border-white/10">
        <p class="font-bold">HMW... 讓她在不與人交談下，預約公園的特定空間？</p>
        <p>HMW... allow her to reserve a specific space in the park without interacting with anyone?</p>
      </li>
    </ul>
  </div>
</div>

<!--
為了讓問題更聚焦，我們用了兩個框架。首先是 Jobs-To-Be-Done，我們問自己：子萱想要「雇用」一個產品來完成什麼工作？答案是「尋求低壓力參與」和「預知活動氛圍」。接著，我們用 How Might We 的句型來發想機會點，例如：「我們該如何，為她提供一個有隱私感的角落？」這些思考幫助我們將模糊的需求轉化為具體的設計方向。
-->

---
layout: section
---

# PART II
## 設計解答探索
## Solution Exploration

<!--
現在進入第二部分：設計解答探索。在這個章節，我們會展示如何回應前面定義出的問題，從概念發想、原型製作，到最終的測試與迭代。
-->

---

# 設計情境：子萱的一天
# Design Scenario: A Day with Zixuan

<div class="grid grid-cols-4 gap-4 items-start h-full text-sm">
  <div class="flex flex-col items-center">
    <div class="i-carbon-face-dissatisfied w-20 h-20 text-red-300"></div>
    <h4 class="font-bold mt-2">1. 感到孤單</h4>
    <h4 class="font-bold">Feeling Lonely</h4>
    <p class="text-white/70 mt-1">在學校感覺格格不入，渴望新的社交圈。</p>
    <p class="text-white/70 mt-1 text-xs">Feels out of place at school, longs for a new social circle.</p>
  </div>
  <div class="flex flex-col items-center">
    <div class="i-carbon-search w-20 h-20 text-sky-300"></div>
    <h4 class="font-bold mt-2">2. 發現平台</h4>
    <h4 class="font-bold">Discovers the Platform</h4>
    <p class="text-white/70 mt-1">看到平台能用「社交強度」篩選活動，感到好奇。</p>
    <p class="text-white/70 mt-1 text-xs">Sees that the platform can filter activities by "social intensity" and is intrigued.</p>
  </div>
  <div class="flex flex-col items-center">
    <div class="i-carbon-camera w-20 h-20 text-yellow-300"></div>
    <h4 class="font-bold mt-2">3. 加入活動</h4>
    <h4 class="font-bold">Joins an Activity</h4>
    <p class="text-white/70 mt-1">選擇了「夕陽散步＋手機攝影」的低壓力活動。</p>
    <p class="text-white/70 mt-1 text-xs">Chooses a low-pressure "Sunset Walk + Phone Photography" activity.</p>
  </div>
  <div class="flex flex-col items-center">
    <div class="i-carbon-face-satisfied w-20 h-20 text-green-300"></div>
    <h4 class="font-bold mt-2">4. 建立連結</h4>
    <h4 class="font-bold">Builds Connections</h4>
    <p class="text-white/70 mt-1">透過共同任務自然地與人互動，不再感到焦慮。</p>
    <p class="text-white/70 mt-1 text-xs">Interacts with others naturally through a shared task, feeling less anxious.</p>
  </div>
</div>
<p class="mt-4 text-center">平台提供了一個「緩衝」，讓她敢於邁出第一步。</p>
<p class="mt-1 text-center text-white/80">The platform provides a "buffer," giving her the courage to take the first step.</p>

<!--
為了具象化我們的解決方案，我們編寫了一個設計情境。故事主角就是子萱。她從一開始在學校感到孤單，到偶然發現我們的平台。平台上「用社交強度篩選」的功能吸引了她，讓她有勇氣報名一個「夕陽散步」的低壓力活動。在活動中，因為有「拍照」這個共同任務當作緩衝，她很自然地跟其他人開始互動，最終成功建立了新的連結。這個故事版幫助我們釐清了產品的核心流程。
-->

---

# 核心設計：心理舒適度優先
# Core Design: Prioritizing Psychological Comfort

<div class="grid grid-cols-2 gap-8 items-center">
  <div class="text-left">
    <h3 class="font-bold text-2xl mb-4">社交強度過濾器</h3>
    <h3 class="font-bold text-2xl mb-4">Social Intensity Filter</h3>
    <p class="text-white/80 mb-4">這是我們設計的核心。使用者不是先選「活動內容」，而是先選「想要的社交方式」。</p>
    <p class="text-white/80 mb-4">This is the core of our design. Users choose their desired "mode of socializing" before selecting the "activity content."</p>
    <ul class="space-y-2">
      <li><span class="font-bold text-teal-300">等級1:</span> 只需要點頭微笑 (Just need to nod and smile)</li>
      <li><span class="font-bold text-teal-300">等級3:</span> 會聊幾句但不會強迫互動 (Will chat a bit, but no forced interaction)</li>
      <li><span class="font-bold text-teal-300">等級5:</span> 適合想認識新朋友的人 (Suitable for those who want to meet new people)</li>
    </ul>
    <p class="text-white/80 mt-4">這給予了慢熟使用者「選擇的權利」，讓他們能待在自己的舒適圈內進行社交。</p>
    <p class="text-white/80 mt-2">This empowers slow-to-warm-up users with the "right to choose," allowing them to socialize within their comfort zone.</p>
  </div>
  <!-- <div>
    <img src="/data/website/activities_filter.png" class="rounded-2xl shadow-xl" alt="Activity Filter UI">
  </div> -->
</div>

<!--
我們設計的核心，就是這個「社交強度過濾器」。傳統的活動平台，你只能選「爬山」或「看電影」。但在我們的平台上，你可以先決定你今天想要的「社交方式」。例如，你可以選擇等級一，「只需要點頭微笑」的活動，或者等級三，「會聊幾句但不會強迫互動」的活動。這個設計翻轉了傳統的邏輯，把「心理舒適度」放在第一位，真正賦予了像子萱這樣的慢熟使用者「選擇的權利」。
-->

---

# 建立信任感與安全感
# Building Trust and Safety

<div class="grid grid-cols-2 gap-8 text-left">
  <div>
    <h3 class="font-bold text-xl mb-2">豐富的個人檔案 (Rich Profiles)</h3>
    <p class="text-sm text-white/80 mb-4">我們設計了超越基本資料的個人檔案，包含「個性風格滑桿」和「可以問我」標籤，幫助使用者找到同頻率的人，並降低初次見面的不確定性。</p>
    <p class="text-sm text-white/80 mb-4">We designed rich profiles that go beyond basic information, including "personality sliders" and "ask me about" tags, to help users find like-minded people and reduce the uncertainty of first meetings.</p>
    <!-- <img src="/data/website/profile_sliders.png" class="rounded-xl shadow-lg" alt="Profile Sliders"> -->
  </div>
  <div>
    <h3 class="font-bold text-xl mb-2">活動驗證與安全指南 (Verification & Safety)</h3>
    <p class="text-sm text-white/80 mb-4">為了確保社群品質，我們設計了活動審核流程。同時，在App內提供「公園安全地圖」和「如何禮貌地提早離開」的教戰守則，大幅降低參與者的心理壓力。</p>
    <p class="text-sm text-white/80 mb-4">To ensure community quality, we designed an activity review process. The app also includes a "park safety map" and a guide on "how to politely leave early," significantly reducing participants' psychological stress.</p>
    <!-- <img src="/data/website/verification_stepper.png" class="rounded-xl shadow-lg" alt="Verification Stepper"> -->
  </div>
</div>

<!--
除了核心功能，我們也致力於建立社群的信任感。在個人檔案頁，我們設計了「個性風格滑桿」，讓使用者可以表達自己是偏向「獨處充電」還是「互動充電」，是「慢節奏」還是「快節奏」。這能幫助大家在見面之前，就找到頻率相似的人。同時，我們也有活動的審核機制，並在App內提供安全指南，例如教你「如何禮貌地提早離開」，這些設計都是為了最大化使用者的安全感。
-->

---

# 原型驗證與優化
# Prototype Verification & Iteration

<div class="text-left">
  <p>我們透過角色扮演的方式，讓受訪者化身為「楊子萱」來對我們的設計進行驗證。得到了許多寶貴的回饋：</p>
  <p class="text-white/80">We used role-playing to have interviewees embody "Yang Zixuan" and validate our design. We received valuable feedback:</p>
  <div class="grid grid-cols-2 gap-4 mt-4 text-sm">
    <div class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
      <p class="text-amber-300 font-bold mb-2">關於天氣 (On Weather):</p>
      <p class="italic">「如果沒有冷氣，我真的不會參加... 但如果是傍晚，天氣比較涼，我可能會考慮。」</p>
      <p class="italic text-white/70 mt-1">"If there's no AC, I really wouldn't go... but if it's in the evening when it's cooler, I might consider it."</p>
      <p class="text-green-400 mt-2">➡️ <span class="font-bold">驗證：</span> 平台上的熱門活動多在黃昏，符合使用者需求。</p>
      <p class="text-green-400 text-xs">➡️ <span class="font-bold">Validation:</span> Popular activities on the platform are mostly at dusk, meeting user needs.</p>
    </div>
    <div class="backdrop-blur-sm bg-white/5 p-4 rounded-lg border border-white/10">
      <p class="text-sky-300 font-bold mb-2">關於發起活動 (On Hosting):</p>
      <p class="italic">「一開始我應該不會主動發起... 但如果平台有『有人加入才成立』的功能，我會願意試試看。」</p>
      <p class="italic text-white/70 mt-1">"I probably wouldn't host at first... but if the platform had a feature where 'it only happens if people join,' I'd be willing to try."</p>
      <p class="text-green-400 mt-2">➡️ <span class="font-bold">優化方向：</span> 在 2.0 版本加入「最低成團人數」的設定。</p>
      <p class="text-green-400 text-xs">➡️ <span class="font-bold">Improvement:</span> Add a "minimum participants" setting in version 2.0.</p>
    </div>
  </div>
</div>

<!--
設計完成後，我們進行了原型驗證。我們邀請受訪者扮演楊子萱，來測試我們的想法。結果非常成功。例如，當我們問到天氣問題，她們的回答跟我們的假設完全一樣，證明了我們將熱門活動設定在黃昏是正確的。同時，我們也得到寶貴的優化建議，例如在發起活動時，增加「最低成團人數」的選項，這也成為我們下一版要改進的目標。
-->

---
layout: section
---

# PART III
## 專案價值與結論
## Value & Conclusion

<!--
最後，來到我們的結論部分。我們將總結這個專案的價值，以及我們從中學到的事情。
-->

---

# 專案價值
# Project Value

<div class="grid grid-cols-3 gap-8 text-left">
  <div>
    <div class="i-carbon-user-favorite w-12 h-12 text-green-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對使用者<br>For the User</h3>
    <p class="text-sm text-white/80">提供一個「社交新手村」。在這裡，犯錯是被允許的，沉默是沒關係的。它賦予了使用者在公共空間中「合法」獨處或進行輕社交的權利。</p>
    <p class="text-sm text-white/80 mt-2">Provides a "social beginner's village" where mistakes are allowed and silence is okay. It grants users the right to be alone or engage in light social activities in a public space.</p>
  </div>
  <div>
    <div class="i-carbon-park w-12 h-12 text-teal-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對公園<br>For the Park</h3>
    <p class="text-sm text-white/80">讓被忽視的青少年族群重新與公園產生連結。公園不再只是長輩的運動場或小孩的遊樂區，它也可以是年輕人建立歸屬感的第三空間。</p>
    <p class="text-sm text-white/80 mt-2">Re-engages the overlooked youth demographic with the park. The park is no longer just for the elderly or children but becomes a third space for young people to build a sense of belonging.</p>
  </div>
  <div>
    <div class="i-carbon-connect w-12 h-12 text-sky-400 mb-2"></div>
    <h3 class="font-bold text-xl mb-2">對社會<br>For Society</h3>
    <p class="text-sm text-white/80">提出一個緩解現代人孤獨感的可能解方。它證明了，有時候我們需要的不是更多的連結，而是「更舒適的連結」。</p>
    <p class="text-sm text-white/80 mt-2">Offers a potential solution to modern loneliness. It proves that sometimes what we need is not more connections, but "more comfortable connections."</p>
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
# <span class="block mt-4 text-white/90 text-4xl font-light tracking-wider">Making friends can be a comfortable choice.</span>

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
  <p class="text-4xl text-white font-light mt-2">Discussions & Feedback</p>
  <div class="mt-8 w-16 h-0.5 bg-white rounded-full"></div>
</div>

<!--
謝謝大家，接下來是問答時間。
-->
