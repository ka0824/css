## 구분선 만들기

가상 클래스 선택자 ::before, ::after를 사용.

```

구분하고 싶은 css 선택자::before {
  content: "";                  // 구분선에 넣을 텍스트, 선만 그릴 것이라면 공백으로 둠.
  background-color: 구분선 색깔    // 구분선의 색깔
  top: 0;
  bottom: 0;
  margin: auto;
}


맨 처음 구분선 제거하기

구분하고 싶은 css 선택자:first-child::before {
  display: none;
}


```
