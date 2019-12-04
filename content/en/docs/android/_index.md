---
title: "Android"
linkTitle: "Android"
weight: 9
description: >
  Low level Android docs for your project.
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}



---
title: "iOS"
linkTitle: "iOS"
weight: 1
description: >
  What does your user need to understand about your project in order to use it - or potentially contribute to it? 
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}


### Prepare
If you read and follow all the steps, it usually only takes 10-15 minutes.
Of course, you also need the available node information, which can generally be obtained from the v2ray provider page.

sign up on v2red.com and buy plan that you like.

> iOS11 above

### Download & Install App


<blockquote>BifrostV <img src="https://www.v2ray.com/en/resources/android.svg" width="20" /></blockquote>
BifrostV is an Android app based on V2Ray core. It supports VMess, Shadowsocks, socks protocols.

Download: <a href="https://play.google.com/store/apps/details?id=com.github.dawndiy.bifrostv" target="_blank" rel="noopener">Play Store</a> | <a href="https://apkpure.com/bifrostv/com.github.dawndiy.bifrostv" target="_blank" rel="noopener">APK Pure</a>
<blockquote>V2RayNG <img src="https://www.v2ray.com/en/resources/android.svg" width="20" /></blockquote>
V2RayNG is an Android app based on V2Ray. It provides same feature set as V2Ray core.

Download: <a href="https://play.google.com/store/apps/details?id=com.v2ray.ang" target="_blank" rel="noopener">Play Store</a> | <a href="https://github.com/2dust/v2rayNG" target="_blank" rel="noopener">GitHub</a>

> Google play store is not avaliable on China Phone. you can download from official dev site or here. 



myserverDownload: <a href="http://v2red.com/files/public-docs/v2rayNG_1.1.12.apk" target="_blank" rel="noopener">Play Store</a> | <a href="https://github.com/2dust/v2rayNG" target="_blank" rel="noopener">GitHub</a>



### Get server infomation

Longin v2red.com and goto 'My service'

![](/img/v2red-ios-01.png)

click 'Services'

![](/img/v2red-ios-02.png)

click name of your plan

![](/img/v2red-ios-03.png)

click 'copy' of subscrition link

![](/img/v2red-ios-04.png)



### Setting App


| mode      | explain         |
|-----------|-----------------|
| Config  | only blocked connection(ex: facebook)  through node (Chinese site not through node) |
| Proxy  | all connection through node    |
| direct  | all connection NOT through node        |
| Secene  | see official website        |
> you can configure more detiles in setting. custimze filtering, please refer website















<h5 id="subscription">方法一，訂閱方式</h5>
打開V2RayNG，右上角點 <img src="https://book.v2rayx.org/images/andoird-settings-icon.png" alt="" height="15" /> ，調出菜單，點“訂閱設置”
<div class="image half"><img src="https://book.v2rayx.org/images/android-02.png" alt="" /></div>
地址(url)填寫提供商提供的訂閱地址，備註可自定義名稱，一般填提供商名稱，方便識別，右上角點勾保存
<div class="image half"><img src="https://book.v2rayx.org/images/android-03.png" alt="" /></div>
自動從訂閱地址獲取所有節點信息，您也可以在右上角菜單中，隨時手動“更新訂閱”

選擇任意已配置節點，點右下角圖標，啟動服務。稍等片刻，提示啟動服務成功
<div class="image half"><img src="https://book.v2rayx.org/images/android-04.png" alt="" /></div>
如果啟動過程彈出提示，請勾選“我信任此應用”，然後確定
<div class="image half"><img src="https://book.v2rayx.org/images/android-05.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試
<h5 id="scan">方法二，掃碼配置</h5>
首先在提供商網頁上打開v2ray節點的二維碼圖片

打開V2RayNG，右上角點“+”，選擇“掃描二維碼”
<div class="image half"><img src="https://book.v2rayx.org/images/android-06.png" alt="" /></div>
程序自動識別二維碼並導入服務器節點信息

選擇任意已配置節點，點右下角圖標，啟動服務。稍等片刻，提示啟動服務成功
<div class="image half"><img src="https://book.v2rayx.org/images/android-04.png" alt="" /></div>
如果啟動過程彈出提示，請勾選“我信任此應用”，然後確定
<div class="image half"><img src="https://book.v2rayx.org/images/android-05.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試
<h5 id="manually">方法三，手動配置</h5>
打開V2RayNG，右上角點“+”，選擇“手動輸入[Vmess]”
<div class="image half"><img src="https://book.v2rayx.org/images/android-07.png" alt="" /></div>
根據提供商提供的節點信息，填入地址／端口／用戶ID/AlterID，其他沒有不用改，remark可自命名，然後點“完成”
<div class="image half"><img src="https://book.v2rayx.org/images/android-08.png" alt="" /></div>
選擇任意已配置節點，點右下角圖標，啟動服務。稍等片刻，提示啟動服務成功
<div class="image half"><img src="https://book.v2rayx.org/images/android-04.png" alt="" /></div>
如果啟動過程彈出提示，請勾選“我信任此應用”，然後確定
<div class="image half"><img src="https://book.v2rayx.org/images/android-05.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試