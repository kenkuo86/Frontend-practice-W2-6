# Frontend-practice-W2-6

Q1.說明三個HTML5裡的標籤作用
●<main>
拿來放整個頁面中最重要的內容，不可以被包含在任何其他tag裡面(body除外)，而且一個頁面中只能出現一次。
用法：
  <main> 所有重要且只會在這個頁面出現一次的內容 </main>
●<mark>
拿來包住要強調的文字，可以另外在CSS設定樣式。
用法：
  <p>這句話裡面的重點就是<mark>這裡</mark></p>
  (CSS)
  mark{ 
  color: black;
  background-color: yellow;                 
  }
  //這樣設定就會出現黃底黑字
●<meter>
https://www.w3schools.com/tags/tag_meter.asp
用來設定出一段程度/進度條，有一些屬性值要設定：
必須設定的屬性：value
用法：
  <meter value="2" min="0" max="10"></meter><br>
  //在設定最大和最小值後把一個落在範圍內的值賦給value
  也可以像這樣：
  <meter value="0.6">60%</meter>
  就會跑出一條60%的圖
