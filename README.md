# 수정중(임시)

백엔드 개발자 · 대구
`Java` `Spring Boot` `TypeScript` `NestJS` `PostgreSQL` `MySQL` `AWS` `Docker`

<br>

## 작업

### 다중 사이트 공통 백엔드 · `2026.07 ~` · 운영 중

- 사이트마다 백엔드 분리 시 사이트 수만큼 서버 증가 → **멀티테넌트 구조로 재설계**
- `appId`로 사이트 식별, 단일 스키마 + `app_id` 컬럼으로 리소스 분리
- 폼 정의 + JSONB로 콘텐츠 구조 범용화 → 테이블 추가 없이 신규 유형 확장
- 프론트엔드 5종 제작, S3 + CloudFront 배포 / Route 53 도메인 연결
- 관리자 콘솔에서 6개 사이트 통합 관리
- 백엔드 설계 및 구현 **단독 담당**

📄 **~~[설계 문서](https://github.com/Julygon/multi-tenant-architecture)~~**(제작중) — 구성도 · 테넌트 식별 흐름 · ERD · 설계 판단
<sub>의뢰처와의 관계상 소스코드 및 실제 사이트 비공개</sub>

`TypeScript` `NestJS` `PostgreSQL` `Docker` `S3` `CloudFront` `Route 53`

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
- 신청 기간 마감 시 일정 시간 후 시간대 별 데이터 자동 삭제
- Docker 컨테이너 배포

`TypeScript` `Node.js` `Docker`

<br>

### here-in-korea — 방한 외국인 여행 정보 서비스 · `2024.04 ~ 2024.12` · 4인 팀

- 대학 졸업작품. 보안관심으로 인증 파트 담당
- JWT 기반 인증 구현 (토큰 발급·검증)
- 회원 도메인 CRUD 백엔드·프론트엔드 양쪽 담당
- 공공데이터 API 연동 → 지역별 행사 정보 게시판·지도 마커 표시
- AWS 서버 환경 구성 및 배포 서브 담당

`Java` `Spring Boot` `MySQL` `React` `AWS`

<br>

---

일본어 JLPT N2 · wlsdyd0824@gmail.com
