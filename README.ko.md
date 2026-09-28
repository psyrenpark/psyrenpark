## Psyren Park

[English](./README.md) · **한국어**

백엔드·클라우드 엔지니어 · 개발 경력 11년 · SV 9년
TypeScript · Node.js · NestJS · PostgreSQL · AWS (Lambda, CDK) · React / React Native

3명 팀에서 서버 개발과 AWS 운영을 총괄합니다.
CDK로 설계한 서버리스 인프라를 4개국(한국·인도네시아·필리핀·브라질)에서 운영하며, 한국 서비스만 월 Lambda 호출 1억~3.5억 회입니다.
기능을 출시한 다음의 문제, 즉 거래 정합성·운영 비용·인수인계를 주로 다룹니다.

### 맡고 있는 서비스

| 서비스 | 맡은 일 | 공개 스토어 정보 |
|---|---|---|
| **세일즈북 SalesVook** — 커머스 앱 | 서버·AWS 총괄 (2023~). 중복 요청 처리를 분리해 원 거래가 보존되도록 수정 | Google Play 10만+ |
| **슈퍼로찌 SuperLozzi** — 글로벌 앱테크 플랫폼 | 서버·AWS 총괄 (2021~). 다계정·다리전 서버리스 운영, React Native iOS 앱 | Google Play 국내 100만+ · 글로벌 100만+ |
| **울트라앱락 Ultra AppLock** | 다국어·관리자·예약 푸시 기능 개발 (2020), 현재 운영 관리 | Google Play 1,000만+ |
| **슈퍼뱅크 SuperVank** — 금융 리워드 앱 | 백엔드·인프라 (2018~2020): 준실시간 주식 동기화, 매크로 방지, 관리자 CMS | — |

고객사 프로젝트 PL (2021~2022):
- **글로벌 게임사 라이브 방송 퀴즈** — AWS IoT(MQTT), 8.5만 명 참여, 문항당 최대 7.2만 명 응답, 8개 언어
- **명품 브랜드 팝업 예약 시스템** — 초과 예약이 나던 시스템을 Aurora PostgreSQL로 재구축, 부하 테스트 12개 시나리오 성공률 99.99%

그 밖에: 공공기관 AI 학습·추론 데이터 과제에서 중간 JSONL 단계를 Arrow 직접 생성으로 대체하고,
검증 규약을 고정해 연구자에게 인수인계했습니다.

### 사례 글

- [중복 요청에도 원 거래를 지키는 법](https://blog.psyrenpark.com/work/reliable-transactions/)
- [AI 학습 데이터 생성부터 연구자 인수인계까지](https://blog.psyrenpark.com/work/data-workflow/)
- [AWS 청구서 분해 — 같은 계정 월 청구액 18.3% 감소](https://blog.psyrenpark.com/notes/aws-cost-analysis/)
- [인증과 서비스별 이용 권한 분리](https://blog.psyrenpark.com/notes/service-access-boundaries/)

### AI 활용

- [휴대폰 안에서 LLM으로 요약하기](https://blog.psyrenpark.com/work/on-device-summary/)
- [AI 도구 활용 원칙 — 구현과 검토에 쓰되, 설계 판단과 검증 기준은 직접](https://blog.psyrenpark.com/notes/ai-assisted-engineering/)

### 오픈소스

업무 중 만난 라이브러리 버그를 직접 고쳐 외부 PR 19건 중 7건이 병합됐습니다:
[OpenNext AWS 엣지 번들 경로](https://github.com/opennextjs/opennextjs-aws/pull/926) ·
[serverless-express](https://github.com/CodeGenieApp/serverless-express/pull/375) ·
[nestjs-i18n 문서](https://github.com/toonvanstrijp/nestjs-i18n/pull/625) ·
[react-native-admob-native-ads](https://github.com/ammarahm-ed/react-native-admob-native-ads/pull/267) 외

실무 코드는 비공개이며, 글에는 설계 판단과 검증 범위를 적었습니다.

**블로그** [blog.psyrenpark.com](https://blog.psyrenpark.com) · **경력** [blog.psyrenpark.com/resume](https://blog.psyrenpark.com/resume/) · **LinkedIn** [in/psyrenpark](https://www.linkedin.com/in/psyrenpark/)
