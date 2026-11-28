# 프로젝트 이력 관리 (jeiel85 Profile)

## 2026-11-28
- 메인 프로필 README를 '프로필 메인' 구성으로 재정리(상단 capsule-render `jeiel85` 배너는 그대로 유지).
  - 인사말·한 줄 소개(포트폴리오 `apps.json`의 tagline 기준)와 기존 신앙·가족·바이브코더 배지를 배너 아래에 묶음.
  - 포트폴리오 버튼 옆에 shields.io 동적 배지(총 Stars, Followers) 추가.
  - `About` 섹션 신설: 로컬 우선·가족 앱·신앙 도구·AI 에이전트·배포 습관.
  - `Featured Projects` 섹션 신설: Android(Play 출시/비공개 테스트 상태 표기) · Windows · Games & Engines 표. 수동 큐레이션이므로 대표작이 바뀌면 같이 갱신 필요.
  - 기술 스택을 실제 저장소 언어/도구 기준으로 교체(Nim·Elixir·C 제거, C#·.NET·Tauri·Three.js·Unity·Blender·Firebase·Cloudflare·Vercel 등 추가)하고 AI 에이전트 배지 행 추가.
  - streak · snake · 방문자 카운터는 `Activity` 섹션으로 묶어 유지. Actions 워크플로 변경 없음.

## 2026-09-01
- 메인 프로필 README에서 `github-profile-summary-cards`의 productive-time 카드(Commits UTC +9) 제거.
  - 위젯은 정상 로드되나 데이터가 매우 희소(월간 소량 커밋)하여 거의 빈 차트처럼 보이는 깨진 영역으로 판단됨.
  - 이번에는 대체 위젯을 넣지 않고 해당 섹션만 제거 (스네이크 → 방문자 카운터로 자연스럽게 연결).

## 2026-08-31
- `github-readme-activity-graph` 공개 인스턴스가 402로 완전히 중단되어, 깨진 Activity Graph 섹션 제거.
- 대체 위젯으로 `github-profile-summary-cards`의 productive-time 카드 추가 (다크: `tokyonight`, 라이트: `github_light`, `utcOffset=9`).
- 업그레이드 드래프트 템플릿(`jeiel85-github-profile-upgrade/profile/README.template.md`)에서도 죽은 activity-graph 참조 제거.

## 2026-04-28
- 초기 상태 확인: `github-profile-summary-cards`를 이용한 기본 통계 카드 적용 확인.
- 프로젝트 이력 관리 파일(`HISTORY.md`) 생성.
- `README.md` 대규모 업데이트:
  - `capsule-render`를 이용한 물결 효과 헤더 배너 추가.
  - `github-readme-activity-graph` (Activity Graph) 섹션 추가.
  - 기존 통계 카드들을 가독성 좋게 재배치 (가로 정렬 및 중앙 정렬).
  - 방문자 수 카운터(`hits`) 추가 및 렌더링 이슈로 인한 제거.
  - 한국 시간대에 맞춰 `utcOffset=9` 설정.
- `README.md` 헤더 디자인 변경:
  - `capsule-render`의 `soft` 타입 및 `fadeIn` 애니메이션 적용.
  - 활동 그래프 및 통계 섹션 레이아웃 미세 조정 (중앙 정렬 강화).
- `README.md` 헤더 렌더링 이슈 수정:
  - 이미지 태그 배치 방식 변경 (`<p align="center">` 사용).
  - URL 파라미터 최적화 (불필요한 파라미터 제거).
- `README.md` 헤더 디자인 최종 고도화:
  - 제목을 `jeiel85`, 설명을 `Happy Coding~`으로 변경.
  - 제공된 고성능 파라미터(height=300, fontSize=90 등) 적용.
  - 텍스트 우측 정렬 적용 (`fontAlign=80`, `descAlign=80`).
- 상세 통계 섹션 분리:
  - `프로필 개요 (Profile Overview)`와 `활동 분석 (Activity Analysis)`으로 섹션 세분화.
- 하단 참고 레포지토리(References) 링크 추가:
  - `capsule-render`, `activity-graph`, `summary-cards` 링크 우측 하단 배치.
- 원격 저장소 푸시 완료.
