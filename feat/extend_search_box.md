## 검색할 때 검색창 동적으로 늘리기

가상 클래스 선택자 focus 사용

```

input {
  width: 40px;         //   늘리기 전 검색창 길이
  transition: 0.4s;    // 검색창 늘리는 애니메이션 실행되는 시간
}

input:focus {
  width: 120px;        //   늘린 이후의 검색창 길이
}

```
