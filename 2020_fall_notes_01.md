2020秋季第一場研讀紀錄
===

###### tags: `TCPSR`,`Reproducibility`

:::info
- **研讀主題:** 解析分析策略的過度彈性
- **地點:** [社會創新實驗中心](https://silab.sme.gov.tw/) 202會議室
- **youtube直播連結:** https://youtu.be/LdumvtaMuNQ
- **日期時間:** Aug 14, 2020 11:00 AM (CST)
- **討論流程**
1. 文獻領講 `15min`
	> [name=CSC]簡報
2. 討論衍生問題 `45min`
	> [name=CSC]發動討論
3. 迷你課程 `45min`
	> [name=CSC]講授
4. 自由討論
- **參與者簽到:** [表情符號包](https://github.com/ikatyang/emoji-cheat-sheet)
    - :man:陳紹慶 (CSC)
    - :man:龔俊嘉 (cck)
    - :heart:林君昱 (CYL)
    - :woman:周蔚倫 (cwl)

- **領講人:** CSC
- **研讀文獻:** - [Silberzahn et al. (2018)](https://doi.org/10.1177/2515245917747646)

:::

## 文獻領講 

- [領講簡報](https://hackmd.io/@CSC/H1WIBm9WD)

:dart: 今天準備要開始一項新研究，你如何決定分析方法？
---
- (討論紀錄)
CWL: 1.共識，同領域多數人用的方法; 2. 

CYL: 我一般進行的是較單純的t test, ANOVA之類的實驗設計，流程上大概會先想要問的研究問題為何，有什麼假設（用IV, DV, 其關係的方式）寫出，然後思考此假設用統計分析的結果會有何預期or預期結果圖、eg 預期何主要效果、交互作用顯著etc…
但讀了這篇新的收獲是特別再想了一下分析中的許多可能的choices（eg p339左：Would you treat
each red-card decision as an independent observation?
How would you address the possibility that some referees
give more red cards than others?... 但我多想到的是 referee本人的膚色是否會影響）.
另外可能也考慮對一個資料都盡量先規劃好嘗試不同種的分析方式，甚至找別人來合作做不同分析。
re:CCK:我也傾向先想好是探索式或驗證式的研究。

CCK: 會根據計畫的方向決定。Silberzahn挑的題目結論很明確，挑選的方法有範圍侷限。如果計畫主題預期的結果有彈性空間，很難決定具體的分析方法。除非文獻有具體的資訊，才能決定。

CSC: 目前也會考慮先做一些 data 的 model simulation, 看看結果應該長什麼樣子...

:books: 如果分析結果不如預期，你有怎麼樣的處理經驗？
---
- (討論紀錄)

CSC: 以前會增加樣本到顯著為止，現在會思考是不是本來就很難發現正面結果

cck: 如果是自己的計畫，通常不管是學生或自己的分析結果，若不符預期的話，第一個反應是：我/學生有那裡做錯了嗎? 通常第一次遇到結果不符預期，自己的反應是檢討自己...然後再二再三的檢查(我們有時叫 sanity check) 後，仍然覺得自己的分析沒做錯..就會開始懷疑，是不是對方的說法(或先前研究預期的假設)有問題?
G*Power的使用經驗：有嘗試事前估計，但是不符合設計需求。CSC 建議Daniel Lakens 的 [ANOVApower](https://github.com/Lakens/ANOVApower)

cyl:
這是我給學生的一些介紹，也歡迎參考指教：
https://docs.google.com/document/d/1Cwaqj8PuKhD6H9-zpiYdMAeoMzauThHPWoCUthFtOf0/edit#bookmark=kix.xm6wo4ub0avm
Gilad Feldman也有很豐富的資源「Effect size, confidence intervals, and power analyses collaborative guide - Google 文件」：
https://docs.google.com/document/d/1_vNjPCI7H52T8tav1reYgWx6puMT03JZVY1wvEPHrWU/edit

CWL: 確認是否有 outliers 的影響；沒時間理就擺著不管

CYL: 確認是否有控制不好或confounds，或分析步驟有錯，思考power是否夠，結果是否穩定、能被replicate，或此效果是否真的夠robust? boundary為何？以前我若得null results或太亂無法解釋有可能就先埋在抽屜中了…



:mag: 最後討論到的三個QRP議題，你曾有相關的經驗嗎？
---
- (討論紀錄)
cck: 有關第一個 p-hacking, 個人覺得仍是無所不在...as a researcher，便已是如此，另外最近也有as a reviewer的經驗，作者努力呈現結果，但只要是顯著邊緣，仍會以(差一點)的心態，對作者要求這要求那，反映了 implicitly 仍是把 p<.05 當成golden rule.

-CYL: 從文章中對歧路花園的說明，我的理解是在資料還沒收完時即先分析，看結果如何、做假設…，然後影響到、決定最後做何種分析，不知是否正確？

-CWL: 曾經歷的Lab文化有意無意鼓勵p-hacking。

-cyl: 讀完的心得&問題：光只決定一種方法的預註冊可能還不夠，要多種？但要如何得知哪個才對、最好呢？（eg 以本篇為例？）

addition Q: so as outsiders, 到底是有無這樣的現象? skin tone affects the judged red-cards? majority of answers are 'yes'?

:closed_book: 迷你課程大綱
--
### 單元1: markdown 動態文件編輯入門 
- markdown是什麼?
- 支援markdown的軟體與平台
- 語法規則，以[HackMD教學手冊](https://hackmd.io/c/tutorials-tw/%2Fs%2Ftutorials-tw)說明
- 活動紀錄製作示範

### 單元2: 如何準備資料編碼簿
- 2012-2013歐洲職業足球比賽紀錄[資料集](https://osf.io/fv8c3/)與[code book](https://osf.io/9yh4x/)
- 變項欄位命名
    - 命名規則
    - 變項間關聯性
- 定義變項值域
    - 連續數值
    - 類別數值
    - 定義遺漏值 

### 自由討論紀錄

[Standard Reviewer Statement for Disclosure of Sample, Conditions, Measures, and Exclusions](https://osf.io/hadz3/)


