# FOWOCO

**E-9 외국인근로자 HR·행정업무를 구조화하는 AI 업무보조 플랫폼**

FOWOCO는 E-9 외국인근로자를 고용한 사업장의 HR·총무 담당자가 복잡한 계약,
체류, 서류, 신고 업무를 빠뜨리지 않도록 돕는 서비스입니다. AI가 업무 요청과
문서를 분석하고, 필요한 절차와 서류 초안을 준비해 담당자의 반복 업무를 줄입니다.

## 서비스 흐름

```text
만료일·HR 요청·문서 업로드
→ 업무 유형과 필요한 정보 분석
→ 필수 서류·유효기간·누락값 확인
→ 업무카드와 문서 초안 생성
→ HR 검토·승인
→ 근로자 안내 또는 기관 제출 준비
→ 결과와 증빙 기록
```

## FOWOCO가 돕는 일

- 근로자별 계약·체류·서류 상태와 만료일 관리
- 업무별 필수정보·서류·유효기간 확인
- 자연어 요청과 업로드 문서를 활용한 업무카드·문서 초안 준비
- 쉬운 한국어·다국어 안내와 근로자 응답 확인
- HR 승인부터 제출 결과와 후속 업무까지 하나의 흐름으로 관리

## Team FOWOCO

FOWOCO는 **KT AIVLE School 빅프로젝트에서 8명의 팀원이 함께 만드는 팀
프로젝트**입니다.

| 팀원 | 역할 | 주요 담당 |
| --- | --- | --- |
| 현준 | TPM · Product Design · Backend | 제품 방향과 Workflow 기획, UI/UX 설계, Spring 기반 서비스 연동 |
| 채은 | Project Operations · ML Engineering | 회의·산출물 관리, Intent 모델 학습·평가, 모델 서빙 |
| 주현 | Agent Engineering | Agent 실행 흐름, Shared State와 도구 호출 구조 구현 |
| 태정 | Document Agent Engineering | HWP·HWPX 문서 분석, 필드 매핑과 초안 생성 |
| 휘 | Agent Engineering | 조건 분기, Agent 간 연동과 결과 검증 |
| 재성 | Data · Backend Engineering | DB 모델링과 영속화, Spring API 구현 |
| 경민 | Full-stack · Platform Engineering | HR 웹 구현, DB 연동, 배포·인프라 구성 |
| 채린 | Backend Engineering | Spring 도메인 로직, Workflow 상태와 서비스 API 구현 |

> 기술을 위한 기능보다 현장에서 실제로 사용할 수 있는 업무 흐름을 만드는 것을
> 목표로 합니다.
