# Playio 1:1 Feedback

플레이오 리더를 위한 1on1 피드백 관리 도구입니다.

## 주요 기능

- **가이드 탭** — SBI 피드백 구조, 1on1 진행 흐름, GNA 핵심가치(솔직/오너십/용기) 10가지 행동양식
- **1on1 탭** — 팀원별 1:1 피드백 기록, IOC 통계, 액션 아이템 추적
- **대시보드** — 전체 기록 현황, 핵심가치 분포, 팀원별 현황, 1on1 리마인드 알림
- **설정** — 팀원 추가/삭제, Google Sheets 연동

## 배포 방법 (GitHub Pages)

1. 이 저장소를 Fork 또는 Clone
2. GitHub 저장소 → **Settings** → **Pages**
3. Source를 **Deploy from a branch** 선택
4. Branch: `main`, 폴더: `/ (root)` 선택 → **Save**
5. 1~2분 후 `https://[사용자명].github.io/[저장소명]/` 에서 접속

## 데이터 관리

- 앱 내 데이터는 각 사용자의 **브라우저 localStorage**에 저장됩니다
- 팀장별로 완전히 분리되어 다른 사람의 데이터를 볼 수 없습니다
- Google Sheets 연동 시 **팀장별 별도 시트**를 사용합니다

## Google Sheets 연동

`Playio_Feedback_GoogleSheets_가이드.md` 파일을 참고하세요.

## 기술 스택

- React 18 (CDN)
- Vanilla CSS (Playio BI 가이드 기반)
- Pretendard 폰트
- Google Apps Script (선택적 연동)
