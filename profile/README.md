<h1 align="center">🎞️ M O V I E &nbsp; R E S E R V A T I O N &nbsp; S Y S T E M</h1>
<p align="center"><b>JAVA + JDBC 기반 콘솔 영화 예매 프로그램</b><br>
<i>KB IT's Your Life 6기 · 17회차 · 2팀 <b>못된 시네마</b> 🐾</i></p>

---

## 📌 프로젝트 개요

**못된 시네마**는 Java와 JDBC를 활용해 제작한  
**콘솔 기반 영화 예매 시스템**입니다.  
직관적인 CLI UI와 직렬화된 흐름으로 예매 기능을 구성하고,  
MySQL과의 연동을 통해 실제 DB 저장/조회가 가능한 구조로 설계되었습니다.

### 🎯 목적

- Java 기초 및 DB 연동 실습 심화
- 팀 단위 개발 및 협업 경험 체득
- 실무에 가까운 로직 설계 및 코드 구현

---

## 🚀 핵심 기능

| 기능 | 설명 |
|------|------|
| 🎬 영화 목록 조회 | 상영 중인 영화 리스트와 상세 정보 제공 |
| 📆 날짜 및 시간 선택 | 사용자가 원하는 날짜와 상영시간 선택 가능 |
| 💺 좌석 선택 | 실시간 잔여 좌석 조회 및 중복 방지 처리 |
| 💳 예매 확정 | 결제 입력을 통한 예매 완료 및 정보 저장 |
| 🔐 관리자 모드 | 전체 예매 내역 조회, 초기화, 필터링 기능 제공 |

---

## 👨‍👩‍👧‍👦 팀원 소개 (못된 시네마 🐾)

| 이름 | GitHub | 프로필 |
|------|--------|--------|
| 김원영 | [`@iamwonyoungkim`](https://github.com/iamwonyoungkim) | <img src="https://avatars.githubusercontent.com/u/90565929?v=4" width="100" /> |
| 김하나 | [`@kimhana11`](https://github.com/kimhana11) | <img src="https://avatars.githubusercontent.com/u/117277958?v=4" width="100" /> |
| 최연우 | [`@rryunn`](https://github.com/rryunn) | <img src="https://avatars.githubusercontent.com/u/122458948?v=4" width="100" /> |
| 오태준 | [`@taejun0`](https://github.com/taejun0) | <img src="https://avatars.githubusercontent.com/u/164321668?v=4" width="100" /> |
| 소영재 | [`@YoungjaeSo`](https://github.com/YoungjaeSo) | <img src="https://avatars.githubusercontent.com/u/188574249?v=4" width="100" /> |

---

## 🛠️ 사용 기술

| 분야 | 기술 |
|------|------|
| Language | Java 17 |
| DB 연동 | JDBC, MySQL 8.x |
| 개발 환경 | IntelliJ IDEA / VSCode |
| 운영체제 | macOS, Windows 혼합 개발 |
| 협업 도구 | GitHub, Notion |

---

## 🗂 ERD & DB 설계

📌 **ERD 및 테이블 구조도**는 추후 업로드 예정입니다.  
SQL 스키마, 초기 데이터, 쿼리 예시까지 함께 포함할 계획입니다.

---

## 🎨 예매 시나리오 예시 (콘솔 흐름)

```plaintext
[영화 선택] → [날짜 선택] → [시간 선택] → [좌석 선택] → [결제] → [완료]
