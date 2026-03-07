# WordPress Single Page 專案集

互動式單頁網頁應用集合，適合嵌入 WordPress 或獨立部署。

## 專案目錄

| 資料夾 | 名稱 | 說明 |
|--------|------|------|
| [`nextfiveyear/`](nextfiveyear/) | 人生模擬器 | 輸入年齡、職業、收入等條件，模擬未來 5 年的收入成長與生活品質 |
| [`xiuxian/`](xiuxian/) | 修仙模擬器 | 文字角色扮演遊戲，選擇天賦與宿命，踏上修仙之路 |

---

## 人生模擬器 [`nextfiveyear/life-simulator.html`](nextfiveyear/life-simulator.html)

根據個人條件模擬三種收入策略下的 5 年人生軌跡。

**主要功能**
- 選擇職業、城市、家庭狀況、月收入
- 三種情境：維持現狀 / 被動收入一萬 / 被動收入五萬
- 收入時間軸、成長圖表、生活品質指標
- 週休三日模擬器、反社畜指數計算
- 支援社群分享（Web Share API）

---

## 修仙模擬器 [`xiuxian/xiuxian-simulator.html`](xiuxian/xiuxian-simulator.html)

隨機抽取天賦、承受宿命烙印，以文字事件推進修仙生涯。

**主要功能**
- 隨機抽四、玩家選二天賦
- 隨機分配一個宿命烙印（負面特性）
- 每次推進隨機經過 2～4 年並觸發隨機事件
- 境界系統：凡人境 → 仙人境（共十境）
- 五維數值：健康、財富、心態、社交、幸運
- 死亡後顯示墓誌銘與完整事件紀錄
- 支援社群分享（Web Share API）

---

## 技術說明

- 純靜態 HTML + CSS + JavaScript，無任何外部依賴
- 可直接嵌入 WordPress 頁面或作為獨立頁面部署
- 響應式設計，支援手機裝置
