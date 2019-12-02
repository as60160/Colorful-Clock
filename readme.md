# Colorful Clock

![Colorful Clock](https://i.imgur.com/0b2PuCu.png)

## Demo

Demo：https://as60160.github.io/Colorful-Clock.html


## 簡介

從 「180 websites in 180 days」 看到的，這是裡面的 Day 11 作品。

- [180 websites in 180 days](https://jenniferdewalt.com/color_clock.html)

這個網頁每過一秒會更新時間，同時漸進式改變背景的顏色，並且將背景顏色的 16 進位代碼 (Hex 色碼) 呈現在畫面上。


### 想法

1. 使用 JavaScript 的 `setInterval()` 讓時間跟顏色每一秒改變一次。
2. 原始作品是用 Hex 色碼表示顏色，我改用 RGB 色碼表示。
3. 原始作品的時間跟顏色之間有關聯，所以重新載入網頁後，顏色不會隨機改變，而是按照原有的設定進行。我的作法是讓網頁每次載入時，都隨機產生顏色。


### 使用工具或技術

全部用 JavaScript 進行操作，其中幾個重要的方法如下：
- 時間函數：
    - `new Date()`
    - `getHours()`
    - `getMinutes()`
    - `getSeconds()`
- 排程設定：
    - `setInterval()`

