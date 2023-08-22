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


<h3>태그 이름으로 getElementsByTagName()메서드</h3>
요소명.getElementByTagName("태그명");
<br> ex)document.getElementsByTagName("p");

<h3>다양한 방법으로 접근하는 querySelector(), querySelectorAll()메서드</h3>
위의 세 개의 메서드의 반환값은 HTMLCollection객체, 여기에는 HTML요소만 저장됨.
<br>텍스트, 속성까지 자유롭게 제어하려면 querySelector, querySelectorAll을 써야함

<br><br>
id선택자 처럼 반환값이 하나라면 셀렉터, class선택자나 태그 이름을 사용하여 여러 값이 한꺼번에 반환될 경우 셀렉터 all사용
<br>
노드.querySelector(선택자)/노드.querySelectorAll(선택자 또는 태그)
<br>ex )querySelector("#heading"), querySelector(".bright");

<H2>웹 요소의 내용을 수정하는 innerText, innerHTML 프로퍼티</H2>
이너텍스트는 텍스트 내용 표시, 이너HTML은 태그까지 반영하여 표시
<br>요소명.innerText = 내용/요소명.innerHTML = 내용

<h2>속성을 가져오거나 수정하는 getAttribute(), setAttribute() 메서드</h2>
웹 요소를 문서에 삽입할 때 태그 속성을 함께 사용하면 DOM트리에 속성 노드가 추가되고, 속성값 저장. 
<p>getAttribute("속성명")/setAttribute("속성명", "값")</p>


<h2>DOM에서 이벤트 처리하기</h2>
<ul>
  <li>DOM요소에 함수 직접 연결하기</li>
  <li>함수 이름을 사용해 연결하기</li>
</ul>

