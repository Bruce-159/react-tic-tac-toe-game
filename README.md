[🔗 GitHub 部署頁面](https://bruce-159.github.io/react-tic-tac-toe-game/)

這是一個使用 React 製作的井字遊戲（Tic-Tac-Toe），作為我學習 React 過程中的練習專案。專案涵蓋了多個 React 核心概念，例如 component 組合、props、state 管理、事件處理、條件渲染、狀態提升等，並採用了模組化與可維護的程式架構。

此專案涵蓋以下 React 關鍵技術與開發觀念：

Component-Based Architecture  
每個畫面區塊皆封裝成獨立的元件（如 Player、GameBoard、GameOver 等)    

Two-Way Binding（雙向綁定）  
利用 useState() 搭配 onChange 與 value 綁定達成雙向資料流    

Lifting State Up（狀態提升  
子元件（如 Player、GameBoard）僅透過 props 接收狀態與操作函式，避免狀態交錯、確保資料一致性）    

Derived State & Immutability  
每次更新格子內容皆使用不可變資料操作（map() 與展開運算子），確保 React 正確觸發重渲染    


##預覽畫面

![image](https://github.com/user-attachments/assets/a0b0daf4-caab-47ac-a9f2-6414280aae0a)
![image](https://github.com/user-attachments/assets/4220bfd0-bc96-4e83-b2f1-15dc9039d0c0)



