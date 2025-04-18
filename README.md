# 🚀 shipping-integrations

이 프로젝트는 제가 실무에서 직접 구축하고 운영한 다양한 API 연동 경험 중 일부를 정리한 예제입니다.  
단순한 샘플이 아닌, **운영 환경에서 실제로 사용되던 실무 로직을 기반**으로 구성된 코드입니다.

---

## ✨ 핵심 역량

- **8년 이상 실무 경험**을 바탕으로, **수십 개의 외부 API 연동** 프로젝트를 주도적으로 수행했습니다.
- SOAP, RESTful API, Webhook, File 연동, WebSocket 등 다양한 통신 방식에 대한 깊은 이해와 실전 경험 보유
- DB 연동, 인증 처리, 보안 고려, 에러 핸들링, 배치 자동화 등 실무에서 요구되는 전반적인 기술 스택에 익숙함
- **물류 API 외에도 다양한 산업군의 API 개발에 즉시 투입 가능**

---

## ✅ 연동 경험이 있는 API 예시

| 분야       | 주요 API 연동 사례 |
|------------|--------------------|
| 해외배송    | DHL, FedEx, SF Express, Asendia, Fastbox |
| 국내배송    | CJ대한통운, Logen, 11MY, Lineclear, Fastbox |
| 이커머스    | Rakuten, Qoo10, Shopify |
| 트래킹      | 17Track, Aftership |
| 기타 플랫폼 | Ninjavan, 등 기타 파트너 API |

※ 본 레포지토리에는 위 중 일부를 **SOAP / REST / Webhook 통신 방식 기준**으로 분류하여 코드 예시로 제공합니다.

---

## 📁 폴더 구조 설명
- `SOAP/`  
  - `CreateShipmentRequest.php` → DHL, ROGEN 실무 API  
  - `OrderSearchRakuten.php` → Rakuten 주문 조회  
  - `AddressLookupService.php` → 주소 기반 배송지 코드 조회

- `REST/`  
  - `TrackingQueryService.php` → FedEx, 17Track 등 REST API로 배송조회

- `Webhook/`  
  - `OrderPushReceiver.php` → Etomars 등 외부 발송형 주문 수신 API

---

## 💬 마무리 한 마디

> “물류 시스템이든, 커머스 플랫폼이든, 의료, 교육, 금융 등 어떤 업종의 API 연동도  
> 명세만 주어지면 설계부터 구현까지 문제없이 처리할 수 있습니다.”

해당 프로젝트는 일부 예시일 뿐이며, 더 다양한 API 연동 경험은 요청 시 상세 설명 드릴 수 있습니다.
