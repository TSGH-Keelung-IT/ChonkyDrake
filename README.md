# ChonkyDrake

Derpy G-Dragon Codex Desktop Pet – Includes Windows installer, animation previews, and user guide.

![憨G龍動舌頭與吐火冒白菸](preview.gif)

## 下載與安裝

**[下載 Windows 安裝包](https://github.com/TSGH-Keelung-IT/ChonkyDrake/releases/latest/download/ChonkyDrake-Windows.zip)**

適用於 Windows。請先安裝並登入支援 Pets 功能的 [Codex 桌面程式](https://chatgpt.com/codex)。如果設定中沒有 Pets，請先更新 Codex。

1. 下載 `ChonkyDrake-Windows.zip`，按右鍵選「全部解壓縮」。
2. 開啟解壓縮後的 `ChonkyDrake` 資料夾，雙擊 `安裝憨G龍.bat`。
3. 開啟 Codex 的「設定 → Pets」，按圓形箭頭「Refresh／重新整理」。
4. 選擇「憨G龍」，按「Wake Pet／喚醒寵物」。

已有舊版時，在安裝工具輸入 `1` 即可備份並更新；完成後也請按 Pets 的「Refresh／重新整理」，再選回憨G龍。

不需要系統管理員權限，也不用另外安裝 Python 或其他開發工具。安裝包不包含 Codex。

## 怎麼玩

- **動舌頭：**讓寵物待機，並將滑鼠移開牠；伸舌、舔嘴角、收舌與眨眼一輪約 6.6 秒。
- **吐火冒白菸：**把滑鼠移到龍身上，牠會吐出小火苗，再吹出白色迷你蘑菇雲。
- **移動位置：**在龍身上按住滑鼠左鍵，拖到想要的位置或另一個螢幕。
- **預覽所有動作：**雙擊安裝包內的 `預覽憨G龍.html`，選擇動作、背景和大小。待機預覽採用 Codex 原生速度，可離線使用。
- **收起寵物：**在 Codex 的寵物選單讓牠休息。

寵物會隨 Codex 的工作狀態顯示等待、思考或檢查等表情。原生寵物的動作與轉頭由 Codex 控制；預覽頁的「跟著看」是頁面上的滑鼠互動。

## 常見問題

**更新後仍是舊動作，或找不到憨G龍？**

確認已完成安裝，再到「設定 → Pets」按圓形箭頭「Refresh／重新整理」，選回憨G龍。

**舌頭怎麼沒有一直動？**

動舌頭是待機動作。吐火、轉頭或執行其他狀態時，會顯示該狀態的動作。請移開滑鼠，待牠回到待機後觀察約 7 秒。

**看得到龍，卻無法拖曳？**

1. 保持 Codex 和桌面寵物開啟，執行 `疑難排解／修復拖曳.bat`。
2. 在 7 秒倒數內，把滑鼠移到龍的肚子上，保持不動。
3. 測試拖曳，回到工具輸入 `1` 保留；其他輸入會還原。

這是可選用的暫時處理方式。如果寵物周圍透明區域擋住點擊，執行 `疑難排解／還原拖曳.bat`。重開 Codex 後若問題再次出現，可重新執行修復工具。找不到合適的寵物視窗時，工具會停止。

**雙擊安裝沒有執行？**

確認已經解壓縮整個 ZIP，且檔案沒有被防毒軟體隔離。受公司管理的電腦若限制執行安裝工具，請向資訊人員申請協助。

**如何移除？**

先在 Codex 改選其他寵物，再刪除 `%USERPROFILE%\.codex\pets\han-g-dragon` 資料夾。若曾自行設定 Codex 資料位置，請在該位置下的 `pets` 資料夾移除憨G龍。
