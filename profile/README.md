<h1>
  <img src="https://avatars.githubusercontent.com/u/223626944?s=200&v=4" width="30" alt="Organization Logo" style="vertical-align: middle;" />
  <span style="vertical-align: middle;">AI 공부 도우미 EVI</span>
</h1>

**EVI**는 디지털 휴먼 AI 가상비서를 공부에 접목한 학습 지원 플랫폼입니다.  
사용자는 **학습 계획 생성**, **문서 요약**, **커뮤니티 활동**을 통해 맞춤형 학습 환경을 누릴 수 있습니다.  

## 1. 📌 프로젝트 소개
- **목적**  
  학습자가 스스로 학습 계획을 세우고, AI를 활용하여 자료를 요약하거나 정리하며, 커뮤니티를 통해 서로 정보를 공유할 수 있는 환경을 제공하는 것.<br/><br/>
- **주요 기능**
  - **AI 학습 지원**: 학습 계획 생성 / 문서 요약 / 결과 카드 렌더링
  - **커뮤니티**: 무한 스크롤 게시판, 댓글/좋아요, Free·Share·Study 카테고리
  - **마이페이지**: 학습 기록 및 챌린지 현황 관리
  - **안정적 서버**: FastAPI 기반 REST API, AWS 인프라 배포

- **시연 영상**

