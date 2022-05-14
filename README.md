# Do it ! HTML5 + CSS3 
> 매일 한 chapter씩 공부하여 pdf로 요약하고 유용한 기능들을 직접 따라하고 commit 하는 것을 목표로 합니다.

###  **[chapter1] HTML 기본 다지기**

- `웹 편집기 선택하기`

  <비주얼 스튜디오 코드>
1. 대부분의 주요 플랫폼에서 사용가능  
2. 태그와 css속성을 친절히 안내함  
3. 태그와 css속성을 간편하게 입력 가능  
4. 확장이 쉬움  
- `비주얼 스튜디오 코드 설치하기`

👉 https://code.visualstudio.com/

- `태그, 이건 꼭 알아두세요 !`  
1. 태그는 <와 >를 사용
2. 태그는 소문자로 씀
3. 여는 태그와 닫는 태그를 정확히 입력
4. 적당히 들여쓰기
5. 태그는 속성과 함께 사용 가능

### **[chapter2] 텍스트 관련 태그들**

- `텍스트를 덩어리로 묶어주는 태그`

    \<h*n*> 제목 \<p> 단락 \<br> 줄 바꿈 \<hr> 수평선 \<blockquote> 인용문 \<pre> 그대로 화면표시  
- `텍스트를 한줄로 표시하는 태그`

   \<storng>,\<b> 굵게 표시 \<em>,\<i> 이탤릭체 \<q> 인용문 \<mark> 형관펜 \<span> 인라인

- `목록을 만드는 태그`

   \<ul>, \<li> 순서없는 목록 \<ol>, \<li> 순서 목록 \<dl>, \<dt>, \<dd> 설명 목록
   
- `표를 만드는 태그`

    \<table>, \<tr>, \<td>, \<th> 표 만들기 \<caption>, \<figcaption> 표 제목 붙이기 \<thead>, \<tbody>, \<tfoot> 표 구조 정의
    
    
    \<col>, \<colgroup> 열 묶기

### **[chapter3] 이미지와 하이퍼링크**

- `이미지`

   \<img> 이미지 삽입 (절대경로/상대경로) alt속성: 대체 텍스트 width, height속성: 이미지 크기조정 \<figure>, \<figcaption> 이미지 설명 붙히기

- `링크 만들기`
   
   \<a>, href: 링크 만들기  
   target속성: 새 탭에서 링크  
   \<map>, \<area>, usemap속성: 이미지맵
   
### **[chapter4] 폼 관련 태그들**
   
- `폼 만들기`

   \<form>, \<label> = 폼, 라벨 만들기 \<feildset>, \<legend> = 폼 요소 그룹으로 묶기

- `사용자 입력을 위한 input태그`

   type="hidden" = 히든필드 type="text" = 텍스트 필드 type="password" = 패스워드 type="number" = 숫자 입력 type="range" = 숫자지정(슬라이드막대)
   type="radio", type="checkbox" = 라디오버튼,체크박스 type="date", type="month", type="week" = 날짜표시

- `<input>태그의 다양한 속성`

   autofocus속성 = 입력커서표시 placeholder속성 = 힌트표시 readonly속성 = 읽기전용 required속성 = 필수필드 min,max,step속성 = 최소,최대값,단위
   size,minlength,maxlength속성 = 길이,최소길이,최대길이 

- `데이터 나열하기`

   \<select>,\<optgroup>,\<option> = 드롭다운목록 \<datalist>,\<option> = 검색 자동완성 \<textarea> = 여러줄 입력하는 텍스트영역 (약관)

### **[chapter5] CSS 기초**

- `주요선택자`

   전체선택자(\*), 태그선택자, 클래스선택자, id선택자, 그룹선택자(h1, h2 {스타일})

- `캐스케이딩`

   1. 인라인 스타일  
   2. id 스타일  
   3. 클래스 스타일  
   4. 태그 스타일

### **[chapter6] 텍스트 관련 스타일**

- `글꼴 관련 스타일`

   font-family (글꼴), 구글 웹 폰트사용, font-size(글자크기), font-weight(글자굵기), font-variant(작은 대문자)

- `텍스트 스타일`

   color(글자 색), text-decoration(밑줄,취소선), text-transform(대소문자 변환), text-shadow(그림자), white-space(공백처리), letter-spacing과word-spacing(자간)

