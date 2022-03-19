## 박스 모델 / box model

> ### 모델의 구성
- content : 표현하고자 하는 내용 ex) 텍스트, 이미지 등
- padding : content와 border(테두리) 사이의 여백
- border : 테두리 선
- margin : 테두리 선에서 외부 공간 사이에서 가지는 여백
<br />
  
> ### box-sizing 속성
- box-sizing: content-box <br />
컨텐츠 영역을 기준으로 width, height 속성 적용됨.
기본값.

- box-sizing: border-box. <br />
테두리 영역을 기준으로 width, height 속성 적용됨.
<br />
  
> ### 적용 예시

```

모든 태그 border-box으로 지정하기

* {
  box-sizing: border-box;
}
```

