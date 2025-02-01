# Network

## 네트워크 기반

![[VPC#VPC 개념]]

![[Transit Gateway#Transit Gateway 개념]]

![[PrivateLink#PrivateLink 개념]]

✔ **VPC가 많고, 온프레미스와 AWS를 연결해야 한다면** → **Transit Gateway 사용 추천**  
✔ **VPC 간 개별 연결만 필요하다면** → **VPC Peering이 더 간단하고 저렴함**  
✔ **서비스 단위로 격리된 연결이 필요하다면** → **AWS PrivateLink 활용**

## 애플리케이션 네트워킹

![[API Gateway#API Gateway 개념]]

![[App Mesh#App Mesh 개념]]

![[ELB#ELB 개념]]

## 엣지 네트워킹

![[Route53#Route53 개념]]


### CloudFront/Global Accelerator 비교

CloudFront: 앱 계층 + 캐싱
GlobalAccelerator: 트래픽 라우팅(TCP/UDP) 및 성능 최적화

![[CloudFront#CloudFront 개념]]

![[Global Accelerator#Global Accelerator 개념]]

## 하이브리드 연결

![[Direct Connect#Direct Connect(DX) 개념]]

![[VPN#VPN 설명]]

- Direct Connect + VPN을 사용하여 VPN을 백업으로 단일 장애 지점 제거 가능

![[CloudWAN#CLoudWAN 설명]]

## 네트워크 보안

![[Shield#Shield 설명]]

![[WAF#WAF 설명]]

![[Network Firewall#Network Firewall 설명]]

![[Security Groups#Security Groups 개념]]

![[NACL#NACL 개념]]

