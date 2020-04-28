---
title: "안드로이드(Android)"
linkTitle: "안드로이드(Android)"
weight: 9
description: >
  안드로이드에 설치하기.
---

{{% pageinfo %}}
카톡을 통해 구독 주소를 받고 진행해야합니다.
구독주소를 통해 여러서버를 한번에 추가가능하며, 항상 최신 정보로 업데이트됩니다.
{{% /pageinfo %}}


### 1. 준비하기
1. 안드로이드폰
2. 구독주소

### 2. 다운로드 및 설치

v2red는 여러가지 프로그램을 통해 사용가능합니다. 사용자의 편의에 맞게 프로그램을 선택할수 있습니다.
유료 및 무료등 여러가지 조금씩 장단점이 있지만 , 여기서는 무료 프로그램인 V2RayNG를 가지고 설명합니다.

<blockquote><i class="fab fa-android"></i> V2ray용 : V2RayNG v1.2.4 | 
<a href="http://v2red.com/files/public-docs/android/v2rayNG_1.2.4.apk" target="_blank" rel="noopener">다운로드</a>
</blockquote>

<blockquote><i class="fab fa-android"></i> IKEv2용 : Strongswan v2.2.1 | 
<a href="https://download.strongswan.org/Android/strongSwan-2.2.1.apk" target="_blank" rel="noopener">다운로드 1</a> or
<a href="http://v2red.com/files/public-docs/android/strongSwan-2.2.1.apk" target="_blank" rel="noopener">다운로드 2</a> 

</blockquote>


따로 설치방법은 없습니다. 다운받고 설치하세요.

![](/img/v2red-android-01.png)
설치화면

### 4. 어플 세팅하기

어플을 실행합니다.

![](/img/v2red-android-02.png)

삼선아이콘 메뉴 클릭

![](/img/v2red-android-04.png)

Subscription setting 클릭

![](/img/v2red-android-05.png)

[+] 아이콘 클릭

![](/img/v2red-android-06.png)

URL에 구독주소 정확히 입력 (Remarks는 아무거나 입력)

> 구독주소 : https://rb.gy/구독코드6자리

> 예시 : https://rb.gy/yghtf5

![](/img/v2red-android-07.png)

Remarks는 보여지는 이름입니다. (옵션) 아무거나 입력후 [v] 클릭

![](/img/v2red-android-08.png)

첫 화면으로 돌아와서 점3개의 아이콘 클릭 후 Update subscription 클릭

![](/img/v2red-android-09.png)

원하는 서버를 선택후 아래 v버튼 클릭

![](/img/v2red-android-10.png)

네트워크 설정변경에 대한 권한요청이 들어옵니다. 클릭 OK

![](/img/v2red-android-11.png)

초록색으로 변하면 연결이 된것입니다.

![](/img/v2red-android-12.png)


이제 웹 브라우져를 열러 테스트 해보세요

>> V2rayNG의 경우 기본 연결 세팅은 Golbal 입니다. 이 경우 구글, 유뷰브등은 연결되지만, 위쳇, 큐큐, 유쿠등 중국 어플 또는 싸이트들이 느리거나 안 될수가 있습니다. 
앱의 세팅에서 동시에 가능하도록 사용자 설정이 가능합니다. 고급 설정과 공식 싸이트를 참고해주세요.

### 5. 연결 설정 (고급)


| 모드      | 설명         |
|-----------|-----------------|
| Config(PAC mode)  | 중국싸이트는 다이렉트로 연결하고, 유투브같은 싸이트는 프록시로 사용자 규칙 또는 기본 규칙에 따라 자동변경 해줍니다. |
| Proxy(Global mode)  | 모든 연결이 프록시를 통해 연결됩니다. (중국싸이트 잘 안됨)|
| Direct  | 모든 연결을 다이렉트로 보냅니다. (유투브같은 싸이트 안됩) (기능을 끄는거와 다름 없음) |
| Secene  | 사용자 설정 |


>> 보통 사용자의 경우 Proxy(Global mode)를 기본으로 두고, 유튜브 구글을 사용할때는 켰다가 중국 싸이트를 이용할때는 끄면서 사용하면 됩니다. 자동으로 변경해주고 싶은 사용자는 직접 공식 웹싸이트를 통해 더욱 자세한 정보는 얻어 사용자 환경에 맞게 직접 설정 할수 있습니다. (네트워크 및 라우팅 기초지식 필요)