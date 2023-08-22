<h1>자바스크립트와 객체</h1>
<p>객체 : 프로그램에서 인식할 수 있는 모든 대상, 웹과 관련된 대상을 모두 객체로 인식</p>
<ul>
  <li>문서 객체 모델(DOM) : 웹 문서 자체, 그 안에 삽입되어 있는 이미지, 링크, 텍스트 필드 등 모두 객체</li>
  <li>브라우저 관련 객체 : 웹 브라우저에서 사용하는 정보도 객체로 나타냄. nav, history, location, screen 객체 등</li>
  <li>내장 객체 : 자바스크립트 안에 미리 객체로ㅓ 정의 되어 있는 거, 시간과 관련된 프로그램 개발하려면 Date 객체 가져와서 사용...(모듈 같은 느낌?)</li>
</ul>

<h4>객체 만들기</h4>
new 객체명

<h4>프로퍼티와 메서드 이해하기</h4>
프로퍼티 : 객체의 특징이나 속성<br>
메서드 : 객체에서 할 수 있는 동작

<p>그냥 필드와 메서드 관계 느낌 같음</p>


<h2>자바 스크립트의 내장 객체</h2>

<h3>Array객체</h3>
배열을 다룸.
<p>var numbers = new Array();  --> 크기 지정 하지 않음</p>
<p>var numbers = new Array(4); --> 크기 지정을 함</p>

<p>var numbers = ["1", "2", "3", "4"] / var numbers = Array("1", "2", "3", "4")</p>

<p>길이 구하기 : length사용</p>

<p>array 객체의 메서드</p>
<ul>
  <li>concat : 기존 배열에 요소를 추가해 새로운 배열을 만듦</li>
  <li>every : 모든 요소가 주어진 함수에 대해 참이면 true, 아니면 false</li>
  <li>filter </li>
  <li>forEach (map함수 느낌?)</li>
  <li>indexOf </li>
  <li>join : 배열 합치기</li>
  <li>push</li>
  <li>pop</li>
  <li>unshift : 배열의 시작 부분에 새로운 요소 추가</li>
  <li>shift : popleft같은 느낌</li>
  <li>splice : 배열에 요소를 추가하거나 삭제</li>
  <li>slice : 배열에서 특정한 부분만 잘라 냅니다</li>
  <li>reverse : 배치 순서 역순</li>
  <li>sort : 정렬</li>
  <li>toString : 배열에서 지정한 부분을 문자열로 반환</li>
</ul>
