---
title: "winOS"
linkTitle: "winOS"
weight: 3
description: >
  Here's where your user finds out if your project is for them.
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}



* [Getting Started](/getting-started/): Get started with $project
* [Examples](/examples/): Check out some example code!









### Setting App
![](/img/v2red-winos-01.jpg)
open app

![](/img/v2red-winos-02.jpg)

click menu

![](/img/v2red-winos-04.jpg)

click subscription setting

![](/img/v2red-winos-05.jpg)

click + butten

![](/img/v2red-winos-06.jpg)

Paste copied link in url box.

![](/img/v2red-winos-07.jpg)

input any remark name. then click check mark

![](/img/v2red-winos-08.jpg)

Back to homepage, click 3 dot , and click Update subscription

![](/img/v2red-winos-09.jpg)


select node you like and click v button

![](/img/v2red-winos-10.jpg)

app asking permission to take control of your network setting, click OK

![](/img/v2red-winos-011.jpg)

if you got green ! Congrat! let's test 'youtube.com'

![](/img/v2red-winos-012.jpg)

![](/img/v2red-winos-013.jpg)


![](/img/v2red-winos-014.jpg)

![](/img/v2red-winos-015.jpg)







<header class="major">
<h3>WINDOWS設備V2RAY使用教程</h3>
前言：您需要確保網絡暢通，windows7以上系統，大致流程為下載軟件，配置節點信息，開始使用。如果您仔細閱讀並遵從所有步驟，一般僅需10－15分鐘。
當然，您還需要可用的節點信息，一般可從v2ray提供商頁面獲取。

</header>

<hr />

<h4>第一步，下載用於WINDOWS設備的V2RAY軟件</h4>
點擊此處下載軟件壓縮包，下載後解壓至任意目錄
<div class="table-wrapper">
<table>
<thead>
<tr>
<th>描述/DESCRIPTION</th>
<th>鏈接/LINKS</th>
</tr>
</thead>
<tbody>
<tr>
<td>32位和64位版本（最新版包含V2Ray核心）</td>
<td><a href="https://book.v2rayx.org/download/v2rayN-windows.zip" target="_blank" rel="noopener">Here</a></td>
</tr>
</tbody>
</table>
</div>
值得注意：軟件由兩個部份組成，一部分為v2ray核心程序，另外一部分為v2ray客戶端界面程序，我們為了方便起見，已合併兩部分並形成壓縮包（即上面提供的壓縮包文件），並且隔日同步更新Github最新版本。如果您不放心或者需要所有版本，可參考下面鏈接前往Github頁面獲得最新程序，下載解壓，並確保解壓後的文件位於同一個文件夾，切記。
<div class="table-wrapper">
<table>
<thead>
<tr>
<th>描述/DESCRIPTION</th>
<th>鏈接/LINKS</th>
</tr>
</thead>
<tbody>
<tr>
<td>v2ray核心程序—v2raycore，請注意區別64位和32位版本</td>
<td><a href="https://github.com/v2ray/v2ray-core/releases" target="_blank" rel="noopener">Here</a></td>
</tr>
<tr>
<td>v2ray界面程序—v2rayN</td>
<td><a href="https://github.com/2dust/v2rayN/releases" target="_blank" rel="noopener">Here</a></td>
</tr>
<tr>
<td>v2ray界面程序—v2rayW，於v2rayN作用相同，二者選其一即可</td>
<td><a href="https://github.com/Cenmrev/V2RayW/releases" target="_blank" rel="noopener">Here</a></td>
</tr>
</tbody>
</table>
</div>
其他：程序運行需要Microsoft .NET Framework 4.5或者更高版本，如果提示相關問題無法運行，請前往Microsoft官網獲取下載安裝相應軟件，<a href="http://go.microsoft.com/fwlink/p/?LinkId=245484" target="_blank" rel="noopener">參考鏈接</a>
<h4>第二步，打開程序文件V2RAYN.EXE，配置節點信息</h4>
目前主要有三種配置節點信息的方法，可以根據妳的習慣和需要選擇
<div class="table-wrapper">
<table>
<thead>
<tr>
<th>方法/METHOD</th>
<th>描述/DESCRIPTION</th>
<th>前往/GO</th>
</tr>
</thead>
<tbody>
<tr>
<td>訂閱方式/Subscription</td>
<td>配置訂閱服務器，可一次性從商家獲取最新的所有節點信息，並可每次啟動自動更新，推薦</td>
<td><a href="https://book.v2rayx.org/index.html#subscription">Here</a></td>
</tr>
<tr>
<td>掃二維碼配置/Scan</td>
<td>通過掃描屏幕中的二維碼，自動配置，每次僅配置單個節點</td>
<td><a href="https://book.v2rayx.org/index.html#scan">Here</a></td>
</tr>
<tr>
<td>手動配置/Manually</td>
<td>增加新節點，並逐一配置相關節點信息</td>
<td><a href="https://book.v2rayx.org/index.html#manually">Here</a></td>
</tr>
</tbody>
</table>
</div>
<h5 id="subscription">方法一，訂閱方式</h5>
打開應用程式v2rayN.exe，注意是v2rayN不是v2ray，點擊“訂閱”－“訂閱設置”
<div class="image main"><img src="https://book.v2rayx.org/images/win-subscribe-01.png" alt="" /></div>
輸入備註和地址信息，備註可自定義，一般填提供商名稱，方便識別，地址填商家提供的訂閱地址，確定保存
<div class="image main"><img src="https://book.v2rayx.org/images/win-subscribe-02.png" alt="" /></div>
點擊“訂閱”－“更新訂閱”，可立即一次性獲取該訂閱來源的所有節點信息

選擇任意節點，右下角任務欄，點擊程序圖標，調出菜單，確保勾選“啟用http代理”，以及選擇一種代理模式
<div class="image main"><img src="https://book.v2rayx.org/images/win-manually-03.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試
<h5 id="scan">方法二，掃碼配置</h5>
首先網頁上打開v2ray節點的二維碼圖片

然後打開應用程式v2rayN.exe，注意是v2rayN不是v2ray，點擊“服務器”－“掃描屏幕上的二維碼”
<div class="image main"><img src="https://book.v2rayx.org/images/win-scan-01.png" alt="" /></div>
程序自動識別二維碼並導入服務器節點信息

選擇節點，右下角任務欄，點擊程序圖標，調出菜單，確保勾選“啟用http代理”，以及選擇一種代理模式
<div class="image main"><img src="https://book.v2rayx.org/images/win-manually-03.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試
<h5 id="manually">方法三，手動配置</h5>
打開應用程式v2rayN.exe，注意是v2rayN不是v2ray，點擊“服務器”－“添加Vmess服務器”
<div class="image main"><img src="https://book.v2rayx.org/images/win-manually-01.png" alt="" /></div>
根據提供商提供的節點信息，填入地址／端口／用戶ID／額外ID，別名可自命名，然後確定保存
<div class="image main"><img src="https://book.v2rayx.org/images/win-manually-02.jpg" alt="" /></div>
右下角任務欄，點擊程序圖標，調出菜單，確保勾選“啟用http代理”，以及選擇一種代理模式
<div class="image main"><img src="https://book.v2rayx.org/images/win-manually-03.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試