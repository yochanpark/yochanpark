## 박요찬 · Park Yochan

**Microsoft 365 · Power Platform 개발자.** 업무 앱을 만들고, 그 앱이 올라가는 인증·보안 인프라까지 같이 다룬다.

- Power Apps · Dataverse · Power Automate로 사내 업무 시스템 구축 (전자결재 · Teams 승인 연동)
- Power Pages 외부 포털, managed 솔루션 배포
- iOS 앱 Intune MAM Wrapping · Entra ID · 조건부 액세스 기술 검증
- 요건정의부터 게시 검증까지 — "저장했다"가 아니라 "게시본에서 확인했다"로 끝낸다

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

### 기술

`Power Apps (Canvas · Power Fx)` `Dataverse` `Power Automate` `Power Pages` `SharePoint` `Teams` <br/>
`Microsoft Intune` `Microsoft Entra ID` `iOS Code Signing` `Xcode` <br/>
`JavaScript` `pac CLI` `Dynamics 365`
