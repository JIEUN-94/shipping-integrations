# 🧩 실무 API 연동 예제 (기능 중심 구조)

이 프로젝트는 다양한 배송/이커머스 API 연동을 **통신 방식과 기능 중심**으로 정리한 포트폴리오입니다.

## 구조 설명

- `SOAP/`  
  - `CreateShipmentRequest.php` → DHL, ROGEN 실무 API  
  - `OrderSearchRakuten.php` → Rakuten 주문 조회  
  - `AddressLookupService.php` → 주소 기반 배송지 코드 조회

- `REST/`  
  - `TrackingQueryService.php` → FedEx, 17Track 등 REST API로 배송조회

- `Webhook/`  
  - `OrderPushReceiver.php` → Etomars 등 외부 발송형 주문 수신 API

> 📌 각 파일에는 실제 운영 중이던 로직 구조를 기반으로 작성된 실무형 코드 예제가 포함되어 있습니다.
