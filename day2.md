#### Day2 요약 정리

## CSS 기본 문법  
CSS는 선택자와 선언 블록으로 구분한다.  
CSS 선택자는 전체 선택자, 요소선택자, class 선택자, id 선택자 등이 있으며 각각의 선택자들은 우선순위 규칙에 따라 적용된다.  
id: 100, class:10, element:1 로 계산하면 대략 맞음
점수가 동일할 때는 나중에 적용한 것이 우선 됨 

선택자{ 속성: 값 ; }

## CSS 박스 모델  
박스의 크기에 영향을 주는 csss 속성으로 width, height, border, margin, padding 속성 등이 있다.  
좌우 auto margin을 주면 가운데 정렬 됨
padding은 상/우/하/좌 시계 방향 순으로

![박스 모델](https://mdn.mozillademos.org/files/8685/boxmodel-(3).png)  
## Position 속성
* static(기본값) : normal flow, 마크업 순서대로
* relative(상대 배치)
* absolute(절대 배치): layer로 배치, 블럭이면서 원하는 크기를 줄 수 있음. 상위 요소 중 static이 아닌 것 기준으로 정렬
* fixed(절대 배치 - viewport(화면에 보이는 영역) 기준)
* sticky(상대 배치, 뷰포트): 최신 버전들만 지원  

## Flex
유연한 박스 모델 기법으로 최근 등장했으며 모던 웹 브라우저를 중심으로 지원하고 있음.  
IE10 버전 이상에서 사용 가능.  
 배치 되는 영역의 부모-container, 자식 item


* [Flex Box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  

* [Flex Froggy](https://flexboxfroggy.com/#ko)  

## Github 개인 홈페이지 만들기
저장소 이름은 github의 id와 github.io라는 이름으로 구성해야 한다.  

[노혜경의 홈페이지](https://hknohgit.github.io/)  
