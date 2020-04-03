---
title: "가입하기"
linkTitle: "가입하기"
weight: 10
description: >
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
</style>



 <br><br>
<form class="form" name="contact" method="POST" data-netlify="true">
  <p>
    <label>이메일(사용자ID): </label><input class="text" type="email" name="email" />
  </p>
  <p>
    <label>비밀번호: </label><input class="text" type="password" name="password" />
  </p>
    <p>
    <label>비밀번호확인: </label><input class="text" type="password" name="passwordcheck" />
  </p>
  <p>
    <label>전화번호: </label> <input class="text" type="text" name="phone" />  
  </p>
  <p>
    <label>기간선택: </label><select name="plan" single>
          <option value="12momth">1년(488원)+2개월 무료</option>
          <option value="6month">6개월(288원)</option>
          <option value="3month">3개월(188원)</option>
          <option value="1month">1개월(88원)</option>
    </select>
  </p>
    <p>
    <label>추천인: </label><input class="text" type="text" name="recomand" />   
  </p>

  <p>
      <label></label><button class="btn btn-lg btn-primary" type="submit">가입하기</button>
    </p>
</form>

### 추천제도
추천 1명당 1개월 무료연장



