# 嗨，我是 Allen

我是一名 App Engineer，主要專注在 iOS、跨平台 App、系統設計與 AI workflow。

我做功能，也整理系統。

對我來說，真正讓專案卡住的通常不是單一功能，而是：

> 資料流不清楚、狀態分散、流程重複、責任邊界沒有被設計好。

最近我也在做另一件事：

> 把 AI 放進既有工程流程，讓它成為可控、可驗證、可重複使用的開發加速器。

---

<p align="center">

![iOS](https://img.shields.io/badge/iOS-Swift-blue)
![Flutter](https://img.shields.io/badge/Flutter-Dart-blue)
![System Design](https://img.shields.io/badge/System-Design-black)
![Realtime](https://img.shields.io/badge/Realtime-Data-orange)
![AI Workflow](https://img.shields.io/badge/AI-Workflow-green)

</p>

---

## 我關心的問題

我喜歡處理那些一開始看起來只是「功能問題」，但其實背後是系統設計問題的東西。

| 問題現象 | 我關心的本質 |
| --- | --- |
| 資料一直更新，畫面容易亂 | UI 與資料狀態沒有穩定同步 |
| 功能越做越多，改一個壞三個 | 責任邊界與流程沒有被拆清楚 |
| 狀態分散，bug 很難追 | 缺少單一可信資料來源 |
| 表單、報表、文件流程重複 | 人工流程沒有被轉成系統流程 |
| AI 可以寫程式，但結果不穩 | 缺少工程規則、驗證流程與上下文約束 |

我的核心方向是：

> 讓系統撐得住規模，也讓流程可以被穩定重複。

---

## 代表作品

### Security Center

[security_center_system_design_flutte](https://github.com/blackman5566/security_center_system_design_flutte)

把密碼、Face ID、鎖定狀態這些分散邏輯整合成一個安全中心系統。

重點不是做一個畫面，而是把安全相關流程集中管理。

- UI 不再處理複雜條件
- 狀態與規則集中，容易維護
- 可跨 iOS / Flutter 思路重用

---

### Real-time Metrics Demo

[RealTimeMetricsDemo](https://github.com/blackman5566/RealTimeMetricsDemo)

處理高頻資料進來時，UI 不能亂跳、不能閃爍、不能不同步的問題。

- 控制更新節奏
- 穩定 UI 與資料的一致性
- 避免重複渲染造成畫面抖動

---

### SwiftUI Presentation Coordinator

[SwiftUI-Presentation-Coordinator](https://github.com/blackman5566/SwiftUI-Presentation-Coordinator)

統一管理 SwiftUI 裡的 sheet、overlay、fullScreen 等呈現流程。

- Flow 可控
- 行為一致
- Debug 更容易

---

### Form Pilot

[form-pilot](https://github.com/blackman5566/form-pilot)

把重複填寫文件的人工流程轉成 AI workflow。

流程概念：

```text
profile.json
  -> Word form
  -> AI-assisted filling
  -> output document
```

這不只是填表工具，而是把：

```text
重複輸入
  -> 結構化資料
  -> 自動產出
```

整合成一個可重複的流程。

---

## 我的工程方法

我通常會先問：

- 這真的是 UI 問題，還是狀態管理問題？
- 這真的是功能問題，還是流程沒有被設計好？
- 這段邏輯應該屬於畫面、狀態、資料流，還是系統規則？
- AI 產出的東西有沒有被規則約束？
- 這個結果能不能被驗證、重複使用、長期維護？

我相信：

- UI 是結果，狀態才是核心。
- 功能可以很快做完，但系統要能長期維護。
- 架構不是為了漂亮，而是為了讓變更可控。
- AI 的價值不只在生成，而在整合進實際工作流程。

---

## 技術關注

- iOS development with Swift / SwiftUI / UIKit
- Flutter app architecture
- Real-time data flow
- State management and single source of truth
- Async flow control
- Cross-framework architecture design
- AI-assisted development workflow
- Prompt as engineering constraint

---

## 目前正在整理

### Allen iOS Code Style

我正在整理一份自己的 iOS code style playbook。

Repo: [blackman5566/allen-ios-code-style](https://github.com/blackman5566/allen-ios-code-style)

第一版先只聚焦一件事：

> 讓 AI 在整理 Swift code 時，能產出更一致、可維護、符合 production review 的程式碼。

目前重點包含：

- 依照責任拆分 Swift extension
- 保留既有行為，不把整理程式碼變成重寫功能
- 使用繁體中文 intent comments 說明目的、流程與限制
- 將 function body 拆成容易閱讀與 review 的階段
- 避免為了看起來高級而過度抽象

之後如果內容更完整，再慢慢整理成更大的 Allen Engineering Playbook。

---

## 一點生活

我是兩個孩子的爸爸。

很多 side project 都是從一句話開始：

> 這件事可不可以更簡單？

---

## 聯絡我

- LinkedIn: https://www.linkedin.com/in/allen-hsu-54180970/
- Portfolio: https://blackman5566.github.io/project/
