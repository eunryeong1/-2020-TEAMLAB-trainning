# -2020-TEAMLAB-trainning
1. HTML 4.x 이후의 HTML 표준의 변천사는 어떻게 되나요?
HTML 4.01 이전에는 css는 HTML안에 있는 형식이었다.결과적으로 여러개의 페이지가 있으면 각각의 페이지마다 css 를 모두 입력해주어야 했고 반복되는 css도 많았다.
HTML 4.01 이후로는 외부의 스타일 시트가 도입되었다. 파일 형태로 스타일 시트를 작성하고 HTML안에 삽입하는 방식이다. 
HTML 에서 사용할 수 있는 새로운 태그도 도입되었다.

2. MS와 IE는 왜 역사의 죄인이 되었을까요?
IE는 크롬에 비교하여 속도, 기능, 디자인 등에서 차이가 많이 나지만 가장 큰 차이점은 보안과 관련된 부분인다.
IE는 메모리의 개체에 부적절하게 엑세스될 경우 원격 코드 실행 취약점이 존재한다.
이 취약점으로 인해 메모리가 손상되면 해커들은 악성 코드를 실행 시킬 수 있다.
IE의 취약한 보안에 대해 MS도 인정하였지만 고치거나 패치할 수 없다는 것이 더 큰 문제이다
결과적으로 ms는 microsoft edge를 내놓았다.

3. <section>과 <div>, <header>, <footer>, <article> 엘리먼트의 차이점은 무엇인가요?
select: 문서 또는 응용 프로그램의 일반적인 섹션/ 주제별로 그룹화된 콘텐츠
         요소의 내용이 문서 개요에 명시적으로 나열되는 경우에만 적합
         html요소는 문서의 일반 섹션을 나타냄
div: 연속적인 요소 그룹에 공통적인 의미를 표시하려면 class,lang및 title 특성과 함께 사용 가능
      요소가 스타일링 목적 또는 스크립팅의 편의를 위해 필요한 경우 사용
      html요소는 흐름 내용의 일반 컨테이너, 본질적으로 아무것도 나타내지 않음
header: 사이트의 이름, 내비게이션, 헤드라인, 검색 등으로 구성
          문서나 각 section, article의 헤더 부분에 사용가능/ 제목이나 간단한 소개 콘텐츠 포함
           브라우저가 헤더 영역을 인식할 수 있게 되면 스크린리더의 내비게이션과 검색엔진의 색인에 도움을 줌
footer: 바닥 영역 또는 꼬리말 지칭/ 저작권, 연락정보 등 본문과의 관련성을 있지만 본문에는 담기 어려운 내용
          맨위로 가기 링크나 헤더의 메인 내비게이션도 반복 제공을 위해 푸터 영역에 둘 수 있음
           일반적으로 푸터 영역은 한 문서 내에서만 제공되지만 section 요소나 article 요소내에 있는 footer요소는 
          해당 영역에 관한 꼬리말을 표시할 수 있음
article: 본문과 별개로 구성되어 다른 영역에 영향을 주거나 받지않고 독립적으로 배포되거나 재사용 가능
         일반적인 상황에서 section의 요소가 article 요소에 포함, 하지만 독립적으로 구성된 내용이 몇개의 섹션으로 
         구성된 경우라면 article 요소가 section 요소를 포함할 수 있음
         article영역 내에서 헤더와 푸터로 둘 수 있음

4. 블럭 레벨 엘리먼트와 인라인 엘리먼트의 차이는 무엇일까요?
블럭레벨 엘리먼트: 화면 전체를 사용하는 태그
인라인 엘리먼트: 화면의 일부를 차지하는 태그
