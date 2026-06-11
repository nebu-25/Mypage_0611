# AI Hub

AI 서비스를 한곳에서 탐색하고 바로 이동할 수 있는 링크 모음 페이지입니다.

**공개 URL:** https://nebu-25.github.io/Mypage_0611/

## 화면 구성

| 영역 | 설명 |
|---|---|
| **상단 메뉴** | 대 카테고리 탭 (전체 / AI 어시스턴트 / AI 창작 도구 / AI 개발 도구 / 플랫폼 & 리소스 / 학습) |
| **사이드 메뉴** | 카테고리 필터 + 서비스 개수 표시 |
| **카드 그리드/리스트** | 서비스 아이콘 · 이름 · 설명 · 요금 뱃지 · 태그 · 방문 버튼 · 크로스 카테고리 뱃지 |
| **검색창** | 상단 우측 — 사이트명 · 설명 · 도메인 실시간 검색 |
| **컨트롤 바** | 밀도 · 보기 방식 · 정렬 버튼 |
| **테마 버튼** | 상단 우측 ☀️/🌙 — 다크/라이트 모드 전환 |

## 주요 기능

### 탐색
- **카테고리 필터** — 상단 탭으로 대 카테고리 전환
- **소 카테고리 필터** — 사이드바에서 세부 분류 선택

### 검색 & 정렬
- **실시간 검색** — 사이트명 · 설명 · 도메인 기준 즉시 필터링 + 키워드 하이라이팅
- **정렬** — 기본순 / 이름 오름차순 / 이름 내림차순
- **키보드 단축키** — `/` 검색창 포커스, `Esc` 검색 초기화

### UI / 디자인
- **다크/라이트 모드** — 시스템 설정 자동 감지, 수동 전환 가능 (localStorage 저장)
- **그리드/리스트 뷰** — `⊞` 그리드 또는 `≡` 리스트 뷰 전환
- **카드 밀도 조절** — 좁게 / 기본 / 넓게 (localStorage 저장)
- **스켈레톤 로딩** — 카테고리 전환 시 shimmer 애니메이션
- **모바일 반응형** — 768px 이하에서 햄버거 메뉴 + 사이드바 오버레이

### 서비스 정보
- **요금 뱃지** — Free · Freemium · Paid 색상 구분 뱃지 (카드에 표시)
- **카드 상세 모달** — 카드 클릭 시 모달 팝업: 주요 기능(4개) · 요금제 상세 · 한국어/API/모바일 앱 지원 여부 표시
- **크로스 카테고리 뱃지** — 여러 카테고리에 등재된 서비스는 카드 하단에 `🔗 다른 카테고리` 뱃지 표시, 클릭 시 해당 카테고리로 바로 이동. 모달에서도 "다른 카테고리에서도 볼 수 있어요" 섹션으로 탐색 가능
- **JSON 데이터 분리** — 서비스 데이터를 `data.json`으로 분리해 HTML과 별도 관리

## 포함 서비스 (49개 고유 서비스 · 55개 항목, `*`는 다른 카테고리에도 등재)

### AI 어시스턴트
| 서비스 | URL | 소개 |
|---|---|---|
| Claude | https://claude.ai | Anthropic의 AI 어시스턴트 |
| ChatGPT | https://chatgpt.com | OpenAI의 AI 챗봇 |
| Gemini | https://gemini.google.com | Google의 멀티모달 AI |
| Grok | https://grok.com | xAI의 실시간 AI 챗봇 |
| Mistral | https://chat.mistral.ai | 오픈소스 기반 LLM |
| Copilot | https://copilot.microsoft.com | Microsoft AI 어시스턴트 |
| Genspark | https://www.genspark.ai | AI 에이전트 검색 플랫폼 |
| Perplexity | https://perplexity.ai | 실시간 웹 검색 AI |

### AI 창작 도구
| 서비스 | URL | 소개 |
|---|---|---|
| Whisk | https://whisk.google.com | Google의 이미지 생성 AI |
| Midjourney | https://midjourney.com | AI 아트 이미지 생성 |
| Stability AI | https://stability.ai | Stable Diffusion 플랫폼 |
| Adobe Firefly | https://firefly.adobe.com | Adobe 생성형 AI |
| Leonardo AI | https://leonardo.ai | 게임·디자인용 이미지 AI |
| SUNO | https://suno.com | AI 음악 생성 |
| Runway ML | https://runwayml.com | AI 비디오 생성·편집 |
| Kling AI | https://klingai.com | AI 비디오 생성 |

### AI 개발 도구
| 서비스 | URL | 소개 |
|---|---|---|
| Lovable | https://lovable.dev | AI 풀스택 앱 빌더 |
| V0 | https://v0.dev | Vercel AI UI 생성기 |
| Bolt.new | https://bolt.new | 브라우저 AI 웹앱 빌더 |
| Replit | https://replit.com | AI 코딩 & 배포 플랫폼 |
| Cursor | https://cursor.sh | AI 코드 에디터 |
| GitHub Copilot | https://github.com/features/copilot | AI 코드 자동완성 |

### 플랫폼 & 리소스
| 서비스 | URL | 소개 |
|---|---|---|
| Hugging Face | https://huggingface.co | AI 모델 & 데이터셋 허브 |
| Replicate | https://replicate.com | AI 모델 API 실행 플랫폼 |
| Together AI | https://together.ai | 오픈소스 LLM API |
| GitHub | https://github.com | 오픈소스 코드 저장소 |
| OpenAI * | https://openai.com | GPT 개발사 |
| Kaggle | https://kaggle.com | AI/ML 데이터셋 & 대회 |
| Papers With Code | https://paperswithcode.com | AI 논문 & 코드 DB |

