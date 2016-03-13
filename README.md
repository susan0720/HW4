# HW4

## Q1. Distance Transform
##Introduction   
在二原色圖中，找到和邊界最近的距離，分別從上方和下方來測定與邊界的最小距離。
##Concept Development  
先把二元圖轉成灰階，再把不是白色的地方標記起來，比較從上方和下方測定的邊界最小距離，最後再根據距離給pixel值。
##Implementation   
先將圖片轉為灰階會比較好進行；之後將灰階值小於250(人眼辨識不出來差一點點的pixel值，圖片本身有一點誤差，所以把範圍放寬一點)的判斷為非白色，只要是非白色的像素做一次轉換，上方是比較{左、左上、上、右上}，而下方是比較{右下、左下、下、右}
##Discussion   
##Reference   
1. http://rgyyhawu.pixnet.net/blog/post/19314913-distance-transform(dt)%E6%BC%94%E7%AE%97%E6%B3%95--perl
2. http://www.cnblogs.com/oomusou/archive/2007/02/25/655759.html



## Q2. Blending
1. Implement multiband blending 
2. Try to blend on your own photos.
