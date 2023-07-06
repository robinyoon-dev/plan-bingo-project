
#### 들어가기에 앞서 
이 repository에서는 다음과 같은 사항을 볼 수 있습니다.
- *플랜 빙고* 소개.
- *플랜 빙고* ver. 0.0.0부터 기록된 이슈 관리 사항.

ℹ️이 repository에서는 *플랜 빙고*의 코드를 공개하지 않는 점 양해바랍니다.

---
# 플랜 빙고
![ogimage](https://user-images.githubusercontent.com/107087958/225212949-0fcd5019-33db-4730-a003-766277923d48.png)


> 사이트: https://planbingo.vercel.app/

> 업데이트 노트:
https://robinyoondev.notion.site/63f4292fae454fbeb98fe83c695d9c01?v=682ff117c4c84f699b6445c0f889f446&pvs=4

## 개발 정보 
- 제작 기간: 2023.01.19 ~ 2023.03.12
- 기술 스택
  - 언어: 
![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?&style=flat-square&logo=HTML5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?&style=flat-square&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=flat-square&logo=JavaScript&logoColor=black)
  - 라이브러리/프레임워크/플랫폼: 
![React](https://img.shields.io/badge/React-61DAFB.svg?&style=flat-square&logo=React&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000.svg?&style=flat-square&logo=Next.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000.svg?&style=flat-square&logo=Vercel&logoColor=white)
  - 데이터베이스: 
![MongoDB](https://img.shields.io/badge/MongoDB-47A248.svg?&style=flat-square&logo=MongoDB&logoColor=white)
  - 기타: 
![Git](https://img.shields.io/badge/Git-F05032.svg?&style=flat-square&logo=Git&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?&style=flat-square&logo=Visual%20Studio%20Code&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000.svg?&style=flat-square&logo=Notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E.svg?&style=flat-square&logo=Figma&logoColor=white)

### 기술 스택 선택 이유

#### Next.js를 선택한 이유
 라우팅을 간소화할 수 있기 때문에 선택했습니다. 여기서 라우팅이란 사용자에게 이 애플리케이션이 여러 페이지가 있는 것처럼 착각하게 하는 것입니다. Next.js는 파일 기반 라우팅을 할 수 있습니다. Next.js 애플리케이션에는 특수 페이지 폴더가 있어서 페이지를 다루는데 용이합니다.

#### MongoDB를 선택한 이유
데이터베이스 후보로 Firebase, Supabase, MongoDB가 있었습니다.
그 중 MongoDB를 선택한 이유는 다음과 같습니다.

1. 자유로운 데이터 구조를 가질 수 있기 때문입니다. 프로젝트를 진행하면서 데이터 구조가 언제든지 변할 수 있다고 판단하여 NoSQL 데이터베이스를 택했습니다. 
2. 지금까지 NoSQL 데이터베이스를 사용해 본 적이 없어서 도전하고 싶었습니다.
3. firebase도 NoSQL 기반이지만 속도가 느리다는 문제가 있기 때문에 firebase 대신 mongoDB를 택했습니다. 
## 플랜 빙고란?
**“이루고 싶은 목표를 이뤄가며 빙고 해봐요.”**

플랜 빙고는 유저가 이루고 싶은 목표로 아홉 칸을 채우고 목표를 이뤄가면서 빙고할 수 있도록 만들어진 서비스입니다. 일종의 ‘빙고’가 접목된 투두리스트입니다.

플랜 빙고는 Neubrutalism과 뉴트로풍으로 디자인되어 유저에게 각인될 수 있도록 만들어졌습니다.

## 제작 계기
**“신입 프론트엔드 개발자로 취업하려면 어느 정도의 실력을 갖춰야 할까요?”**

위의 질문은 제가 한 프론트엔드 개발자님께 했던 질문입니다.


그분은 다음과 같이 답해줬습니다.
1. 리액트를 써서 투두리스트를 만들 수 있을 정도면 회사에 지원할 수 있다.
2. 회사에서는 배포 및 서비스 운영 경험이 있는 신입 개발자를 원한다.


이 말을 듣고 다음과 같이 생각했습니다. 


‘이제 리액트를 공부해서 투두리스트를 만들어야겠다.’ 

‘그러는 김에 배포도 해봐야지.’

***'그런데 평범한 투두리스트를 만들면 과연 사람들이 쓸까?’***


이 생각을 토대로 저는 투두리스트와 ‘빙고’를 합쳐서 특이한 형태의 투두리스트를 만들게 됩니다.  

그것이 바로 **플랜 빙고**입니다.

## 주요 기능 소개(ver.0.1.5 위주)
- 회원가입 & 튜토리얼 (ver.0.1.14)
  
  ![1_signup_tutorial](https://github.com/robinyoon-dev/plan-bingo-project/assets/107087958/9043cc39-de26-4b5f-852f-0b27b8625cb3)


- 새로운 빙고판 생성 (ver.0.1.14)
  
  ![2_create_new_board_-_Clipchamp로_제작_AdobeExpress](https://github.com/robinyoon-dev/plan-bingo-project/assets/107087958/3d554446-0d73-4898-9d99-2aaa90ae8396)


- 빙고판을 생성하지 않은 경우
  
  ![6_whenUserDoesn_tCreateBoard_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821904-5ddff02f-03a8-4bd7-b9b7-2320918767d6.gif)

- 빙고판 내용 수정 (ver.0.1.14)

  ![4_edit_board](https://github.com/robinyoon-dev/plan-bingo-project/assets/107087958/c91e9432-1a35-41de-b3e8-3e65553dbf5f)

- 체크 완료 및 체크 후 각 상황에 따라 다른 이펙트
  - 일반적인 빙고인 경우
  
  ![4_CheckBoard_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821309-51661dff-9fe0-47f7-b19e-e424916e0fd1.gif)

  - 모든 칸이 체크된 경우
  
  ![5_8bingo_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821401-ef5f2398-9697-4e1b-8005-f3c6b1aba267.gif)


- 반응형 웹으로 만들어서 모바일 환경에서도 이용할 수 있습니다.

  ![7_responsive_AdobeExpress](https://user-images.githubusercontent.com/107087958/227822281-9388d7bc-956c-415c-a2d9-87a7f3ceab7a.gif)


- 이 외에도 다음과 같은 기능이 있습니다. 
  - 빙고판 공유
  - 로그인 등.


## 프로젝트를 통해 배운 점
- 웹 접근성
- 시간 관리
- 기술 부분

### 웹 접근성 - 다양한 유저들이 각기 다른 방식으로 웹을 이용한다는 것을 깨달았습니다.

input 태그의 CSS를 다룰 때였습니다. input 요소를 꾸밀 때 `outline:none`을 사용했습니다. 그런데 `outline:none`을 사용하면 웹 접근성 관련 문제가 생긴다는 글을 읽게 되었습니다. 웹 접근성을 고려하는 것이 중요하다는 것을 익히 들었기에 웹 접근성을 해치지 않을 방법을 강구하게 됩니다.

그런데 저는 여기서 실수하게 됩니다. 단순히 `outline:none` 코드만 안 쓰면 웹 접근성을 해치지 않으리라 생각했습니다. 그래서 outline의 색깔을 배경 색깔과 똑같이 만들어서 outline이 없는 것처럼 보이게 만들었습니다. outline이 안 보이는 것 자체가 웹 접근성을 해치는 것인지 모르고 한 행동이었습니다.

실수를 깨달은 건 유저의 피드백을 반영하여 수정할 때였습니다. tab 키 이동에 관한 피드백을 반영할 때에서야 과거에 잘못 생각했다는 것을 알게 되었습니다.  input요소의 outline이 안 보이면 input이 focus 된 상태인지 알기 힘듭니다. 이렇게 되면 마우스를 안 쓰는 키보드 유저와 시력이 안 좋은 유저가 불편함을 겪고, 이는 바로 웹 접근성이 떨어지는 것이란 걸 몸소 깨닫게 되었습니다.

앞으로 개발 시 웹 접근성을 고려하고 다양한 유저들이 동질의 서비스를 받을 수 있게 하겠습니다.

### 기술 부분에서는 다음과 같은 점을 배웠습니다.
- CSS flex와 grid 
- React.js
- Next.js getStaticPorps와 getServerSideProps의 차이점
- Next.js API handler사용법
- MongoDB Atlas 사용법
- Client Side와 Server Side의 차이점 등.

## 후기
플랜 빙고는 저에게 ‘처음’이라는 타이틀을 안겨주었습니다. 처음으로 Figma를 사용하여 기획 및 디자인하고, 처음으로 React.js, MongoDB, Next.js를 사용하여 처음으로 배포하고 처음으로 유저를 얻은 프로젝트입니다. 그래서 이 프로젝트는 저에게 의미가 큽니다.

플랜 빙고는 저에게 자신감을 안겨주었습니다. 프로젝트를 시작할 당시 두려웠습니다. 제가 프로젝트를 완성하여 배포까지 할 수 있을지 자신이 없었습니다. 그런데 웬걸, 해냈습니다. 아득히 높은 산 정상에 오른 기분입니다. 이 경험으로 저는 불가능해 보이는 것을 가능하게 바꾸는 힘이 생겼습니다.

이처럼 플랜 빙고는 저에게 많은 것을 안겨주었습니다. 이에 보답하고자 플랜 빙고를 앞으로도 꾸준히 업데이트할 것을 약속합니다.

