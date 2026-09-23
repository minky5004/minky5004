# 안녕하세요, Talking Potato입니다

> 새로운 기술을 빠르게 흡수해 실제 서비스에 녹여내는 것을 즐기며,
> 내가 필요한 것을 직접 만들 수 있는 Java 백엔드 개발자

📧 minky5004@gmail.com · 📍 충청남도 천안시

---

## Projects

- **[study-log](https://study-log-n6ez.onrender.com)** (2026.08 – Present)
  공부 세션 기록 + 검색·통계 웹 애플리케이션. 포트폴리오 중 유일하게 **Spring Boot 4.1** 실서비스로 배포 · CI 연동
    - 스택: Spring Boot · Spring Security · JPA · PostgreSQL · Testcontainers

- **[daily-log-bot](https://github.com/minky5004/daily-log-bot)** (2026.08 – Present)
  study-log에 매일 자정 그날 커밋·PR을 TIL로 자동 게시 — study-log를 직접 채우는 짝 프로젝트. 프레임워크 없이 HttpClient+Jackson 직접 구현
    - 스택: Java 21 · HttpClient · Jackson · Gemini API

- **[ai-cards-news](https://minky5004.github.io/ai-cards-news/)** (2026.07 – Present)
  매일 밤 사람 손 없이 수집부터 발행까지 도는 AI 뉴스 카드 파이프라인. GitHub Pages 정적 배포 · 37회 중 33회 무인 완주
    - 스택: Gemini API · Playwright · Astro · GitHub Actions

---

## Learning

- **[Mario_RL_Project](https://github.com/minky5004/Mario_RL_Project)** (2026.06 – 2026.07)
  강화학습 공부 기록. Java(두뇌) ↔ Python(게임 환경) TCP 연결, 12개 두뇌를 20일간 비교·강화하며 완주

---

## Experience

- **Team Project: 실시간 역경매 서비스** (2026.04 – 2026.05)
  구매자가 물품을 등록하면 판매자들이 경쟁적으로 가격을 낮춰 입찰하는 역경매 플랫폼. 4인 팀.
    - **Redisson 분산락** + `REQUIRES_NEW` 트랜잭션 분리로 동시 입찰 Race Condition 제어 및 커밋·락 해제 순서 보장
    - **AWS EventBridge Scheduler + Lambda** 로 경매 생명주기(시작·종료) 자동화 — `@TransactionalEventListener(AFTER_COMMIT)` 으로 고아 스케줄 방지
    - **Redis Pub/Sub → SSE** 실시간 알림 파이프라인 — 메인 서버·알림 서버 ECS 독립 배포 구조 설계
    - **Elasticsearch + PostgreSQL Fallback** 이중 검색 아키텍처 설계 — ES 장애 시 자동 DB Fallback
    - **Spring AI Tool Calling · pgvector RAG** 기반 AI 상담 챗봇 전체 설계·구현

---

## TechStack

### Language
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)

### Data & Infra
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Redisson](https://img.shields.io/badge/Redisson-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

### AI / LLM
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

### Cloud & DevOps
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![AWS EventBridge](https://img.shields.io/badge/AWS_EventBridge-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

### Test & Build
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=testcontainers&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

### Web
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)

---

## Education

- **내일배움캠프 Spring 백엔드 트랙** (2025.11 – 2026.05)

---

## GitHub Stats

![GitHub Streak](https://github-readme-streak-stats-eight.vercel.app?user=minky5004&theme=default)
