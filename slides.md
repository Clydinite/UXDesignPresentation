---
theme: seriph
background: https://images.unsplash.com/photo-1614850523296-d8c1af93d400?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: Tainan Park Activity Platform Full Case Study
css: unocss
---

# <span class="text-white drop-shadow-xl text-6xl font-bold italic tracking-tighter">台南公園輕社交平台</span>
## <span class="text-white/80 tracking-widest mt-4 block font-light text-2xl">從行為觀察到「反思型社交」的設計實踐</span>

<div class="pt-20 flex justify-center text-sm font-mono">
  <div class="backdrop-blur-md bg-white/10 border border-white/20 px-8 py-4 rounded-2xl shadow-2xl">
    UX COMPLETE CASE STUDY | 30 PAGES DOCUMENTATION
  </div>
</div>

---
layout: section
---

# PART I: DISCOVERY
### 田野觀察與問題界定

---

# 1. 核心疑問：為何退回個人世界？

當使用者身在公共空間，卻仍然選擇退回個人世界時，他們真正的需求是什麼？

- **觀察現象**：年輕學生在公園、通勤或等待中，長時間使用手機。
- **心理矛盾**：呈現一種「獨自、分心、卻又不完全放鬆」的狀態。
- **設計起點**：不直接想解法，而是從行為背後的動機出發。

---

# 2. 田野觀察完整紀錄 (U1 - U6)

<div class="grid grid-cols-2 gap-4 text-[10px] font-light">
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-blue-300">(U1) 騎車小孩</p>
    <p>穿著黑衣、獨自騎車。喜歡觀察行人對話，對公園路徑展現極高熟悉度。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-pink-300">(U2) 散步情侶</p>
    <p>邊走邊滑手機，社交氛圍極度私密且快樂，外界難以介入。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10 text-slate-400 italic">
    <p class="font-bold">(U3) 長凳友人</p>
    <p>分享手機螢幕、在樹下涼快，屬於封閉的小圈圈互動。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-amber-300">(U4) 涼亭長者</p>
    <p>整理物品、喝水抽菸，對環境有強烈地盤意識與固定行為。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-amber-300">(U5) 玩牌長者</p>
    <p>全神貫注於牌局，對觀察者展現出警覺性。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10 ring-1 ring-sky-400/50">
    <p class="font-bold text-sky-300">(U6) 運動長者 (關鍵樣本)</p>
    <p>主動詢問「今天不是假日嗎？」語氣友善但不真誠，引發觀察者社交焦慮。</p>
  </div>
</div>

---

# 3. 田野觀察完整紀錄 (U7 - U12)

<div class="grid grid-cols-2 gap-4 text-[10px] font-light">
  <div class="backdrop-blur-md bg-yellow-500/10 p-3 rounded-xl border border-yellow-500/30">
    <p class="font-bold text-yellow-300">(U7) 南二中同學 (核心族群)</p>
    <p>模仿短片內容、抱怨段考、集體等車。身體在場但心理依賴數位群體。</p>
  </div>
  <div class="backdrop-blur-md bg-yellow-500/10 p-3 rounded-xl border border-yellow-500/30">
    <p class="font-bold text-yellow-300">(U8) 大學生</p>
    <p>專注遊戲與通訊軟體，行動電源不離手，維持長時數位連結。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10 text-slate-400">
    <p class="font-bold">(U9) 等車者</p>
    <p>頻繁查看公車 App，因出汗與人潮擁擠顯得焦躁不安。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-blue-200">(U10) 遊樂區小孩</p>
    <p>使用滑索與設施，純粹的體力消耗，無複雜社交需求。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-emerald-200">(U11) 顧小孩家長</p>
    <p>樹蔭下回訊息、偶爾交談。維持「多重任務」的零碎社交。</p>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-3 rounded-xl border border-white/10">
    <p class="font-bold text-indigo-300">(U12) 慢跑男子</p>
    <p>耳機隔絕外界，沉浸在穩定的運動頻率中。</p>
  </div>
</div>

---

# 4. 同理心地圖：理解行為背後的心理



[Image of Empathy Map: Say, Do, Think, Feel]


<div class="grid grid-cols-2 gap-4 mt-4 text-xs">
  <div class="p-3 bg-white/5 rounded-xl border border-white/10">
    <h4 class="text-blue-300 mb-1">說什麼 (Say)</h4>
    <p class="text-white/60 italic font-light">「超扯！那個 Reels 你按讚沒？」<br>「公車還有五分鐘到...」</p>
  </div>
  <div class="p-3 bg-white/5 rounded-xl border border-white/10">
    <h4 class="text-emerald-300 mb-1">想什麼 (Think)</h4>
    <p class="text-white/60 italic font-light">「可以再滑五分鐘，時間還夠。」<br>「如果被補習班老師發現遲到就慘了。」</p>
  </div>
