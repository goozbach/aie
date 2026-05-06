# Frontend

## Running the Application

### Prerequisites
- Backend must be running at `http://localhost:8000`

### Option 1: Python HTTP Server
```bash
cd frontend
python -m http.server 3000
```
Then open http://localhost:3000

### Option 2: VS Code Live Server
Open `index.html` in VS Code and use the Live Server extension.

### Option 3: Any Static Server
```bash
npx serve frontend
# or
npm install -g serve
serve frontend
```

## API Integration
The frontend calls `POST /api/chat` with `{"message": "your message"}` and expects `{"reply": "response"}`.