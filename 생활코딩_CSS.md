# 생활코딩

## WEB2 - CSS



1. Introduction

* 웹페이지를 좀더 아름다우면서 보기 좋게 만드는 방법에 대한 불만족



2. The world before CSS

* 쉬운길; HTML의 문법에 태그 추가.
* `<font></font>`



3. The advent of CSS

* 주석표시: `<!--""-->`
* CSS. 새로운 언어.
  * `<style></style>`
  * `tag_name {color:red;}`
    * HTML에서의 font color = CSS에서의 color
  * 중복된 코드를 제거할 수 있다. 유지보수. 가독성.
  * HTML이 정보에 전념하기 위해서 디자인의 기능을 뺏어온 것.
  * HTML을 통해서 디자인하는 것보다 더 효율적.



4. Basic grammar of CSS

* 속성

  * html태그에 style 속성 사용.

  * `style="color:red"`: html 속성

  * ```css
    <style>
    	a {									/*selector*/
        color:black;			/*declaration (property:value)*/
      }										
    ```

    * 효과를 누구에게 지정할 것인가?: "a {}" - **Selector**, 선택자
    * 효과?: **Declaration** - "선택자를 사용할 필요는 없다. (style 속성)"



5. Revolutionary change

* 2 paths
  * 어떠한 property가 존재하는가
  * 그 효과를 더 정확하게 선택하기 위해서 다양한 selector 알아보기



6. Learn CSS properties on your own

* 불만족스러운것? - h1태그를 좀더 크게, 가운데 정렬로 하고싶다?

* 검색: "CSS text size property" / "CSS text center property"

  * ```css
    h1 {
      font-size:45px;
      text-align: center;
    }
    ```



7. Basics of CSS Selectors

* 모든링크는 기본적으로 검은색, 방문했던 각각의 글들은 회색, 현재 페이지는 빨간색
* 인라인 태그는 지움.
* **class 속성**: html태그에 인라인으로 적용
  * CSS style태그에 '.'을 붙여서 사용
  * 여러개의 속성이 들어올 수 있다. 순서가 중요. 가장 나중에 있는 명령이 더 큰 영향력
* id selector > class selector > tag selector
  * id 는 단 한번만 등장 가능. 중복 X
  * 구체적일수록 우선순위가 높다.
* 검색: "css selector"



8. Box Model

* **"Box Model"**이라는 개념

  * a태그는 줄바꿈 X, heading태그는 줄바꿈 O

  * 경계선을 그어서 태그의 크기를 알아보자

  * **"block level element"** / **"inline element"**

  * display:inline / display:block 으로 변경 가능

  * display:none으로 태그가 보이지 않게 할 수도 있음

  * ```css
    h1, a {
      /*border-width:5px;
      border-color:red;
      border-style: solid;*/
      border: 5px solid red;
    }
    ```



9. How to use Box Model

* border-bottom, margin, padding
* border-right, width
* 개발자모드로 margin, padding 확인



10. Introduction to Grid

* design이라는 목적을 위해 어떤 의미도 없는 태그. "**div**"(division) 또는 span

* ```css
  display:grid;
  grid-template-columns:150px 1fr;
  ```

  * fr로 나머지. ex) 2fr 1fr일 경우 2/3 1/3

* caniuse.com



11. Using Grid

* "나란히 놓는다" -> grid
* `#grid ol {}`: ol태그 중 부모태그의 id="grid"인 ol태그
* `#grid #article {}`: id="article"인 태그 중 부모태그의 id="grid" 



12. Introduction to Media Queries

* responsive design: 반응형 디자인.

  * 화면의 크기에 따라 요소들이 반응해서 최적화된 모양으로 바뀜.

  * **media query**

    `@media(min-width: 800px) {}`: 화면의 크기가 800px이 넘어가면, 다음 내용을 실행.



13. Using Media Query

* 



14. Recycling CSS Code

* 뭔가를 바꾼다? 모든 웹페이지의 중복되는 것들? "중복의 제거"?
* `<link rel="stylesheet" href="style.css">`
* **Caching**: "저장"
  * 네트워크적인 측면: CSS코드를 내장 vs CSS코드 다운 -> 내장이 효율적 BUT
  * caching을 통해 훨씬 더 빠르게 웹페이를 보여주고, 네트워크 트래픽(사용료) 절감
  * 따라서, css코드를 작성했다면, 중복될 일이 많다면, 파일로 저장하는게 효율적