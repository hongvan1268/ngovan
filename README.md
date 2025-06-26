# 🕵️‍♀️ JobPlanet 기업정보 크롤러

국내 취업 정보 플랫폼인 [JobPlanet](https://www.jobplanet.co.kr)에서 특정 기업의 평점, 리뷰 수, 세부 통계 정보를 자동 수집하는 크롤링 프로젝트입니다.

---

## 📌 주요 기능

- ✅ 기업명 기반 자동 검색 및 기업 ID 추출
- ✅ 검색 결과에서 평점, 리뷰 수, 세부 항목(복지, 워라밸 등) 수집
- ✅ Selenium을 사용한 동적 크롤링 및 예외 처리
- ✅ 수집 데이터를 CSV로 저장하며 중단 지점부터 복구 가능

---

## 🔧 사용 기술 스택

| 기술 | 설명 |
|------|------|
| Python 3.x | 전체 크롤링 코드 구현 |
| Selenium | 웹 브라우저 자동화 (동적 요소 대응) |
| BeautifulSoup | HTML 파싱 및 데이터 추출 |
| Pandas | CSV 처리 및 데이터 저장 |
| tqdm | 진행률 표시 |
| re (정규표현식) | 기업 ID 및 리뷰 수 추출 |

---

## 🚀 실행 방법

1. **의존 라이브러리 설치**
   ```bash
   pip install selenium beautifulsoup4 pandas tqdm
