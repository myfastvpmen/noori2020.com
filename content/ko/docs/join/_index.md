---
title: "가입신청"
linkTitle: "가입신청"
weight: 10
description: >
menu:
  main:
    weight: 20
---

<style>
form.form input.text, form.form textarea.standard, form.form select, form.form input.date { 
   background-color:#FFFFFF;
   border:solid 1px #A9A9A9;
   font-size:18px;
   color:#000000;
   -moz-border-radius:10px;
   -webkit-border-radius:10px;
   border-radius:10px;
   padding-top:5px;
   padding-bottom:5px;
   padding-left:5px;
   padding-right:5px;
}
form.form p label {
   font-size:18px;
   color:#333333;
   font-weight:normal;
   padding-top:0px;
   padding-bottom:0px;
   width:160px;
   display:inline-block;
   text-align:right;
   padding-right:10px;
}

form.form p.submit input {
   background-color:#FFFFFF;
   border:solid 3px #A9A9A9;
   font-size:16px;
   color:#000000;
   font-weight:bold;
   padding-top:10px;
   padding-bottom:10px;
   padding-right:25px;
   padding-left:25px;
   -moz-border-radius:5px;
   -webkit-border-radius:5px;
   border-radius:5px;
}
form.form p.submit {
   margin-top:0px;
   margin-bottom:0px;
   text-align:left;
}
form.form p.required label, form.form span.required label {
    font-weight:bold;
}
p.hidden {
  visibility: hidden;
}
</style>

<form class="form" name="application" method="POST" netlify-honeypot="bot-field" data-netlify="true">
  <p class="hidden">
    <label>D<input name="bot-field" /></label>
  </p>
  <p>
    <label>이메일: </label><input class="text" type="email" name="Email" />
  </p>
  <p>
    <label>폰번호: </label> <input class="text" type="text" name="Phone" />  
  </p>
    <p>
    <label>위쳇ID: </label> <input class="text" type="text" name="Wechat" />  
  </p>
  <p>
    <label>기간선택(할인가): </label><select name="plan" single>
          <option value="Free">1달 무료신청</option>
          <option value="V-12">고급:1년(480위엔)</option>
          <option value="V-6">고급:6개월(280위엔)</option>
          <option value="V-3">고급:3개월(160위엔)</option>
          <option value="V-1">고급:1개월(70위엔)</option>
          <option value="K-12">일반:1년(240위엔)</option>
          <option value="K-6">일반:6개월(140위엔)</option>
          <option value="K-3">일반:3개월(80위엔)</option>
          <option value="K-1">일반:1개월(35위엔)</option>
    </select>
  </p>
    <p>
    <label>추천인: </label><input class="text" type="text" name="Recomend" />   
  </p>

  <p>
      <label></label><button class="btn btn-lg btn-primary" type="submit">가입하기</button>
    </p>
</form>

### 추천제도
추천한사람 받은사람 모두 1개월 무료연장

<div class="table container" style="max-width: max-content;">
	<p class="lead mt-5">2020년 5월 런칭기념 할인가격!<br>
		30일 이내 서비스 불만족시 묻지도 따지지 않고 100% 환불해드립니다.
	</p>
<table style="max-width: max-content;">
	<thead>
	<tr>
	<th></th>
	<th>골드 계정</th>
	<th>프리미엄 계정</th>
	</tr>
	</thead>
	
	<tbody>
	<tr>
	<td>가격</td>
	<td>1년 이용시 40위엔/월</td>
	<td>1년 이용시 80위엔/월</td>
	</tr>
	
	<tr>
	<td>접속방식</td>
	<td>IKEv2/V2ray</td>
	<td>IKEv2/V2ray</td>
	</tr>

	<tr>
	<td>동시접속</td>
	<td>무제한</td>
	<td>무제한</td>
	</tr>
	
	<tr>
	<td>기본서버</td>
	<td>홍콩/무제한(속도 8Mps)</td>
	<td>홍콩/무제한(속도 8Mps)</td>
	</tr>

	<tr>
	<td>프리미엄 서버</td>
	<td>한국KT,SKT/미국</td>
	<td>한국KT,SKT/미국</td>
	</tr>

	<tr>
	<td>프리미엄 서버 트래픽</td>
	<td>50기가/월</td>
	<td>150기가/월</td>
	</tr>
	
	
	<tr>
	<td>프리미엄 서버 속도</td>
	<td>20 Mps</td>
	<td>30 Mps</td>
	</tr>
	
	<tr>
	<td>넷플릭스</td>
	<td>불가</td>
	<td>가능</td>
	</tr>
	</tbody>
	</table>
</div>


