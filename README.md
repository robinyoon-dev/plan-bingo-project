
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
https://emphasized-dibble-f24.notion.site/63f4292fae454fbeb98fe83c695d9c01?v=682ff117c4c84f699b6445c0f889f446

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

## 주요 기능 소개(ver.0.1.5 기준)
- 회원가입 & 튜토리얼

  ![1_signUp_and_Tutorial_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821150-5bcc698d-d57e-4260-beea-c569cb7af900.gif)

- 새로운 빙고판 생성

  ![2_CreateNewBoardAndShare_-_Clipchamp로_제작_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821275-28328aaa-41fb-4377-a268-e3f8df1cddeb.gif)

- 빙고판을 생성하지 않은 경우

  ![6_whenUserDoesn_tCreateBoard_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821904-5ddff02f-03a8-4bd7-b9b7-2320918767d6.gif)

- 빙고판 내용 수정

  ![3_EditBoard_AdobeExpress](https://user-images.githubusercontent.com/107087958/227821300-69be5c3c-cb9e-4b1f-bf6f-814e60d51927.gif)

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


## 개발 애로사항


