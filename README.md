# Project Pinpoint 🎯

> **Micro-B2B SaaS Portfolio Strategy for E-commerce Sellers**  
> 이커머스 셀러 도구 시장에서 단일 기능에 특화된 MVP 4개를 빠르게 출시하고, 시장 반응이 오는 제품을 스케일업하는 린(Lean) SaaS 프로젝트입니다.

---

## 📌 Project Overview

**Project Pinpoint**는 사방넷, 플레이오토와 같은 대형 통합 셀러 솔루션이 지닌 복잡함과 사각지대를 공략합니다.
셀러가 매일 반복하여 시간과 비용을 소모하는 **단일 기능 하나에 집중(+1 차별화)**하여, 기존 통합 솔루션보다 훨씬 뛰어난 경험과 효율을 제공하는 Micro-B2B SaaS를 구축합니다.

- **Target Market**: 국내외 이커머스 셀러 (스마트스토어, 쿠팡, 11번가 등)
- **Business Model**: Micro-B2B SaaS (월 $30 ~ $99 구독형)
- **Execution Strategy**: 2주 단위 MVP 개발 및 다작(Portfolio) 검증 후 집중 투자

---

## 💡 Key Strategies & Principles

### 1. 후커블(Hookable) 공식

- **Focus**: "모든 것을 다 해주는" 솔루션 대신, "가장 번거로운 딱 하나"를 압도적으로 잘 해결.
- **+1 차별화**: 검증된 시장 내 기존 서비스의 명확한 페인포인트 하나를 해결하여 빠른 고객 전환 유도.

### 2. 데이터 기반 의사결정 (Data-Driven)

- 뇌피셜(추측)을 배제하고 **실제 시장 데이터, 셀러 지출 비용, TAM, 경쟁사 사용자 불만**에 기반하여 우선순위 결정.

### 3. 엔지니어링 경쟁력 (Deep Engineering)

- 단순 Wrapper 수준을 넘어, **대용량 파이프라인, 비동기 MSA 오케스트레이션, 트랜잭션 무결성**이 적용된 견고한 백엔드 시스템 기반.

---

## 🎯 Candidate MVP Domains

| #   | 영역 (Domain)              | 해결하고자 하는 페인포인트                      | 비고 및 현황          |
| --- | -------------------------- | ----------------------------------------------- | --------------------- |
| 1   | **CS 자동 응대**           | 단순 반복 문의(배송, 취소, 환불 등) 자동화      | 전체 CS의 약 70% 차지 |
| 2   | **상품명 / 키워드 최적화** | 네이버 / 쿠팡 검색 상위 노출 알고리즘 맞춤 태깅 | 검색 순위 direct 영향 |
| 3   | **정산 / 매출 분석**       | 마켓별 정산 주기 차이 및 수수료 자동 정산/비교  | 사방넷 사각지대 공략  |
| 4   | **카드뉴스 / SNS 마케팅**  | SNS 마케팅용 숏폼/카드뉴스 자동 생성 및 관리    | 특화 도구 부재 시장   |

---

## 🛠 Tech Stack & Infrastructure

- **Backend**: NestJS, TypeScript, gRPC (Microservice Architecture)
- **Database & Cache**: PostgreSQL, MySQL, TypeORM, Redis
- **Frontend**: Next.js, React, Tailwind CSS
- **Cloud & DevOps**: AWS, Azure (AZ-204 / AZ-400), Docker, GitHub Actions

---

## 🗺️ Roadmap

- [x] **Phase 1**: 프로젝트 정의 및 전략 수립 (`project-pinpoint-definition.md`)
- [ ] **Phase 2**: 4개 후보 영역 Fact Sheet 조사 및 TAM/페인포인트 분석
- [ ] **Phase 3**: MVP 1순위 도메인 선정 및 2주 MVP 개발
- [ ] **Phase 4**: 랜딩페이지 오픈, 초기 셀러 유치 및 유료 전환 검증 (4주)
- [ ] **Phase 5**: MRR $1K 달성 시 스케일업 및 차순위 MVP 확장

---

## 📄 Documentation Map & Index

이 프로젝트에 새로 합류한 개발자나 AI 에이전트는 아래 프로젝트 맵을 참고하여 필요한 문서로 즉시 접근할 수 있습니다.

### 1. 프로젝트 헌장 & 정의서
- [프로젝트 정의서 (project-pinpoint-definition.md)](./project-pinpoint-definition.md)
  - **설명**: Project Pinpoint의 핵심 Identity, 의사결정 3대 원칙(후커블, 데이터 기반, 깊은 엔지니어링), 탈락 사유 및 성공/실패 기준을 정의한 Single Source of Truth.

### 2. Candidate MVP Fact Sheets (영역별 리서치 및 기획서)
각 후보 도메인의 시장성, 페인포인트, TAM/SAM/SOM, 백엔드 구현 포인트를 정리한 팩트시트입니다.
- 🎯 [Fact Sheet 01: CS 자동 응대 (docs/01-cs.md)](./docs/01-cs.md)
  - **설명**: 1인 셀러의 반복 CS를 Zero-Setup AI RAG 및 마켓 API(스마트스토어/쿠팡) 실시간 송장 연동을 통해 무인 대응하는 SaaS 리서치.
- 🎯 [Fact Sheet 02: 상품명/키워드 최적화 (docs/02-keyword.md)](./docs/02-keyword.md)
  - **설명**: API 직접 연동형 1-Click 최적화, 로직 감점 방지용 실시간 SEO 린터(Linter) 엔진, 검색 순위 변동 감지 기반 자동 리프레시 SaaS 리서치.
- 🎯 [Fact Sheet 03: 정산/매출 분석 (docs/03-settlement.md)](./docs/03-settlement.md)
  - **설명**: 주문 건별 실시간 역마진 감지, 마켓별 수수료 및 광고비 귀속, 반품 배송비 누락 및 오공제 자동 탐지(Audit) 특화 SaaS 리서치.
- 🎯 [Fact Sheet 04: 카드뉴스/SNS 마케팅 (docs/04-sns.md)](./docs/04-sns.md)
  - **설명**: 상품 URL 기반 인스타 릴스 영상/카드뉴스 자동 렌더링(Remotion Lambda) 및 API 예약 발행 오토파일럿 SaaS 리서치.

---

## 👤 Owner Profile

- **Project Owner**: 정민영 (Leones)
- **Email/Contact**: (프로젝트 소유자 정보 관리)
