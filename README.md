### [과제] 숙련주차 과제 답# hh99-lv2-exam
1. 추가하기 버튼을 클릭해도 추가한 아이템이 화면에 표시되지 않음.
- 추가하기 버튼을 눌렀을때 실행되는 함수에 리듀서로 보내는 역할을 하는 dispatch 함수가 빠져있어서 내용이 담긴 todo객체를 넣어 리듀서로 전송한 후 리듀서에서 리턴받아 저장했습니다.

2. 추가하기 버튼 클릭 후 기존에 존재하던 아이템들이 사라짐.
- redux 부분에서는 todos리스트를 리턴하면서 payload로 받은 새로운 내용들을 계속 추가 해줘야 하기 때문에 ...전개연산자를 사용해서 기존에 객체들을 넣어주고 새로 받은 객체들을 추가해서 리듀서에서 새로운 배열을 반환 받았습니다.

3. 삭제 기능이 동작하지 않음.
4. 상세 페이지에 진입 하였을 때 데이터가 업데이트 되지 않음.
5. 완료된 카드의 상세 페이지에 진입 하였을 때 올바른 데이터를 불러오지 못함.
6. 취소 버튼 클릭시 기능이 작동하지 않음.
7. 선택) 과제를 마쳤다면 배포도 한번 해볼까요?
