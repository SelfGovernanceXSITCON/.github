# 顛覆傳統投票

## 競賽議題 & 子議題
- 團隊名稱：海碼戰團
- 成員姓名：[張銀軒](https://github.com/Argentum11), [吳𧙗葳](https://github.com/350016z), [黃見弘](https://github.com/wilsoncodehard)
- 競賽議題：公創新世代：學生力量與科技共創公民參與
    - 子議題：學生自治 X SITCON


### 專案簡介
- 用途/功能：

- 動機：<br>
  學校提供平台有以下缺點:
    1. 沒有RWD的教學務系統，對手機不離手的我們相當不友善。
    2. 投票通知在平常不會去看的地方，且通知非常晚，在我們還不熟悉政見時就要求我們進行投票。
    3. 投票過程繁雜，降低投票意願。<br>
 - 為此，我們開發了 **學生自製機器人**。
     - 平時潛伏在Discord社群中，要投票時直接傳訊息告訴你是時候要投票了，不怕錯失投票!
     - 投票直接在Discord進行，簡單方便，不用複雜的登入即可行使學生自治權利。
     - 自製 = 自治，學生的權益，學生自行捍衛。 

  

- 操作方式：
    - 環境設置
        1. 可以看到 .env 檔案新增了兩個 API，
            * OPENAI_API_KEY<br>
            此為必需新增的 API，否則無法與智慧城市對話。
            * LANGCHAIN_API_KEY<br>
            此為開發用 API，可以透過 LangSmith 看清楚整體 Chain 流程。可加可不加
        2. 必須把修改後的 .env 檔案複製進 Taipei-City-Dashboard-AI 資料夾裡
    - 使用者操作方式<br>
        只需點擊智慧城市按鈕，之後並可與之對話。

### 使用資源
- 企業資源：
    - { OpenAI }<br>
    我們所選用的模型。
- 公開資源：
    - {LangChain}<br>
    有了這個 package，可以更輕鬆的客製化我們的模型。

### 你還想分享的事情
- 開發過程
  - 我們在前端設計了一些看似無用實則無用的功能:3
  - 後端非常的炸裂，全部擠在一個 app.py 裡面
- 遇到的困難
  - 在進行這次的專案之前我們對開發幾乎一無所知，唯一清楚的只有我們想做的事
  - 原本以為只要 figma 用一用就好了，結果是要真的做出東西來。然後發現自己前端後端資料庫和網站原理都不懂，笑死。
- 非常好commit訊息，簡單明瞭!<br>
![image](https://hackmd.io/_uploads/SkfcTPvvA.png)

### 成果展示
- [專案介紹的投影片](SITCON_present.pdf)
- 功能截圖展示:
    - 選舉推播公告
        - 管理員輸入:

           <img src="https://github.com/Voting-Redefined/.github/assets/100845242/6e274288-4301-46b3-b42e-7f540711bf60" width="500"  alt="一張圖片">
           
        - 公告畫面如下:

           <img src="https://github.com/Voting-Redefined/.github/assets/100845242/9dc44346-98cc-465c-b7e7-7e333db67706" width="300" alt="一張圖片"> 
           
    - 選舉投票介面
        - 使用者輸入 `/vote` 開啟投票介面
          
          <img src="https://github.com/Voting-Redefined/.github/assets/100845242/882ab001-1488-4fe2-bed7-dac56fd9cc29" width="300" alt="一張圖片"> 


> SITCON Hackathon 2024 \_\_INIT\_\_
