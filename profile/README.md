# 🍽️ Eatmoji 프로젝트

![eatmoji](https://github.com/user-attachments/assets/48bc651f-5caf-4d92-90e3-89c0fbb26602)

**이모지를 이용한 사용자의 감정과 건강 정보를 기반으로 음식 메뉴를 추천하는 AI 기반 추천 시스템입니다.**

---

## 🚀 주요 기능

- 😊 이모지 기반으로 사용자 감정 파악 후 메뉴 추천
- 📊 사용자 프로필(선호 카테고리, 맛, 질병, 알레르기)과 과거 히스토리(좋아요한 음식)를 반영한 개인화 추천
- ⚡️ Spring Boot와 FastAPI를 연동하여, GPT-4o 기반 AI 추천 결과를 제공합니다
- 🗃️ MongoDB로 사용자 기록 관리 및 분석

---

## 서비스 이용 방법

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
| Eatmoji 실행 링크     | `eatmoji-fe.vercel.app`                                      |
| Swagger 문서          | `http://3.37.53.72:8080/swagger-ui/index.html`              |

👉 **사용자는 위 링크를 통해 서비스를 바로 사용할 수 있습니다.**

---

## 기술 스택

### ✔️Front-end
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /><img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" /><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /><img src="https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=Zustand&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/SWR-000000?style=for-the-badge&logo=vercel&logoColor=white" /><img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" /><img src="https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white" /><img src="https://img.shields.io/badge/React Icons-E91E63?style=for-the-badge&logo=react&logoColor=white" />

### ✔️Back-end
<img src="https://img.shields.io/badge/Spring-61BA55?style=for-the-badge&logo=Spring&logoColor=white"><img src="https://img.shields.io/badge/SpringBoot-8ED16A?style=for-the-badge&logo=SpringBoot&logoColor=white"><img src="https://img.shields.io/badge/Springsecurity-39A346?style=for-the-badge&logo=Springsecurity&logoColor=white"><img src="https://img.shields.io/badge/FastAPI-2BA498?style=for-the-badge&logo=FastAPI&logoColor=white"><img src="https://img.shields.io/badge/MongoDB-4AB349?style=for-the-badge&logo=MongoDB&logoColor=white">

### ✔️Development & Deployment Environment
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" /><img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" /><img src="https://img.shields.io/badge/AWS EC2-FFFFFF?style=for-the-badge&logo=AWS&logoColor=white" />

### ✔️AI
<img src="https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=OpenAI&logoColor=white"><img src="https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">

### ✔️API document
<img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">

--- 

## Developer

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/sseobi16">
          <img src="https://avatars.githubusercontent.com/sseobi16" width="120px;" alt="고준섭 프로필"/><br />
          <sub><b>고준섭</b></sub><br />
          <sub>백엔드 개발<br />
             AWS EC2 배포<br />
             DB 연동<br />
             통합 API 개발<br />
          </sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/jinha0907">
          <img src="https://avatars.githubusercontent.com/jinha0907" width="120px;" alt="김진하 프로필"/><br />
          <sub><b>김진하</b></sub><br />
          <sub>백엔드 개발<br />
             AI 추천 시스템 개발<br />
             문서화 담당<br />
          </sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Head-ddy">
          <img src="https://avatars.githubusercontent.com/Head-ddy" width="120px;" alt="라희수 프로필"/><br />
          <sub><b>라희수</b></sub><br />
          <sub>프론트엔드 개발<br />PM<br />UI/UX 디자인</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/mingyulee327">
          <img src="https://avatars.githubusercontent.com/mingyulee327" width="120px;" alt="이민규 프로필"/><br />
          <sub><b>이민규</b></sub><br />
          <sub>백엔드 개발<br />
             서비스 기획<br />
             통합 API 개발<br />
          </sub>
        </a>
      </td>
    </tr>
  </tbody>
</table>

--- 

> Made with ❤️ by Team DionysOS – 2025  
> This project was created as part of the **Open Source Software Project** course.
> 
