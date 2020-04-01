---
title: "가입하기"
linkTitle: "가입하기"
weight: 10
description: >
---
 <br><br>
<form class="form" name="contact" method="POST" data-netlify="true">
  <p>
    <label>성함: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>이메일: <input type="email" name="email" /></label>
  </p>
    <p>
    <label>비밀번호: <input type="password" name="password" /></label>
  </p>
  <p>
    <label>위쳇: <input type="text" name="phone" /></label>   
  </p>
  <p>
    <label>기간선택: <select name="plan" single>
          <option value="12momth">1년 + 3개월무료</option>
          <option value="6month">6개월 + 1개월 무료</option>
          <option value="3month">3개월</option>
          <option value="1month">1개월</option>
    </select>
    </label>
  </p>
    <p>
    <label>추천인: <input type="text" name="recomand" /></label>   
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>