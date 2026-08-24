<div align="center">

# FOWOCO

### E-9 외국인 근로자 HR·행정업무를 연결하는 AI 업무보조 서비스

**KT AIVLE School AI Track** · **2026.06.29 - 2026.08.26**

<br>

<img width="1920" height="815" alt="FOWOCO 현재 서비스 대시보드" src="https://github.com/user-attachments/assets/6ccd3f61-28af-4206-8e1e-bf558ba6d421">

</div>

---

외국인 근로자 한 명의 재계약과 체류 업무에는 **계약 종료일, 고용허가기간, 취업활동기간과 체류기간**을 각각 확인하고, 고용24·HiKorea 등 기관별 절차를 순서대로 처리하는 일이 필요합니다. 서류가 누락되거나 만료되면 담당자는 근로자에게 다시 요청하고 진행 상태를 처음부터 확인하게 됩니다.

문제는 이 과정이 **엑셀, 문서 폴더, 메신저와 담당자의 기억**에 흩어져 있다는 점입니다. FOWOCO는 담당자 대신 다음을 먼저 확인합니다.

- 어떤 근로자의 어떤 기한이 임박했는지
- 필요한 문서가 준비됐고 유효한지
- 다음에 처리할 업무와 필요한 승인이 무엇인지
- 근로자에게 무엇을 요청했고 제출이 완료됐는지

한마디로 FOWOCO는 외국인력 행정업무를 **담당자가 기억하는 일에서 시스템이 추적하는 일로 전환**하는 플랫폼입니다. 기한 감지와 자연어 요청 분석부터 문서 초안, HR 승인, 쉬운 한국어·모국어 안내, 근로자 응답과 완료 증빙까지 하나의 업무 흐름으로 연결합니다.

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

<table width="100%">
  <thead>
    <tr>
      <th width="18%">Contributor</th>
      <th width="82%">주요 구현</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>최현준</b><br><a href="https://github.com/hywznn">@hywznn</a></td>
      <td>• 제조업 HR 인터뷰 기반 서비스 범위와 3개 Master Workflow 설계<br>• Case·Task·승인 모델 및 Spring Server–AI Runtime 비동기 연동 구현<br>• Figma UX, 개인정보 보호, 멀티레포 운영과 대표 E2E 시나리오 통합</td>
    </tr>
    <tr>
      <td><b>이채은</b><br><a href="https://github.com/chaeeunn4">@chaeeunn4</a></td>
      <td>• Intent 데이터 1,340건 검수와 학습·평가 데이터 관리<br>• A.X-4.0-Light QLoRA와 BERT Intent 분류 모델 학습<br>• Few-shot·QLoRA·BERT 성능 및 추론 자원 비교</td>
    </tr>
    <tr>
      <td><b>안주현</b><br><a href="https://github.com/ajh1004ajh00">@ajh1004ajh00</a></td>
      <td>• CLOVA Template OCR 기반 여권·외국인등록증 인식 파이프라인 구현<br>• 문서 유형별 필드 추출, 날짜·식별번호 정규화와 형식 검증<br>• OCR 신뢰도·필드 출처 관리와 Server 저장 계약 연동</td>
    </tr>
    <tr>
      <td><b>박태정</b><br><a href="https://github.com/taejung3852">@taejung3852</a></td>
      <td>• HWPX XML 구조 분석과 공식 서식별 필드 매핑 구현<br>• DB·OCR·HR 입력값을 조합한 행정문서 초안 생성<br>• 쉬운 한국어·다국어 안내와 핵심정보 보존 검증 연동</td>
    </tr>
    <tr>
      <td><b>이휘</b><br><a href="https://github.com/EHWIYA">@EHWIYA</a></td>
      <td>• LangGraph 기반 Supervisor Graph와 Shared State 설계<br>• Intent·Slot·모호성 분석 및 조건별 Workflow 라우팅 구현<br>• 중단 지점 저장, 정보 보완 후 실행 재개와 AI Serving API 구축</td>
    </tr>
    <tr>
      <td><b>김재성</b><br><a href="https://github.com/krestar">@krestar</a></td>
      <td>• PostgreSQL 도메인 스키마와 Flyway 마이그레이션 구축<br>• RLS 기반 사업장 데이터 격리와 시드 데이터 관리<br>• 문서·업무 데이터의 트랜잭션 및 멱등 저장 기반 구현</td>
    </tr>
    <tr>
      <td><b>김경민</b><br><a href="https://github.com/BcKmini">@BcKmini</a></td>
      <td>• React 기반 대시보드·업무함·문서함·근로자 화면 구현<br>• 비동기 실행 상태와 예외 상태를 포함한 API 연동 UX 구축<br>• Docker·GitHub Actions/k3s on AWS 배포 및 모니터링 환경 구성</td>
    </tr>
    <tr>
      <td><b>김채린</b><br><a href="https://github.com/chaeliki">@chaeliki</a></td>
      <td>• 근로자·문서·대시보드 중심 Application API 구현<br>• 만료형 Worker 보안 링크와 모바일 응답·파일 제출 처리<br>• 멱등 제출, 응답 상태 반영과 담당자 후속 알림 연결</td>
    </tr>
  </tbody>
</table>

---

## Expected Impact

> 인터뷰 기준선과 대표 시나리오를 바탕으로 설정한 **2주 파일럿 검증 목표**입니다. 실제 도입 효과는 처리시간·재요청·누락 건수로 재측정합니다.

<table width="100%">
  <thead>
    <tr>
      <th width="23%">평가 지표</th>
      <th width="20%">현재 기준</th>
      <th width="24%">FOWOCO 목표</th>
      <th width="33%">산정 근거</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>주간 행정 처리시간</b></td>
      <td>주 1~2시간</td>
      <td><b>50% 이상 단축</b></td>
      <td>숙련 제조업 HR 인터뷰 기준, 기한 확인·서류 점검·재요청 업무 포함</td>
    </tr>
    <tr>
      <td><b>업무 확인 접점</b></td>
      <td>4개 이상</td>
      <td><b>1개 업무 흐름으로 통합</b></td>
      <td>Excel·문서 폴더·메신저·기관 사이트의 진행 상태를 Case·Task로 연결</td>
    </tr>
    <tr>
      <td><b>공통정보 반복 입력</b></td>
      <td>서식별 반복 입력</td>
      <td><b>1회 검증 후 3종 서식 재사용</b></td>
      <td>근로자·회사 DB와 OCR 정보를 계약·취업활동·체류 서식에 반영</td>
    </tr>
    <tr>
      <td><b>근로자 후속 확인</b></td>
      <td>메신저 수동 추적</td>
      <td><b>4단계 상태 추적</b></td>
      <td>요청 발송·근로자 확인·서류 제출·HR 검토 이력 연결</td>
    </tr>
  </tbody>
</table>

<sub>※ 주 1~2시간은 숙련 제조업 HR 담당자 인터뷰 기준이며, 목표값은 실사용 기업 파일럿에서 검증 예정입니다.</sub>

