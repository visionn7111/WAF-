#웹 애플리케이션 방화벽(WAF) 구축
## 목적
아파치 웹서버 위에 XSS, SQL Injection, CSRF 등과 같은 웹 스크립트 공격에 대한 보안 시스템 구축

## 주요 기능
- HTTP 요청 필터링 (SQL 인젝션, XSS, CSRF 등)
- 사용자 정의 규칙 설정 및 관리
- 실시간 로그 수집 및 시각화
- 고성능 처리를 위한 비동기 요청 처리 및 캐싱

## 기술 스택
- 운영체제 : 아파치
- 웹 방화벽 오픈소스 : modsecurity
- 보안 규칙 : OWASP
