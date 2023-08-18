 |<h1>5장 : 입력 양식 작성하기</h1>

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
  <br><i>size(필드의 길이지정), value(텍스트 필드 부분에 보여주는 내용, 비번에서는 사용  x), maxlength(최대 문자수)</i>
  </li>
</ul>
type 추가 
<ul>
  <li>type="search" : 검색</li>
  <li>type = "url" : 웹 주소 입력</li>
  <li>type = "email" : 이메일</li>
  <li>type= "tel" : 전화번호</li>
</ul>

체크박스와 라디오 버튼
<ul>
  <li> type="checkbox" : 여러 항목 중 2개 이상 선택</li>
  <li> type = "radio" : 여러 항복 중 1개만</li>
</ul>
<p>이때 속성으로 value(서버에 알려줄 때 값 지정, 영문 또는 숫자), checked : 기본으로 선택해놓고 싶은 항목에 사용. 속성값은 다로 없음.
<br>그리고 radio 에서 name값이 같은 것은 하나만 체크할 수 있으니, name 잘 써먹으셈</p>


<h2>숫자 입력 필드</h2>

<ul>
  <li>type="number" : 스핀 박스가 나타나면서 숫자 를 선택할 수 있음.</li>
  <li>type="range" : 슬라이드 막대를 움직여 숫자 입력</li>
</ul>
<p>이 때 속성으로, min(최소값), max(최대값), step(숫자 간격 지정, value : 필드에 표시할 초기값이 있음.</p>

<h2>날짜 입력</h2>
input type="date | month | week"
<ul>
  <li>date : yyyy-mm-dd 형식으로 연도, 월, 일이 표시</li>
  <li>month : yyyy-mm 형식으로 연도, 월까지만 입력</li>
  <li>week : 1월 첫째주 기준 지금이 몇 번째 주인가</li>
</ul>

<h2>시간 입력</h2>
input type="time | datetime | datetime-local"
<ul>
 <li>time : 오전오후/시/분</li>
 <li>datetime/datetime-local : 지역에 맞는 날짜외 시간</li>
</ul>
** 애네도 min, max, step, value 있음



<h2>전송, 리셋 버튼 나타내기</h2>
input type="submit | reset" value ="버튼에 표시할 내용"

<p> submit 제출 시, form에 연결된 (action)으로 넘어가지고, reset 버튼 입력시 폼에 입력된 내용 싹 삭제</p>

<h2>이미지 버튼 추가하기</h2>
input type="image" src="이미지 경로" alt="대체 텍스트"

<h2>그냥 버튼 넣기</h2>
input type="button" value="버튼에 표시할 내용"

