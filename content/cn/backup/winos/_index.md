---
title: "윈도우 (winOS)"
linkTitle: "윈도우 (winOS)"
weight: 3
description: >
  윈도우 컴퓨터에 설치하기.
---

{{% pageinfo %}}
카톡을 통해 구독 주소를 받고 진행해야합니다.
windows 10 이상에서 정상작동합니다.
구독주소를 통해 여러서버를 한번에 추가가능하며, 항상 최신 정보로 업데이트됩니다.
{{% /pageinfo %}}

### 1. 다운로드 및 설치

<blockquote><i class="fab fa-windows"></i> V2ray용 : V2RayN v3.13 | 
<a href="http://v2red.com/files/public-docs/win/v2rayN-Core.zip" target="_blank" rel="noopener">다운로드(22.4MB)</a>
</blockquote>

<blockquote><i class="fab fa-windows"></i> V2ray용 : qv2ray v2.4.1  | 
<a href="http://v2red.com/files/public-docs/win/qv2ray-2.4.1-win64.exe" target="_blank" rel="noopener">다운로드 64bit (20.8MB)</a> |
<a href="http://v2red.com/files/public-docs/win/qv2ray-2.4.1-win32.exe" target="_blank" rel="noopener">다운로드 32bit (17.8MB)</a>
</blockquote>

<blockquote>IKEv2용 : 설치 필요없음
</blockquote>


다운로드후 C:폴더에 압축을 풀고 v2rayN.exe 를 우클릭하여 관리자권한으로 실행합니다. 
![](/img/v2red-winos-01.jpg)

![](/img/v2red-winos-02.jpg)

옵션 : 언어변경하기
![](/img/v2red-winos-09.jpg)

>>실행시 에러가 나거나 실행이 안되는 경우 보통 Win10 이하에서는 Microsoft .NET Framework 4.5 이상이 필요합니다. <a href="http://go.microsoft.com/fwlink/p/?LinkId=245484" target="_blank" rel="noopener">MS공식싸이트에서 다운받기</a>

### 2. 구독주소 얻기

### 3. 프로그램 세팅

subscription 아이콘 -> subscription setting 클릭
![](/img/v2red-winos-04.jpg)

URL에 구독주소 정확히 입력 (Remarks는 아무거나 입력)

> 구독주소 : https://rb.gy/구독코드6자리

> 예시 : https://rb.gy/yghtf5

![](/img/v2red-winos-05.jpg)

원하는 서버를 선택후 엔터
![](/img/v2red-winos-06.jpg)

오른쪽아래 프로그램 아이콘을 클릭하여 모드 선택
![](/img/v2red-winos-07.jpg)

이래그림과 같이 바뀌면 연결완료
![](/img/v2red-winos-08.jpg)


### 4. 어플 설정 (고급)


| 모드      | 설명         |
|-----------|-----------------|
| Config(PAC mode)  | 중국싸이트는 다이렉트로 연결하고, 유투브같은 싸이트는 프록시로 규칙에 따라 자동변경 해줍니다. |
| Proxy(Global mode)  | 모든 연결이 프록시를 통해 연결됩니다. (중국싸이트 잘 안됨)|
| Direct  | 모든 연결을 다이렉트로 보냅니다. (유투브같은 싸이트 안됩) (기능을 끄는거와 다름 없음) |
| Secene  | 사용자 설정 |
> 
어플 세팅을 통해 필터링이나 룰등을 사용자 환경에 맞게 설정 및 변경할수 있습니다.
자세한 정보는 어플 또는 프로그램 공식웹싸이트를 참고해주세요.



