# 📁 프로젝트명

>실버세대의 건강관리와 사회적 교류를 위한 플랫폼, 실버포션  


---

## 📌 목차

1. [프로젝트 개요](#프로젝트-개요)
2. [문서 목록](#문서-목록)
3. [프로젝트 기획서 (프로젝트기획)](#프로젝트-기획서-프로젝트기획)
4. [요구사항 정의서 (프로젝트기획)](#요구사항-정의서-프로젝트기획)
5. [시스템 아키텍처 설계서 (프로젝트기획)](#시스템-아키텍처-설계서-프로젝트기획)
6. [WBS (프로젝트기획)](#wbs-프로젝트기획)
7. [ERD (프로젝트기획)](#erd-프로젝트기획)
8. [화면설계서 (프로젝트기획)](#화면설계서-프로젝트기획)
9. [프로그램사양서 (백엔드 설계 및 구축)](#프로그램사양서-백엔드-설계-및-구축)
10. [단위 테스트 결과서 (백엔드 설계 및 구축)](#단위-테스트-결과서-백엔드-설계-및-구축)
11. [UI/UX 단위 테스트 결과서 (프론트엔드 설계 및 구축)](#uiux-단위-테스트-결과서-프론트엔드-설계-및-구축)
12. [배포 후 통합 테스트 결과서 (시스템 통합)](#배포-후-통합-테스트-결과서-시스템-통합)
13. [CI/CD 계획서 (시스템 통합)](#cicd-계획서-시스템-통합)
14. [배포 및 운영](#배포-및-운영)
15. [팀원 정보](#팀원-정보)

---

## 📖 프로젝트 개요

- **프로젝트명** : 실버포션  
- **목표 및 목적** : 
   **1️⃣ 노년층의 건강 관리 효율성 강화**
   **2️⃣ 사회적 고립 해소 및 정서적 안정 지원**
   **3️⃣ 가족 및 보호자의 안심 돌봄 환경 구축**
  
- **주요 기능 요약** :  
    **1️⃣ 실버 헬스케어**  
    📌웨어러블 연동 및 건강 데이터 관리
    - 갤럭시 워치, 애플워치 등 웨어러블 기기 연동을 통한 실시간 데이터 수집(걸음수,심박수,체온,혈압,소모칼로리 등)
    - 수집된 데이터를 통해 일/주/월 단위로 건강 리포트 제공
      
    📌 AI 기반 건강 추천 서비스
    - AI가 개인 건강 데이터를 분석해 약/영양제, 병원 위치, 운동 방법 추천
    
    📌 보호자 연동 기능
    - 보호자가 노인의 건강 데이터를 조회할 수 있음    
    
    **2️⃣ 소모임(커뮤니티)**  
     📌소모임 생성 및 참여 지원
    - 사용자가 자신의 관심사(운동,요리,독서,음악)등을 기반으로 손쉽게 모임 생성 및 가입 가능  
    - 모임별로 독립된 커뮤니티 공간을 제공하여 각 모임마다 홈,게시판,사진첩,채팅방 기능을 제공
      
---

## 📄 문서 목록

| 문서명 | 분류 | 설명 | 다운로드 |
|:----------------------------------|:--------------------------|:------------------------------------------|:---------------------------------------------|
| 프로젝트 기획서 (프로젝트기획) | 프로젝트기획 | 프로젝트 배경, 목적, 추진 전략 등 | [📎 프로젝트 기획서 다운로드](./docs/프로젝트_기획서.pdf) |
| 요구사항 정의서 (프로젝트기획) | 프로젝트기획 | 기능 및 비기능 요구사항 정의 | [📎 요구사항 정의서 다운로드](./docs/요구사항_정의서.pdf) |
| 시스템 아키텍처 설계서 (프로젝트기획) | 프로젝트기획 | 시스템 구성 및 흐름도 | [📎 시스템 아키텍처 설계서 다운로드](./docs/시스템_아키텍처_설계서.pdf) |
| WBS (프로젝트기획) | 프로젝트기획 | 업무 분장 및 세부 일정 | [📎 WBS 다운로드](./docs/WBS.pdf) |
| ERD (프로젝트기획) | 프로젝트기획 | 데이터베이스 구조 및 관계 | [📎 ERD 다운로드](./docs/ERD.pdf) |
| 화면설계서 (프로젝트기획) | 프로젝트기획 | UI/UX 화면 흐름 및 구조 | [📎 화면설계서 다운로드](./docs/화면설계서.pdf) |
| 프로그램사양서 (백엔드 설계 및 구축) | 백엔드 설계 및 구축 | 각 기능별 상세 사양 기술 | [📎 프로그램사양서 다운로드](./docs/프로그램사양서.pdf) |
| 단위 테스트 결과서 (백엔드 설계 및 구축) | 백엔드 설계 및 구축 | 기능별 테스트 수행 결과 | [📎 단위 테스트 결과서 다운로드](./docs/단위_테스트_결과서.pdf) |
| UI/UX 단위 테스트 결과서 (프론트엔드 설계 및 구축) | 프론트엔드 설계 및 구축 | 화면 기반 사용자 테스트 결과 | [📎 UI/UX 단위 테스트 결과서 다운로드](./docs/UIUX_단위_테스트_결과서.pdf) |
| 배포 후 통합 테스트 결과서 (시스템 통합) | 시스템 통합 | 배포 후 통합 테스트 결과 정리 | [📎 배포 후 통합 테스트 결과서 다운로드](./docs/배포후_통합_테스트_결과서.pdf) |
| CI/CD 계획서 (시스템 통합) | 시스템 통합 | 배포 및 자동화 파이프라인 계획 | [📎 CI/CD 계획서 다운로드](./docs/CICD_계획서.pdf) |

---

## 📑 프로젝트 기획서 (프로젝트기획)
- 프로젝트 추진 배경, 목적, 전략 정리
👉 [📎 문서 보기](./docs/프로젝트_기획서.pdf)

---

## 📑 요구사항 정의서 (프로젝트기획)
- 기능적 / 비기능 요구사항, 유즈케이스
👉 [📎 문서 보기](./docs/요구사항_정의서.pdf)

---

## 📑 시스템 아키텍처 설계서 (프로젝트기획)
> 시스템 구성도 이미지 삽입  
![시스템 아키텍처](./images/architecture.png)  
👉 [📎 문서 보기](./docs/시스템_아키텍처_설계서.pdf)

---

## 📑 WBS (프로젝트기획)
- 업무 분류 체계, 일정계획
👉 [📎 문서 보기](./docs/WBS.pdf)

---

## 📑 ERD (프로젝트기획)
> 데이터베이스 구조  
![ERD](./images/erd.png)  
👉 [📎 문서 보기](./docs/ERD.pdf)

---

## 📑 화면설계서 (프로젝트기획)
> 주요 UI/UX 흐름  
![UI 흐름](./images/ui-flow.png)  
👉 [📎 문서 보기](./docs/화면설계서.pdf)

---

## 📑 프로그램사양서 (백엔드 설계 및 구축)
- 상세 기능별 사양, 입력/출력 정의
👉 [📎 문서 보기](./docs/프로그램사양서.pdf)

---

## 📑 단위 테스트 결과서 (백엔드 설계 및 구축)
| 테스트 항목 | 테스트 내용 | 결과 | 비고 |
|:-------------|:------------------|:----:|:------|
| 로그인 기능 | 올바른 ID/Password | ✅ 성공 | 정상 작동 |
| 회원가입 기능 | 필수 입력값 누락 테스트 | ✅ 성공 | 예외처리 확인 |

👉 [📎 문서 보기](./docs/단위_테스트_결과서.pdf)

---

## 📑 UI/UX 단위 테스트 결과서 (프론트엔드 설계 및 구축)
- 사용성 테스트, 인터페이스 반응
👉 [📎 문서 보기](./docs/UIUX_단위_테스트_결과서.pdf)

---

## 📑 배포 후 통합 테스트 결과서 (시스템 통합)
- 통합 테스트 항목 및 결과 요약
👉 [📎 문서 보기](./docs/배포후_통합_테스트_결과서.pdf)

---

## 📑 CI/CD 계획서 (시스템 통합)
| 항목 | 내용 |
|:------------------|:-------------------------------|
| 자동화 도구 | GitHub Actions, Docker |
| 배포 환경 | AWS EC2 / ECS |
| 테스트 방식 | 단위/통합 자동 테스트 포함 |

👉 [📎 문서 보기](./docs/CICD_계획서.pdf)

---

## 🚀 배포 및 운영

- 운영 URL : [https://yourproject.com](https://yourproject.com)  
- 배포 환경 : AWS / Vercel / 기타  
- 컨테이너 이미지 : `yourproject:latest`

---

## 👨‍👩‍👧‍👦 팀원 정보

| 이름 | 역할 | GitHub |
|:------|:------------------------|:-----------------------------|
| 홍길동 | PM / 기획 | [github.com/hong](https://github.com/hong) |
| 이몽룡 | 백엔드 개발 | [github.com/lee](https://github.com/lee) |
| 성춘향 | 프론트엔드 개발 | [github.com/sung](https://github.com/sung) |




### Git Commit Convention
- 커밋 메시지 형식 <br>
  태그 종류 <br>
  Feat : 새로운 기능 추가 <br>
  Fix : 버그 수정 <br>
  Docs : 문서 수정 <br>
  Style : 세미콜론 누락 등 코드 변경이 없는 경우 <br>
  Refactor : 코드 리팩토링 <br>
  Test : 테스트 코드 및 리팩토링 테스트 코드 추가 <br>
  커밋 메시지 작성 규칙 <br>
  제목은 간결하게 작성. <br>
  본문에는 무엇을 변경했는지 또는 왜 변경했는지를 상세히 기록.
