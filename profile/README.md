<div align="center">

# FOWOCO

### E-9 외국인 근로자 HR·행정업무를 연결하는 AI 업무보조 서비스

계약·체류·서류·신고 업무를 하나의 흐름으로 관리하고<br>
AI가 요청 분석부터 문서 초안, 근로자 안내와 후속 업무까지 지원합니다.

**KT AIVLE School AI Track** · **2026.06.29 - 2026.08.26**

</div>

---

## Service Flow

```text
기한 감지·HR 요청·문서 업로드
→ 업무 분석·필수정보 확인
→ Case·Task 생성·문서 초안
→ HR 검토·승인
→ 근로자 안내·서류 제출
→ 완료 증빙·후속 업무 연결
```

## Key Features

- **업무 구조화**: 자연어 요청과 만료일을 분석해 실행할 업무와 절차 생성
- **문서 초안**: DB·OCR 정보를 HWPX 서식에 반영하고 누락정보 확인
- **다국어 소통**: 쉬운 한국어와 모국어 안내, 질문·확인·서류 제출 추적
- **상태 관리**: Case별 진행 단계, 승인, 완료 증빙과 다음 업무 통합 관리

> AI는 분석과 초안 작성을 지원하며, 최종 승인과 기관 제출은 HR 담당자가 수행합니다.

## Team

<table>
  <tbody>
    <tr>
      <td align="center" width="25%"><a href="https://github.com/hywznn"><img src="https://github.com/hywznn.png?size=120" width="80" alt="최현준 GitHub 프로필"></a><br><b>최현준</b><br><a href="https://github.com/hywznn">@hywznn</a><br><sub>TPM · Product Design<br>Backend Integration</sub></td>
      <td align="center" width="25%"><a href="https://github.com/chaeeunn4"><img src="https://github.com/chaeeunn4.png?size=120" width="80" alt="이채은 GitHub 프로필"></a><br><b>이채은</b><br><a href="https://github.com/chaeeunn4">@chaeeunn4</a><br><sub>Project Operations<br>ML Engineering</sub></td>
      <td align="center" width="25%"><a href="https://github.com/ajh1004ajh00"><img src="https://github.com/ajh1004ajh00.png?size=120" width="80" alt="안주현 GitHub 프로필"></a><br><b>안주현</b><br><a href="https://github.com/ajh1004ajh00">@ajh1004ajh00</a><br><sub>OCR Agent<br>Document Intake</sub></td>
      <td align="center" width="25%"><a href="https://github.com/taejung3852"><img src="https://github.com/taejung3852.png?size=120" width="80" alt="박태정 GitHub 프로필"></a><br><b>박태정</b><br><a href="https://github.com/taejung3852">@taejung3852</a><br><sub>Language · Document Agent<br>HWPX Automation</sub></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/EHWIYA"><img src="https://github.com/EHWIYA.png?size=120" width="80" alt="이휘 GitHub 프로필"></a><br><b>이휘</b><br><a href="https://github.com/EHWIYA">@EHWIYA</a><br><sub>Agent Orchestration<br>AI Serving</sub></td>
      <td align="center"><a href="https://github.com/krestar"><img src="https://github.com/krestar.png?size=120" width="80" alt="김재성 GitHub 프로필"></a><br><b>김재성</b><br><a href="https://github.com/krestar">@krestar</a><br><sub>Database<br>Backend Engineering</sub></td>
      <td align="center"><a href="https://github.com/BcKmini"><img src="https://github.com/BcKmini.png?size=120" width="80" alt="김경민 GitHub 프로필"></a><br><b>김경민</b><br><a href="https://github.com/BcKmini">@BcKmini</a><br><sub>Frontend · Platform<br>Infrastructure</sub></td>
      <td align="center"><a href="https://github.com/chaeliki"><img src="https://github.com/chaeliki.png?size=120" width="80" alt="김채린 GitHub 프로필"></a><br><b>김채린</b><br><a href="https://github.com/chaeliki">@chaeliki</a><br><sub>Application<br>Backend Engineering</sub></td>
    </tr>
  </tbody>
</table>

## Team Contributions

| Name | GitHub | 주요 구현 |
| --- | --- | --- |
| **최현준** | [@hywznn](https://github.com/hywznn) | • 제조업 HR 인터뷰 기반 서비스 범위와 3개 Master Workflow 설계<br>• Case·Task·승인 모델 및 Spring Server–AI Runtime 비동기 연동 구현<br>• Figma UX, 개인정보 보호, 멀티레포 운영과 대표 E2E 시나리오 통합 |
| **이채은** | [@chaeeunn4](https://github.com/chaeeunn4) | • Intent 데이터 1,340건 검수와 학습·평가 데이터 관리<br>• A.X-4.0-Light QLoRA와 BERT Intent 분류 모델 학습<br>• Few-shot·QLoRA·BERT 성능 및 추론 자원 비교 |
| **안주현** | [@ajh1004ajh00](https://github.com/ajh1004ajh00) | • CLOVA Template OCR 기반 여권·외국인등록증 인식 파이프라인 구현<br>• 문서 유형별 필드 추출, 날짜·식별번호 정규화와 형식 검증<br>• OCR 신뢰도·필드 출처 관리와 Server 저장 계약 연동 |
| **박태정** | [@taejung3852](https://github.com/taejung3852) | • HWPX XML 구조 분석과 공식 서식별 필드 매핑 구현<br>• DB·OCR·HR 입력값을 조합한 행정문서 초안 생성<br>• 쉬운 한국어·다국어 안내와 핵심정보 보존 검증 연동 |
| **이휘** | [@EHWIYA](https://github.com/EHWIYA) | • LangGraph 기반 Supervisor Graph와 Shared State 설계<br>• Intent·Slot·모호성 분석 및 조건별 Workflow 라우팅 구현<br>• 중단 지점 저장, 정보 보완 후 실행 재개와 AI Serving API 구축 |
| **김재성** | [@krestar](https://github.com/krestar) | • PostgreSQL 도메인 스키마와 Flyway 마이그레이션 구축<br>• RLS 기반 사업장 데이터 격리와 시드 데이터 관리<br>• 문서·업무 데이터의 트랜잭션 및 멱등 저장 기반 구현 |
| **김경민** | [@BcKmini](https://github.com/BcKmini) | • React 기반 대시보드·업무함·문서함·근로자 화면 구현<br>• 비동기 실행 상태와 예외 상태를 포함한 API 연동 UX 구축<br>• Docker·GitHub Actions·k3s 배포 및 모니터링 환경 구성 |
| **김채린** | [@chaeliki](https://github.com/chaeliki) | • 근로자·문서·대시보드 중심 Application API 구현<br>• 만료형 Worker 보안 링크와 모바일 응답·파일 제출 처리<br>• 멱등 제출, 응답 상태 반영과 담당자 후속 알림 연결 |
