# Premium YouTube Trend Board (Serverless $0 Edition)

Premium Serverless YouTube Trend Dashboard in Sleek Dark Theme (Glassmorphism).

유튜브 Data API v3를 활용하여 실시간 급상승 인기 비디오 및 키워드별 트렌드 영상을 한눈에 스캔하는 프리미엄 웹 대시보드입니다.

---

## Key Features (핵심 기능)

- Sleek Dark Theme & Glassmorphism: 네온 아쿠아 블루와 오렌지 그라디언트 기반의 프리미엄 3D 벤토 카드 디자인.
- 100% Serverless ($0 Cost): 별도의 서버 인프라 없이 브라우저 단에서 유튜브 API와 직접 통신하여 운영비 영구히 0원.
- LocalStorage Security: 사용자가 입력한 API 키는 웹 서버로 전송되지 않고 브라우저 로컬 저장소에만 안전하게 암호화 보관.
- Real-time Shorts Filter: ISO 8601 재생 시간 메타데이터를 실시간 연산하여 60초 미만의 진짜 세로형 숏츠만 격리 필터링.
- Dynamic Sorting: 새로고침 없이 최신순(시간별 날짜별) 및 조회수순으로 실시간 정렬 지원.
- Fallback Search Mode: 한국(KR) 지역 카테고리 데이터 누락 오류 발생 시 검색 API로 자동 전환되는 지능형 우회 로직 탑재.

---

## Live Demo (실시간 라이브 데모)

👉 [https://2gosooclass.github.io/friendly-it-trend-board/](https://2gosooclass.github.io/friendly-it-trend-board/)

---

## How to Use (사용 방법)

1. 구글 클라우드 콘솔에서 무료 YouTube Data API v3 키를 발급받습니다.
2. 라이브 데모 웹페이지 상단의 입력창에 발급받은 API 키를 입력하고 [저장] 버튼을 누릅니다.
3. API 키는 로컬스토리지에만 저장되어 안전하게 작동하며, 즉시 실시간 트렌드 비디오 카드가 로드됩니다.

---

## Repository Structure

```text
├── index.html       # Single Page Application Source Code
└── README.md        # Documentation
```
