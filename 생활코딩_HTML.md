# 생활코딩

## WEB1 - HTML & Internet



1. **수업소개**

* 나의 문제를 코딩으로 해결하려는 "엔지니어"가 되어보자!



2. **How this project started**

* "HD화질"의 강의



3. **Product Design**

* 만들기 전에 무엇을 만들 것인가? -> "기획"



4. **Coding and HTML**

* 어떤쪽이 "사람"이 하는 쪽이고, 어떤쪽이 "기계"가 하는 쪽인가.
* "원인"과 "결과" 파악
* Code, Source, Language: 
* Application, App, Program, Webpage, Website:
* 바라보는 "관점"에 따라 "이름"이 다르다.
* `HTML`이라는 언어를 살펴보자! `HyperText Managing Language`
* "Public Domain"



5. **Preparing environment for practicing HTML coding**

* HTML도 이해하고 사람도 이해할 수 있는 코드를 작성할 프로그램이 필요하다.
  * "편집하는 프로그램": `editor`
* 생활코딩에서 쓰일 HTML Editor: "ATOM"
* http://atom.io
* `web`디렉토리 안에 `1.html` 만들기
* 웹페이지를 연다? -> 주소를 입력한다? => 다른 컴퓨터에 저장돼있는 웹페이지를 열기 때문에 주소를 입력한다.
* 내컴퓨터에 `1.html`파일을 연다 -> 웹브라우저에서 command + alphabet 'O'
* 웹페이지를 만들었고, 웹페이지를 웹브라우저로 실행한 것/열어본 것



6. **Basic syntax: Tags**

* `Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications.` 에서 **creating web pages**  강조하고싶다? => `"Tag"`
  * `<strong>""</strong>`
  * 반드시 save 후 reload
  * 여기서 **web**을 더 강조하고싶다? => "밑줄" 'u'nderline
    * `<u>""</u>`
* "Tag": (ex. price tage, '상품정보')



7. Revolutionary Change

* `h` tag (headings): `h1` `h6`



8. Statistical Learning

* 150개의 tags - 다 외울 필요 X
* 통계를 통해 어떤 방식으로 공부해야할지 알아보자.
  * www.advancedwebranking.com에 의하면 보통 25-26개의 tag로 이루어져 있다.



9. Wrapping

* "단락". 코드에서 줄바꿈을 해도 웹페이지에서는 반영 X
* "줄바꿈 태그": search "html new line tag"
  * `<br>`: 시각적인 의미만 갖고 있다. -> closing tag X
* 단락을 표현할 때 써야하는 태그: search "html paragraph tag"
  * `<p></p>`: opening tag and closing tag.



10. Why HTML is important

* **business** and **accessibility(humanism)**



11. The last attributes(속성) and img

* Include images. `<img>` tag.
  * 태그의 이름만으로는 정보가 부족하다.
  * `<img src="filename">` 
    * `src`: "source"
    * unsplash.com => good quality images website
* `<img src="coding.jpg" width="100%">`
  * `src="coding.jpg"` & `width="100%"`: **"Attribute"**
    * 위치/순서는 상관없음.
    * 태그 이름만으로는 정보가 부족할때 **"속성"**을 이용한다.



12. Parent-child relationships and lists

* 목차/목록 태그 => **"list"**,  `<li>`
*  `<ul>`: **"Unordered list"**. (`<li>`의 부모태그)
  * 목록의 경계를 나누기 위해 쓰는 태그. grouping parent tag.
  * `<ul>` `<li>`
* `<ol>` (instead of `<ul>`): **"Ordered list"**
  * 숫자가 자동으로 numbering



13. Document structure and superstars

* `<title>`: 웹페이지의 타이틀 태그. 검색엔진에서 책으로 비유하면 책표지와 같은 정보로 사용.
* 파일을 utf-8코드로 저장 -> 웹페이지를 열 때도 utf-8코드로 열어야 한다.
  * `<meta charset="utf-8">`
    * `charset`: character set
* 본문은 `<body>`, 본문(body)을 설명하는 `<head>`: "고위직 태그"
* 전체를 감싸는 `<html>`: 최고위층 태그
  * `<!doctype html>`: 관용적으로 `<html>`태그 위에 '이 문서는 html파일이다'를 표시



14. The lords of HTML tags

