# Algorithm
알고리즘 문제 풀이

## 자바스크립트 알고리즘 문제풀이
혼자 고민해보고 강의 들으면서 공부 중😁  
듣고 있는 강의 -> [인프런](https://inf.run/HfQv)  
  
1. [세 수 중 최솟값](SY-Algorithm/1-1.js)<br>
**- 'if'문 간결하게 작성하기**<br>
```
if( a>b ) answer=a;
else answer=b;

//물음표 연산자
a>b ? answer=a : answer=b;
```

---
2. [삼각형 판별하기](SY-Algorithm/1-2.js)<br>
**- 삼각형 만드는 공식**<br>
가장 긴 막대의 길이가 나머지 두 막대의 합보다 크거나 같아야 삼각형이 만들어진다.<br>
이 공식을 이용해 a,b,c 중 최대값 max 를 구해서 해결할 수 있다.
---
3. [연필개수](SY-Algorithm/1-3.js)<br>
**- Math()**<br>
Math.ceil() : 소수점 올림, 정수 반환<br>
Math.floor() : 소수점 버림, 정수 반환<br>
Maht.round() : 소수점 반올림, 정수 반환
---
4. [1부터 N까지의 합](SY-Algorithm/1-4.js)

---

5. [최솟값 구하기](SY-Algorithm/1-5.js)<br>
- Number.MAX_SAFE_INTEGER
자바스크립트에서 안전한 최대 정수를 반환해 준다.<br>
- Math.min/max
```
let arr=[1,3,5];
let answer1 = Math.min(1,3,5);
console.log(answer1); //1 -> 소괄호 안에 인자값이 들어가야 값을 구해준다.

let answer2 = Math.min(arr);
console.log(answer2); //NaN -> 소괄호 안에 배열 자체를 넣으면 값을 구해주지 않는다.

let answer3 = Math.min(...arr);
console.log(answer3); //1 -> 전개연산자를 이용해 Math 를 활용할 수 있다.
console.log(...arr); //1,3,5

let answer4 = Math.min.apply(null, arr);
console.log(answer4); //1
```
- 전개 구문(...arr)
❗브라우저 호환성 : IE x





---
6. [filter algorithm](https://www.notion.so/ES6-a1e92905808b4b8cbe8667b752495b8a);
- filter
```

```
