## 🛠️ Tech Stack

| Category | Stack |
| -- | -- |
| Backend | ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat&logo=spring&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) |
| Frontend | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| Database & Cache | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) |
| Messaging | ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) |
| Infra & DevOps | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white) |
| Monitoring | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F2CC0C?style=flat&logo=grafana&logoColor=black) ![Alloy](https://img.shields.io/badge/Alloy-FF6B35?style=flat&logo=grafana&logoColor=white) |
---

## 👤 Profile
- 홍익대학교 컴퓨터공학과 (2021.03 ~ )
- 신촌 연합 IT 창업동아리 CEOS - 23기 BE (2026.03 ~ 2026.08)

---

## 🚀 Featured Projects
- **IPX** : 특허 등록 지원 플랫폼 (2026.04 ~ 2026.08)
  - `Hybrid Search`: BGE-M3 + pgvector 기반의 벡터 검색과 OpenSearch 기반의 키워드 검색을 결합하여 검색 정확도 향상
  - `RRF`(Reciprocal Rank Fusion) 알고리즘: 서로 다른 검색 엔진의 출력 순위를 통합하여 `Top-K 검색 재현율` 최적화
  - `LLM` 연동: Claude API를 통해 사용자 쿼리 구조화, HyDE(가상 문서 임베딩) 생성 및 특허 분석 자동화 프로세스 구현
  - `비동기 상태 추적`: Redis 기반 비동기 작업 추적 시스템을 구축하여 프론트엔드 실시간 폴링 환경 구현
- **PathKeeper** : 실시간 위치 추적 플랫폼 (2026.03 ~ )
  - `분산 아키텍처`: 대용량 트래픽 대비 및 서비스 간 장애 격리를 달성하고 고가용성 수신 환경 구축
  - `Kafka`: 위치 이벤트를 비동기로 수신하여 응답성 확보 및 userId 기반 파티셔닝으로 데이터 순서 보장 및 수평 확장성 확보
  - `다단계 필터링`: 3단계 필터링(Redis Bounding Box 캐시 → 단축 평가 → PostGIS)을 통해 공간 DB 조회 작업 최소화
  - `GPS 노이즈 차단`: Hysteresis 상태 머신을 모델링하여 GPS 경계 영역 오차 및 진동으로 인한 무차별 알림 차단
  - `모니터링`: PLG + Alloy 모니터링 스택을 통해 peak Load Average를 관찰하고, CPU 자원 한계로 인해 p99 지연이 발생함을 진단
- **영화 예매 서비스** : (2026.03 ~ 2026.05)
  - `Redis 분산 락`: 동시 예매 환경에서의 Race Condition 해결
  - `Caching`: Redis Look-Aside 캐싱을 구현하여 DB 부하 완화 및 서비스 고가용성 확보
  - `RestClient`를 통한 결제 서버 연동: Http 클라이언트를 통한 외부 결제 서버 연동
  - `커넥션 풀 최적화`: PLG + Alloy 스택을 통해 DB 커넥션 풀 고갈 지점을 파악하고, 커넥션 풀 재설정 통해 Latency spike 해결

