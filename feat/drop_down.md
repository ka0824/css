## drop down 메뉴 만들기

> ### 결론
- 평소에는 display: none 속성을 가짐
- 상위 엘리먼트가 hover될 때 display: block으로 해당 엘리먼트 나타나게 함

> ### 에제 코드

```
<ul className="menu-name">테스트 메뉴</ul>
  <li className="sub-menu">하위 메뉴1</li>
  <li className="sub-menu">하위 메뉴2</li>



.css 

.menu-name:hover .sub-menu {
  display: block;
}

.sub-menu {
  display: none;
}

```
