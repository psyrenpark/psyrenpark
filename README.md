## Psyren Park

**English** · [한국어](README.ko.md)

**Backend & Cloud Engineer · Customer Solutions · Applied AI**

11 years in development. At SV, I lead server development and AWS operations in a three-person team. I turn customer and operational requirements into systems, then work through implementation, rollout, training, and handover.

TypeScript · Node.js · NestJS · PostgreSQL · AWS CDK / Lambda · Next.js · React Native / Expo · Python

### AI implementation and workplace adoption

- **Memo — on-device summarization:** shipped an LLM feature using llama.rn, Gemma, and TinyLlama. Built model selection, downloads, and fallback behavior. Evaluated output format and factuality separately in 252 Mac-based runs; this is development evaluation, not a product-wide accuracy claim.
- **Customer-support records at SV:** proposed and taught a manual CLOVA transcription and summarization workflow. When a recognition error changed the meaning of a summary, added human correction to the procedure. Trained two staff members and received feedback that the workflow remained in use.
- **SalesVook operations:** built a sales-state-based chain to open the next selling wave from pre-registered configuration. Taught staff and managers how to use it, addressed operational exceptions, and supported adoption of scheduled Hermes / Codex checks and Telegram reporting.
- **Public-sector AI environment — independent client project:** replaced an intermediate training-data JSONL step with direct Arrow generation while preserving the operational data path. Validated data and API contracts and handed over a Windows-based workflow that researchers reported using.
- **Personal tools:** multi-account lodging change notifications, AI-assisted real-device QA, and GPU generation workflows with human review and failure recovery.

### Customer delivery and production engineering

- **Cloud operations:** prepared infrastructure for seven markets and operated services in four countries (KR, ID, PH, BR). Organized deployment into nine country/app CDK stacks. The Korean shared AWS account recorded roughly 100M–350M Lambda invocations per month across multiple services (July 2025–August 2026).
- **Client delivery:** supported AWS migration, troubleshooting, and environment cleanup for 11 clients. Built a luxury-brand reservation system from requirements and load testing through launch, an operations contract, and handover.
- **Live broadcast quiz:** led backend/infrastructure delivery for a global game publisher; approximately 85K cumulative participants in the first event, eight languages, and AWS IoT / MQTT.
- **Reusable foundations:** developed and maintained 12 npm packages for authentication, storage, APIs, and cloud infrastructure, with documentation and developer training.

### Products and tools

- **SalesVook:** commerce app; mobile, delivery/payment APIs, operations tooling, and transaction correctness.
- **SuperLozzi:** rewards app; Korean/global iPhone releases, backend, unified authentication, and cloud operations. **SuperVank:** stock-data collection and reward-state processing. **Ultra AppLock:** selected feature development and subsequent product maintenance.
- **Memo · Lotto · Vote · HostAuto:** personal products built with Next.js and Expo. **Base Kernel:** shared authentication and service permissions. **DataBridge:** data collection and delivery contracts. **Device Farm:** Android/iOS device QA. **Local Asset Studio:** GPU job execution and review.

### Case studies

- [On-device LLM summarization](https://blog.psyrenpark.com/work/on-device-summary/)
- [AI-assisted engineering and verification](https://blog.psyrenpark.com/notes/ai-assisted-engineering/)
- [Training data generation and researcher handover](https://blog.psyrenpark.com/work/data-workflow/)
- [Preserving transactions under duplicate requests](https://blog.psyrenpark.com/work/reliable-transactions/)
- [AWS cost analysis](https://blog.psyrenpark.com/notes/aws-cost-analysis/) — same-account monthly billing decreased 18.3% from July to August 2026, with usage and backup changes among the contributing factors.
- [Authentication and service access boundaries](https://blog.psyrenpark.com/notes/service-access-boundaries/)

### Open source

Fixes for issues encountered in implementation and operations:
[OpenNext AWS](https://github.com/opennextjs/opennextjs-aws/pull/926) ·
[serverless-express](https://github.com/CodeGenieApp/serverless-express/pull/375) ·
[nestjs-i18n](https://github.com/toonvanstrijp/nestjs-i18n/pull/625) ·
[react-native-admob-native-ads](https://github.com/ammarahm-ed/react-native-admob-native-ads/pull/267).

Production code is private. The articles explain design choices, responsibilities, and validation scope.

**Blog:** [blog.psyrenpark.com](https://blog.psyrenpark.com) · **LinkedIn:** [psyrenpark](https://www.linkedin.com/in/psyrenpark/)
