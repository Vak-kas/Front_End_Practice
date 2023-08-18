<h1>5장 : 입력 양식 작성하기</h1>

<h1> 5-1<h1>
<h2>폼 삽입하기</h2>
<p> <.form>[속성 = "속성값"]<./form> 여러 폼 요소</p>
<ul>
  <li>method -> get(256~4096만 데이터를 보낼 수 있으나, 주소 표시줄에 사용자가 입력한 내용이 그대로 드러남), post(입력한 내용의 길이에 제한 받지 않고, 내용도 드러나지 않음.</li>
  <li>name -> 자바스크립트로 폼 제어할 때 사용할 폼의 이름 지정</li>
  <li>action : 폼 태그 안의 내용을 처리해줄 서버 프로그램 지정</li>
  <li>target : 현재 창이 아닌 다른 창에서 열리게 하기</li>
  <li>autocomplete : 자동완성</li>
</ul>

<h2>품 요소를 그룹으로 묶기</h2>
<ul>
  <li> fieldset -> 하나의 폼 안에서 여러 구역으로 나누어 표시</li>
  <li> legend : 그룹 이름</li>  
</ul>

<h2>레이블</h2>
<p>폼 요소에 레이블을 붙이는 레이블 태그</p>
사용법 <ul>
  <li><./label>아이디(6자이상)<.input type="text"><./label></li>
    <li><./label for "user-id">아이디(6자 이상)<./label><br>
    <.input type="text id="user-id"></li>
</ul>

<h1>5-2</h1>
<p>input 을 이용하여 사용자에게 입력을 요구할 수 있음.</p>
속성
<ul>
  <li>텍스트와 비밀번호 나타내기 : type="text", type="password"
  <br><i>size(필드의 길이지정), value(텍스트 필드 부분에 보여주는 내용, 비번에서는 사용  x), maxlength(최대 문자수)
  </li>
</ul>
