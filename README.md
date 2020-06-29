# 全自動老闆偵測警報器
## <br>Team Members
 1.106820003 潘建蒼<br>
 1.106820038 林庭伃<br>
 2.106820046 凃昱安
 
## Problem Statement

### 1.專案簡介
<pre>
    RPG(角色扮演)遊戲是一種遊戲類型，在遊戲中，玩家扮演虛擬世界中的一個或者幾個角色進行遊戲，玩家通過操控遊戲角色與敵人戰鬥，提升
等級、收集裝備和完成遊戲設置的任務，並體驗劇情。通常這類遊戲都是由玩家扮演角色在遊戲世界中漫遊，而一路上的各種遭遇則是玩家人物成長
及遊戲進行的重要關鍵所在。
</pre>

### 2.何為Arduno
<pre>
    Arduino Leonardo是基於ATmega32u4一個微控制器板。它有20個數字輸入/輸出引腳（其中7個可用於PWM輸出、12個可用於模擬輸入），一個
16 MHz的晶體振蕩器，一個Micro USB接口，一個DC接口，一個ICSP接口，一個復位按鈕。它包含了支持微控制器所需的一切，你可以簡單地通過把
它連接到計算機的USB接口，或者使用AC-DC適配器，再或者用電池來驅動它。


                              <img src="https://github.com/a0935210570602/Electronics_Lab/raw/master/Arduno.jpg" width="40%" height="40%" />
                                             (圖一) Arduino Leonardo
</pre>
        
### 3.材料

名稱           | 數量  
:--------------:|:-----:
Arduno  Leonardo  | 1個
超音波感測器    | 1個
單芯線  | 11條
RGB LED | 1個
100K電阻  | 1個
可變電阻  | 3個
蜂鳴器  | 1個

### 4.電路設計
<img src="https://github.com/a0935210570602/Electronics_Lab/raw/master/Schematic_%E9%9B%BB%E5%AD%90%E5%AD%B8%E5%AF%A6%E7%BF%92%E5%A0%B1%E5%91%8A_2020-06-29_16-38-28.png" width="120%" height="120%" />

### 5.demo
<pre>
1. 角色動作：
    採集資源：玩家可以使用採集功能鍵，將遇到的物資採集進背包裡。
    挖掘物資：玩家必須裝備十字搞和圓鍬等工具，才能對石頭和植物進行挖掘的動作。
    攻擊怪獸：玩家可以透過武器來施放各種技能，在沒有武器的情況下只能用最低的攻擊力攻擊怪物。
    合成物資：玩家可以透過左邊欄位的物品合成欄，來合成所需物資，但須具備該物資所需材料。
    使用背包中物件 : 玩家可以透過點擊食用食物、裝備道具、種植植物。

2. 遊戲定義
    遊戲中的一天：等於現實的2分鐘

</pre>

### 6.參考資料
[https://kknews.cc/digital/lvo496e.html](https://kknews.cc/digital/lvo496e.html)<br>
[https://easyeda.com/editor?authenticate=force#id=588b2fc6eb914a76816edad05295735d|!03754f9d5f5745dfaa544d9984f19bb0](https://easyeda.com/editor?authenticate=force#id=588b2fc6eb914a76816edad05295735d|!03754f9d5f5745dfaa544d9984f19bb0)
