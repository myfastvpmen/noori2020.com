---
title: "가입하기"
linkTitle: "가입하기"
weight: 10
description: >
  가입하기.
---

{{% pageinfo %}}
가입하기
{{% /pageinfo %}}


<form name="contact" method="POST" data-netlify="true" data-netlify-recaptcha="true">
  <p>
    <label>이름: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>아이디&이메일: <input type="email" name="email" /></label>
  </p>
    <p>
    <label>원하는 비번: <input type="password" name="password" /></label>
  </p>
  <p>
    <label>전화번호: <input type="text" name="phone" /></label>   
  </p>
  <p>
    <label>기간선택: <select name="plan[]" multiple>
      <option value="6month">6개월</option>
      <option value="12momth">1년</option>
    </select></label>
  </p>
    <p>
    <label>추천인: <input type="text" name="recomand" /></label>   
  </p>

<div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>