</div>

---

# 5. 行為模式萃取：兩極化的社交現象

我們發現公園內的行為分佈呈現兩極：

<div class="flex justify-around items-center mt-12 gap-8 text-center">
  <div class="flex-1 backdrop-blur-md bg-white/5 p-6 rounded-3xl border border-white/10 shadow-xl">
    <div class="text-3xl mb-2 text-pink-300">🔒</div>
    <h3 class="text-xs font-bold mb-2">封閉圈</h3>
    <p class="text-[9px] text-white/50 leading-relaxed italic">關係網絡已固化，<br>外人難以加入。</p>
  </div>
  <div class="flex-1 border-y border-white/20 py-4 italic text-sm text-yellow-200">
    社交真空區
  </div>
  <div class="flex-1 backdrop-blur-md bg-white/5 p-6 rounded-3xl border border-white/10 shadow-xl">
    <div class="text-3xl mb-2 text-blue-300">🎧</div>
    <h3 class="text-xs font-bold mb-2">孤立島</h3>
    <p class="text-[9px] text-center text-white/50 leading-relaxed italic">藉由數位設備，<br>在公共空間自保。</p>
  </div>
</div>

---

# 6. 行為與心理狀態維度分析



我們分析了多個維度：
- **移動性**：靜止狀態 vs. 快速移動。
- **目的性**：漫無目的 vs. 有明確目標。
- **互動度**：無設施互動 vs. 深度使用。
- **情緒**：焦慮/分心 vs. 舒適放鬆。

---

# 7. 數據視覺化：社交座標軸

[Image 1: User Segmentation Matrix on Tainan Park]

- **發現**：大多數使用者（U1-U12）分佈在兩極。
- **缺口**：缺乏一個「有目的性、但低社交門檻」的中介空間。

---

# 8. 關鍵轉折 (The Pivot)

與其做導覽，不如解決**「想交朋友但不知道怎麼開始」**的恐懼。

- **觀察點**：青少年在公園「等公車」或「消磨時間」的空檔是潛在社交窗口。
- **痛點**：目前的社交活動預設使用者是「外向」的。
- **對策**：將公園視為「低壓力的中介空間」。

---
layout: section
---

# PART II: DEFINITION
### 人物誌與利害關係人

---

# 9. Persona：楊子萱 (16歲，高一)



<div class="grid grid-cols-2 gap-8 mt-6 text-sm font-light leading-relaxed">
  <div class="backdrop-blur-md bg-white/5 p-4 rounded-xl">
    <h4 class="text-blue-300 font-bold mb-2">行為特徵</h4>
    <ul class="list-disc list-inside space-y-1 opacity-70">
      <li>長時間滑手機避免眼神互動</li>
      <li>在既有群體外圍徘徊</li>
      <li>需要放鬆但容易被打斷</li>
    </ul>
  </div>
  <div class="backdrop-blur-md bg-white/5 p-4 rounded-xl">
    <h4 class="text-pink-300 font-bold mb-2">情境需求</h4>
    <ul class="list-disc list-inside space-y-1 opacity-70">
      <li>渴望校外的新關係</li>
      <li>需要「安心感」的設計</li>
      <li>不想被迫參與高互動遊戲</li>
    </ul>
  </div>
</div>

---

# 10. 子萱的心聲：現實社交困境

- **社交圈固定化**：後來加入的人往往成為局外人。
- **高心理壓力**：不知道如何開啟對話，怕顯得格格不入。
- **外向者的專屬**：許多活動要求「快速破冰」，對子萱來說是災難。

---

# 11. 公園作為「中介空間」的優勢



1. **開放且免費**：沒有消費壓力與門檻。
2. **沒有角色期待**：可以是散步者，也可以是發呆者。
3. **適合「一起做事」**：透過共同活動產生連結，比面對面交談更自在。

---

# 12. 利害關係人地圖 (Stakeholder Map)

[Image 2: Stakeholder Map - Internal/External/Context]

- **核心**：青少年使用者 (U7, U8)。
- **外部**：老人 (U6, U4, U5)、家長 (U11)。
- **環境**：公車系統、公園設施管理單位。

---

# 13. JTBD：子萱的關鍵任務

1. **降低啟動門檻**：不需要像賭博一樣參加活動。
2. **篩選適合氛圍**：先選擇「社交方式」，再選擇「活動」。
3. **心理緩衝**：需要一個漸進式參與的選項。

---
layout: section
---

# PART III: CONCEPT & DESIGN
### 概念發展與設計方案

---

# 14. 核心翻轉：反思型社交

