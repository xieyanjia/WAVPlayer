# WAV 音效播放器

## 專案簡介

本專案是一個使用 C# Windows Forms 製作的 WAV 音效播放器，主要功能是讓使用者透過圖形化介面選擇本機的 WAV 音效檔案，並進行播放、重複播放、停止播放與結束程式等操作。

程式使用 `System.Media.SoundPlayer` 類別來載入與播放 WAV 音效檔案，並搭配 `OpenFileDialog` 讓使用者可以從電腦中選擇音效檔。當使用者執行不同操作時，畫面下方的狀態文字會即時更新，方便使用者了解目前程式狀態。

---

## 執行說明與功能介紹

### 1. 瀏覽音效檔

使用者可以按下「瀏覽」按鈕開啟檔案選擇視窗，選擇電腦中的 WAV 音效檔案。

選擇完成後，檔案路徑會顯示在文字方塊中，並將狀態更新為「準備就緒」。

---

### 2. 播放一次

使用者按下「播放一次」按鈕後，程式會載入目前選擇的 WAV 音效檔，並播放一次。

播放時狀態會顯示為「正在播放...」。

---

### 3. 重複播放

使用者按下「重複播放」按鈕後，音效會持續循環播放。

音效播放完後會自動從頭開始再次播放，直到使用者按下「停止播放」為止。

重複播放時狀態會顯示為「正在重複播放...」。

---

### 4. 停止播放

使用者按下「停止播放」按鈕後，程式會停止目前正在播放或正在重複播放的音效。

停止後狀態會顯示為「已停止」。

---

### 5. 結束程式

使用者按下「結束程式」按鈕後，程式會關閉應用程式。

在關閉前，系統會跳出確認視窗，詢問使用者是否確定要關閉程式，避免誤按造成程式意外關閉。

---
<img width="514" height="322" alt="image" src="https://github.com/user-attachments/assets/69576c06-4156-45e2-9d6b-1186186135aa" />
<img width="513" height="323" alt="image" src="https://github.com/user-attachments/assets/e100361c-4e09-4b09-9856-ce7bf8b124df" />
<img width="512" height="322" alt="image" src="https://github.com/user-attachments/assets/b7b4dd71-3e95-4242-b247-c3fc7e3b863b" />
<img width="511" height="320" alt="image" src="https://github.com/user-attachments/assets/08e1e024-0fb5-4041-8890-95bf9e1062c0" />
<img width="513" height="322" alt="image" src="https://github.com/user-attachments/assets/8e55b3f5-5660-43e0-92d0-c432a02aeb51" />
<img width="512" height="323" alt="image" src="https://github.com/user-attachments/assets/ed61040e-05fc-4522-9c94-d10acddffa3d" />







