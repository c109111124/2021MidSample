# 第一大題 
## (a) 小題
### 1. 利害人關係表
|利害關係人|目標|
|------|------|
|客戶|1.可觀看產品分類頁面，並於各個產品分類頁面，觀看該分類各個產品的圖片與產品敘述，但不得進行使用購物車|
||2.完成註冊可進行登入，登入後得以使用購物車功能挑選產品並產生訂單|
||3.當訂單成立後，可與ΟΟ銀行所提供的金流驗證系統，進行信用卡轉帳，最後完成訂單下訂|
||4.完成註冊的客戶完成訂單後，即可查詢該員過往訂單|
|瀏覽者|1.可觀看產品分類頁面，並於各個產品分類頁面，觀看該分類各個產品的圖片與產品敘述，但不得進行使用購物車|
|公司人員|1.客戶及公司人員都需於前台進行註冊(email)登記，並由已經註冊的公司人員或系統維護人員於後台進行審核註冊|
||2.已註冊的公司人員可進入後台進行訂單管理|
||3.可查詢所有人的所有訂單，並觀看訂單內某會員買了什麼產品|
||4.已註冊的公司人員或系統維護人員藉由登入後亦可修改訂單狀態|
|名系統維護人員|1.客戶及公司人員都需於前台進行註冊(email)登記，並由已經註冊的公司人員或系統維護人員於後台進行審核註冊|
||2.已註冊的系統維護人員藉由登入後，可進入後台進行訂單管理|
||3.可查詢所有人的所有訂單，並觀看訂單內某會員買了什麼產品|
||4.已註冊的公司人員或系統維護人員藉由登入後亦可修改訂單狀態|

### 2. 事件表
#### 霓薇公司商品購買平台-前台系統之事件表
|事件名稱|使用案例名稱|
|------|------|
|能讓客戶登記個人基本資料與聯絡訊息|客戶註冊作業|
|能讓客戶修改個人基本資料與聯絡訊息||
|客戶註冊後可查詢過往訂單||
|能讓公司人員登記個人基本資料與聯絡訊息|公司人員註冊作業|
|能讓公司人員修改個人基本資料與聯絡訊息||
|能讓客戶及參與者觀看圖片及敘述|產品查詢作業|
|客戶可登入系統|客戶登入作業|
|客戶登入後可使用購物車選擇產品並產生訂單||
|客戶能夠登入會員|會員註冊作業|
|客戶能夠接收及發送email給平台|平台溝通作業|
|客戶可透過系統進行信用卡轉帳|平台線上付款系統|

#### 霓薇公司商品購買平台-後台系統之事件表
|事件名稱|使用案例名稱|
|------|------|
|已註冊的公司人員或系統維護人員於後台進行審核註冊|公司人員(系統維護人員)審核作業|
|公司人員或系統維護人員可登入系統|公司人員(系統維護人員)登入作業|
|公司人員或系統維護人員登入後，可進入後台進行訂單管理||
|公司人員或系統維護人員可查詢所有人的所有訂單|檢視客戶資料|
|公司人員或系統維護人員可觀看訂單內某會員買了什麼產品||
|公司人員或系統維護人員可修改訂單狀態|修改客戶訂單|
|公司人員或系統維護人員可查看產品成本|系統費用估算作業|
|公司人員或系統維護人員可查看公司營業額||
|平台能夠接收客戶email資訊|客戶溝通作業|
|能夠提供收款及付款|平台線上付款系統|


## (c) 小題
### 1. 寫出使用案例
#### 客戶註冊作業使用案例
<table>
    <tr>
        <td>用案例名稱</td>
        <td>客戶註冊作業</td>
    </tr>
    <tr>
        <td>使用案例描述</td>
        <td>讓客戶登記個人基本資料與聯絡訊息</td>
    </tr>
    <tr>
        <td>主要參與者</td>
        <td>使用者</td>
    </tr>
    <tr>
        <td>利害關係人與目標</td>
        <td>客戶：完成註冊的客戶可產生訂單，也可查詢過往訂單<br>
          系統管理員：登入後可查詢所有人的所有訂單亦可修改訂單狀態</td>
    </tr>
    <tr>
        <td>前置條件</td>
        <td>客戶需於前台進行註冊(email)登記</td>
    </tr>
    <tr>
        <td>後置條件</td>
        <td>並由已經註冊的公司人員或系統維護人員於後台進行審核註冊</td>
    </tr>
    <tr>
        <td>主要成功情節</td>
        <td>1.客戶於前台進行註冊(email)登記，並由已經註冊的公司人員或系統維護人員於後台進行審核註冊<br>
            2.以完成註冊的客戶才可進行登入，登入後才得以使用購物車功能挑選產品並產生訂單<br>
            3.當訂單成立後，將與ΟΟ銀行所提供的金流驗證系統，進行信用卡轉帳，最後完成訂單下訂<br>
            4.當完成註冊的客戶完成訂單後，即可查詢該員過往訂單
      </td>
    </tr>
    <tr>
        <td>例外情節</td>
        <td>*a.當出現盜用帳號或者盜用交易資料問題:<br>
            1.密碼不要太簡單或多帳號使用相同密碼，容易被猜出密碼<br>
            2.確保公共電腦使用網站是否未登出，否則有帳號遭冒用的風險<br>
            3.小心透過郵件寄送偽造網站的連結，引誘使用者輸入登入，洩漏帳號密碼<br>
            4.注意資料存取控管不嚴，造成資料無意外洩<br>
            5.不要使用委外開發，因經費不足，只驗收功能，未要求安全品質的軟體<br>
      </td>
    </tr>
    <tr>
        <td>其他需求</td>
        <td>1.註冊須以(email)登記<br>
            2.密碼需有八位數，並包含英文大小寫及標點符號<br>
            3.須登記聯絡方式<br>
      </td>
    </tr>
</table>|

