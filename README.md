# Data Dashboard Project

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
