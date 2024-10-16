# React History
- 기존 복잡한 MVC 패턴에서 Flux 패턴으로

# Javascript for REACT
```js
typeof null === 'object' // true
```

`String`을 포함한 원시타입은 불변
```js
let hello = 'hello'
let hi = 'hello'
hello === hi // true
```


> TODO: 리액트에서의 동등비교를 완벽이해

클로져: 호출되는 방식에 따라 동적으로 결정되는 `this`와 다르게 코드가 작성된 순간에 정적으로 결정
> 정의: 함수와 함ㅅ무가 선언된 어휘적 환경의 조합
-> `useState`가 동작할 수 있는 이유!

`{}` 로 스코프 범위를 지정하지 않는다. (기본적으로)


> [js visualizer](https://ui.dev/javascript-visualizer)

# Record
```js
type studentNames = {
  name1: string;
  name2: string;
  name3: string;
  name4: string;
};
```

```js
type studentNames = Record<
  'name1' | 'name2' | 'name3' | 'name4',
  string 		
>;
```
# Bonus
> WebWorker, Worker(in Node)

브라우져 랜더링은 마이크로 태스크 큐(promise)와 태스크 큐 사이에서 일어난다. 

`forEach`는 에러를 던지거나 promise를 종료하지 않는 이상 멈출 수 없다.

# Question
인덱스 시그니처를 쓰나..?!