# @Management, Governance

![[CloudTrail#CloudTrail 개념]]

![[CloudWatch#CloudWatch 개념]]

![[EventBridge#EventBridge 개념]]

- CloudWatch는 모니터링 로그 분석 경고 알림
- EventBridge는 이벤트 소스로 이벤트를 수집해 라우팅(Lambda, SNS, SQS)해 자동화

![[Config#Config 개념]]

![[CloudFormation#CloudFormation 개념]]

![[Trust Advisor#Trust Advisor 개념]]

![[Session Manger#Session Manager 개념]]

## AWS 비용 관리 도구 비교표

|**도구**|**주요 기능**|**주요 목적**|**사용 사례**|
|---|---|---|---|
|**AWS Cost Explorer**|비용 시각화, 트렌드 분석|비용 분석 & 예측|월별, 일별 비용 변화 분석|
|**AWS Budgets**|비용 및 사용량 알람|초과 지출 방지|예산 초과 시 알림 설정|
|**AWS Cost & Usage Report (CUR)**|상세 비용 리포트 (CSV)|정밀한 비용 분석|데이터 웨어하우스로 전송|
|**AWS Trusted Advisor (비용 최적화 항목)**|비용 절감 추천|리소스 최적화|미사용 인스턴스 식별|
|**AWS Compute Optimizer**|EC2/RDS/ASG 최적화|인스턴스 크기 조정|비효율적인 EC2 리소스 분석|
|**AWS Pricing Calculator**|예상 비용 계산|아키텍처 비용 예측|신규 서비스 도입 시 비용 산정|
|**AWS Cost Anomaly Detection**|비정상 비용 감지|이상 비용 탐지|예상보다 급격히 증가한 비용 감지|