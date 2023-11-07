# react를 이용한 포트폴리오 사이트 만들기

## 설치 
1. 폴더를 만들고 리액트를 설치 `npx create-react-app 프로젝트 이름`
2. git에 업로드
3. [lenis 사이트](https://github.com/studio-freight/lenis) 

## 설치
1. react 설치 `npx create-react-app 프로젝트 이름`
2. gsap 설치 `npm i gsap`
3. sass 설치 `npm i sass`
4. lenis 설치 `npm i @studio-freight/lenis`
5. react-router-dom 설치 `npm i react-router-dom`

## 트러블 슈팅
<details>
<summary>Whitespace 에러 </summary>
유닉스 시스템에서는 한 줄의 끝이 LF(Line Feed)로 이루어지는 반면,
윈도우에서는 줄 하나가 CR(Carriage Return)와 LF(Line Feed),즉 CRLF로 이루어지는데
Git이 이 둘 중 어느 쪽을 선택할지 혼란이 온 것이다 !   

해결방법   
`git config --global core.autocrlf true` // 시스템 전체에 적용
`git config core.autocrlf true` // 해당 프로젝트에만 적용

GSAP
GSAP, 또는 GreenSock Animation Platform은 웹 애니메이션을 만들기 위한 강력한 JavaScript 라이브러리입니다. GSAP는 HTML, SVG, 캔버스 등 다양한 웹 요소를 애니메이션화하는 데 사용됩니다.

이 라이브러리는 강력한 기능과 직관적인 API를 제공하여 다양한 애니메이션 효과를 만들기 쉽게 합니다. GSAP는 성능이 우수하며, 애니메이션의 부드러움과 자연스러움을 유지하는 데 강점을 가지고 있습니다.   

lenis
lenis.js는 JavaScript로 작성된 오픈 소스 웹 프레임워크입니다. 이 프레임워크는 웹 애플리케이션 및 API를 개발하기 위해 사용됩니다. lenis.js는 경량화되고 빠른 속도로 동작하며, 간단한 문법과 구조를 제공하여 개발자가 쉽게 웹 애플리케이션을 구축할 수 있도록 도와줍니다.
</details>