## Psyren Park

[English](https://github.com/psyrenpark/psyrenpark/blob/main/README.md) · **한국어**

**백엔드·클라우드 엔지니어 · 고객 시스템 구축 · AI 업무 적용**

AI로 달라지는 업무 환경에 적응하며, 새 기술을 서비스와 현업에 연결하는 백엔드·클라우드 엔지니어입니다. 총 개발 경력은 약 11년이며 SV에서는 2023년부터 서버 개발·운영을 총괄합니다. 현재 개발팀은 3명입니다.

상용 앱 출시·다국가 AWS 운영·고객 구축과 인계를 맡아왔습니다. 새 기능과 도구는 기존 시스템에 연결하고, 오류와 사용자 피드백에 따라 방법을 조정합니다. 문서·교육·운영 절차로 팀과 고객의 사용을 지원합니다.

[거래 처리·운영 개선](https://blog.psyrenpark.com/work/reliable-transactions/) · [고객 데이터·인계](https://blog.psyrenpark.com/work/data-workflow/) · [온디바이스 LLM 출시·평가](https://blog.psyrenpark.com/work/on-device-summary/)

TypeScript · Node.js · NestJS · PostgreSQL · AWS CDK/Lambda · Next.js · React Native/Expo · Python

### 고객 구축·클라우드 운영

- 7개 시장 준비·4개국 운영(KR·ID·PH·BR), 국가·앱별 CDK 스택 9개. 한국 공유 계정의 월 Lambda 약 1억에서 3.5억 회(2025년 7월부터 2026년 8월, 여러 서비스 합산).
- 고객사 11곳의 AWS 이관·장애 대응·환경 정리 지원. 명품 브랜드 예약 시스템의 요구 협의·부하 검증·오픈·운영 계약·인계 담당.
- 글로벌 게임사 라이브 퀴즈: 3명 팀 PL·서버/인프라, 첫 행사 누적 약 8.5만 명·8개 언어·AWS IoT/MQTT.
- 인증·저장·API·AWS 공통 기반의 npm 패키지 12개를 약 4년간 개발·유지하고 고객 프로젝트 20여 개에 적용. 사용처의 업데이트 부담을 고려해 하위 호환과 메이저 버전을 관리하고 문서·발표·교육으로 보급.

- **교육·납품:** 신입 약 11명 온보딩·프로젝트 지도. SSAFY 납품 과제 PM으로 웹·서버·IoT 실습·교재·예제·장비 구성 제작.

### AI 구현·현업 적용

- **Memo 온디바이스 요약:** llama.rn·Gemma·TinyLlama 연동, 모델 선택·다운로드·실패 시 기존 요약 복귀, 기능 출시. 출시 모델과 별도의 2개 모델을 Mac에서 252회 평가하며 출력 형식과 사실성 구분.
- **Memo MCP·PC 파일럿(개인):** AI 도구에서 메모 검색·원문 조회·보강 초안을 만들도록 구현. SQLite FTS5 검색과 원문 버전 확인·사람의 검토 후 반영을 분리하고 지정 계정의 iPhone–Mac 왕복·Codex 읽기 조회 검증. 개인 파일럿으로 일반 배포·장기 사용과 구분.
- **공고 검토(개인):** Python 문서 처리·출처 검증과 JEV·Codex 활용. 실제 모델의 잘못된 인용·자격 판단을 발견해 입력·검증을 수정하고 동일 표본 재시험. 협력 역량 입력 보완·운영 반영, 판단 품질 개선 효과는 검증 중.
- **DataBridge AI 진단(개인 실험):** 파일 입력 기반 읽기 전용 CLI에서 코드의 상태 분류와 모델의 근거 설명을 분리. 합성 사례의 출력·인용 계약을 검증했으며 실제 장애 해결 효과와 구분.
- **고객 상담 기록:** 클로바 수동 전사·요약 활용법 제안, 담당자 2명 교육. 오인식이 요약에 전파되는 사례에서 사람의 텍스트 보정 절차 적용·지속 사용 피드백 수신.
- **SalesVook 운영:** 매진 후 수동 등록을 사전 등록·판매 상태 기반 체인으로 전환. 실무자·상급자에게 사용법 권장·교육·실제 업무 적용, 운영 예외 수정. Hermes·Codex 예약 점검·Telegram 보고 활용 교육·적용 지원.
- **공기업 AI 환경(독립 고객 과제):** 운영 데이터 경로를 보존하며 학습용 Arrow 직접 생성, 데이터·API 계약 검증. Windows 실행·검수 절차를 연구자에게 인계, 직접 사용 피드백 수신.
- **개인 도구:** 여러 계정의 숙박 일정 변경 알림, AI와 Android·iOS 실기기 QA, GPU 생성 작업·결과 검토·실패 복구.

### 제품·개발 도구

- **SalesVook:** 커머스 앱·배송/결제 API·운영 도구·거래 배치. **SuperLozzi:** 참여·보상 앱의 국내·글로벌 iPhone 출시·서버·통합 인증·AWS.
- **SuperVank:** 시세 데이터·보상 상태 처리. **Ultra AppLock:** 일부 기능 개발·제품 관리.
- **Memo·Lotto·Vote·HostAuto:** Next.js·Expo 개인 제품. **Base Kernel:** 공통 인증·서비스 권한. **DataBridge:** 수집·데이터 전달. **Device Farm:** 실기기 QA. **Local Asset Studio:** GPU 작업 관리.

### 사례 글

- [온디바이스 LLM 요약](https://blog.psyrenpark.com/work/on-device-summary/)
- [AI와 개발·검증](https://blog.psyrenpark.com/notes/ai-assisted-engineering/)
- [학습 데이터 처리·연구자 인계](https://blog.psyrenpark.com/work/data-workflow/)
- [중복 요청과 거래 결과 보존](https://blog.psyrenpark.com/work/reliable-transactions/)
- [AWS 비용 분석](https://blog.psyrenpark.com/notes/aws-cost-analysis/) — 동일 계정 2026년 7월에서 8월 청구 약 18.3% 감소 확인(사용량·백업 등 복합 요인).
- [인증과 서비스 권한 분리](https://blog.psyrenpark.com/notes/service-access-boundaries/)

### 오픈소스

업무에서 만난 문제 수정·기여: [OpenNext AWS](https://github.com/opennextjs/opennextjs-aws/pull/926), [serverless-express](https://github.com/CodeGenieApp/serverless-express/pull/375), [nestjs-i18n](https://github.com/toonvanstrijp/nestjs-i18n/pull/625), [react-native-admob-native-ads](https://github.com/ammarahm-ed/react-native-admob-native-ads/pull/267).

운영 코드는 비공개이며 사례 글에서 판단·담당 범위·검증 조건을 설명.

[블로그](https://blog.psyrenpark.com) · [LinkedIn](https://www.linkedin.com/in/psyrenpark/)
