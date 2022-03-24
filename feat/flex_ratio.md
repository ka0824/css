## flex 비율로 정리하기

하위 엘리먼트에 flex-grow 속성을 적용.

```
.parent {
  display: flex;
}

.first-child {
  flex-grow: 1;
}

.second-child {
  flex-grow: 1;
}


=> parent의 자식 엘리먼트가 first-child와 second-child만 있을 경우
50%, 50% 비율로 나뉘어서 표현된다.

```