* `<a>`: **"anchor. 닻"**, 정보의 바다에 정박한다. => ***link***
* 링크를 걸고싶은 곳에 a태그로 감싼다. 그러나? 정보가 부족하다. anchor를 어디로 내려야 할지.
  * `href` attribute(속성): 'h'ypertext 'ref'erence
  * `target="_blank"`: 클릭했을때 새 탭에 열리게
  * `title="html5 specification"`: 툴팁으로 클릭하기전에 정보제공



15. Completing a website

* atom editor 다루는법
* 웹페이지들을 엮어서 하나의 완성된 웹사이트를 만들어보자!
* WEB 클릭하면 -> index.html
* 1. HTML 클릭하면 -> 1.html
  2. CSS 클릭하면 -> 2.html
  3. Javascript 클릭하면 -> 3.html



16. Primitive Web

* 내가 만든 웹사이트를 공유한다. -> "웹사이트란 무엇인가?"
* 웹의 역사
  * 인터넷과 웹이 어떻게 세상에 등장했는가.
  * 정보기술을 바라보는 관전포인트 넓히기.
* **Internet** VS **Web**
  * Internet > Web
    * 인터넷을 하나의 도시라면, 웹은 그 도시안에 있는 건물 하나.
  * 1960년 Internet 등장
    * 1960년대의 화두. "핵".
    * 중앙집중적 통신. -> 핵공격에도 견딜 수 있는 강인한 통신 필요 -> "Internet"
    * 수많은 통신장치들이 분산해서 전화국과 같은 역할. 
  * 30년 후, 1990년 Web의 등장
    * Switzerland, 정밀기술, 금융, 산좋고 경치좋은 시골의 느낌
    * Why Switzerland?
      * CERN. 유럽입자물리연구소
      * Higgs boson 입자.
    * Tim Berners Lee
      * "Enquire" + Internet
      * http://info.cern.ch/



17. The key to the Internet: Server and Client

* 인터넷이 동작하는 기본원리
  * 최소 컴퓨터 2대 필요. 1대는 인터넷이 아니고, 3대는 본질적이지 않다.
  * "Web Browser"컴퓨터 + "Web Server"컴퓨터
    * Internet으로 연결
    * Web Server 컴퓨터는
      * http://info.cern.ch라는 주소를 가지고 있고,
      * 하드디스크 안에 index.html이라는 파일이 있다.
    * Web Browser 컴퓨터에서
      * http://info.cern.ch/index.html을 친다면?
    * Web Browser에서 info.cern.ch에 index.html파일 열기를 **"요청"**. Web Server에서 index.html코드를 Web Browser로 **"응답"**. Web Browser에서 코드를 해독하여 화면에 표시. -> Web 동작. 정보를 주고받음.
    * "자본주의의 관계": "고객"과 "사업자".
      * **"Client"** & **"Server"**
* Web Server를 사용할 줄 안다? -> 내가 만든 웹페이지를 다른 누군가가 볼 수 있다.
  * "Web Hosting" VS "Web Sever"



18. Web hosting: Github pages

* 웹서버를 제공해주는 회사: Web hosting 업체 - **"Github"**
* new repositories - public check - initialize this repository with a README check - upload files - choose files - commit changes(with messages)
* settings - github pages - source - master branch



19. Managing a Web Server

* 내컴퓨터에 웹서버 설치하기.
* 인터넷이 동작하는 원리 알아보기.
* **Apache** - MAC OS
  * bitnami mama stack
  * "manager-osx" application
  * /Applications/mampstack-8.0.9-0/apache2/htdocs 디렉토리에 html파일
  * **"127.0.0.1"**: IP(Internet Protocol) address
  * **"8080"**: PORT. 맥에는 기존 웹서버가 존재. 기존 웹서버와 구분하기 위해 존재.
* **Web Server and HTTP (Mac)**
  * **"HTTP"**: Hyper Text Transfer Protocol. 웹페이지를 전송하기 위해 고안된 통신규약.
* **Communication between Web Server and Web Browser (Mac)**
  * Web Browser가 Web Server에게 파일을 요청하기 위해서는 IP Address가 필요하다.
  * Web Server가 설치된 컴퓨터의 IP를 어떻게 알 수 있을까? & 스마트폰으로 실습
  * System Preference -> Network -> (Connected)Wi-Fi Advanced -> TCP/IP -> IPv4 Address(내 컴퓨터의 IP주소)
    * 같은 와이파이 공유. http://192.168.0.9:8080/index.html



20. Conclusion

* 충분히 불만족하라. -> 충분히 좌절하라. -> 공부해라.



21. Appendix

* 