### 학습
| 서비스 | URL | 소개 |
|---|---|---|
| Claude * | https://claude.ai | Anthropic의 AI 어시스턴트 |
| ChatGPT * | https://chatgpt.com | OpenAI의 AI 챗봇 |
| GitHub * | https://github.com | 오픈소스 코드 저장소 |
| GitHub Desktop | https://desktop.github.com | Git GUI 데스크톱 클라이언트 |
| Streamlit | https://streamlit.io | Python AI/데이터 앱 프레임워크 |
| V0 * | https://v0.dev | Vercel AI UI 생성기 |
| Lovable * | https://lovable.dev | AI 풀스택 앱 빌더 |
| Vercel | https://vercel.com | 프론트엔드 배포·호스팅 플랫폼 |
| Netlify | https://netlify.com | 정적 사이트 배포 플랫폼 |
| Antigravity | https://antigravity.dev | AI 인터랙티브 코딩 학습 |
| OpenRouter | https://openrouter.ai | 100+ LLM 단일 API 허브 |
| NotebookLM | https://notebooklm.google.com | Google AI 연구·노트 도우미 |
| Anthropic | https://anthropic.com | Claude 개발사 & AI 안전 연구 |
| OpenAI * | https://openai.com | GPT 시리즈 개발사 |
| Google DeepMind | https://deepmind.google | Google AI 연구 조직 |
| Meta AI | https://ai.meta.com | Llama 오픈소스 모델 허브 |
| Mistral AI | https://mistral.ai | 유럽 대표 오픈소스 LLM |
| Product Hunt | https://producthunt.com | 신규 테크·AI 프로덕트 커뮤니티 |
| Hacker News | https://news.ycombinator.com | YC 기술·스타트업 뉴스 포럼 |
| TechCrunch | https://techcrunch.com | 테크 산업 뉴스 미디어 |
| The Verge | https://theverge.com | 소비자 기술 트렌드 미디어 |
| MIT Technology Review | https://technologyreview.com | MIT 심층 기술 분석 매거진 |
| Ars Technica | https://arstechnica.com | 심층 기술·과학 뉴스 |
| VentureBeat | https://venturebeat.com | AI & 테크 비즈니스 뉴스 |
| 요즘IT | https://yozm.wishket.com | 한국어 IT 트렌드 미디어 |
| GeekNews | https://news.hada.io | 한국어 기술 뉴스 큐레이션 |

## 기술 스택

- HTML5 / CSS3 / Vanilla JavaScript (외부 의존성 없음)
- `data.json` — 서비스 데이터 분리 관리 (fetch API로 로드)
- GitHub Pages 배포

## 이슈 관리

### 해결된 이슈

| 날짜 | 이슈 | 해결 방법 |
|---|---|---|
| 2026-06-11 | `.claude/settings.local.json` (Claude Code 설정 파일)이 실수로 커밋·푸시됨 | `git rm --cached`로 추적 해제 후 `.gitignore`에 `.claude/` 추가 |
| 2026-06-11 | 5개 프로젝트 전체에 `.gitignore` 미설정으로 내부 도구 파일 노출 위험 | 전체 프로젝트에 `.gitignore` 생성/업데이트 완료 |
| 2026-06-11 | 사이드바 레이블 "소 카테고리" → 의미 불명확 | "카테고리"로 텍스트 수정 |
| 2026-06-11 | **GitHub Pages 미배포** | GitHub Pages 배포 완료 — https://nebu-25.github.io/Mypage_0611/ |
| 2026-06-11 | **서비스 데이터 하드코딩** | `data.json`으로 분리, `fetch()` 비동기 로드로 전환 |
| 2026-06-11 | **요금 정보 미표시** | Free / Freemium / Paid 뱃지 카드에 추가 완료 |
| 2026-06-11 | **서비스 상세 정보 접근 불가** | 카드 클릭 시 상세 모달 팝업 구현 (기능·요금·지원 정보) |
| 2026-06-11 | **학습 카테고리 README 누락** | 학습 카테고리(AI 프로덕트·AI & LM·AI 리서치·IT 트렌드) 및 26개 항목 README 반영 |
| 2026-06-11 | **중복 서비스 UX 미처리** | `alsoIn` 필드 추가 — 카드 하단 크로스 카테고리 뱃지 및 모달 내 카테고리 이동 링크 구현 |

### 알려진 이슈 (미해결)

| 우선순위 | 이슈 | 설명 |
|---|---|---|
| 높음 | **파비콘 외부 API 의존** | Google Favicon API(`s2/favicons`)를 사용해 오프라인 또는 API 차단 시 아이콘 미표시 |
| 중간 | **모바일 상단 탭 미노출** | 768px 이하에서 대 카테고리 탭이 숨겨져 햄버거 메뉴로만 접근 가능 |
| 낮음 | **fetch 로컬 실행 불가** | `file://` 프로토콜로 직접 열면 CORS 오류로 `data.json` 로드 불가 (GitHub Pages·웹 서버에서는 정상) |

## 개선 예정

- [ ] 즐겨찾기 기능 (localStorage)
- [ ] 모바일 하단 탭바 (대 카테고리 접근성 개선)
- [ ] 파비콘 로컬 캐싱 (외부 API 의존 제거)
- [ ] PWA 지원