| 기능 | 시연 GIF |
|------|-----------|
| Landing Page (로그인 전) | ![로그인 전 랜딩](https://github.com/user-attachments/assets/d2ff516e-8f4f-40ec-bd30-71130ed088c7) |
| Landing Page (로그인 후) | ![로그인 후 랜딩](https://github.com/user-attachments/assets/5b337f68-5352-480d-bdf4-71bf0eeee17d) |
| 소셜 로그인 |  ![03-socialLogin](https://github.com/user-attachments/assets/ce37c279-cbe5-4463-89c7-c6499ad6c90e) |
| AI 스터디 플랜 | ![학습 플랜](https://github.com/user-attachments/assets/a1646e74-b4cf-4bfb-8f39-1ee5c3e2ae92) |
| AI 요약 정리 | ![06-aiPage-summary](https://github.com/user-attachments/assets/6f7ca72f-ceb8-4212-b006-2c8ba6c829f2) |
| AI 요약 정리 - 실패한 경우 | ![07-aiPage-summary-failCase](https://github.com/user-attachments/assets/1a1939df-89d9-426c-a5dc-f675e1a4130a)|
| My Page 신청자 목록 | ![08-myPage-ListOfApplicants](https://github.com/user-attachments/assets/3b4effe4-ac1f-446e-8873-3ade1b5ff363) |
| My Page 회원탈퇴 | ![09-myPage-MembershipWithdrawal](https://github.com/user-attachments/assets/e396e258-69ad-4d4c-86d5-78c9b44237aa) |
| My Page 캘린더 & 챌린지 | ![10-myPage-CalendarChallenge](https://github.com/user-attachments/assets/ba6142ba-8671-4827-af13-9d81e15cda9c) |
| My Page 스터디 신청 현황 | ![11-myPage-StudyApplicationStatus](https://github.com/user-attachments/assets/35f15103-8651-469b-b8b2-33c53b3963fd) |
| My Page 닉네임 수정 | ![12-myPage-ModifyingNickname_wrotenPost](https://github.com/user-attachments/assets/dd258594-15d2-476c-a17f-70673b99d45d) |
| Community 게시글 작성 폼 확인 | ![게시글 작성 폼 확인](https://github.com/user-attachments/assets/0e95764a-5de7-4f0a-bae9-06a21e1a3739) |
| Community 게시글 작성 및 파일 첨부 | ![ 게시글 작성 및 파일첨부](https://github.com/user-attachments/assets/b12b304d-5463-40a4-ab5f-b16dcd3f9b3c) |
| Community 필터링별 검색 기능 | ![필터링별 검색기능](https://github.com/user-attachments/assets/4ebc577a-1e2e-45d0-845d-e2249568fb5f) |
| Community 카테고리 TOP 5  | ![top 5 구현](https://github.com/user-attachments/assets/98b3f1e1-7bf6-4444-b444-2664ce0fac98) |
| Community 탭 별 리스트 무한스크롤 | ![탭 별 리스트 무한스크롤](https://github.com/user-attachments/assets/cda0e071-8383-41f8-8155-4849855ae8fe) |
| Community 좋아요 반영 및 찜 목록 확인 | ![좋아요 반영 및 찜목록 확인](https://github.com/user-attachments/assets/cfe97bea-aa8d-4be5-b48a-68e20597ae16) |
| Community 댓글/대댓글 수정 및 삭제 확인 | ![댓글_대댓글 수정 및 삭제 확인](https://github.com/user-attachments/assets/33f9d9d9-56bc-46b1-91f7-6ef872edb59c) |


## 2. 🛠️ 기술 스택 (Tech Stack)

<img width="1920" height="1080" alt="Web_App_Reference_Architecture_1" src="https://github.com/user-attachments/assets/5a13d89d-daf8-4006-a043-ee1d85cee329" />

### 🌐 Frontend
- React 19, TypeScript, Vite  
- Tailwind CSS, Framer Motion, Swiper  
- React Router, TanStack Query, Zustand  
- Axios, Zod, date-fns, React Virtuoso, React Dropzone  
- ESLint, Prettier
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vite/vite-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="50" />
</p>

### ⚙️ Backend
- Python (FastAPI), PostgreSQL (Tortoise ORM)  
- Gemini API  
- AWS (EC2, RDS, S3), Nginx

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,aws,nginx" />
</p>


## 3. 🔗 배포 링크
- **서비스**: https://evida.site  
- **백엔드 API**: https://backend.evida.site  


## 4. 👨‍👩‍👧‍👦 팀 소개

<p>본 프로젝트는 오즈코딩스쿨 <b>FE-BE 합동 프로젝트팀 원트원킬</b>이 진행했습니다.</p>

### 🚀 Frontend
<table>
  <tr>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/206815651?v=4" width="96"/><br/>
        <b>김은빈</b> (<a href="https://github.com/bin00125">@bin00125</a>)
      <br/>
      <sub>Header · Login · 마이페이지</sub>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/117453101?v=4" width="96"/><br/>
        <b>박재민</b> (<a href="https://github.com/jamminP">@jamminP</a>)
      <br/>
      <sub>Landing · AI 페이지</sub>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/202897450?v=4" width="96"/><br/>
        <b>이재은</b> (<a href="https://github.com/Jaeeun0723">@Jaeeun0723</a>)
      <br/>
      <sub>커뮤니티 페이지</sub>
    </td>
  </tr>
</table>

### ⚙️ Backend
<table>
  <tr>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/203993673?v=4" width="96"/><br/>
        <b>김희수</b> (<a href="https://github.com/kimshineday">@kimshineday</a>)
      <br/>
      <sub>소셜로그인 API · User 데이터관리</sub>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/206352569?v=4" width="96"/><br/>
        <b>유승협</b> (<a href="https://github.com/yoo-sh-96">@yoo-sh-96</a>)
      <br/>
      <sub>커뮤니티 API (CRUD) · DB 관리</sub>
    </td>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/204955431?v=4" width="96"/><br/>
        <b>이종찬</b> (<a href="https://github.com/jclee5419">@jclee5419</a>)
      <br/>
      <sub>AI 공부 계획 · 정보 요약 API</sub>
    </td>
  </tr>
</table>


## 5. 📌 팀 컨벤션

### 🗓 일정
- 데일리 스크럼 : 매일 오전 10시 10분  
- 코어 타임 : 오후 1시 ~ 3시, 오후 4시 ~ 6시  

### 📣 의사소통 규칙
- 욕하지 않기  
- 사랑과 평화 지향  
- 말하기 전에 심호흡하기  

### 🛠️ 개발 규칙
- **Commit**: 타입은 영어, 설명은 한국어  
  - 예) `feat: 학습 계획 API 연동`  
  - Gitmoji 사용 ❌  
- **Branch**: 영어 기반 네이밍 (`feature/<scope>`, `fix/<scope>`)  
- **PR**: 템플릿 기반, 팀원 확인 후 머지  
- **Issue**: Bug / Feature 템플릿 사용  
- **Backend**: develop → main 머지 전 팀원 공유 및 확인 필수  
