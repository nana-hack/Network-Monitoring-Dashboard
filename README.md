# Network Monitoring Dashboard

A real-time network monitoring solution built with Python (FastAPI) backend and React frontend.

## Author

**NANA KWAME AMPORFUL**

## Features

- Real-time network statistics monitoring
- CPU and Memory usage tracking
- Network traffic analysis
- Interactive charts and graphs
- Modern, responsive UI

## Prerequisites

- Python 3.8+
- Node.js 14+
- npm or yarn

## Project Structure

```
network-monitoring-dashboard/
├── backend/               # Python FastAPI backend
│   ├── app/
│   │   ├── main.py
│   │   ├── monitor.py
│   │   └── schemas.py
│   └── requirements.txt
└── frontend/             # React frontend
    ├── public/
    ├── src/
    ├── package.json
    └── README.md
```

## Setup Instructions

### Backend Setup

1. Create a virtual environment:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the backend server:
   ```bash
   uvicorn app.main:app --reload
   ```

### Frontend Setup

1. Install dependencies:
   ```bash
   cd frontend
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

## License

MIT
