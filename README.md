# Data Dashboard Project (English)

## Overview
This project creates a web-based data visualization dashboard using Python and FastAPI.

## Features
1. Data collection using web scraping or public datasets.
2. Data analysis and visualization using Pandas and Matplotlib.
3. Real-time data updates on the dashboard.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/LeeKyungOk/data-dashboard.git
   cd data-dashboard
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run the Code
1. Start the backend server:
   ```bash
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```
2. Open the `frontend/index.html` file in your browser.

## Folder Structure
```
data-dashboard/
├── data/                # Data files (e.g., public datasets or scraped data)
├── src/                 # Backend API code (FastAPI)
├── frontend/            # Frontend code (HTML/CSS/JavaScript)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Future Improvements
1. Add user authentication for personalized dashboards.
2. Integrate real-time data updates using WebSocket or APIs.
3. Expand visualization options with interactive libraries like Plotly or Dash.

## Contact
For more information, please contact me at [ @gmail.com]


---


# 데이터 대시보드 프로젝트 (한국어)

## 개요
이 프로젝트는 Python과 FastAPI를 사용하여 웹 기반 데이터 시각화 대시보드를 생성합니다.

## 주요 기능
1. 웹 크롤링 또는 공공데이터를 사용한 데이터 수집.
2. Pandas와 Matplotlib을 활용한 데이터 분석 및 시각화.
3. 대시보드에서 실시간 데이터 업데이트 지원.

## 설치 방법
1. 저장소 클론:
   ```
   git clone https://github.com/LeeKyungOk/data-dashboard.git
   cd data-dashboard
   ```
2. 의존성 설치:
   ```
   pip install -r requirements.txt
   ```

## 코드 실행 방법
1. 백엔드 서버 실행:
   ```
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```
2. 브라우저에서 `frontend/index.html` 파일 열기.

## 폴더 구조
```
data-dashboard/
├── data/                # 데이터 파일 (예: 공공데이터 또는 크롤링 데이터)
├── src/                 # 백엔드 API 코드 (FastAPI)
├── frontend/            # 프론트엔드 코드 (HTML/CSS/JavaScript)
├── requirements.txt     # Python 의존성 목록
└── README.md            # 프로젝트 설명 파일
```

## 향후 개선 사항
1. 사용자 인증 기능 추가로 개인화된 대시보드 제공.
2. WebSocket 또는 API를 사용하여 실시간 데이터 업데이트 통합.
3. Plotly 또는 Dash와 같은 인터랙티브 라이브러리를 활용한 시각화 옵션 확장.

## 문의하기
추가 정보가 필요하다면 @gmail.com 으로 연락주세요.