**「不是不想交朋友，而是怎麼開始。」**

- **傳統模式**：活動內容 → 人員湊齊 → 強制社交。
- **本案概念**：社交強度篩選 → 低壓任務 → 自然連結。

---

# 15. 概念發展圖

[Image 3: Concept Development and Storyboard Flow]

從子萱在校門口感到無聊，到她透過 App 發現適合的「低強度攝影活動」，最後在公園內與志同道合的人建立連結。

---

# 16. 設計原則：3 低原則

1. **低壓力**：匿名預熱，不必立即現身。
2. **低門檻**：不需特定技能，只要「在場」即可。
3. **低頻率**：不強制維繫關係，享受當下的連結。

---

# 17. 應用程式介面：首頁探索

[Image 4: Mobile UI - Activity Discovery Screen]

- **介面設計**：清爽、通透的毛玻璃樣式。
- **亮點**：分類清晰，強調「活動氛圍」標籤。

---

# 18. 子萱的疑慮與介面回應

當子萱點開活動列表，她會感到焦慮：「這真的有比學校社團好嗎？」

- **解法**：提供詳細的「主持人氛圍描述」。
- **預覽**：顯示目前的參與者特質（如：80% 為內向者）。

---

# 19. 活動詳情：透明化社交預期

[Image 5: Mobile UI - Activity Details with Vibe Description]

- **詳細介紹**：主持人會標註「本活動適合開朗朋友」或「適合靜態慢熟者」。
- **決策權**：子萱不需要賭博，她可以選擇最適合自己的舒適圈。

---

# 20. 關鍵功能：過濾器篩選

[Image 6: Mobile UI - Filter Screen with Range Sliders]

子萱發現系統提供「社交強度拉條」：
- **人數上限**：可篩選小於 5 人的小團體。
- **互動等級**：低、中、高強度選擇。

---

# 21. 低社交活動：攝影新手攝影活動

子萱最終選擇了「低社交攝影」：
- **吸引點**：留言歡迎攝影新手。
- **氛圍感**：主打靜態、觀察公園。

---

# 22. 安心指標與預先互動

[Image 7: Mobile UI - Pre-activity Chat & Safe Badge]

- **破冰任務**：在線上先分享一張自己拍的照片。
- **安心標記**：顯示「主持人已通過身分驗證」。

---

# 23. 實體場域引導

[Image 8: Offline Guidance - Meeting Point in Tainan Park]

App 結合地圖導引，標註在公園內的精確集合點，減少子萱找路時的焦慮。

---

# 24. 情境模擬：公園現場

[Image 9: Scenario Illustration - Zi-Xuan arriving at the Park]

子萱到達現場，手持相機作為媒介，這讓她有了「合理的掩護」，不必為了交談而交談。

---

# 25. 互動的發生：從工作到連結

- **非語言連結**：共同拍攝夕陽。
- **自然對話**：「你也用這台相機嗎？」
- **結果**：成功建立無壓力的初次接觸。

---
layout: section
---

# PART IV: VALUE & CONCLUSION
### 專案價值與反思

---

# 26. 解決方案總結：三層保障

1. **數位緩衝層**：篩選與預覽活動。
2. **物理場景層**：公園的開放中介性。
3. **心理安全層**：強調任務導向的互動。

---

# 27. 專案價值：重新連結公共空間

- **對子萱**：找到社交新手村。
- **對公園**：讓被忽視的青少年族群重新定義空間的使用方式。
- **對社會**：緩解孤獨感，建立輕量的社會連結。

---

# 28. 數據驗證與反思 (Based on U6/U7)

我們回過頭看當初的 U6 (老人侵略性詢問)：
- **設計回應**：若子萱當時正在參加平台的「讀書團」，她可以更有自信地回應：「我在參加活動」，這賦予了她在公共空間的行為合法性。

---

# 29. 未來展望

- **場景擴散**：不僅是公園，圖書館、通勤站點也能導入此模式。
- **AI 輔助**：透過 AI 模擬 Persona 對活動方案的壓力測試。

---
layout: center
class: text-center
---

# <span class="bg-gradient-to-r from-blue-300 to-emerald-300 bg-clip-text text-transparent font-bold text-5xl italic tracking-tighter">認識朋友，可以是一種舒適的選擇。</span>

<p class="mt-8 text-white/40 font-mono text-xs tracking-[0.4em] uppercase font-light underline decoration-white/20">Thank you for your attention</p>

---
layout: default
---

# Q & A

<div class="h-full flex flex-col justify-center items-center opacity-30 italic">
  <p class="text-4xl text-white font-light">討論與反饋</p>
  <div class="mt-8 w-16 h-0.5 bg-white rounded-full"></div>
</div>