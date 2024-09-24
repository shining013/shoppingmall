### 커밋
feat : 새로운 기능 추가  
fix : 버그 수정  
docs : 문서 수정  
style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우  
refactor : 코드 리펙토링  
test : 테스트 코드, 리펙토링 테스트 코드 추가  
chore : 빌드 업무 수정, 패키지 매니저 수정  

### 브랜치
기능 추가 => feature/#이슈번호   
오류 해결 => fix/#이슈번호

### 구현 시 어려웠던 점과 해결
모두 다 tailwindcss 사용법 익숙치 않음

윤주 : 검색창 구현 시 product.js 데이터에서 filter를 적용시켜 검색 결과로 출력하는 것을 구현했는데 
이 데이터를 map을 사용해 출력할 때 map을 사용하는데 약간의 에러가 나서 어려웠다.
map으로 돌리는 값을 중괄호 안에 넣어서 구현했다. 
그리고 출력된 데이터를 클릭하면 navigate를 사용해 그 상품 상세 페이지로 이동하도록 했다.
이걸 구현할 때 익숙하지 않아서 좀 시간이 걸렸다. 

준수 : pc화면으로 예쁘게 잘 나왔는데 모바일로 확인해보니 생각한대로 안 나와서 어려움을 겪었다.
swiper를 리액트에서 사용하려고 하니  
pagination, navigation을 커스텀하는 것이 어려웠다

채린 : 리액트와 tailwind 문법이 익숙지 않아 어려웠다
세부 카테고리페이지에서 파라미터 값에 따라서 데이터를 필터링하여 뿌려주는 부분에서 어려움

유정 : 장바구니 어려웠던 점
redux의 return 해야 하는 값을 잘못 입력해서 변경된 state가 뷰에 전달되지 않았던 문제를 겪었다.
처음 코드를 작성할 때 한 파일에 장바구니 더미 데이터와 데이터 변경 함수를 작성해서 관리하기 편하게 만드려고 했다. 
나중에 redux와 연결하면서 오히려 하위 컴포넌트에 어떤 함수를 dispatch해야 하는지 찾기 힘들었다. 
기능 구현 후 리팩토링 작업을 거쳤다.

효원 :  드로워를 tailwindcss material을 사용했는데 리액트랑 리액트 돔이랑 버전 충돌 문제가 있어서 원인을 찾는데 어려움, 옵션
