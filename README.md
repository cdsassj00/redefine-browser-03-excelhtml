# Redefine Browser 03: ExcelHTML

브라우저는 이미 파일을 읽고, 표를 그리고, 계산하고, 다시 파일로 내보낼 수 있습니다.  
이 저장소는 그 생각을 하나의 HTML 파일로 증명하는 **AI Excel / Web Spreadsheet** 실험입니다.

## 바로 실행

- 배포 URL: https://cdsassj00.github.io/redefine-browser-03-excelhtml/
- 로컬 실행: `index.html`을 브라우저로 열면 됩니다.

## 무엇을 할 수 있나

- 엑셀처럼 셀을 선택하고 값을 입력합니다.
- `SUM`, `AVERAGE`, `COUNT`, `MAX`, `MIN` 같은 기본 수식을 계산합니다.
- CSV, TSV, XLSX, XLS, JSON 파일을 불러옵니다.
- 값, 수식, 서식, 차트를 보존하는 저장 흐름을 제공합니다.
- 조건부 서식, 표 서식, 정렬, 필터, 틀 고정, 차트 삽입을 지원합니다.
- AI 패널에서 선택 영역 기반 분석과 수식 생성을 요청할 수 있습니다.

## 브라우저 재정의 시리즈에서의 위치

| 번호 | 저장소 | 질문 |
|---|---|---|
| 01 | `redefine-browser-01` | 브라우저가 영상 편집기가 될 수 있을까? |
| 02 | `redefine-browser-02` | 브라우저 확장이 금융 데이터 분석기가 될 수 있을까? |
| 03 | `redefine-browser-03-excelhtml` | 브라우저가 엑셀과 AI 분석 화면이 될 수 있을까? |

## 구조

```text
.
├── index.html   # 앱 전체가 들어 있는 단일 HTML
└── README.md
```

## 메모

AI 기능은 사용자가 직접 입력한 API 설정을 사용합니다. 저장소에는 API 키가 포함되어 있지 않습니다.
