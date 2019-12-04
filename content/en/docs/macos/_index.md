---
title: "macOS"
linkTitle: "macOS"
weight: 2
description: >
  What does your user need to know to try your project?
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}

Information in this section helps your user try your project themselves.

* What do your users need to do to start using your project? This could include downloading/installation instructions, including any prerequisites or system requirements.

* Introductory “Hello World” example, if appropriate. More complex tutorials should live in the Tutorials section.

Consider using the headings below for your macOS page. You can delete any that are not applicable to your project.

## Prerequisites

Are there any system requirements for using your project? What languages are supported (if any)? Do users need to already have any software or tools installed?

## Installation

Where can your user find your project code? How can they install it (binaries, installable package, build from source)? Are there multiple options/versions they can install and how should they choose the right one for them?

## Setup

Is there any initial setup users need to do after installation to try your project?

## Try it out!

Can your users test their installation, for example by running a commmand or deploying a Hello World example?



<header class="major">
<h3>OS X設備(MACBOOK)V2RAY使用教程</h3>
前言：您需要確保網絡暢通。下載軟件，配置節點信息，開始使用。
仔細閱讀並遵從所有步驟，一般僅需10－15分鐘。
當然，您還需要可用的節點信息，一般可從v2ray提供商頁面獲取。

</header>

<hr />

<h4>第一步，下載用於MAC設備的V2RAY軟件</h4>
目前僅有一款支持Mac點軟件V2RayX，可在本站下載，也可以前往Github下載
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
<td>V2RayX （最新版 Latest Version）</td>
<td><a href="https://book.v2rayx.org/download/V2RayX.app.zip" target="_blank" rel="noopener">本地下載</a></td>
</tr>
<tr>
<td>V2RayX （Github所有release版本）</td>
<td><a href="https://github.com/Cenmrev/V2RayX/releases" target="_blank" rel="noopener">Github Here</a></td>
</tr>
</tbody>
</table>
</div>
<h4>第二步，解壓下載的ZIP文件，得到V2RAYX文件</h4>
將V2RayX文件複製到應用程式，然後直接打開，在彈出的窗口點"install"進行安裝，此過程可能需要輸入系統密碼，授予相關權限，請放心
<div class="image half"><img src="https://book.v2rayx.org/images/mac-03.png" alt="" /></div>
如果打開程序，出現如下提示
<div class="image half"><img src="https://book.v2rayx.org/images/mac-01.png" alt="" /></div>
請前往“系統偏好設置”－“安全性和隱私”，點“仍要打開”，再點"install"安裝
<div class="image half"><img src="https://book.v2rayx.org/images/mac-02.png" alt="" /></div>
安裝完成後，可進入launchpad，找到V2RayX圖標打開
<h4>第三步，打開程序，配置節點</h4>
右上角出現V2RayX圖標，點擊圖標調出菜單，點Configure，進行節點設置

V2RayX暫時僅支持URL方式添加，或者手動配置添加，暫不支持訂閱以及二維碼方式添加
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
<td>URL方式/URL</td>
<td>輸入一個URL鏈接，即可完成一個節點配置，相對手動配置方便很多，推薦</td>
<td><a href="https://book.v2rayx.org/mac.html#url">Here</a></td>
</tr>
<tr>
<td>手動配置/Manually</td>
<td>增加新節點，並逐一配置相關節點信息</td>
<td><a href="https://book.v2rayx.org/mac.html#manually">Here</a></td>
</tr>
</tbody>
</table>
</div>
<h5 id="url">方法一，URL添加</h5>
打開程序，右上角出現V2RayX圖標，點擊圖標調出菜單，點Configure，進行節點設置
<div class="image half"><img src="https://book.v2rayx.org/images/mac-04.png" alt="" /></div>
點擊圖中紅色圈出的設置圖標，點擊import導入
<div class="image half"><img src="https://book.v2rayx.org/images/mac-07.png" alt="" /></div>
從提供商頁面複製節點URL，然後黏貼入彈出的輸入框，點OK
<div class="image half"><img src="https://book.v2rayx.org/images/mac-08.png" alt="" /></div>
回到節點配置頁面，可以看到已自動導入該節點信息，點OK

