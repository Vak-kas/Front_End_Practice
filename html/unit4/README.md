# 주요 내용
<h2>4-1</h2>

- hn : 제목 나타내기
  
- p  단락 나타내기
- br = 줄바꿈
- blockquote 인용구
- string, b : 굵게 표시 (둘의 차이는 화면낭독기의 기능)
- em, i : 기울기

- abbr : 줄임말 표시
- cite : 웹 문서나 포스트에서 참고 내용 표시
- code : 컴퓨터 인식을 위한 소스 코드
- small : 부가 정보처럼 작게 표시 해도 되는 텍스트
- sub : 아래첨자
- sup : 위첨자
- s : 취소선

- u : 밑줄
- ins : 새로운 내용 삽임
- del : 기존 내용 삭제


<h2>4-2</h2>

- ol & li : 순서 있는 목록 만들기 type = "a/A/i/I/1", start= "시작번호"
- ul % li : 순서 없는 목록 만들기

- 설명 목록 만드는 dl(설명목록) dt(이름,단어명) dd(값, 설명)


<h2>4-3</h2>

- 표 만들기 : table
- 캡션 넣기 : caption(표제목)
- 행 만들기 : tr(row)
- 열 만들기 : td(col)

표의 구조를 지정 하기
- thead : 제목
- tbody : 본문
- tfoot : 요약

표 행이나 열 함치기

- rowspan = "합칠 셀의 개수"
- colspan= " 합칠 셀의 개수"

열을 묶어 주는 col, colgroup -> 특정 열의 배경색을 바꾸거나 하고 싶을 때

<h2>4-4</h2>

- 이미지 삽입하기 : img src = "파일 주소" alt=" 대체 텍스트">
- width, height 로 높이와 너비 조정하게 width = 50% or width = 50 ( 웹 브라우저의 창과 너비 기준으로 이미지 크기 결정 아니면, 고정값)
  둘 중에 하나만 정의해도 알아서 조정

<h2>4-5</h2>

- 다양한 멀티미디어 삽입하기
  <.object width =" 너비" height = "높이" data = " 주소"></object>    -> 얘는 닫는 태그 있어야함
  <.embed src " 파일경로" width=" 너비" height="높이">                 -> 얘는 필요없음

- 오디오 삽입
  <.audio src= "오디오 파일 경로"></audio>

- 비디오 삽입
  <.video>video src="경로" </video>
  
 오디오 비디오의 태그 속성
 - controls
 - autoplay
 - loop
 - muted
 - preload
 - width, height
 - poster= "파일 이름"

<h2>4-6</h2>

- 텍스트 링크 만들기 : <.a href="링크할 주소">텍스트<./a>
- 이미지 링크 만들기 : <.a href="링크할 주소"><.img src="경로" alt="대체 텍스트"><./a>
- 새 창에서 연결된 문서 열리기 : target ="_blank" 속성 사용
