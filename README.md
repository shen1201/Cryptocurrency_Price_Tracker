## 連結 https://shen1201.github.io/Cryptocurrency-Price-Tracker/Cryptocurrency%20Price%20Tracker.html
主要功能：<br>
  1.下拉式選單：可以選擇查看 BTC、ETH、ADA、DOGE 和 SOL 這五種加密貨幣的價格<br>
  2.動態主題顏色：根據選擇的加密貨幣自動改變頁面主題顏色（每種幣有專屬顏色）<br>
  3.實時價格更新：<br>
    ● 每 60 秒自動更新一次<br>
    ● 帶有倒數計時器顯示距離下次更新的時間<br>
    ● 可手動點擊按鈕立即更新<br><br>

技術亮點：<br>
  1.API 雙保險：<br>
    ● 主要使用 CoinGecko API 獲取價格和 24 小時漲跌幅<br>
    ● 備用 Binance API，當 CoinGecko 失敗時自動切換<br>
    ● 清晰的提示信息，指示當前使用的是哪個數據源<br>
  2.API 請求優化：<br>
    ● 設置了請求頻率限制，避免過快刷新導致 API 限制<br>
    ● 顯示明確的等待時間提示<br>
  3.針對不同幣種的優化：<br>
    ● 根據幣值大小自動調整小數點顯示位數（比特幣 2 位，ADA 4 位等）<br>
    ● 每種幣都有中英文名稱顯示<br>
  4.用戶體驗：<br>
    ● 響應式設計，適配手機和電腦<br>
    ● 清晰的價格和漲跌幅顯示<br>
    ● 漲跌幅顏色指示（上漲綠色，下跌紅色）
