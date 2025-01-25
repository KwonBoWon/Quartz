# CloudFront

## CloudFront 개념

* (CDN) 짧은 지연 시간과 빠른 전송 속도로 안전하게 콘텐츠 전송
* 글로벌 엣지 로케이션에서 콘텐츠(이미지, 동영상, API) 캐싱 및 전달

## 보안

1. Shield
	- DDoS보호
2. WAF
	- HTTP/S 트래픽 보호
	- SQL Injection, HTTP헤더, Bot
3. HTTPS TLS 암호화
	- 엔드투엔드 암호화
	- SSL/TLS 인증서
4. 서명된 URL및 쿠키를 통한 접근 제어
	- 특정 사용자에게만 접근 권한 부여
	- IP 주소 기반 제한
5. 오리진 보호(OAC, OAI)
	- Origin Access Control, Origin Access Identity를 통해 S3버킷 보호
	- CloudFront를 통해서만 S3 접근, 퍼블릭 액세스 차단
	- IAM 정책으로 접근 제어 가능
6. 접근 제어 정책 및 리퍼러 검증
	- HTTP Referer 헤더를 이용한 차단
	- 특정 국가, IP 블록 기반 차단
7. 로그 및 모니터링(CloudWatch, S3)
	- 실시간 트래픽 모니터링
	- CloudTrail을 통해 API 호출 감사 및 이상 탐지
	- 특정 패턴(봇 활동, 이상 접속 시도)탐지 및 경고 설정
8. 경로 기반 접근 제한 및 캐시 제어
	- CloudFront URL 경로 및 캐시 제어를 통해 특정 파일 또는 폴더보안 정책
9. 
10. 
11. 


