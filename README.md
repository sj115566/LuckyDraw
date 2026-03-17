# 線上抽籤系統 (Lucky Draw)

本專案是一個方便好用的線上抽籤工具。
此為 [Lucky Bacon](https://github.com/sj115566/LuckyDraw) (由 [BaconBao Lin](https://baconbao.github.io/) 原創) 的修改（Fork）版本，並加入了更多實用功能與現代化的介面設計。

## 🌟 專案特色 (Features)

- **現代化 UI 介面**：採用全新的色彩設計與排版，提供更好的使用者體驗。
- **客製化項目設定**：除了維持自動編號 (項目 #1, 項目 #2...) 外，支援為每個項目自訂專屬名稱。
- **靈活的項目管理**：可隨時新增項目、調整名額，並支援「刪除特定項目」的功能。
- **防呆與人數驗證**：在開始抽籤前，系統會自動檢查並提醒「參與人數是否少於項目總名額」，避免發生名額多於參與者的問題。
- **公平公正的演算法**：採用 [The Fisher-Yates (aka Knuth) shuffle](http://stackoverflow.com/a/2450976) 亂數演算法。
- **自動排除已中籤者**：每一輪抽籤會自動排除上一輪的中籤者，確保每個人最多只會中籤一次。

## 🚀 如何使用 (How to use)

1.  在左側區塊輸入**參與抽籤的名單**，請以「換行」做為每個人名的分隔。
2.  在右側區塊設定**項目與名額**：
    - 點擊右上方的紅色 `+` 按鈕可新增項目。
    - 可透過 `+` / `-` 按鈕調整該項目的抽出人數。
    - 如需自訂項目名稱，可填寫至「自訂名稱(選填)」欄位中。
    - 如需刪除特定項目，請點擊該項目右側的「刪除」按鈕。
3.  確認名單與項目無誤後，點擊 **「開始抽籤！」**。
4.  系統將會以優雅的介面呈現各項目的中籤名單！

## 📜 版權與致謝 (Credits & License)

- **Original Project**: [LuckyBacon](https://github.com/baconbao/LuckyBacon)
- **Original Author**: [BaconBao Lin](https://baconbao.github.io/)
- **Modifications**: This is a modified version forked and customized with additional features and UI enhancements.
