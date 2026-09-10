# 남궁진용

백엔드 개발자 · 대구
`Java` `Spring Boot` `TypeScript` `NestJS` `PostgreSQL` `MySQL` `AWS` `Docker`

<br>

## 작업

### 다중 사이트 공통 백엔드 · `2026.07 ~` · 2인 팀

- 사이트마다 서버·테이블 분리 시 감당 불가 → 하나의 백엔드로 여러 사이트 처리하는 구조로 이동
- **범용 콘텐츠 모듈 설계·구현** — 폼 정의 + JSONB 분리로 테이블 추가 없이 신규 콘텐츠 유형 확장
- `(app_id, key)` 유니크 / `(app_id, form_id)` 복합 인덱스 구성
- **사이트 5종 프론트엔드 직접 제작**, S3 + CloudFront 배포 / Route 53 도메인 연결
- **관리자 콘솔 직접 구현** (React) — 6개 사이트 통합 관리 / 일부 기능 선임 개발자 보완
- 인증·가드 기반 구조는 선임 개발자 담당, 그 위에 콘텐츠 모듈을 설계해 연결

📄 **[설계 문서](https://github.com/Julygon/multi-tenant-architecture)** — 구성도 · 테넌트 식별 흐름 · ERD · 설계 판단
<sub>의뢰처와의 관계상 소스코드 및 실제 사이트 비공개</sub>

`TypeScript` `NestJS` `PostgreSQL` `React` `Vite` `Docker` `S3` `CloudFront` `Route 53`

<br>

### 결제 대행 서비스 앱 백엔드 · `2026.06 ~` · 개발 참여

- 약관 동의 / 공지사항 / 이벤트 / 1:1 문의 / FAQ / 메타데이터 관리 **API 설계·개발**
- 프론트엔드 사용 전제로 응답 구조·예외 처리 형식 협의 후 통일
- 담당 도메인 엔티티 및 스키마 작성

<sub>실서비스 개발 참여. 배포 전 단계로 서비스명 비공개</sub>

`TypeScript` `NestJS` `PostgreSQL` `MikroORM`

<br>

### 예약 관리 텔레그램 봇 · `2026.08` · 단독 개발

- 행사 시간대별 예약 접수 + 관리자 실시간 알림·목록 조회
- 타임당 20명 정원, 하루 2~5타임, 100건 이상 처리
- **조건부 UPDATE로 정원 확인·증가 원자적 처리** → 동시 신청 시 초과 예약 방지
- 신청자 이름·연락처 마스킹 적용
- Docker 컨테이너 배포

`TypeScript` `Node.js` `Docker`

<br>

### here-in-korea — 방한 외국인 여행 정보 서비스 · `2024.04 ~ 2024.12` · 4인 팀

- 대학 졸업작품. 보안 관심으로 **인증 파트 직접 선택**
- JWT 기반 인증 구현 (토큰 발급·검증)
- 회원 도메인 CRUD 백엔드·프론트엔드 양쪽 담당
- 공공데이터 API 연동 → 지역별 행사 정보 게시판·지도 마커 표시
- AWS 서버 환경 구성 및 배포 서브 담당

`Java` `Spring Boot` `MySQL` `React` `AWS`

<br>

---

일본어 JLPT N2 · wlsdyd0824@gmail.com
