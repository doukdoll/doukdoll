# doukdoll

백엔드를 중심으로 **실시간 데이터가 서비스의 기능으로 이어지는 과정**을 만듭니다. API와 데이터 흐름을 구현하고, 실행·검증 과정에서 발견한 문제를 문서로 남깁니다.

## Selected projects

### 수어 기반 기차 예매 키오스크

웹캠의 수어 입력을 역 이름 인식과 열차 조회로 연결하는 키오스크 프로토타입입니다.

- 브라우저에서 추출한 MediaPipe 키포인트를 WebSocket으로 전달하고, Spring Boot 중계를 거쳐 Python 서버의 ONNX 모델로 추론합니다.
- 열차 시간표 조회 API와 키오스크 화면을 연결하고, 인식 세션의 재접속·초기화 흐름을 구현했습니다.
- 실제 철도 예매 및 결제 서비스와 연결된 제품은 아닙니다. 구현 범위와 검증 결과를 저장소에 구분해 기록했습니다.

`React` · `TypeScript` · `Spring Boot` · `WebSocket` · `Python` · `ONNX Runtime`

[저장소](https://github.com/doukdoll/sign_language_ver.2) · [시스템 흐름](https://github.com/doukdoll/sign_language_ver.2#%EC%8B%9C%EC%8A%A4%ED%85%9C-%ED%9D%90%EB%A6%84) · [연동 검증 기록](https://github.com/doukdoll/sign_language_ver.2/blob/main/docs/LIVE_RECOGNITION_CHECK.md)

### SmartFishTank

해수어항의 센서 데이터를 수집하고 상태를 확인하는 IoT 프로젝트입니다. 백엔드와 인프라를 중심으로 작업했습니다.

- MQTT로 들어오는 기기 데이터를 API와 저장소에 연결하고, MySQL·Redis·Docker Compose 기반 실행 환경을 다룹니다.
- 기기 시계 오차 때문에 오래된 센서 값이 최신으로 선택되던 문제를 서버 수신 시각 기준으로 수정했습니다.
- 로컬 실행 방식, 환경변수 차이, MQTT 연결 문제와 배포 과정을 문서화했습니다.

`Java` · `Spring Boot` · `MySQL` · `Redis` · `MQTT` · `Docker Compose`

[저장소](https://github.com/doukdoll/SmartFishTank) · [실행 및 트러블슈팅](https://github.com/doukdoll/SmartFishTank#%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85) · [협업 기록](https://github.com/doukdoll/SmartFishTank/blob/master/docs/gitlab-history/README.md)

---

<sub>코드와 함께 설계 의도, 검증 과정, 해결한 문제를 기록합니다.</sub>
