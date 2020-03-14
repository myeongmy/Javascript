# Javascript

===

웹 브라우저를 동적으로 동작하게 해주는 언어

사용자가 웹 브라우저를 통해 서버에 요청을 하면 서버가 html 페이지로 응답을 준다.

html 페이지는 정적인 문서! 자바스크립트를 이용해 웹 브라우저를 동적으로 사용자가 이용할 수 있게 된다.



* Javascript Event (예시)

  1. onclick: 사용자가 어떤 키를 눌렀을 때 발생하는 이벤트

  2. onchange: 텍스트의 내용이 변경되었을 때 발생하는 이벤트

  3. onkeydown: 어떤 키던 무언가를 입력했을 때 발생하는 이벤트

     

> 개발자 도구 console 창을 이용하여 자바스크립트 코드 작성 가능하다. 해당 코드는 개발자 도구를 연 페이지를 대상으로 동작한다.

* Data type
  1. String
  2. Number

* Selecting a tag to control

  1. Tag select : document.querySelector('body')
  2. ClassName select : document.querySelector('.myclass') - 클래스 명이 myclass인 tag 찾음
  3. ID select: document.querySelector('#myId')

  ex> document.querySelector('body').style.color

  ​		document.querySelector('body').value

  ​		document.querySelector('body').innerHTML

  ​		document.querySelectorAll('a') -> 배열 객체 반환

  

* Html vs Javascript

  html: 웹 언어 (시간 순서에 따라 실행해야하는 것이 전혀 없음, 정적인 언어)

  javascript: 웹 '프로그래밍' 언어

  프로그래밍이란? 어떤 의도에 따라 순서대로 여러 기능을 수행할 수 있는 프로그램을 만드는 행위