- `문단 스타일`

   line-height(줄 간격), text-overflow(넘치는텍스트 표기), text-indent(들여쓰기)

### **[chapter7] 색상과 배경을 위한 스타일**

- `배경색과 배경이미지`

   background-color(배경색 지정하기), background-clip(배경적용범위 조절), background-image(배경이미지), background-repeat(배경이미지 반복), background-size(배경이미지 크기)
   background-position(배경이미지 위치), background-origin(배경이미지 배치기준), background-attachment(배경이미지 고정)

- `그라데이션`

   linear-gradient(선형 그라데이션), radial-gradient(원형 그라데이션)

### **[chapter8] CSS와 박스 모델**

- `CSS와 박스 모델`

   블록레벨 요소 : 한 줄 차지(너비:100%), 너비나 마진, 패딩 설정 가능  
   인라인레벨 요소 : 한 줄 차지 x, 콘텐츠만큼만 영역차지, 너비나 마진, 패딩 설정 불가능

- `테두리 관련 속성들`

   border-style(테두리 스타일), border-width(테두리 두께), border-color(테두리 색상), border-radius(모서리 둥글게), box-shadow(그림자)

- `마진 중첩 현상`

   요소를 세로로 배치할 경우, 마진과 마진이 만날 때 마진값이 큰 쪽으로 겹쳐지는 현상
   
### **[chapter9] CSS 레이아웃**

- `CSS포지셔닝과 주요 속성들`

   float속성(왼쪽이나 오른쪽으로 배치), clear속성(float속성 해제), position속성(배치방법), visiblility(보이기), z-index(쌓는순서)

### **[chapter10] HTML5와 시맨틱 태그**

- `HTML문서`

   시맨택태그를 써야하는 이유 : 어느 부분이 무슨 내용인지 쉽게 파악할 수 있으며 접근성이 좋다. 구조파악이 쉽다.

- `시맨틱태그`

   \<header>, \<nav>, \<section>, \<aside>, \<footer>  
   👉\<header>안에 또 \<header>, \<nav>, \<section>, \<aside>, \<footer> 들어갈 수도 있다. \<header>외 다른 시맨틱태그들도 마찬가지, 정해진 규칙이 없다.

### **[chapter11] HTML5와 멀티미디어**

- `웹과 멀티미디어`

   \<object> 외부파일 삽입하기 \<embed> 외부파일 삽입하기 - \<object>태그를 지원하지 않는 이전 브라우저에서 주로 사용함.

- `오디오 & 비디오 재생하기`

   \<audio> 오디오파일 삽입 \<video> 비디오파일 삽입

### **[chapter12] 다재다능한 CSS 선택자**

- `연결 선택자`

   하위 선택자 - 지정한 모든 하위 요소에 스타일 적용하기 (기본형: 상위요소 하위요소)  
   자식 선택자 - 자식 요소에만 스타일 적용하기 (부모요소 > 자식요소)  
   인접형제 선택자 - 가장 가까운 형제요소에 스타일 적용하기 (요소1 + 요소2)  
   형제 선택자 - 형제요소에 스타일 적용하기 (요소1 ~ 요소2)

- `속성 선택자`

   [속성] : 지정한 속성 [속성=값] : 특정값을 갖는 속성 [속성~=값] : 여러 값 중 특정 값이 포함된 속성 [속성|=값] : 특정값이 포함된 속성  
   [속성^=값] : 특정 값으로 시작하는 속성 [속성$=값] : 특정 값으로 끝나는 속성 [속성*=값] : 값의 일부가 일치하는 속성

### **[chapter13] CSS와 애니메이션**

- `변형`

   translate : 이동 scale : 크기 rotate : 회전 skew : 왜곡 

- `변형 관련 속성들`

   transform-origin : 변형 기준점 설정 backface-visibility : 요소의 뒷면 표시

- `트랜지션`

   웹 요소의 배경색이 바뀌거나 도형의 테두리가 원형으로 바뀌는 것처럼 스타일 속성이 바뀌는 것을 의미합니다.

- `애니메이션`

   트랜지션과 비슷하지만 애니메이션은 시작해 끝나는동안 원하는 곳 어디서든 스타일을 바꾸며 애니메이션을 정의할 수 있다는 점이 트랜지션과 다른점임.
















































































