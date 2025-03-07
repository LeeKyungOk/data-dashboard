# data-dashboard
[ AI - portfolio ] 데이터 대시보드 프로젝트

# Data Dashboard Project

## Overview
This project is part of my AI portfolio and demonstrates my ability to create a web-based data visualization dashboard. The dashboard integrates data analysis, visualization, and web development skills.

## Features
1. **Data Collection**:
   - Web scraping using BeautifulSoup and Selenium.
   - Public datasets from sources like Seoul Open Data Portal.
2. **Data Analysis**:
   - Data preprocessing and analysis using Pandas and Numpy.
   - Visualization using Matplotlib and Seaborn.
3. **Web Development**:
   - Backend API development using FastAPI.
   - Frontend integration using HTML, CSS, and JavaScript.

## Installation
1. Clone the repository:
git clone https://github.com/LeeKyungOk/data-dashboard.git
cd data-dashboard

2. Install dependencies:
pip install -r requirements.txt

## How to Run the Project
1. Start the backend server:
uvicorn src.main:app --reload --host 0.0.0.0 --port 8000

text
2. Open the `frontend/index.html` file in your browser to view the dashboard.

## Folder Structure
📁 data-dashboard/
├── 📁 data/ # Data files (e.g., public datasets or scraped data)
├── 📁 src/ # Backend API code (FastAPI)
├── 📁 frontend/ # Frontend code (HTML/CSS/JavaScript)
├── requirements.txt # Python dependencies
└── README.md # Project documentation

text

## Future Improvements
1. Add user authentication for personalized dashboards.
2. Integrate real-time data updates using WebSocket or APIs.
3. Expand visualization options with interactive libraries like Plotly or Dash.

## Contact
For more information, please contact me at [sunnynhoya@google.com]
