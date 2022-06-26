# Web 기본기 테스트
COW HTML, CSS, JS 기본기 테스트를 위한 Repository입니다.

### 과제 진행 및 제출 방식
1. [과제 Repository](https://github.com/MJU-Coin/22-S-basic-test)를 fork하여 개인 Repo를 생성
![Github Fork 하기](https://user-images.githubusercontent.com/61923768/175819407-61e3df49-11f9-4565-b358-5d5fd399b45d.png)
![Github Fork Detail](https://user-images.githubusercontent.com/61923768/175819509-bd16563f-c37f-4183-95a1-9455390e0335.png)
2. 개인 Repo에서 과제 작업 진행
3. 여러분의 개인 Repo에 작업하며 
4. 이 Repo에 PR을 보내어 멘토의 코드 리뷰와 피드백을 받으세요.

### Branch 명명 규칙 + 팀의 PR규칙 정하기
1. 여러분 repo는 알아서 해주시고 😀(본인 레포니 main으로 하셔두 되져)
2. prgrms-be-devcourse/spring-board 레포로 PR시 branch는 gituser_id을 적어주세요 :)  
    - base repo : `여기repo` base : `username` ← head repo : `여러분repo` compare : `main`또는 `github_id`
3. 실제 진행할 PR규칙은 멘토+팀원들과 정하여 진행해주세요 :) 
    - ← head repo : `여러분repo` compare : `main`로 할지
    - 또는 ← head repo : `여러분repo` compare : `github_id`로 할지
- 참고 : [Github 위치 및 피드백 기준 가이드](https://www.notion.so/backend-devcourse/Github-e1a0908a6bbf4aeaa5a62981499bb215)

### 과제를 통해 기대하는 역량

- 깃허브를 통한 코드리뷰를 경험해보자
- 기본적인 테스트 코드 작성 및 활용하는 능력해보자
- 스스로 OOP를 생각하고 코드로 옮길 수 있는 능력해보자

### 요구사항
- 콘솔로 구현입니다.(스윙으로 구현하시는 분들 계실까봐) 
- 객체지향적인 코드로 계산기 구현하기
    - [ ]  더하기
    - [ ]  빼기
    - [ ]  곱하기
    - [ ]  나누기
    - [ ]  우선순위(사칙연산)
- [ ]  테스트 코드 구현하기
- [ ]  계산 이력을 맵으로 데이터 저장기능 만들기
    - 애플리케이션이 동작하는 동안 데이터베이스 외에 데이터를 저장할 수 있는 방법을 고안해보세요.
- (선택) 정규식 사용

### 실행결과(콘솔)
```
1. 조회
2. 계산

선택 : 2

1 + 2
3

1. 조회
2. 계산

선택 : 2

1 + 2 * 3
7

1. 조회
2. 계산

선택 : 1

1 + 2 = 3
1 + 2 * 3 = 7

선택 : 2

3 - 2 * 2
-1
```
