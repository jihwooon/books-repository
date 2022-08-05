# 공간 제약 다루기

* 공간 복잡도의 빅 오
* 시간과 공간 트레이드오프
* 재귀에 숨겨진 비용
* 마무리

<details>
<summary>시간 복잡도와 공간 복잡도의 차이는 무엇인가요?</summary>
* 시간 복잡도는 알고리즘이 얼마나 빠른가에 초점을 두었다면 공간 복잡도는 알고리즘이 얼마나 메모리는 소모하는가 입니다.
이 둘 차이점은 빠르기와 메모리 차이점입니다. 
</details>

<details>
<summary>다음 코드를 보고 공간 복잡도 O(N) -> O(1) 변경 하려면 어떻게 해야 하나요?</summary>

```javascript
function maksUpperCase(array) {
   let newArray = [];
  for(let i = 0; i < array.length; i++) {
    newArray[i] = array[i].toUpperCase();
  }

  return newArray;
}
```

* 새로 배열 생성한 부분을 빼고 array로 바로 반환합니다.
</details>

