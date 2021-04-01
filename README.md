# TODO
# 1. 학습
## 1-1. JS 문법 및 ES6
- [X] for문 3가지 (forEach, for in, for of) (3/25 목)
- [X] Array 고차 함수 (map, filter, reduce 등)
- [ ] this 학습하기
- [ ] 콜백 함수 학습하기
- [ ] 오브젝트 클론 - Object.assign()

## 1-2. 리액트
- [ ] 리액트 일반적인 폴더 구조 학습하기 (왜 하는지, 했을 때의 효과)
- https://reactjs.org/docs/faq-structure.html
- 1.Group by features or routes
  - Make a folder by feature or route
  - Put related CSS, JS, and tests together inside 
  - - For instance, make folder of 'common', 'feed', and 'profile'
- 2.Group by file type
  - Group similar files together
  - For instance, make folder of 'api' and 'components'
- Avoid too much nesting: consider limiting yourself to a maximum of three or four nested folders within a single project. 
- Don't overthink it: You’ll likely want to rethink the file structure anyway after you’ve written some real code, so just start within 5 minutes.
- [ ] 리액트 functional component 학습하기
- [ ] 리액트 hook 학습하기
- [ ] 리액트 Eject 이해하기 (개발환경 관련)
- [X] 웹팩 강의 수강하기

## 1-3. 면접 및 개인 학습
- [ ] 조용구님 블로그 - 설계 섹션 공부하기

-https://chodragon9.github.io/
- [ ] 면접 질문 학습하기

-https://joshua1988.github.io/web-development/interview/frontend-questions/

-https://joshua1988.github.io/web-development/javascript/javascript-interview-3questions/
- [ ] localStorage & SessionStorage & Cookie 이론적 차이점 + 실제 코드에 세 경우 적용해보기
- [ ] git ignore 학습
- [ ] Open Graph Protocol 학습 (중요도 낮음, 포트폴리오 개선 위해)
- [ ] Kent C. Dodds Youtube 시청 (중요도 낮음)

https://www.youtube.com/user/kentdoddsfamily

## P.S.
- array-related functions: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
- every(), some(), find(), findIndex(), etc

# 2. 포트폴리오 정리
## 2-1. 개인 공부 학습한 것 적용
- [X] const 적용하기
- noteApp은 App.jsx에만 let이 있고 수정해야 함
- dogAPI는 Details.js에만 let이 있고 수정해야 함
- [X] for문 3가지 적용하기 (3/25 목)
- 모든 포트폴리오에 적용 완료 (3/25 목) [X]
- noteApp의 App.js에 존재하는 localStorage 관련 for-loop에 적용 아직 못함 (3/25 목) [ ]
- [ ] Array 고차 함수 적용하기
- [ ] 안쓰는 코드 정리하기
- [x] Prettier & ESLint 설정 후 적용하기
- [ ] ESLint 규칙(개인적으로 선호하는 규칙 집합 1개 정도 생성)
- [ ] bind() 빼고 넣을 때의 this가 무엇인지 알아보기
## 2-2. 각 포트폴리오 개선점
### 1) HTML5 WebRTC & Canvas API 포트폴리오 
#### To Do
- [X] 코드 최적화 (prettier&ESLint 적용)
- [X] 스타일링 개선
- [X] WebRTC & Canvas 코드 다시 짜기 - 사이즈 조절 문제  
#### 한계점
- [ ] 웹캠이 켜있지 않은 상태에서 브라우저 창 크기 조절시 두 캔버스의 크기가 동일하게 조정이 안됨

### 2) 도라에몽 미니게임 포트폴리오 
#### To Do
- [X] 코드 최적화(prettier&ESLint 적용)
- [X] 스타일링 개선
#### 한계점
- [ ] 스마트폰 사이즈 미지원: 미리 정해둔 캔버스 사이즈에 의존하는 함수 계산 때문에 캔버스 크기를 조정하기 원하면 함수의 계산 공식이 바뀌어야 함

### 3) Pokemon API 포트폴리오 
#### To Do
- [X] 코드 최적화(prettier&ESLint 적용)
- [X] 스타일링 개선
- [ ] 모바일 디바이스에서 무한 스크롤 기능이 잘 작동하지 않는 듯 싶음
#### 한계점
- [ ] API fetching 능력을 보여주기 위해 포트폴리오를 제작했고 목표를 잘 완수하나 기능이 부족하다고 여겨짐
  - 예를 들어 https://www.pokemon.com/us/pokedex/ 와 같은 사이트처럼 포켓몬을 검색하거나 필터링할 수 있는 기준을 제공하지 못함

### 4) 노트 앱 포트폴리오 
#### To Do
- [X] 코드 최적화(prettier&ESLint 적용)
- [X] 스타일링 개선하기
- [X] 파일 구조 재정립
- [X] form 스타일링 개선하기
- [ ] tag 버튼 적용/해제를 토글링으로 바꾸기
- [X] Desktop 
#### 한계점
- [X] 현업에서 쓰이는 노트 툴과 같은 스타일링이 어려움
#### Future To Do
- [ ] Grid의 각각의 아이템을 접을 수 있는 기능

### 5) Dog API 포트폴리오 
