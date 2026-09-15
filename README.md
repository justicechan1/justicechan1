<div class="header">
  <img src="https://capsule-render.vercel.app/api?type=transparent&fontColor=F5C0CA&text=UiChan's%20GitHub%20&height=150&fontSize=60&descAlignY=75&descAlign=60" alt="UiChan GitHub">
</div>

<div align="center">
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact Me 🧑‍💻 </h2>
  <div align="center">
    <a href="mailto:uichanjeong129@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white">
    </a>
    <a href="https://github.com/justicechan1">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
    </a>
  </div>
  <br>
  <p align="center">
    🔍 <strong>로그 분석을 통한 원인 파악과 코드 개선의 가치를 믿는 백엔드 개발자 정의찬입니다.</strong>
  </p>
  <br>

  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> ✨ Tech Stack ✨ </h2>

  <!-- Backend & Language -->
  <div>
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
  </div>
  <br>

  <!-- Auth & External API -->
  <div>
    <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON Web Tokens&logoColor=white">
    <img src="https://img.shields.io/badge/OAuth2-4285F4?style=for-the-badge&logo=Auth0&logoColor=white">
    <img src="https://img.shields.io/badge/Gemini API-8E75B2?style=for-the-badge&logo=Google Gemini&logoColor=white">
  </div>
  <br>

  <!-- Database & Infra -->
  <div>
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
    <img src="https://img.shields.io/badge/H2-003545?style=for-the-badge&logo=Databricks&logoColor=white">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
    <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=NGINX&logoColor=white">
    <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">
  </div>
  <br>

  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🚀 Featured Projects 🚀 </h2>
</div>

### 🎪 모빌리티 쇼 예약 관리 플랫폼 (Mobility Expo)
> Agile + MSA 구조 백엔드 팀 프로젝트 · 2026.08~2026.09

- Booth 참가 신청 승인 시 부스 상태 미동기화 버그 발견 → 상태 머신(AVAILABLE→RESERVED→ASSIGNED) 재설계, 멱등 처리
- 결제 API IDOR(소유권 검증 누락) 발견 → Gateway 헤더(X-User-Id) 기반 신원 검증으로 전환
- 목록 조회 N+1 쿼리 3곳 JOIN FETCH로 해결
- Gemini API 비용 감사 → 재시도 횟수 캡, 프롬프트 필드 압축으로 토큰 비용 절감

`Java` `Spring Boot` `Spring Security` `MySQL` `Docker` `GitHub Actions` `Gemini API`

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/likelion-backend-24th/Final-Project-Team4)

---

### 🐾 PetInside — 반려동물 집사 커뮤니티
> 5인 팀 프로젝트 · 부팀장/백엔드 담당 · 2026.07~2026.08

- 결제 버튼 연타·재시도로 인한 이중 구독 생성 문제 → 비관적 락(PESSIMISTIC_WRITE) + 락 범위 최소화로 해결
- 소셜 로그인 JWT URL 노출 문제 → 60초 만료 1회용 코드 교환 방식 도입
- Refresh Token SHA-256 해시 저장, 로그아웃 즉시 폐기

`Java 17` `Spring Boot 3.5` `Spring Security` `JPA` `MySQL` `PortOne API v2` `React` `AWS EC2`

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/likelion-backend-24th/like-lion-team3-PetInside)

---

### 🧭 Trendy Trip — 감성 여행 플랜 웹사이트
> 3인 팀 · 팀장/백엔드 전담 · 캡스톤디자인 · 2025.01~2025.11 · 교내 공학작품전시회 최우수상

- 벡터 임베딩 기반 시맨틱 검색으로 감성 맞춤 여행지 추천 시스템 직접 설계·구현
- MySQL JSON 컬럼 임베딩 타입 불일치(list/str)·0벡터 방어 로직 구현
- 일정 재계산 API를 3단계로 분리 + 인메모리 캐싱으로 응답속도 개선
- Gemini 2.0 Flash API로 관광지 설명 문구 자동 생성

`Python` `FastAPI` `MySQL` `Selenium` `Gemini API` `Vue.js` `TypeScript`

[![Repo](https://img.shields.io/badge/Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/justicechan1) <!-- TODO: 실제 repo 주소로 교체 -->

<div align="center">
  <br>
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 📋 GitHub Stats 📋 </h2>
  <img src="https://github-readme-stats.vercel.app/api?username=justicechan1&show_icons=true&theme=radical" alt="justicechan1's GitHub stats">
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=justicechan1&theme=radical" alt="justicechan1's GitHub streak">
  <br><br>
</div>
