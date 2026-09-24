<h1 align="center">안녕하세요, doukdoll입니다 👋</h1>

<p align="center">
  카메라와 기기가 보내는 신호를, 사람이 쓸 수 있는 기능으로 연결합니다.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-1F2937?style=flat-square" alt="Backend" />
  <img src="https://img.shields.io/badge/Real--time-0F766E?style=flat-square" alt="Real-time" />
  <img src="https://img.shields.io/badge/IoT-1F2937?style=flat-square" alt="IoT" />
</p>

---

## ✨ 만들고 기록하는 것

데이터가 화면에 도착하기까지의 흐름을 만드는 일을 좋아합니다. 잘 동작한 결과뿐 아니라, 연결 과정에서 만난 문제와 해결 방법도 함께 기록합니다.

### 🚆 [수어 기반 기차 예매 키오스크](https://github.com/doukdoll/sign_language_ver.2)

> 웹캠의 수어 입력으로 역을 선택하고 열차를 조회하는 키오스크 프로토타입

- **연결한 흐름** · MediaPipe 키포인트 → WebSocket → Spring Boot → Python·ONNX 추론
- **구현 포인트** · 열차 시간표 조회 API, 인식 세션의 재접속과 초기화 흐름
- **현재 단계** · 실제 철도 예매·결제 시스템과 연결되지 않은 프로젝트 프로토타입

`React` · `TypeScript` · `Spring Boot` · `WebSocket` · `Python` · `ONNX Runtime`

[시스템 흐름 보기 ↗](https://github.com/doukdoll/sign_language_ver.2#%EC%8B%9C%EC%8A%A4%ED%85%9C-%ED%9D%90%EB%A6%84) · [연동 검증 기록 ↗](https://github.com/doukdoll/sign_language_ver.2/blob/main/docs/LIVE_RECOGNITION_CHECK.md)

<br />

### 🐠 [SmartFishTank](https://github.com/doukdoll/SmartFishTank)

> 해수어항의 상태를 살피는 IoT 프로젝트 · 백엔드와 인프라 중심으로 작업

- **데이터 연결** · MQTT로 들어오는 기기 데이터, Spring Boot API, MySQL·Redis 기반 데이터 처리
- **해결한 문제** · 기기 시계 오차로 오래된 센서 값이 최신으로 보이던 오류를 서버 수신 시각 기준으로 수정
- **운영 기록** · Docker Compose 실행, 환경변수 차이, MQTT 연결과 배포 과정 문서화

`Java` · `Spring Boot` · `MySQL` · `Redis` · `MQTT` · `Docker Compose`

[실행·트러블슈팅 보기 ↗](https://github.com/doukdoll/SmartFishTank#%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85) · [협업 기록 ↗](https://github.com/doukdoll/SmartFishTank/blob/master/docs/gitlab-history/README.md)

---

<p align="center"><sub>코드와 함께 설계 의도와 해결 과정을 남깁니다.</sub></p>
