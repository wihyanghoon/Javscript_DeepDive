## 1.1 프로그래밍이란?

* 프로그래밍이란 컴퓨터에게 실행을 요구하는 일종의 <code>**커뮤니케이션**</code>
* 0과 1밖에 모르는 기계가 실행할 수 있을정도로 <code>**정확하고 상세하게 요구사항**</code>을 설명하는 작업
* 문제해결 방안을 고려할때 컴퓨터의 입장에서 봐라봐야한다. 이를 <code>**컴퓨팅 사고**</code>라 한다.

## 1.2 프로그래밍 언어
* 사람이 이해할 수 있는 <code>구문<sup>syntax</sup>(문법)</code> <code>프로그래밍 언어</code>를 사용해 컴퓨터가 이해 할 수 있는 기계어로 변환하는 일종의 번역기를 이용한다.
* 번역기를 <code>컴파일러</code> 혹은 <code>인터프리터</code> 라고한다.

```javascript
// 자바스크립트를 이용한 Hello World를 출력 하는 방법

console.log('Hello World');
```

## 1.3 구문과 의미
* 다른 언어와 마찬가지로 문법에 맞는 문장을 구성하는것은 물론 <code>의미<sup>semantics</sup></code>를 가지고 있어야 한다.

```javascript
// 문법적으로는 이상이 없다고 하여도 의미적으로 옳지않은것은 사용하지 말아야한다.


const number = "string";
console.log(number + number) // NAN
```

프로그래밍은 요구사항을 집합하고 분석, 적절한 자료구조와 함수의 집합으로 변환, 그 흐름을 제어하는 것이다.