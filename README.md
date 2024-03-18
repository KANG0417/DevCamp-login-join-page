# 로그인/회원가입 페이지

**진행날짜**: 2024.03.18~

# 목차
[24.03.18](#24.13.18-공부한-내용)

## 24.03.18 공부한 내용
### **shadcn/ui**  
재사용 가능한 컴포넌트 모음이다.
종속성이 없기 때문에 패키지 관리자로 따로 설치할 필요없이
프레임워크에(Next.js, Vite, Remix, Gatsby, Astron Laravel, Manual) 코드를 복붙에서
사용하면 된다.
대신에 components.json을 통해서 여러가지 설정을 할 수 있는 것 같다.
tailwind css에 환경에서 적용하는 방법이나 테마 설정, Next.js에서의 서버 컴포넌트 환경 설정,
또는 타입스크립트인지 자바스크립트에서의 환경 설정이 주다.
CLI((Command Line Interface, 명령프롬프트)을 통해서 설치하고 작업환경을 세팅할 수도 있다.

**장점**
- 다운 받을 필요 없이 바로 코드 복붙으로 사용 가능 하다.  
- ui가 깔끔하다.  

### **Zod**  
`npm install zod`  
`yarn add zod`  
`bun add zod`  
`pnpm add zod`  
중복 되는 유형선언을 없애기 위해 나온 도구로, 스키마 또는 유효성 검사 라이브러리이다.  
유효성 검사기를 만들어서 타입스크립트를 자동으로 추론해 줄 수 있다.  

**장점**  
- 다양한 패키지 관리자를 지원한다.
- 데이터베이스에 들어가는 데이터에 타입을 설정할 수 있다.
- 종속성이 없다. (불필요한 패키지가 깔리거나, 패키지 참조가 충돌하거나, 버전간의 호환성 문제를 걱정안해도 된다!)  

**버전**: 3.22.4  
**업데이트 된 날짜**: 5 달전  
**만든 날짜**: 4 년전(나온지 거의 얼마 안된 것 같다)  
**다운 용량**: 628 kB(무척 가볍다)  

### react-hook-form
`npm install react-hook-form`  
일단 npm을 통해서 설치해야 하며 폼이나, 에러메세지, 유효성검사 등
재사용할 수 있는 컴포넌트를 만들어주는 라이브러리이다.  

**장점**  
- 업데이트가 활발하다.
- 활용도가 다양하며, 참고할것이 많다.

**버전**: 7.51.1  
**업데이트 된 날짜**: 2 일전  
**만든 날짜**: 5 년전  
**다운 용량**: 898 kB  
