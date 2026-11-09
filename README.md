# 역량 강화 N8N — 에이전틱 워크플로우를 활용한 전사적 비용 절감 솔루션 구축

n8n으로 데이터 처리·멀티 에이전트·예외 처리 흐름을 실습하고, 나만의 AI 에이전트를 기획·구축·발표하는 3회차(총 24시간) 과정의 수강생 안내 페이지입니다. 2026년 11월 12일·19일·26일(목) 09:00–18:00, 향군타워 9층 대강의실.

## 배포 방법 (GitHub Pages)

1. `ax-helloworldlabs` 조직에 새 저장소를 만듭니다. 예: `ax-n8n-agentic` → `https://ax-helloworldlabs.github.io/ax-n8n-agentic/`
2. 이 폴더 안의 파일을 모두 저장소 최상위에 올립니다. `.nojekyll`(숨김 파일)도 함께 올려 주세요.
3. 저장소 **Settings → Pages**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/(root)`로 저장합니다.
4. 1–2분 뒤 위 주소에서 페이지가 열리는지 확인합니다.

## 무엇을 어디서 고치나

| 고칠 내용 | 파일 · 위치 |
|---|---|
| 페이지 제목·검색/공유 설명 | `index.html` `<head>` |
| 과정명·소개 문구 | `index.html` `section.hero` |
| 날짜·시간·장소 요약 띠 | `index.html` `.event-strip` |
| 준비물 카드 | `index.html` `#preparation` |
| 일정 카드·장소·출입/주차 안내 | `index.html` `#place` (`.elevator-note`) |
| 주소 복사 버튼의 주소 | `script.js` 첫 줄 `const address` |
| 커리큘럼(회차별 모듈) | `index.html` `#curriculum` |
| 교육 결과물 3가지 | `index.html` `.outcome` |
| 사전 안내 PDF·SafariON·카카오·전화·FAQ | `index.html` `#resources` |
| 모바일 하단 고정 바 | `index.html` `.mobile-bar` |

CSS·JS를 고친 뒤에는 `index.html`의 `?v=` 끝 숫자를 1 올려 주세요.

## 확인할 정보

- **실습 계정 지원**: Claude 유료 계정 1개월 지원, 계정 정보 교육 당일 제공 (`index.html` `#support`)
- **강사명**: 시간표(강보람)에 있으나 표기하지 않았습니다.
- **공통 정보 재사용**: 준비물, 사전 안내 PDF, SafariON 로그인 정보, 카카오톡 채널, 전화번호, 향군타워 엘리베이터·주차 안내는 지난 과정 값을 그대로 썼습니다.
- **실습 자료**: 구글 드라이브 폴더 링크 카드(`#resources`). 폴더 공유 설정이 '링크가 있는 모든 사용자'인지 확인하세요.
