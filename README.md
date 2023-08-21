## 資展國際C#微軟班-147期第4組-期末專題(福祿獸寵物商城)


### Demo連線設定：
#### App.config =>
"ConnectionStrings": {  
  "GraduationTopicConnection": "Data Source=.;Initial Catalog=GraduationTopic;User ID=sa6;Password=sa6;Integrated   Security=True;TrustServerCertificate=true;MultipleActiveResultSets=true"  
},  
"MailSettings": {  
    "Mail": "furrystore45@gmail.com",  
    "Password": "bkjswjcpssrvejgh",  
  },  
"PayPalOptions": {  
  "ClientId": "AZxEmrPk2ON-B6KLx0RLV_wJIh2g_Q5Hpz0T3f0WSTp1NHtaNbVNjZ5mQ1jjce2h9xt1pYWt-1LR0S5x",  
  "ClientSecret": "EOv1xxrGLeT9jiA6x6ECAPwzgStSIUlBc7kJCCucWZfxe1NgyMOuUHE7OENQnDnALQqpAMoZlPF3YA-P"  
}  
#### Models/LinePay/LinePayService =>
private readonly string channelId = "2000393663";  
private readonly string channelSecretKey = "4770917b92fee21968eb314291424734";  




### 個人參與
#### 負責：
* Project Owner
* 專案建置與架構劃分
* 版控與分支整合
* 資料庫建置與假資料生成
#### 製做功能：
* 首頁與前後台Layout
* 購物車系統
* 購買系統(串接paypal與linepay)
* 推薦商品Partial View
* 後台員工與權限系統
* 後台統計系統
* 後台熱門推薦排序系統
* 元件製做(bootstrap驗證prototype, animateCSS 動畫prototype,sha256 extend method...等)


