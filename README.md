Todolist
=========================================================================
* html, css, js를 이용해서 날짜, 요일, 시간, 할일들, 오늘의 명언, 바로가기 아이콘 등을 구현해 보았습니다.
# 기간
* 2021.10.21 ~ 2021.10.29
# 사용스킬
* HTML5, CSS3, JavaScript
# 기술 블로그
* https://you8775.tistory.com/category/Project/Mypage%20-%20JS
# 기능설명
1. 날짜    
* 날짜 요일 시간은 js에 있는 Date()를 활용해서 날짜, 시간, 요일 등을 변수로 저장한 뒤 html파일에 미리 구현되어 있는 Id에 추가하는 방식으로 구현했습니다.   
2. Todo     
* 할일들(todo)는 form을 만들어 놓은 뒤 이에 대한 submit event를 listen하면 입력된 정보와 hash값을 리스트에 저장하고 localstorage에 복사해준 뒤 html파일에 element를 추가합니다. todo를 삭제하는 것도 입력받는 동시에 만들어놓은 다음 이에 대한 click이 감지되면 hash 값을 리스트에 있는 값들과 비교하고, 그 hash를 가진 인덱스를 제외한 나머지 친구들을 리스트에 저장합니다. 그리고는 리스트를 출력해 줍니다.
3. 명언,배경화면     
* 오늘의 명언과 배경 사진은 여러개의 자료들을 준비한 뒤 리스트에 저장한 후 random()함수를 사용해서 리스트의 랜덤인덱스가 출력되게 설정해 주었습니다.
4. 아이콘 바로가기
* 즐겨 찾는 홈페이지들의 아이콘을 image src로 달아주고, 그 안에 href를 걸어주어서 바로 그 페이지로 이동할 수 있게 설정해 주었습니다.