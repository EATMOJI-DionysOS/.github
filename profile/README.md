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
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"><img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white"><img src="https://img.shields.io/badge/tailwindCss-38BDF8?style=for-the-badge&logo=Css&logoColor=white"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=TypeScript&logoColor=white">
### ✔️Back-end
<img src="https://img.shields.io/badge/SpringBoot-61BA55?style=for-the-badge&logo=SpringBoot&logoColor=white"><img src="https://img.shields.io/badge/FastAPI-2BA498?style=for-the-badge&logo=FastAPI&logoColor=white"><img src="https://img.shields.io/badge/MongoDB-4AB349?style=for-the-badge&logo=MongoDB&logoColor=white">

### ✔️Distribution
<img src="https://img.shields.io/badge/AWS EC2-FFFFFF?style=for-the-badge&logo=AWS&logoColor=white"><img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">

### ✔️AI
<img src="https://img.shields.io/badge/OpenAI-000000?style=for-the-badge&logo=OpenAI&logoColor=white"><img src="https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">

### ✔️API document
<img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
