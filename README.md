# ChonkyDrake

Derpy G-Dragon Codex Desktop Pet – Includes Windows installer, animation previews, and user guide.

![憨G龍](preview.gif)

## 下載與安裝

**[下載 Windows 安裝包](ChonkyDrake-Windows.zip)**

適用於 Windows。請先安裝並登入支援 Pets 功能的 [Codex 桌面程式](https://chatgpt.com/codex)。如果設定中沒有 Pets，請先更新 Codex。

1. 下載 `ChonkyDrake-Windows.zip`，按右鍵選「全部解壓縮」。
2. 開啟解壓縮後的 `ChonkyDrake` 資料夾，雙擊 `安裝憨G龍.bat`。
3. 開啟 Codex 的「設定 → Pets」，選擇「憨G龍」，按「Wake Pet／喚醒寵物」。

不需要系統管理員權限，也不用另外安裝 Python 或其他開發工具。寵物安裝在目前 Windows 使用者的個人資料夾；安裝包本身不包含 Codex，也不會替你登入帳號。

## 怎麼玩

- **吐小火苗：**把滑鼠移到龍身上；移開後回到原本狀態。
- **移動位置：**在龍身上按住滑鼠左鍵，拖到想要的位置或另一個螢幕。
- **預覽所有動作：**雙擊安裝包內的 `預覽憨G龍.html`，選擇動作、背景和大小。預覽可以離線使用。
- **收起寵物：**在 Codex 的寵物選單讓牠休息。

牠也會隨 Codex 的工作狀態顯示等待、思考或檢查等表情。實際反應由 Codex 控制。

## 常見問題

**安裝後找不到憨G龍？**

請完全退出 Codex，再重新開啟並進入 Pets 選擇憨G龍。只關閉設定頁不一定會更新清單。

**更新後仍是舊動作？**

先改選另一隻寵物，再選回憨G龍；必要時重開 Codex。安裝工具發現不同版本時會先詢問，確認更新後會備份原本的圖片。

**看得到龍，卻無法拖曳？**

1. 保持 Codex 和桌面寵物開啟，執行 `疑難排解／修復拖曳.bat`。
2. 在 7 秒倒數內，把滑鼠移到龍的肚子上，保持不動。
3. 測試拖曳，回到工具輸入 `1` 保留；其他輸入會還原。

這是可選用的暫時處理方式。如果寵物周圍透明區域擋住點擊，執行 `疑難排解／還原拖曳.bat`。重開 Codex 後若問題再次出現，可重新執行修復工具。找不到合適的寵物視窗時，工具會停止。

**雙擊安裝沒有執行？**

確認已經解壓縮整個 ZIP，且檔案沒有被防毒軟體隔離。受公司管理的電腦若限制執行安裝工具，請向資訊人員申請協助。

**如何移除？**

先在 Codex 改選其他寵物，再刪除 `%USERPROFILE%\.codex\pets\han-g-dragon` 資料夾。若曾自行設定 Codex 資料位置，請在該位置下的 `pets` 資料夾移除憨G龍。
