# ResponsiveWeb
반응형 웹 프리온보딩 참가

20230829 - 프리온보딩 참가 신청, 강의 시작 전 미리 만들어보기 과제

## 요구사항 정리

### 1. Desktop

**total length** 
- width  : 1440 (px)
- height : 1,603 (px)

**header**
- logo
- navigation menu
- hamburger menu

**section**
- cards
  - 316 * 274 4개
  - 316 * 580 2개
  - 1012 * 581 1개
  - 663 * 274 1개
    - 카드 요소들 배치하기 (flex) 
    - margin 공통 요소로 관리 
    - 

**footer**
- company information
- email input
- site map
  - 4 * 2

### 2. Tablet
기존 화면과 달라진 점 중심으로 기술함

**length** 
- width  : 768 (px)


**header**
- navigation menu 제외 
- => 햄버거 메뉴 기능으로 대체한 것으로 추측

**section**
- cards
    - width 작아졌으므로 한 줄에 표시되는 card 개수도 변경
      - => 한 줄에 width 큰 건 1개, 작은 건 2개 표시
    - 좁아진 화면에 맞춰 전체적인 width, height 값 변경

**footer**
- email input 이 제일 밑으로 이동
- site map
  - 3 * 3


### 3. Mobile
기존 화면과 달라진 점 중심으로 기술함

**length** 
- width  : 375 (px)


**header**
- navigation menu 제외 
- => 햄버거 메뉴 기능으로 대체한 것으로 추측

**section**
- cards
    - width 작아졌으므로 한 줄에 표시되는 card 개수도 변경
      - => 한 줄에 1개씩 표시
    - 좁아진 화면에 맞춰 전체적인 width, height 값 변경
      - 특히 width 나 height 중 하나만 특출나게 길었던 직사각형 요소들도 height 가 더 긴 직사각형으로 통일

**footer**
- logo
- email input
- site map
  - 2 * 4
- => footer 요소 작성된 순서대로 위에서 부터 배치 됨