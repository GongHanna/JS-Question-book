# ✍🏻우당탕 자바스크립트 문제풀이✍🏻 #

목표 : 배웠던 자바스크립트를 활용하여 문제를 내고 풀어보자

## 2. 한글로렘입숨 생성기 ##

👇🏻작업물 보러가기👇🏻
[한글로렘입숨생성기](https://javascript-team-project.github.io/javaScriptTeamProject/)

기여자 : 공한나, 안윤지

**선정 이유**
- 선생님께서 즐겨 사용하시던 한글 입숨 페이지(「청춘예찬」과 「별 헤는 밤」을 소스로 하는)가 사라져 아쉬워하는 선생님을 위해 제작하기로 하였습니다.

**목표**
1. 랜덤으로 한글 입숨 생성하기
2. 생성, 짧게, 중간, 길게 버튼 '클릭 시' 출력되는 이벤트 발생
3. 함수, 배열, for문, if문, document.querySelector(), addEventListener를 사용해서 제작

**제작 과정**
1. 랜덤으로 나타날 배열을 제작한다 (별 헤는 밤을 소스로 선정)
2. 짧게, 중간, 길게의 배열 범위 선정(짧게 : 10~15, 중간: 25~30, 길게: 40~50)
3. 반복이 되어야 하기 때문에 for 문을 사용하여 사용자가 input 창에 숫자를 입력한 값만큼 랜덤 단어가 나타나야 함
4. 랜덤 단위 사이의 공백(띄어쓰기) 필요 -> for 문을 사용하여 빈 공백 생성 및 추가
5. input 창에 숫자 외의 것을 입력하거나 0을 입력했을 시 HTML에 "0 이상의 숫자를 입력해주세요" 메세지 출력
6. Math.floor 및 Math.random 사용하여 랜덤으로 배열 생성

**제작 과정 이슈**
1. 함수를 호출했는데 결과값이 보이지 않는다!
    - 해결방법: 자바스크립트 내에서 함수에 코드를 작성하면 return를 작성. return를 작성하지 않으면, 함수를 호출했을 때 결과값(data)를 반환하지 못해 결과값을 볼 수 없음.
  
2. 이슈: 랜덤 단위 생성까지 성공했지만 공백이 존재하지 않아 보기 불편!
    - 해결방법: if 조건문과 Math.floor 및 Math.random, .repeat()를 사용하여 공백을 만들어내는 조건문 생성 및 적용.
  
**리뷰**
- 자바스크립트를 배운지 얼마 지나지 않아서 배웠던 내용들을 토대로 주제를 선정해 문제를 만드는 과정이 많이 어렵고, 많은 공부가 필요했다.
- 하지만 점점 완성되고 이슈들을 해결하는 과정에서 즐거움과 뿌듯함을 느낄 수 있었다.
- 앞으로 더 많은 코드들에 대해 공부하고 예제들을 연습할 때 자주 사용하게 될 것 같아서 좋았다😁