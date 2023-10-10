```js
var object1 = { same: 'same' };
var object2 = { same: 'same' };

console.log(object1 === object2, object1 == object2) 
```
console.log 에서 무엇을 출력할까요?
(보기 중 선택)

[1] true false
[2] false true
[3] true true
[4] false false

<br/>

내가 선택한 답안 : 2번  

❓ 답을 고른 이유
> '==='은 저장된 주소도 같아야 하고 '=='은 저장된 값만 같다고 알고 있어서 2번을 선택하였다.

<br/>

✅ 정답 : 4번
> 객체 데이터의 경우 참조 자료형으로 독립된 메모리 주소를 참조한다. 따라서 두 객체의 메모리 주소는 다르기 때문에 false, false가 출력된다.   


<br/>

```js
var val1 = false;
var val2 = 0
console.log(val1 === val2, val1 == val2) 
```
> 위 코드의 경우는 위의 내가 답을 고른 이유로 설명될 수 있다.   
객체일 때 주의하며 비교하자.