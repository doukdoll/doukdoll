<h1 align="center">안녕하세요, doukdoll입니다 👋</h1>

<p align="center">
  <strong>데이터와 자원을 연결하고, 동작의 이유까지 기록합니다.</strong><br />
  백엔드 API부터 실시간 통신, 실행 환경과 운영 로그까지 관심을 두고 만들고 있습니다.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-1F2937?style=flat-square" alt="Backend" />
  <img src="https://img.shields.io/badge/Real--time-0F766E?style=flat-square" alt="Real-time" />
  <img src="https://img.shields.io/badge/Systems-1F2937?style=flat-square" alt="Systems" />
</p>

---

## ✨ 만들고 기록하는 것

화면에 보이는 기능 뒤에서 데이터가 어떻게 흐르고, 작업이 어떻게 끝나는지 살피는 일을 좋아합니다.
문제가 생기면 로그와 재현 가능한 사례에서 원인을 찾고, 다음 사람이 다시 따라갈 수 있도록 남깁니다.

### 🖥️ G-Shared <sub>비공개 프로젝트</sub>

> 쉬고 있는 GPU와 AI 연산이 필요한 사용자를 연결하는 GPU 공유 플랫폼

- **작업의 흐름** · GPU 워커 등록 → 작업 견적·배정 → 컨테이너 학습 → 결과 확인·정산
- **살펴본 문제** · 작업 상태와 실행 결과의 일관성, 실패 처리, 여러 서비스에 흩어진 로그 추적

`Java` · `Spring Boot` · `Python` · `WebSocket` · `Docker` · `Grafana / Loki / Alloy`

<br />

### 🔎 [circuit-agent](https://github.com/doukdoll/circuit-agent)

> 회로의 연결을 읽고, 계산 결과와 판단 근거를 함께 보여주는 검사 데모

- **만든 흐름** · QCV 파싱 → 부품·핀·넷 모델 구성 → 명목 FB 분압 계산 → JSON·HTML 보고서
- **판정의 기준** · 정상·위반·사람 검토를 구분하고, 값 누락이나 모호한 연결은 검토 대상으로 처리
- **검증 기록** · 공개 샘플과 기대 결과를 분리하고, 줄바꿈 차이까지 포함한 테스트 38개 통과 기록

`Java 21` · `Maven` · `JUnit`

[개발·실행 가이드 ↗](https://github.com/doukdoll/circuit-agent/blob/main/docs/DEVELOPMENT_GUIDE.md) · [샘플과 기대 결과 ↗](https://github.com/doukdoll/circuit-agent/blob/main/samples/README.md)

<br />

### 🐠 SmartFishTank <sub>비공개 프로젝트</sub>

> 해수어항의 센서 데이터를 모으고 상태를 살피는 IoT 프로젝트 · 백엔드·인프라

- **데이터 연결** · MQTT 기기 데이터 수집, Spring Boot API, MySQL·Redis 기반 데이터 처리
- **해결한 문제** · 기기 시계 오차로 오래된 값이 최신으로 선택되던 오류를 서버 수신 시각 기준으로 수정
- **함께 남긴 것** · Docker Compose 실행 방법, 환경변수 차이, MQTT 연결과 배포 트러블슈팅

`Java` · `Spring Boot` · `MySQL` · `Redis` · `MQTT` · `Docker Compose`

<br />

### 🚆 [수어 기반 기차 예매 키오스크](https://github.com/doukdoll/sign_language_ver.2)

> 웹캠의 수어 입력으로 역을 선택하고 열차를 조회하는 키오스크 프로토타입

- **연결한 흐름** · MediaPipe 키포인트 → WebSocket → Spring Boot → Python·ONNX 추론
- **다듬은 부분** · 사용자별 인식 세션 분리, 재접속·초기화, 카메라 종료와 예약 상태 처리
- **검증 기록** · FE·BE·AI 회귀 테스트와 GitHub Actions CI 구성, 실제 ONNX 연동은 별도 합성 입력으로 확인

`React` · `TypeScript` · `Spring Boot` · `WebSocket` · `Python` · `ONNX Runtime`

[연동 검증 기록 ↗](https://github.com/doukdoll/sign_language_ver.2/blob/main/docs/LIVE_RECOGNITION_CHECK.md) · [자동 검증 범위 ↗](https://github.com/doukdoll/sign_language_ver.2/blob/main/docs/CI.md)

---

<p align="center">
  <sub>작동하는 코드와 함께, 선택한 이유와 해결 과정을 남깁니다.</sub><br />
  <sub>Updated · 2026.11</sub>
</p>
