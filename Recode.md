# TodoList 개발일지

## 2019/2/21
- 프로젝트 생성
- 입력폼, 입력 기능, 날짜 지정, 디데이 기능 구현
- 할 일 리스트 출력 구현
- 마감날짜 - 입력날짜 해서 디데이를 만들자

## 2019/2/21
- 등록날짜, 마감날짜, 디데이 기능 제거
    - 입력내용이 많아서 사용자 피로도가 증가한다고 판단
    - 왜 굳이 날짜가 필요하냐는 반응이 많았고, 차라리 중요도로 해달라는 의견이 있었음

## 2019/2/25
- complete 버튼 누르면 완료된 할일 목록 리스트로 옮겨지는 기능 추가
- 필터링, 검색 기능추가 : 중요도에 따른 필터링, 입력하는 키워드에 따라 바로바로 검색
- 삭제 기능 추가
- Revert 버튼 클릭시 다시 할일 목록으로 돌아가는 기능 추가
- Reset 버튼을 누른 뒤 다시 같은 라디오 버튼을 누르면 onChange가 실행되지 않아 입력에 오류가 생겨서 일단 Reset 버튼을 삭제했다.
- 입력폼에서 배경을 누르면 입력폼이 사라지는 처리 추가. X버튼 왜 필요한것...?