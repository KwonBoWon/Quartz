# EBS

## EBS 개념

- EC2인스턴스를 위한 블록 스토리지 서비스
- EC2인스턴스가 종료되더라도 EBS볼륨은 유지
- 애플리케이션 중단없이 확장 가능(수동확장)
- S3에 백업 가능

## EBS 종류

|볼륨 타입|사용 사례|IOPS 성능|처리량(Throughput)|특이점|
|---|---|---|---|---|
|**gp3 (General Purpose SSD)**|대부분의 일반적인 워크로드|3,000~16,000|최대 1,000 MiB/s|비용 절감 + 성능 조정 가능|
|**gp2 (General Purpose SSD)**|범용적인 사용 (기본값)|3 IOPS/GB, 최대 16,000|최대 250 MiB/s|크기에 따라 IOPS 증가|
|**io2 / io1 (Provisioned IOPS SSD)**|고성능 DB, 빅데이터|100~256,000|최대 4,000 MiB/s|io2는 더 높은 내구성 (99.999%)|
|**st1 (Throughput Optimized HDD)**|빅데이터, 로그 분석|500 IOPS|최대 500 MiB/s|대용량 처리 최적화|
|**sc1 (Cold HDD)**|데이터 백업, 아카이빙|250 IOPS|최대 250 MiB/s|저비용, 비정기적 접근용|

1. 범용 SSD(gp3, gp2)
2. 프로비저닝된 IOPS SSD(io2, io1)
	고성능 IOPS 요구사항
3. 처리량 최적화 HDD(st1)
	대규모 데이터 분석
4. 콜드 HDD(sc1)
5. 마그네틱 볼륨
