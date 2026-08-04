# FOWOCO

> **E-9 외국인근로자 HR·행정업무를 구조화하는 AI 업무보조 서비스**

## Project

| 구분 | 내용 |
| --- | --- |
| **소속** | KT AIVLE School AI Track 빅프로젝트 · 수도권 5반 14조 |
| **기간** | 2026.06.29 - 2026.08.26 |
| **주제** | E-9 외국인근로자를 고용한 사업장의 계약·체류·서류·신고 업무 지원 |
| **목표** | 분산된 기한과 서류를 업무 흐름으로 연결해 담당자의 반복 확인과 누락을 줄이는 것 |

## Service

FOWOCO는 단순 번역이나 법률 판단 서비스가 아닙니다. HR 담당자가 해야 할 일을 놓치지 않도록 **요청 분석, 절차 안내, 문서 초안, 근로자 소통, 처리 상태**를 하나의 흐름으로 연결합니다.

```text
만료일·HR 요청·문서 업로드
→ 업무 유형과 필요한 정보 확인
→ Case·Task와 문서 초안 준비
→ HR 검토·승인
→ 근로자 안내·서류 제출
→ 증빙 확인과 다음 업무 진행
```

- 계약·체류·서류 기한과 진행 상태 통합 확인
- 자연어 요청과 문서에서 처리할 업무 후보 생성
- 공식 서식 기반 행정문서 초안과 제출 체크리스트 제공
- 쉬운 한국어·다국어 안내와 근로자 응답 추적

> AI는 업무를 분석하고 초안을 준비하며, 최종 검토와 기관 제출은 담당자가 수행합니다.

## Team

<table>
  <tbody>
    <tr>
      <td align="center" width="25%"><a href="https://github.com/hywznn"><img src="https://github.com/hywznn.png?size=120" width="90" alt="현준 GitHub 프로필"></a></td>
      <td align="center" width="25%"><a href="https://github.com/chaeeunn4"><img src="https://github.com/chaeeunn4.png?size=120" width="90" alt="채은 GitHub 프로필"></a></td>
      <td align="center" width="25%"><a href="https://github.com/ajh1004ajh00"><img src="https://github.com/ajh1004ajh00.png?size=120" width="90" alt="주현 GitHub 프로필"></a></td>
      <td align="center" width="25%"><a href="https://github.com/taejung3852"><img src="https://github.com/taejung3852.png?size=120" width="90" alt="태정 GitHub 프로필"></a></td>
    </tr>
    <tr>
      <td align="center"><b>현준</b><br><a href="https://github.com/hywznn">@hywznn</a></td>
      <td align="center"><b>채은</b><br><a href="https://github.com/chaeeunn4">@chaeeunn4</a></td>
      <td align="center"><b>주현</b><br><a href="https://github.com/ajh1004ajh00">@ajh1004ajh00</a></td>
      <td align="center"><b>태정</b><br><a href="https://github.com/taejung3852">@taejung3852</a></td>
    </tr>
    <tr>
      <td align="center"><sub>TPM · Product Design · Backend</sub></td>
      <td align="center"><sub>Project Operations · ML Engineering</sub></td>
      <td align="center"><sub>OCR Agent · Document Intake</sub></td>
      <td align="center"><sub>Document Agent · HWPX Automation</sub></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/EHWIYA"><img src="https://github.com/EHWIYA.png?size=120" width="90" alt="휘 GitHub 프로필"></a></td>
      <td align="center"><a href="https://github.com/krestar"><img src="https://github.com/krestar.png?size=120" width="90" alt="재성 GitHub 프로필"></a></td>
      <td align="center"><a href="https://github.com/BcKmini"><img src="https://github.com/BcKmini.png?size=120" width="90" alt="경민 GitHub 프로필"></a></td>
      <td align="center"><a href="https://github.com/chaeliki"><img src="https://github.com/chaeliki.png?size=120" width="90" alt="채린 GitHub 프로필"></a></td>
    </tr>
    <tr>
      <td align="center"><b>휘</b><br><a href="https://github.com/EHWIYA">@EHWIYA</a></td>
      <td align="center"><b>재성</b><br><a href="https://github.com/krestar">@krestar</a></td>
      <td align="center"><b>경민</b><br><a href="https://github.com/BcKmini">@BcKmini</a></td>
      <td align="center"><b>채린</b><br><a href="https://github.com/chaeliki">@chaeliki</a></td>
    </tr>
    <tr>
      <td align="center"><sub>Agent Orchestration · AI Serving</sub></td>
      <td align="center"><sub>Data · Backend Engineering</sub></td>
      <td align="center"><sub>Frontend · Platform Engineering</sub></td>
      <td align="center"><sub>Application · Backend Engineering</sub></td>
    </tr>
  </tbody>
</table>

### Team Responsibilities

| 담당 | 책임 영역 | 주요 결과물 |
| --- | --- | --- |
| **현준** | TPM · Product Design · Backend Integration | 서비스 범위와 UX 의사결정, Case·Task·승인 설계, Server와 AI Runtime 연동 |
| **채은** | Project Operations · ML Engineering | 회의·산출물 관리, Intent 데이터 구축, A.X·BERT 학습과 성능 비교·평가 |
| **주현** | OCR Agent · Document Intake | 여권·외국인등록증 분류, CLOVA OCR 호출, 필드 정규화와 저장 계약 |
| **태정** | Language/Document Agent · HWPX Automation | HWPX 구조 분석, 필드 매핑·초안 작성, 렌더링과 수정 결과 검증 |
| **휘** | Supervisor Agent · AI Serving | Intent·모호성 분석, LangGraph 상태·분기 관리, Workflow 실행·재개 API |
| **재성** | Database · Backend Engineering | PostgreSQL 스키마·Flyway, RLS 사업장 격리, 시드 데이터와 DB 안정성 |
| **경민** | Frontend · Platform · Infra | 화면·공통 컴포넌트와 API 연동, 접근성·상태 UX, Docker·Actions·k3s 배포 |
| **채린** | Application · Backend Engineering | 근로자·문서 API, Worker 보안 링크, 멱등 파일 제출과 근로자 응답 처리 |

 
