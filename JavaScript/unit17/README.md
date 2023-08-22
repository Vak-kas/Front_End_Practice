<h1>문서 객체 모델(DOM)</h1>
<h2>문서 객체 모델 알아보기</h2>
<p>문서 객체 모델 : 자바스크립트를 이용하여 웹 문서에 접근하고 제어할 수 있도록 객체를 사용해 웹 문서를 체계적으로 정리하는 방법</p>
<p>DOM은 웹 문서를 하나의 객체로 정의. <br>웹 문서를 이루는 텍스트나 이미지, 표 등의 모든 요소도 각각 객체로 정의</p>

<h3>DOM트리</h3>
<p>DOM은 웹 문서의 요소를 부모 요소와 자식 요소로 구분함.</p>
<ol>
  <li>모든 HTML태그는 요소(element) 노드</li>
  <li>HTML태그에서 사용하는 텍스트 내용은 자식 노드인 텍스트 노드</li>
  <li>HTML 태그에 있는 속성은 자식 노드인 속성 노드</li>
  <li>주석은 주석 노드</li>
</ol>
<p>웹 문서를 해석할 DOM 구조를 만드는 것이 중요함.</p>


<h2>DOM요소에 접근하고 속성 가져오기</h2>

<h3>id 선택자로 접근하는 getElementById()메서드</h3>
요소명.getElementById("id명");
<br> ex) document.getElementBytId("heading");

<h3>class값으로 접근하는 getElementsByClassName()메서드</h3>
요소명.getElementByClassName("class명");
<br> ex) document.getElementsByClassName("bright");