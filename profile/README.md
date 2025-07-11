# 🍽️ Eatmoji 프로젝트

![eatmoji](https://github.com/user-attachments/assets/48bc651f-5caf-4d92-90e3-89c0fbb26602)

**이모지를 이용한 사용자의 감정과 건강 정보를 기반으로 음식 메뉴를 추천하는 AI 기반 추천 시스템입니다.**

---

## 🚀 주요 기능

- 😊 이모지 기반으로 사용자 감정 파악 후 메뉴 추천
- 📊 사용자 프로필(선호 카테고리, 맛, 질병, 알레르기)과 과거 히스토리(좋아요한 음식)를 반영한 개인화 추천
- ⚡️ Spring Boot와 FastAPI를 연동하여, GPT-4o 기반 AI 추천 결과를 제공합니다
- 🗃️ MongoDB로 사용자 기록 관리 및 분석

**[🔗 GitHub Wiki에서 더 자세히 보기](https://github.com/EATMOJI-DionysOS/Eatmoji_BE/wiki/%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5)**

---

## 🛎️ 서비스 이용 방법

1. 로그인을 안 한 경우
   
   - 일반 이모지 기반 음식 추천만 가능합니다.
     
2. 로그인을 한 경우
   
   - 개인 프로필에 접근하여 본인의 알레르기, 선호 카테고리 등의 개인정보를 추가할 수 있습니다.
   - 추천 결과에 나온 좋아요 버튼을 누르면 해당 음식이 추후 추천 결과에 적용됩니다.
   - 로그인을 한 경우 이모지 기반 음식 추천 시 본인의 프로필과 히스토리를 반영한 개인화 추천이 가능합니다.
   - 감정에 기반하지 않고 프로필과 히스토리만을 반영한 오메추 기능을 사용할 수 있습니다.


## ⚙️ 배포 상태 및 API 엔드포인트

✅ 현재 Eatmoji 서비스는 **FE는 Vercel, BE는 AWS EC2**에서 배포·운영되고 있습니다.

| 기능                  | 주소                                                  |
|-----------------------|-------------------------------------------------------------|
| Eatmoji 실행 링크     | `https://eatmoji-fe.vercel.app`                                      |
| Swagger 문서          | `https://3.37.53.72.nip.io/swagger-ui/index.html`              |

👉 **사용자는 위 링크를 통해 서비스를 바로 사용할 수 있습니다.**

---

## 🛠️ 기술 스택

### ✔️Front-end
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /><img src="https://img.shields.io/badge/React-9333EA?style=for-the-badge&logo=react&logoColor=61DAFB" /><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /><img src="https://img.shields.io/badge/Zustand-708090?style=for-the-badge&logo=Zustand&logoColor=white" /><img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/SWR-F59E0B?style=for-the-badge&logo=vercel&logoColor=white" /><img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" /><img src="https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white" /><img src="https://img.shields.io/badge/React Icons-E91E63?style=for-the-badge&logo=react&logoColor=white" />

### ✔️Back-end
<img src="https://img.shields.io/badge/Spring-61BA55?style=for-the-badge&logo=Spring&logoColor=white"><img src="https://img.shields.io/badge/SpringBoot-8ED16A?style=for-the-badge&logo=SpringBoot&logoColor=white"><img src="https://img.shields.io/badge/Springsecurity-39A346?style=for-the-badge&logo=Springsecurity&logoColor=white"><img src="https://img.shields.io/badge/FastAPI-2BA498?style=for-the-badge&logo=FastAPI&logoColor=white"><img src="https://img.shields.io/badge/MongoDB-4AB349?style=for-the-badge&logo=MongoDB&logoColor=white">

### ✔️Development & Deployment Environment
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" /><img src="https://img.shields.io/badge/Vercel-C71585?style=for-the-badge&logo=vercel&logoColor=white" /><img src="https://img.shields.io/badge/AWS EC2-FFFFFF?style=for-the-badge&logo=AWS&logoColor=white" /><img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />

### ✔️Cloud Storage
<img src="https://img.shields.io/badge/AWS S3-FFFFFF?style=for-the-badge&logo=aws&logoColor=white" />

### ✔️AI
<img src="https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=OpenAI&logoColor=white"><img src="https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">

### ✔️API document
<img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">

--- 

## 👩‍💻 팀 구성원 및 역할

<h2>🟩 주요 업무 분담</h2>
<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>이름</th>
       <th>ID</th>
      <th>역할</th>
      <th>상세 내용</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>고준섭</td>
       <td>sseobi16</td>
      <td>🟡 백엔드 개발, 배포 및 운영 관리</td>
      <td>
        <ul>
          <li>Recipe API 개발</li>
          <li>AWS 기반 MongoDB 연동</li>
          <li>AWS EC2 기반 서버 배포</li>
          <li>Github Action 기반 CI/CD 자동 배포</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>김진하</td>
       <td>jinha0907</td>
      <td>🟡 백엔드, AI 추천 로직 개발</td>
      <td>
        <ul>
          <li>이모지-감정 데이터셋 전처리</li>
          <li>lanhchain 기반 프롬프트 관리</li>
          <li>GPT 음식 추천 FastAPI , Spring-FastAPI 연동 API 개발</li>
          <li>전체 프로젝트 문서화(Swagger, README, CONTRIBUTING, WIKI 등)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>라희수</td>
       <td>Head-ddy</td>
      <td>🟡 프론트엔드 개발, PM, Design</td>
      <td>
        <ul>
          <li>React, Next 기반 프론트엔드 전체 개발</li>
          <li>Figma 기반 UI/UX Design</li>
          <li>Vercel 기반 프론트엔드 배포</li>
          <li>Github Action 기반 CI/CD 자동 배포</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>이민규</td>
       <td>mingyulee327</td>
      <td>🟡 백엔드 개발, 기획</td>
      <td>
        <ul>
          <li>로그인/회원가입, 즐겨찾기, 프로필 API 개발</li>
          <li>Spring Security 기반 JWT 토큰 관리</li>
          <li>보안 및 서버 모니터링</li>
          <li>서비스 기획</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>공동 작업</td>
       <td> </td>
      <td>🟡 테스트</td>
      <td>
        <ul>
          <li>QA 및 테스트</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

--- 

> Made with ❤️ by Team DionysOS – 2025  
> This project was created as part of the **Open Source Software Project** course.
> 
