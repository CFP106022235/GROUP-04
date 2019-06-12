# GROUP-04
## I. 主題
   光纖架設與路徑作圖
## II. 成員
1.郭理全 (106022235)<br/>
2.劉柏暄 (106022125)<br/>
3.房昀凱 (106022122)<br/>
4.陳映全 (106022272)<br/>

## III. 目標
1.輸入材質的折射率，計算出光線入射所需的最小角度為何。<br/>
2.輸入光纖彎折的曲率與位置，讓程式判斷光訊號是否能順利傳送過去，會不會有光線的損害。<br/>
3.畫出光在彎道中的路徑圖。<br/>
4.校正直線長度，以利重複測量。<br/>

## IV. 程式設計想法
註:以2維幾何光學來做<br/>
1.給定光疏光密介質折射率<br/>
2.利用全反射公式找出臨界角<br/>
3.給定最初入射角度、內彎半徑、軌道寬度、直線區域長度<br/>
4.利用三角函數運算取得彎道最初的光線直線方程式f1(座標化)<br/>
5.輸入彎道角度<br/>
6.利用f1以及全反射角，畫出最終軌跡圖。<br/>
7.依據結果顯示"傳輸成功"或"彎道產生資訊損失"<br/>
8.將最後彎道光線方程式進行座標轉換，得到下次模擬所需的"入射角度"和"校正長度"<br/>
9.以"後半直線資訊損失"提示辨別第2段直線是否會無法全反射<br/>
10.重複執行<br/>

## V.使用方式
開啟final_project.ipynb，按下執行，接著依照要求輸入資訊(無輸入則為預設值)，結果會自動顯示在下方。

## VI. 分工
郭理全--報告製作、彎道區段設計、程式修飾<br/>
劉柏暄--作圖設計、改良作圖方式<br/>
房昀凱--彎道區段設計、改良作圖方式<br/>
陳映全--主題提供、簡報製作、直線區段設計、程式修飾<br/>

PPT連結
https://docs.google.com/presentation/d/1acoNoffpBrhz62TRQPPjx288jlWsYWZ-hVAANfm90ZI/edit?usp=sharing
