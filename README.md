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

## firebase
<details>
Firebase는 Google이 모바일 및 웹 애플리케이션 제작을 위해 개발한 플랫폼입니다. 개발자가 고품질 앱을 구축하고, 앱 품질을 개선하고, 사용자 기반을 확대하는 데 도움이 되는 다양한 도구와 서비스를 제공합니다.

1. Firebase 실시간 데이터베이스 및 Firestore : 실시간으로 사용자 간에 데이터를 저장하고 동기화할 수 있는 클라우드 호스팅 NoSQL 데이터베이스입니다. Firestore는 더 나은 쿼리 및 확장 기능과 같은 더 많은 기능을 제공하는 최신 데이터베이스입니다.

2. Firebase 인증 : 백엔드 서비스, 사용하기 쉬운 SDK, 기성 UI 라이브러리를 제공하여 앱에 사용자를 인증합니다. 비밀번호, 전화번호, Google, Facebook, Twitter 등 널리 사용되는 연합 ID 공급자를 사용한 인증을 지원합니다.

3. Firebase Cloud Storage : 확장성을 고려하여 설계되었으며 Google 규모에 맞게 구축된 강력하고 단순하며 비용 효율적인 객체 스토리지 서비스입니다. 사진이나 비디오와 같은 사용자 생성 콘텐츠를 저장하고 제공할 수 있습니다.

4. Firebase Cloud Functions : Firebase 기능 및 HTTPS 요청에 의해 트리거된 이벤트에 대한 응답으로 백엔드 코드를 자동으로 실행할 수 있는 서버리스 프레임워크입니다.

5. Firebase 호스팅 : 웹 앱, 정적 및 동적 콘텐츠, 마이크로서비스를 위한 빠르고 안전한 호스팅을 제공합니다.

6. Firebase Analytics : Firebase SDK를 사용하여 정의할 수 있는 최대 500개의 개별 이벤트에 대한 무제한 무료 보고를 제공합니다. Analytics는 사람들이 iOS 또는 Android 앱을 사용하는 방식을 이해하는 데 도움이 됩니다.

7. FCM(Firebase Cloud Messaging) : Android, iOS, 웹 등 플랫폼 전반에서 사용자에게 알림과 메시지를 무료로 보낼 수 있습니다.

8. Firebase 앱 배포 : 신뢰할 수 있는 테스터에게 앱을 손쉽게 배포할 수 있습니다. 테스터의 기기에 앱을 빠르게 설치하면 피드백을 조기에 자주 얻을 수 있습니다.

9. Firebase 성능 모니터링 : iOS, Android 및 웹 앱의 성능 특성에 대한 통찰력을 얻는 데 도움이 됩니다.

10. Firebase Test Lab : 다양한 기기 및 구성에서 Android 및 iOS 앱을 테스트하기 위한 클라우드 기반 인프라를 제공합니다.

11. Firebase 예측 : Firebase Analytics와 통합되어 예측된 행동을 기반으로 동적 사용자 그룹을 생성합니다.

12. Firebase 동적 링크 : 앱 설치 프로세스 후에도 사용자를 앱 내의 특정 콘텐츠로 안내할 수 있는 동적 링크를 생성 및 관리할 수 있습니다.

13. Firebase 원격 구성 : 앱 업데이트를 게시하지 않고도 앱의 동작과 모양을 변경할 수 있습니다.
</dtails>
1. firebase 로그인
2. 프로젝트 만들기
3. TERMINAL로 프로젝트가 있는 폴더로 이동
4. C:\Users\line\Desktop\WEBS1111\react-project>firebase login
5. Allow Firebase to collect CLI and Emulator Suite usage and error reporting information? Yes
5. C:\Users\line\Desktop\WEBS1111\react-project>firebase init
6. ? Are you ready to proceed? Yes
7. ? Please select an option: Use an existing project
8. ? What do you want to use as your public directory? build
9. ? Configure as a single-page app (rewrite all urls to /index.html)? No
10. ? Set up automatic builds and deploys with GitHub? No
11. ? File build/index.html already exists. Overwrite? No
12. C:\Users\line\Desktop\WEBS1111\react-project>firebase deploy

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