---
title: "맥북/아이맥 (macOS)"
linkTitle: "맥북/아이맥 (macOS)"
weight: 2
description: >
  맥북/아이맥에 설치하기.
---

{{% pageinfo %}}

카톡을 통해 구독 주소를 받고 진행해야합니다.
구독주소를 통해 여러서버를 한번에 추가가능하며, 항상 최신 정보로 업데이트됩니다.

{{% /pageinfo %}}

### 1. 준비하기

macOSX Mojavie 버젼 이상

### 2. 어플 다운로드하기

<blockquote><i class="fab fa-apple"></i> V2ray용 : V2rayU v3.13 | 
<a href="http://v2red.com/files/public-docs/win/v2rayN-Core.zip" target="_blank" rel="noopener">다운로드(22.4MB)</a>
</blockquote>

IKEv2: 설치필요 없음

### 3. 어플 설치하기

v2rayU.dmg 더블클릭, 어플을 어플리케이션 폴더로 복사

![](/img/v2red-macos-01.jpg)

어플리케이션 폴더에서 v2rayU 실행, 경고창이 뜨면 Ok 클릭

> 오픈소스 어플이기에 Github를 통해 어플 소스코드를 모두 확인 할수 있습니다.

![](/img/v2red-macos-02.jpg)

왼쪽위 애플 아이콘 -> 시스템 환경설정(System preferencese) -> 보안 & 개인정보 (Security & Privacy)

![](/img/v2red-macos-03.jpg)

자물쇠가 잠겨 있다면, 죄물쇠 아이콘을 클릭 -> 맥 비번입력 -> 열기(Open anyway) 클릭

![](/img/v2red-macos-04.jpg)

경고창 뜨면 열기 (open)

![](/img/v2red-macos-05.jpg)

네트워크시스템 설정변경 권한부여, 맥 비번 입력 후 Okay

![](/img/v2red-macos-06.jpg)

탑바에 아이콘이 보이면 어플 실행중 및 준비완료

![](/img/v2red-macos-07.jpg)

### 4. 구독주소 얻기

### 5. 어플 세팅하기

탑바에서 v2rayU 아이콘 클릭 -> 클릭 Subcsribe

![](/img/v2red-macos-012.jpg)

URL에 구독주소 정확히 입력 (Remarks는 아무거나 입력) 후 update servers 클릭

> 구독주소 : https://rb.gy/구독코드6자리

> 예시 : https://rb.gy/yghtf5

![](/img/v2red-macos-013.jpg)

아래 그림처럼 나온다면 서버입력 완료! 오른쪽 위 빨간버튼[x] 눌러 창닫기

![](/img/v2red-macos-014.jpg)


### 6. 어플 설정

아이콘 클릭 -> Golbal mode 클릭 -> server에서 서버 선택하면 자동으로 서버로 연결됩니다. 상단에 Core가 ON아되고, 아이콘에 G가 들어가면 연결완료!

![](/img/v2red-macos-015.jpg)

모드는 변경가능합니다.

| 모드      | 설명         |
|-----------|-----------------|
| Config(PAC mode)  | 중국싸이트는 다이렉트로 연결하고, 유투브같은 싸이트는 프록시로 규칙에 따라 자동변경 해줍니다. |
| Proxy(Global mode)  | 모든 연결이 프록시를 통해 연결됩니다. (중국싸이트 잘 안됨)|
| Direct  | 모든 연결을 다이렉트로 보냅니다. (유투브같은 싸이트 안됩) (기능을 끄는거와 다름 없음) |
| Secene(Manual)  | 사용자 설정 |
> 
어플 세팅을 통해 필터링이나 룰등을 사용자 환경에 맞게 설정 및 변경할수 있습니다.



| APP                  | Official github        |
|----------------------|--------------------------------|
| V2RayU  (추천) | [Github](https://github.com/yanue/V2rayU)       |
| V2RayX   | [Github](https://github.com/Cenmrev/V2RayX)     |
| V2RayC   | [Github](https://github.com/gssdromen/V2RayC)   |
| ClashX   | [Github](https://github.com/yichengchen/clashX) |