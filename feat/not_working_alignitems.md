## align-items가 적용이 안되는 현상 해결하기

> ### 결론

- align-items를 사용할 때는 높이를 명시적으로 설정해야 함.

<br />

> ### 문제 코드

```
.head-list {
    display: flex;
    list-style: none;
    align-items: center;    << 적용이 안됨.
}
```

<br />

> ### 개선 코드

```
.head-list {
    display: flex;
    list-style: none;
    align-items: center;
    height: 30px;          << 높이를 설정함.
}
```
