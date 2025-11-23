# Expense Tracker with Calendar

간단하고 직관적인 **달력 기반 가계부 웹 애플리케이션**입니다.  
사용자는 날짜를 클릭하여 **수입/지출을 기록**하고,  
**월간 소비 흐름 및 카테고리별 지출 패턴**을 파악할 수 있습니다.

이 프로젝트는 HTML, CSS, JavaScript로 구현되며,  
브라우저의 `localStorage`를 활용하여 **서버 없이도 데이터가 저장**됩니다.

---

## 주요 기능 (Features)

### 1. 월간 달력 UI
- 현재 월 달력을 7열 그리드로 표시  
- 날짜 클릭 시 해당 날짜의 상세 가계부 팝업 표시  
- 날짜 칸에 **수입/지출 요약 표시**

### 2. 날짜별 가계부 팝업
- 수입/지출 선택  
- 카테고리, 내용, 금액 입력  
- 항목 추가/삭제  
- 해당 날짜의 **총 수입 / 총 지출 / 순수입 자동 계산**

### 3. 월간 통계 페이지
- 총 수입/지출/순수입 요약  
- 카테고리별 지출 표  
- Chart.js 파이 차트

### 4. 소개 페이지
- 앱 목적 및 사용 방법 안내  
- 기술 스택 설명  

---

## 페이지 구성

| 파일명 | 설명 |
|--------|------|
| `index.html` | 메인 페이지 (달력 + 날짜팝업) |
| `stats.html` | 통계 페이지 |
| `about.html` | 앱 설명 |
| `daily.html`, `weekly.html` | 플레이스홀더 페이지 |

---

## 기술 스택

- HTML5  
- CSS3  
- Vanilla JavaScript  
- Web Storage API (`localStorage`)  
- Chart.js  
- GitHub  
- Vercel  

---

## localStorage 데이터 저장 방식

모든 데이터는 사용자의 브라우저 `localStorage`에 저장됩니다.

- 같은 브라우저에서는 데이터 유지  
- 다른 브라우저/기기에서는 데이터 공유되지 않음  
- 캐시 삭제/시크릿 모드/접근환경 변경 시 데이터 삭제 가능  

⚠ 중요한 금융 데이터 저장용으로 적합하지 않습니다.

---

## 설치 방법

```bash
git clone https://github.com/your-username/Expense-Tracker.git
cd Expense-Tracker

