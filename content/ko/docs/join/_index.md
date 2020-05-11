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



