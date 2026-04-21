# 👋 嗨，我是 Allen

我是一個做 App 的工程師。

這幾年慢慢發現，  
比起把功能做出來，我更在意的是：

👉 系統到底穩不穩  
👉 資料在流動的過程，有沒有亂掉  

很多時候問題不是功能，而是系統本身開始撐不住。

我現在主要在做的事情，就是：

👉 把已經上線、有流量的 App，  
👉 慢慢整理成一個團隊可以安心開發的系統。

---

## 🧠 我平常在處理的東西

比較常遇到的，其實都是這種情境：

- 資料更新很快，但 UI 跟不上（開始亂）
- 功能越加越多，改一個地方就壞別的
- 狀態分散在各個地方，很難 debug

在一個 10萬+ DAU 的產品裡，我做的事情比較單純：

把資料流整理好，讓狀態有地方放，  
最後讓整個系統「穩下來」。

（那次把 crash rate 壓到 0.1%，其實就是這樣來的）

---

## ⚙️ 最近在做的事

我最近在摸的東西，大概都圍繞在：

- real-time 資料更新
- 狀態管理（讓資料跟 UI 對得起來）
- async flow（不要讓系統自己打架）
- 跨框架設計（SwiftUI / UIKit / Flutter）

有些會變成 side project，  
有些只是把一個問題想清楚。

---

## ⭐ 幾個比較有代表性的東西

如果你是第一次來，可以從這幾個看看：

---

### 🔐 Security Center（系統設計）

一開始只是覺得：  
為什麼密碼 / Face ID / 鎖定這些東西都散在各個畫面？

後來就把這些邏輯抽出來，做成一個統一的系統。

→ UI 不用再處理一堆條件  
→ 邏輯集中，後面比較好改  
→ 同一套設計可以跑在 iOS / Flutter

👉 https://github.com/blackman5566/security_center_system_design_flutte

---

### ⚡ Real-time System Design

這個是處理「資料一直來，但畫面不能亂」的問題。

→ 控制更新節奏  
→ 讓 UI 跟資料保持一致  
→ 避免畫面閃動或錯位  

這種問題其實在聊天、賽事、交易都會遇到。

👉 https://github.com/blackman5566/RealTimeMetricsDemo

---

### 📱 Presentation Coordinator

多層 modal 很容易亂掉（sheet、overlay、fullScreen）

所以我把「怎麼開 / 怎麼關」這件事統一管理。

→ View 不用再處理流程  
→ 行為變得可預測  
→ debug 也簡單很多  

👉 https://github.com/blackman5566/SwiftUI-Presentation-Coordinator

---

## 💡 我自己的一些想法

- 系統如果一開始沒想清楚，後面一定會補  
- UI 是表面，狀態才是核心  
- 複雜的東西，通常只是沒有被好好拆開  
- 好的系統，應該讓人比較輕鬆，而不是更累  

---

## 👨‍👧‍👦 一點生活

我是兩個孩子的爸爸。

寫程式之外，其實也就是在過生活。

很多我做的東西，
都是從「這件事好像可以更簡單」開始的。

---

## 📫 找到我

如果你剛好也在做類似的東西，或只是想聊聊：

- LinkedIn: https://www.linkedin.com/in/allen-hsu-54180970/
- Portfolio: https://blackman5566.github.io/project/
