# ntpusu-regulation-typesetting
**NTPUSU Regulatory Typesetting Tool** (國立臺北大學學生自治會法規排版工具) 是為臺北大學學生會法規資料庫設計的排版工具。使用者可以依照指定格式，輸入法規的純文本內容，再由 JavaScript 程式處理後，輸出成 HTML + CSS 格式，貼上到學生會的法規資料庫。

## 使用方式
1. 點擊[Regulatory Typesetting Tool](https://robertgelb.github.io/ntpusu-regulation-typesetting/)進入使用頁面。
2. 依照下列格式說明，輸入法規的純文字內容。範例可參考 [ntpusu-regulation-text](https://github.com/robertgelb/ntpusu-regulation-text) 專案。
    * **編章節、條號：**不用縮排。
    * **項（及不分項條文）：**每行前面加上一個全形空白「　」。
    * **款、目：**以「一、」、「（一）」開頭。
3. 輸入完成後，點擊輸入框下面的 `Generate` 按鈕，就會在右邊的輸出框看到標記好格式的法規，最終呈現結果也會顯示在下面預覽。
4. 請瀏覽下方的預覽結果，確認都沒問題（如果有問題，請回到第 2 步，修改輸入框中的內容）後，點擊輸出框下的藍色 `Copy` 按鈕，就會自動將標記好格式的法規複製到你的剪貼簿中。
5. 登入學生會網站後台，把標示好格式的結果，貼上到法規 post 的自訂 HTML 區塊。
6. 請將第 2 步驟輸入的法規純文字檔留好備份（也可以 PR 到前述 [ntpusu-regulation-text](https://github.com/robertgelb/ntpusu-regulation-text) 專案中），未來修改時，就可以以此為基底，不用每次都按照本工具的格式重新調整法規內容。

## Screenshot
!["實際運作畫面擷圖"](https://github.com/robertgelb/ntpusu-regulation-typesetting/blob/main/example.webp)
