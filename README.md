# Task Timer

A minimalist web application for tracking time spent on tasks with a clean, intuitive interface.

## Features

- Create and manage tasks
- Start/stop timer for each task
- View daily and task-specific statistics
- Clean, responsive interface
- Light/dark theme support

## Tech Stack

### Frontend
- React
- Context API
- Chart.js
- CSS Modules

### Backend
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js 14+
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ProjectAnalyst/task-timer.git
cd task-timer
```

2. Backend Setup:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Frontend Setup:
```bash
cd frontend
npm install
```

4. Start the development servers:

Backend:
```bash
cd backend
uvicorn main:app --reload
```

Frontend:
```bash
cd frontend
npm start
```

## Project Structure

```
task-timer/
├── backend/
│   ├── app/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   ├── tests/
│   └── main.py
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── contexts/
│   │   └── pages/
│   └── package.json
└── docs/
    ├── genesis_prompt.md
    └── whitepaper.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 