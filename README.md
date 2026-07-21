# 안녕하세요, Talking Potato입니다

  > 새로운 기술을 빠르게 흡수해 실제 서비스에 녹여내는 것을 즐기며,
  > 내가 필요한 것을 직접 만들 수 있는 Java 백엔드 개발자

  📧 minky5004@gmail.com  · 📍 충청남도 천안시

  ---

  ## Experience

  - **Team Project: 실시간 역경매 서비스** (2026.04 – 2026.05)
    구매자가 물품을 등록하면 판매자들이 경쟁적으로 가격을 낮춰 입찰하는 역경매 플랫폼. 4인 팀.
      - **Redisson 분산락** + `REQUIRES_NEW` 트랜잭션 분리로 동시 입찰 Race Condition 제어 및 커밋·락 해제 순서 보장
      - **AWS EventBridge Scheduler + Lambda** 로 경매 생명주기(시작·종료) 자동화 —
  `@TransactionalEventListener(AFTER_COMMIT)` 으로 고아 스케줄 방지
      - **Redis Pub/Sub → SSE** 실시간 알림 파이프라인 — 메인 서버·알림 서버 ECS 독립 배포 구조 설계
      - **Elasticsearch + PostgreSQL Fallback** 이중 검색 아키텍처 설계 — ES 장애 시 자동 DB Fallback
      - **Spring AI Tool Calling · pgvector RAG** 기반 AI 상담 챗봇 전체 설계·구현

  - **Personal Project: J.A.R.V.I.S** (2026.05 – Present)
    음성 명령을 이해하고 Tool Calling으로 기능을 자동 실행하는 AI 어시스턴트 백엔드 서비스.
      - **Whisper STT → GPT Tool Calling → 외부 API** 자동 실행 파이프라인 구축
      - 한국어 자연어 명령으로 날씨 · 일정 · 검색 기능 자동 실행 구현

  - **Personal Project: LOL TierPeek** (2026.03 – 2026.04)
    League of Legends 친구들의 랭크 변화를 실시간으로 추적하는 백엔드 서비스.
      - **배치 쿼리**로 N+1 문제 해결 — 다수 친구의 최신 랭크를 단일 쿼리로 조회
      - **Token Bucket** 알고리즘 직접 구현으로 Riot API Rate Limit 준수
      - **AtomicBoolean** 기반 스케줄러 중복 실행 방지 및 WebFlux 비동기 외부 API 호출

  ---

  ## ️TechStack

  ### Languages
  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

  ### Frameworks & Libraries
  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
  ![Spring
  Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
  ![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
  ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
  ![QueryDSL](https://img.shields.io/badge/QueryDSL-0085CA?style=flat-square)
  ![Redisson](https://img.shields.io/badge/Redisson-DC382D?style=flat-square&logo=redis&logoColor=white)

  ### Database
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
  ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
  ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
  ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

  ### AI / Vector
  ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
  ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

  ### DevOps & Cloud
  ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
  ![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
  ![Amazon RDS](https://img.shields.io/badge/Amazon_RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
  ![Amazon SQS](https://img.shields.io/badge/Amazon_SQS-FF9900?style=flat-square&logo=amazonsqs&logoColor=white)
  ![AWS
  EventBridge](https://img.shields.io/badge/AWS_EventBridge-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
  ![GitHub
  Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

  ### Monitoring
  ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
  ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
  ![K6](https://img.shields.io/badge/K6-7D64FF?style=flat-square&logo=k6&logoColor=white)

  ---

  ## Education

  - **내일배움캠프 Spring 백엔드 트랙** (2025.11 – 2026.05)

  ---

  ## GitHub Stats

  ![GitHub Streak](https://streak-stats.demolab.com/?user=minky5004&theme=default)                                                                                                                                                                        
