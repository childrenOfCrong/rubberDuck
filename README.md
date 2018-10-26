# rubberDuck
rubber Duck Study


### 1회차 KeyWord Closure

나온 질문들:D

---

### 2회차 KeyWord Execution-context

나온 질문들 :D 

---

### 3회차 KeyWord Prototype

* 개선점: 인터뷰 예제를 참고해서 질문을 구성하자
* 주제: prototype
* 시간: 미정(목요일 또는 금요일) 

---

### 4회차 KeyWord Prototype

* 개선점: 인터뷰 예제를 참고해서 질문을 구성하자
* 주제: prototype
* 시간: 0706 16:00-17:40 

나온 질문들 
1. 프로토타입 체인이 어떻게 작동하는지 설명하시오
2. 왜 자바스크립트는 프로토타입을 사용하나요?
3. 생성자 함수가 인스턴스를 만들 때 인스턴스와 생성자 함수 prototype이랑은 어떻게 연결이 되는지 설명해보시오 
4. prototype 을 이용하여 instance 생성과 코드를 재사용하는 방식을 코드를 적어 설명해보기 [참고 toast meetup](http://meetup.toast.com/posts/104)
* ETC -> 기존 class기반 언어와 prototype언어와의 차이점 장단점 

---

### 5회차 KeyWord Arrow function

* 개선점: 
1. github-wiki에 자신이 정리한 자료 올리기(선택) > 틀린자료 있으면 수정해주기 
2. 당일 나온 질문들 한사람이 정리해서 github에 올리기

* 주제: arrow function
* 시간: 0713 16:00-17:20 

나온 질문들 
1. function과 Arrow function의 차이점에 대해 설명해주세요.
2. function과 arrow function을 사용하는 자신만의 기준은 무엇인가요?
3. addEventListener 함수의 콜백 함수를 화살표 함수로 정의하면 this 는 어디를 가르키는가? 

---

### 6회차 KeyWord Network


* 개선점: 질문 시간이 오버되지 않도록, 인터뷰어는 질문 시간과 질문양을 조절한다.
* 주제: www.naver.com을 검색했을 때 브라우저에 화면이 띄워지는 과정을 설명하시오.
* 시간: 0720 16:00-17:20 

나온 질문들 
1. 브라우저에다가 https://www.naver.xn--com-of0o 입력했을 때, 접속하는 과정에 대해 자세히 설명해주세요
2. 질문 TCP/UDP차이를 설명하시오
3. http의 get방식과 post방식에 대해 설명하세요
4. 각 계층마다 왜 헤더가 있는지

---

### 7회차 KeyWord HTTP(cache, cookie)

* 시간: 0727 16:10-17:20 

나온 질문들 
1. 쿠키와 캐시는 무엇인가?
2. 쿠키와 캐시는 왜 사용하는가?
3. 쿠키의 통신 과정은?
4. 쿠키 캐시의 장단점
5. 쿠키와 캐시의 차이점

---


### 8회차 KeyWord 스코프와 클로저 

* 시간: 0921 16:00

나온 질문들 

1. Scope가 무엇인가요?/ let/const에 대해서 설명
2. 클로저는 어떻게 동작하나요?
3. 렉시컬스코프에 따른 변수의 참조위치는?
4. 자바스크립트 엔진이 var a = 2; 를 처리하는 과정에 대해 설명해보기.
5. 클로저 정의/클로저 프로젝트에서 어떻게 활용했는지

---
### 9회차 KeyWord : 실행컨텍스트(Execute Context, EC)

* 시간: 0928 16:00-17:00

나온 질문들 
1. 실행컨텍스트 개념과 실행컨텍스트가 실행될 때 필요한 정보들은 어떤 형태? 어떤 것들이 담기는지 아는데로 설명해보시오
2. 스코프 체인은 실행컨텍스트를 어떻게 활용하는지 그 과정에 대해서 설명해보시오
3. 아래 코드에서 'use strict'가 있을 때, 없을 때의 결과의 차이가 생기는 이유는?
```javascript
// "use strict";

let person = {
  name: ‘peter’,
  birthYear: 1994,
  calcAge: function() {
    console.log(2018 - this.birthYear);
 }
};

person.calcAge(); // ?

let calculateAge = person.calcAge;

calculateAge(); // ?
```

---
### 10회차 KeyWord : this

* 시간: 1005 16:00-17:00

나온 질문들 
1. 객체 리터럴과 생성자 함수의 차이점은?
2. 객체 리터럴이 아닌 생성자함수를 써야 하는 상황은?
3. 비동기 함수안에서의 this가 가리키는 것과 그 이유는?
4. 렉시컬 스코프와 this의 생성방식 차이점은?
5. 아래 코드에서 각 호출 방식에 따른 바인딩 우선순위에 따른 결과값은?

```javascript
// 명시적 바인딩과 new 바인딩의 우선순위

function hello(name) {
  this.name = name
}

var obj1 = {
};

var helloFn = hello.bind(obj1);

helloFn(‘hello’);

var obj2 = new helloFn(‘world’);

console.log(obj1.name); // ?
console.log(obj2.name); // ?
```

---
### 11회차 KeyWord : OOP(Object-oriented programming)

* 시간: 1012 16:30-18:00


나온 질문들 이라기보다 같이 공부
1. OOP의 특성 캡슐화, 추상화, 상속, 다형성 ...
2. super접근 가능한 부분 같이 확인  
3. JS class에서 상속 어떻게 구현하나

* [JS_객체지향](https://developer.mozilla.org/ko/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [클래스_생성자함수_차이](https://gomugom.github.io/is-class-only-a-syntactic-sugar/)

---


---
### 12회차 KeyWord : Promise & Async Awiat 비동기 처리

* 시간: 10.26 17:00

나온 질문들
1. JS비동기 처리 어떻게 동작하는지
2. Error핸들링 처리 어떻게 하는지
3. 어떤 상황에서 제너레이터로 이터레이터를 만드는지
4. 제너레이터를 사용할 때 주의해야 할 점

* [제너레이터 강의](https://www.youtube.com/watch?v=82UuFxh7wKc&index=5&list=PLBNdLLaRx_rIF3jAbhliedtfixePs5g2q)
---

---
### 12회차 KeyWord : css & javascript 애니메이션 차이

* 시간: 11.02 16:00 예정

---
#### reference 

* [프론트엔드_인터뷰_핸드북](https://github.com/yangshun/front-end-interview-handbook/blob/master/Translations/Korean/README.md)
* [front-end-handbook-2018](https://frontendmasters.com/books/front-end-handbook/2018/)
* [신입프론트엔드_면접질문](https://taegon.kim/archives/5770)
* [프론트엔드_면접_은행](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Korean)
* [essential_js_interview_qna](https://www.toptal.com/javascript/interview-questions)
* [10_interview_questions_you_should_know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)


#### 찾아보기 좋은 사이트들 


* [mdn](https://developer.mozilla.org/ko/docs/Web/JavaScript)
* [poiemaweb](https://poiemaweb.com/)
* [toast](http://meetup.toast.com/)
* [freeCodeCamp](https://guide.freecodecamp.org/javascript/)
