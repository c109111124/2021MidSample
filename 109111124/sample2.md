# 第二大題 
## (a) 小題
### 1. 利害人關係表
|利害關係人|目標|
|------|------|
|業務員|1.業務員利用 Line 加入群組後，由業務員利用 Line 對欲加入會員發送註冊連結|
||2.會員填寫完註冊資料後與拍照後，需由業務員確認|
||3.業務員可修改部分會員資料|
|會員|1.會員填寫完註冊資料後與拍照後，因為會員相關權利關係，需由業務員確認，才得以成為會員|
||2.會員可修改部分會員資料|
||3.成為會員後，若要進入場地，將藉由第三方寫好的臉部辨識系統與註冊資料中的拍照的照片比對，若成功則可進入，若失敗則不可進入|
### 2. 事件表
#### 城集行銷公司臉部辨識會員系統-會員系統之事件表
|事件名稱|使用案例名稱|
|------|------|
|能讓會員登記個人基本資料與聯絡訊息|會員註冊作業|
|能讓會員修改個人基本資料與聯絡訊息||
|會員可修改部分會員資料|會員查詢資料|
|會員註冊後可查詢過往紀錄||
|會員可登入系統|會員登入作業|
|會員能夠接收及發送簡訊給系統合作之銀行|系統溝通作業|
|會員每月需繳交付費金額|系統線上付款作業|

#### 城集行銷公司臉部辨識會員系統-業務員系統之事件表
|事件名稱|使用案例名稱|
|------|------|
|業務員利用 Line 加入群組|業務員註冊作業|
|業務員利用 Line 對欲加入會員發送註冊連結|業務員發送註冊申請|
|會員填寫完註冊資料後與拍照後，需由業務員確認|業務員審核作業|
|業務員可修改部分會員資料|業務員查詢與修改作業|
|業務員可查詢會員過往紀錄||
|業務員可登入系統|業務員登入作業|
|系統利用合作之銀行對會員進行簡訊發送|會員溝通作業|
|系統可接收會員每月需繳交付費金額|系統線上收款作業|


## (c) 小題
### 1. 寫出使用案例
#### 會員註冊作業使用案例
<table>
    <tr>
        <td>用案例名稱</td>
        <td>會員註冊作業</td>
    </tr>
    <tr>
        <td>使用案例描述</td>
        <td>讓會員登記個人基本資料與聯絡訊息及拍照</td>
    </tr>
    <tr>
        <td>主要參與者</td>
        <td>使用者</td>
    </tr>
    <tr>
        <td>利害關係人與目標</td>
        <td>會員：成為會員後，若要進入場地，將藉由第三方寫好的臉部辨識系統與註冊資料中的拍照的照片比對，若成功則可進入，若失敗則不可進入<br>
          系統管理員：能將減少讓城集公司於檢查欲進入場地人員是否為會員再放行讓其進入之時間</td>
    </tr>
    <tr>
        <td>前置條件</td>
        <td>業務員利用 Line 加入群組後，由業務員利用 Line 對欲加入會員發送註冊連結</td>
    </tr>
    <tr>
        <td>後置條件</td>
        <td>當會員填寫完註冊資料後與拍照後，因為會員相關權利關係，需由業務員確認，才得以成為會員</td>
    </tr>
    <tr>
        <td>主要成功情節</td>
        <td>1.業務員利用 Line 加入群組後，由業務員利用 Line 對欲加入會員發送註冊連結，當會員填寫完註冊資料後與拍照後，因為會員相關權利關係，需由業務員確認，才得以成為會員<br>
            2.，將藉由第三方寫好的臉部辨識系統與註冊資料中的拍照的照片比對，若成功則可進入，若失敗則不可進入<br>
            3.該臉部辨識會員系統也需要與華鐘電信與騎華銀行共同合作，使臉部辨識會員系統在會員每月需付費的前一周，先透過華中電信對會員進行簡訊發送<br>
            4.若會員於期限內若未能付費，則將騎華銀行會於過期隔天給予系統發起通知臉部辨識會員系統，再由系統利用華鐘電信對會員進行簡訊發送<br>
            5.該功能將減少讓城集公司於檢查欲進入場地人員是否為會員再放行讓其進入之時間亦降低業務員需個別對帳之需求
      </td>
    </tr>
    <tr>
        <td>例外情節</td>
        <td>*a.辨識時的不穩定以及侵犯隱私:<br>
            1.人臉會隨著年齡增長或整容而改變，<br>
            2.光線角度和表情的不同都可能影響辨識結果<br>
            3.透過人臉辨識，有特殊狀況時立刻通知站務或警務人員處理。不過，消息一出，人臉辨識功能引發爭議，外界認為有侵犯隱私疑慮<br>
            4.有人臉辨識系統誤判而抓錯人的事件，大多以男性和白人為主，因此在識別女性或有色人種時有較大的錯誤機會<br>
      </td>
    </tr>
    <tr>
        <td>其他需求</td>
        <td>1.註冊須完整寫完註冊資料後並拍照<br>
            2.密碼需有八位數，並包含英文大小寫及標點符號<br>
            3.須登記聯絡方式<br>
            4.照片規格需以證件照模式的JPEG檔格式
            5.需在規定日期內繳交會員入會金額
      </td>
    </tr>
</table>|
