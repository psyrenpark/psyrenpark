## Psyren Park

**English** · [한국어](https://github.com/psyrenpark/psyrenpark/blob/main/README.ko.md)

**Backend & Cloud Engineer · Customer Solutions · Applied AI**

I am a backend and cloud engineer adapting to AI-driven changes in how we work and putting new technology to use in products and everyday operations. I have approximately 11 years of development experience and have led server development and AWS operations at SV since 2023. Our current development team has three members.

My work spans commercial app releases, multi-country AWS operations, and customer delivery through handover. I connect new capabilities to existing systems, revise methods based on errors and user feedback, and help teams and customers use them through documentation, training, and operating procedures.

[Transaction reliability](https://blog.psyrenpark.com/work/reliable-transactions/) · [Customer data workflow and handover](https://blog.psyrenpark.com/work/data-workflow/) · [On-device LLM delivery and evaluation](https://blog.psyrenpark.com/work/on-device-summary/)

TypeScript · Node.js · NestJS · PostgreSQL · AWS CDK / Lambda · Next.js · React Native / Expo · Python

### Customer delivery and production engineering

- **Cloud operations:** prepared infrastructure for seven markets and operated services in four countries (KR, ID, PH, BR). Organized deployment into nine country/app CDK stacks. The Korean shared AWS account recorded roughly 100M–350M Lambda invocations per month across multiple services (July 2025–August 2026).
- **Client delivery:** supported AWS migration, troubleshooting, and environment cleanup for 11 clients. Built a luxury-brand reservation system from requirements and load testing through launch, an operations contract, and handover.
- **Live broadcast quiz:** led backend/infrastructure delivery for a global game publisher; approximately 85K cumulative participants in the first event, eight languages, and AWS IoT / MQTT.
- **Reusable foundations:** developed and maintained 12 npm packages for authentication, storage, APIs, and cloud infrastructure over approximately four years, applied them in around 20 customer projects, managed backward compatibility and major versions to account for update costs, and supported adoption with documentation and developer training.

- **Training and curriculum delivery:** onboarded and mentored approximately 11 new hires. Served as PM for an SSAFY curriculum delivery project covering web, server, and IoT exercises, teaching materials, examples, and equipment setup.

### AI implementation and workplace adoption

- **Memo — on-device summarization:** shipped an LLM feature using llama.rn, Gemma, and TinyLlama. Built model selection, downloads, and fallback behavior. Evaluated two models different from the shipped models in 252 Mac-based runs, assessing output format and factuality separately. These runs do not establish product-wide accuracy.
- **Memo MCP and PC integration — personal pilot:** built search, source retrieval, and enrichment-draft tools using the TypeScript SDK and SQLite FTS5. Separated revision-based citations, explicit synchronization, and reviewed updates. Verified iPhone–Mac round trips and Codex read access with a designated account; broad distribution and long-term use remain outside this evidence.
- **Opportunity review — personal workflow:** implemented Python document processing and source validation, alongside JEV screening and Codex review. Found incorrect citations and eligibility judgments, revised inputs and validation, and retested the same samples. Updated collaboration-capability inputs in operation; improvement in judgment quality is still being evaluated.
- **DataBridge AI diagnosis — personal experiment:** separated code-based state classification from model explanations in a file-input, read-only CLI. Verified output and citation contracts on synthetic cases; this does not establish effectiveness in resolving real incidents.
- **Customer-support records at SV:** proposed and taught a manual CLOVA transcription and summarization workflow. When a recognition error changed the meaning of a summary, added human correction to the procedure. Trained two staff members and received feedback that the workflow remained in use.
- **SalesVook operations:** built a sales-state-based chain to open the next selling wave from pre-registered configuration. Taught staff and managers how to use it, addressed operational exceptions, and supported adoption of scheduled Hermes / Codex checks and Telegram reporting.
- **Public-sector AI environment — independent client project:** replaced an intermediate training-data JSONL step with direct Arrow generation while preserving the operational data path. Validated data and API contracts and handed over a Windows-based workflow that researchers reported using.
- **Personal tools:** multi-account lodging change notifications, AI-assisted real-device QA, and GPU generation workflows with human review and failure recovery.

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
