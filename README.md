## 박요찬 · Park Yochan

**Microsoft 365 · Power Platform 개발자.** RPA에서 시작해 Power Platform, AI Agent까지 — 업무 앱을 만들고, 그 앱이 올라가는 인증·보안 인프라까지 같이 다룬다. 자동화·개발 약 5년.

- Power Apps · Dataverse · Power Automate로 사내 업무 시스템 구축 (전자결재 · Teams 승인 연동)
- Power Pages 외부 포털, managed 솔루션 배포
- iOS 앱 Intune MAM Wrapping · Entra ID · 조건부 액세스 기술 검증
- Teams + GPT LLM 업무 자동화 에이전트, RPA 200여 개 과제 운영
- 요건정의부터 게시 검증까지 — "저장했다"가 아니라 "게시본에서 확인했다"로 끝낸다

📫 x9vsyo@gmail.com

---

### 프로젝트

| 프로젝트 | 무엇을 했나 | 기술 |
|---|---|---|
| [**사내 자산관리 시스템**](https://github.com/yochanpark/powerapps-asset-management) | 검수 피드백 14장·40건 반영. Power Fx Code128 라벨 PDF, CSV 일괄 업로드, 사업부 위치 기반 조직 권한, Teams 전자결재 | Power Apps · Dataverse · Power Automate |
| [**iOS 앱 Intune MAM Wrapping**](https://github.com/yochanpark/ios-intune-mam-wrapping) | App Extension 6개를 유지한 채 재서명 → Wrapping → MAM 정책 적용까지 실기기로 실증. 커스텀 앱이 조건부 액세스를 통과 못 하는 구조적 제약 규명 | iOS 코드 서명 · Intune · Entra ID |
| [**Power Pages 주문 접수 포털**](https://github.com/yochanpark/powerpages-order-portal) | 외부 거래처 주문 포털. 채번 규칙을 설정 테이블로 분리, 채번 완료 시점 트리거, managed 솔루션 배포 | Power Pages · Dataverse · Power Automate |
| [**Kintone 전자결재 커스터마이징**](https://github.com/yochanpark/kintone-approval-customization) | 결재 완료 후에도 금액이 수정되던 내부통제 결함을 3중 차단(버튼·화면·저장)으로 봉쇄 | JavaScript · Kintone API |
| [**ERP 업무 RPA 요건정의**](https://github.com/yochanpark/rpa-process-requirements) | D365 업무 7건을 입력 경로 기준으로 분해. 화면 녹화로 프로세스 복원, 미확정 항목은 요청으로 되돌림 | RPA · Dynamics 365 |

---

### 경력

**FUJIFILM Business Innovation Korea** · SD(Solution Design)팀 · 2025.11 ~ 재직 중
Power Platform · UiPath · Kintone 기반 자동화·플랫폼 개발, 고객사 대응 단독 담당
- 자산관리 Canvas 앱 — KPI 대시보드, 자산 검색·상세, 바코드 출력, 바코드 스캔 기반 재고실사
- 전자결재 시스템 — Power Apps 화면 + Power Automate 순차 결재 라우팅 + Teams Adaptive Card 알림
- 의료기기 제조사 모바일 보안 PoC — Intune MAM 기반 iOS 앱 래핑, Entra 앱 등록·프로비저닝
- 디자인사 회원·주문 포털 — Power Pages, Dataverse Web API 인증·권한 이슈 해결, SharePoint 문서 권한 주문 단위 스코핑
- 법인카드 영수증 처리 Teams 봇 — GPT-4 Vision 인식 결과를 RPA용 JSON으로 정제해 Adaptive Card로 전달
- UiPath 자동화 — 수백 개 `.xaml`의 셀렉터를 PowerShell로 일괄 수정 (XML 이스케이프 구조 분석)

**레인보우브레인** · 기술본부 PS팀 선임 · 2024.06 ~ 2025.10
AI Agent 및 RPA 기반 업무 자동화 시스템 설계·개발
- 제약사 — MS Teams와 GPT LLM을 연동한 업무자동화 에이전트, 수작업 보고 시간 **60% 이상 단축**
- 바이오 기업 — 내부 DB와 AWS API를 연동한 전사형 자동화, 정확도 **99%**

**에코아이티** · RPA사업본부 대리 · 2021.06 ~ 2024.01
전사 RPA 과제 개발·컨설팅, BrityRPA 인프라 구축
- 화학 제조사 — 자동화 과제 **200여 개**를 RPA PL로 운영·유지보수, COE 조직 전략 수립·운영 정책 표준화
- 공공기관 3곳 — 시스템 연계 및 성능 최적화

**스타일링단단** · VMD디자인팀 대리 · 2018.09 ~ 2020.06
VMD 디스플레이 디자인 기획, 브랜드 프로모션 컨설팅 — 디자인에서 개발로 전환하기 전 경력

---

### 학력 · 교육

- **자바(JAVA) 스프링 응용SW 개발자 양성과정 (파이썬 활용)** — 한국정보교육원 · 2020.11 ~ 2021.05 · 1,440시간
- **신구대학교 그래픽아츠미디어과** — 전문학사 · 2019.02 졸업

---

### 기술

| 구분 | 내용 |
|---|---|
| Power Platform | Power Apps (Canvas · Model-driven · Power Fx), Power Automate, Power Pages, Dataverse (Web API) |
| Microsoft 365 · 보안 | Entra ID 앱 등록·권한, Intune MAM, 조건부 액세스, SharePoint, Teams (Adaptive Cards) |
| 모바일 | iOS 코드 서명, App ID·프로비저닝 프로파일, Intune App Wrapping |
| AI · 자동화 | GPT API, GPT-4 Vision, Teams AI Agent, UiPath, Automation Anywhere, BrityRPA |
| 개발 · 데이터 | PowerShell, JavaScript, Node.js (Express), Python, MySQL, MSSQL, `pac` CLI |
| 협업 플랫폼 | Kintone, Dynamics 365 |
