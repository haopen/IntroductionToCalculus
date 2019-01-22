# 微積溯源

這個項目旨在提供一版經過精細排版和修訂的微積溯源，並同時研究使用XeLaTeX進行中文竪排的技術。

## 關於微積溯源

微積溯源乃清代洋務運動之時傅蘭雅、華蘅芳所譯之微積分教科書。這本書由於開創性地翻譯了許多現今數學之專有名詞（如“函數”等），因此有將其整理出的價值。

## 關於本項目

本項目分𤔡兩個部分，一者𤔡整理和修訂文字（即校讎學相關），一者𤔡研究XeLaTex竪排中文的技術。目前均由NSKernel獨自進行。由於NSKernel比較喜歡摸魚，所以進度上沒有任何保證，且文件都只是散落在整個項目內，請見諒。

## 如何使用/貢獻本項目

下載後請參照根目錄下的`微積溯源.tex`內的字體設定，找齊字體扔在根目錄下，然後拿XeLaTeX編譯即可。事實上，由於NSKernel懶惰的本質，編譯好的PDF文件也在repo裏，可自行取用。

本項目歡迎任何人貢獻，如果您有好的patch或者建議，可以直接提交pull request或提issue，我們可以一起討論並提升最終的文字與排版質量。

## 目前進度

文字上：目前已經排好了序，正文第一章進行了一半。
排版上：目前仍未能'''優雅'''地解決以下問題：`chapter`頁默認𤔡`plain`（我們想要`fancy`，目前通過在`chapter`命令下面直接插入`thispagestyle`解決）；左右footer設定分別𤔡章節名和小節名，然而在序言等沒有小節的地方，我們希望兩側都顯示章節名（目前考慮定義新的pagestyle，但是這也不算優雅吧）
代碼上：主代碼文件可以稱𤔡髒亂差的典範，基礎設定還需重新整頓，包括清除多餘設定和按類型整理其餘設定。
