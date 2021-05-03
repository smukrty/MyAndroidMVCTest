# MyAndroidMVCTest
AndroidMVCTest
MVC

MODEL

管理應用程序的數據，邏輯和規則。
模型負責管理應用程序的數據。

VIEW

UI設計，如何將數據顯示到USER屏幕。
視圖表示以特定格式表示數據。

CONTROLLER

控制器通常是一塊，它控制用戶執行的所有任務/事件，例如事件處理，導航，模型與視圖之間的通信發生在MVC的控制器中。
控制器接收輸入，對其進行驗證，然後將經過驗證的輸入傳遞給模型。


使用LoginController類創建了一個對象，該類幫助我們使用OnLogin方法在按鈕按下時發送用戶輸入的數據，然後檢查所有用戶輸入字段是否成功均返回Validation返回結果。