重複上述步驟即可導入多個節點
<div class="image half"><img src="https://book.v2rayx.org/images/mac-09.png" alt="" /></div>
再次調出菜單，確保servers已勾選可用節點，點"Load core"開啟V2RayX，一般選擇PAC Mode
<div class="image half"><img src="https://book.v2rayx.org/images/mac-10.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試
<h5 id="manually">方法二，手動配置</h5>
打開程序，右上角出現V2RayX圖標，點擊圖標調出菜單，點Configure，進行節點設置
<div class="image half"><img src="https://book.v2rayx.org/images/mac-04.png" alt="" /></div>
<h5 id="manually">方法二，手動配置</h5>
打開程序，右上角出現V2RayX圖標，點擊圖標調出菜單，點Configure，進行節點設置
<div class="image half"><img src="https://book.v2rayx.org/images/mac-04.png" alt="" /></div>
先點左下角"+"，增加節點。然後根據提供商提供的節點信息，填入address(服務器地址），後面是端口號，User ID對應UUID，以及alterID，其他如果沒有相關參數，無須修改

DNS處填8.8.8.8,8.8.4.4，點OK保存此節點
<div class="image half"><img src="https://book.v2rayx.org/images/mac-05.png" alt="" /></div>
再次調出菜單，確保servers已勾選可用節點，點"Load core"開啟V2RayX，一般選擇PAC Mode
<div class="image half"><img src="https://book.v2rayx.org/images/mac-06.png" alt="" /></div>
完成，可打開瀏覽器訪問網址測試

如果某些網址無法訪問，可嘗試Global Mode



<blockquote>V2RayW <img src="https://www.v2ray.com/en/resources/win.svg" width="20" /></blockquote>
Download: <a href="https://github.com/Cenmrev/V2RayW" target="_blank" rel="noopener">Github</a>
<blockquote>V2RayN <img src="https://www.v2ray.com/en/resources/win.svg" width="20" /></blockquote>
Download: <a href="https://github.com/2dust/v2rayN" target="_blank" rel="noopener">Github</a>
<blockquote>Clash for Windows <img src="https://www.v2ray.com/en/resources/win.svg" width="20" /></blockquote>
Download: <a href="https://github.com/Fndroid/clash_for_windows_pkg" target="_blank" rel="noopener">Github</a>
<blockquote>V2RayX <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /></blockquote>
Download: <a href="https://github.com/Cenmrev/V2RayX" target="_blank" rel="noopener">Github</a>
<blockquote>V2RayU <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /></blockquote>
Download: <a href="https://github.com/yanue/V2rayU" target="_blank" rel="noopener">Github</a>
<blockquote>V2RayC <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /></blockquote>
Download: <a href="https://github.com/gssdromen/V2RayC" target="_blank" rel="noopener">Github</a>
<blockquote>ClashX <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /></blockquote>
Download: <a href="https://github.com/yichengchen/clashX" target="_blank" rel="noopener">Github</a>
<blockquote>Qv2ray <img src="https://www.v2ray.com/en/resources/win.svg" width="20" /> <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /> <img src="https://www.v2ray.com/en/resources/linux.svg" width="20" /></blockquote>
Qv2ray: v2ray Cross-Platform GUI written in Qt, supports multi-language, connection edit and auto-check updates

Download: <a href="https://github.com/lhy0403/Qv2ray" target="_blank" rel="noopener">GitHub</a>

Website (Chinese): <a href="https://lhy0403.github.io/Qv2ray" target="_blank" rel="noopener">https://lhy0403.github.io/Qv2ray</a>
<blockquote>Mellow <img src="https://www.v2ray.com/en/resources/win.svg" width="20" /> <img src="https://www.v2ray.com/en/resources/apple.svg" width="20" /> <img src="https://www.v2ray.com/en/resources/linux.svg" width="20" /></blockquote>
Mellow is a rule-based global transparent proxy client for Windows, macOS and Linux.

Download: <a href="https://github.com/mellow-io/mellow" target="_blank" rel="noopener">Github</a>
<blockquote>Kitsunebi <img src="https://www.v2ray.com/en/resources/ios.svg" width="20" /></blockquote>
Kitsunebi is an iOS app based on V2Ray. It provides full functionality as V2Ray. It also supports importing and exporting V2Ray compatible JSON configuration.

Download: <a href="https://itunes.apple.com/us/app/kitsunebi-proxy-utility/id1446584073?mt=8" target="_blank" rel="noopener">iTunes</a>
<blockquote>i2Ray <img src="https://www.v2ray.com/en/resources/ios.svg" width="20" /></blockquote>
i2Ray is another iOS app based on V2Ray with easy-to-use UI design.

Download: <a href="https://itunes.apple.com/us/app/i2ray/id1445270056?mt=8" target="_blank" rel="noopener">iTunes</a>
<blockquote>Shadowrocket <img src="https://www.v2ray.com/en/resources/ios.svg" width="20" /></blockquote>
Shadowrocket is a generic VPN app. Is supports multiple protocols such as Shadowsocks, VMess, SSR etc.

Download: <a href="https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8" target="_blank" rel="noopener">iTunes</a>
<blockquote>Pepi (was ShadowRay) <img src="https://www.v2ray.com/en/resources/ios.svg" width="20" /></blockquote>
Pepi is V2Ray compatible app. Is is able create VPN connections based on VMess protocol, and communicate with any V2Ray servers.

Download: <a href="https://itunes.apple.com/us/app/pepi/id1283082051?mt=8" target="_blank" rel="noopener">iTunes</a>
<blockquote>Quantumult <img src="https://www.v2ray.com/en/resources/ios.svg" width="20" /></blockquote>
Download: <a href="https://itunes.apple.com/us/app/quantumult/id1252015438?mt=8" target="_blank" rel="noopener">iTunes</a>
<blockquote>BifrostV <img src="https://www.v2ray.com/en/resources/android.svg" width="20" /></blockquote>
BifrostV is an Android app based on V2Ray core. It supports VMess, Shadowsocks, socks protocols.

Download: <a href="https://play.google.com/store/apps/details?id=com.github.dawndiy.bifrostv" target="_blank" rel="noopener">Play Store</a> | <a href="https://apkpure.com/bifrostv/com.github.dawndiy.bifrostv" target="_blank" rel="noopener">APK Pure</a>
<blockquote>V2RayNG <img src="https://www.v2ray.com/en/resources/android.svg" width="20" /></blockquote>
V2RayNG is an Android app based on V2Ray. It provides same feature set as V2Ray core.

Download: <a href="https://play.google.com/store/apps/details?id=com.v2ray.ang" target="_blank" rel="noopener">Play Store</a> | <a href="https://github.com/2dust/v2rayNG" target="_blank" rel="noopener">GitHub</a>

