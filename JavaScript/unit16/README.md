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

<p>date 객체랑 math 객체 버림 ㅅㄱ</p>

<h2>브라우저와 관련된 객체</h2>
웹 브라우저 열리면 window 객체 만들어지고, 밑으로 하위 ㅇ ㅛ소에 해당하는 객체들이 나타남.
<p>window 밑에 document, navigator, history, location, screen</p>
<p>document 밑에 area, image, form, anchor</p>
<p>form 밑에 textarea, button, text, checkbox, fileUpload, radio...</p>

<ul>
  <li>window : 브라우저 창이 열릴때마다 하나씩 만들어짐, 최상위에 있음</li>
  <li>document : body 태그를 만나면 만들어짐, html 문서의 정보가 담겨있음</li>
  <li>navigator : 현재 사용하는 브라우저의 정보가 들어있음</li>
  <li>history : 현재 창에서 사용자의 방문 기록을 저장</li>
  <li>location : 현재 페이지의 url 정보 담겨 있음</li>
  <li>screen : 현재 사용하는 화면 정보를 다룸</li>

  <p>지금부터 내용이 좀 많고 처음 보는 것들도 많아서, 일단 정리만 해두고, 나중에 프로젝트 하면서 일일이 찾아보면서 만들어보면서 외워야 할 듯. 일단은 정리만이라도 해둠</p>

  <h3>window 객체의 프로퍼티</h3>
  <ul>
    <li>document : 브라우저 창에 표시된 웹 문서에 접근</li>
    <li>frameElement : 현재 창이 다른 요소 안에 포함되어 있을 경우, 요소 반환, 아니면 null 반환</li>
    <li>innerHeight : 내용 영역의 높이</li>
    <li>innerWidth : 내용 영역의 너비를 나타냄</li>
    <li>localStorage : 웹 브라우저에서 데이터를 저장하는 로컬 스토리지를 반환</li>
    <li>location : window객체의 위치 또는 현재 URL 나타냄.</li>
  </ul>
  개많아서 포기 gg

  <h3>window 객체의 메서드</h3>
  <ul>
    <li>alert, confirm, prompt 는 앎</li>
    <li>open : 새 브라우저 창을 열음 --> open(경로, 창 이름, 창 옵션)</li>
    <li>close : 브라우저 창을 닫음 -- > button.onclick = "javascript:window.close();"</li>
  </ul>
</ul>

<h3>navigator객체</h3>
