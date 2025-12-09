# 🚀 Quick Start Guide - RakshaNetra

## ✅ Prerequisites (Already Installed)
- ✅ Python 3.14.0
- ✅ Node.js v24.11.1
- ✅ Backend Dependencies Installed
- ✅ Frontend Dependencies Installed
- ✅ Google Gemini API Key Configured

---

## 🎯 How to Run (Super Simple!)

### Option 1: Double-Click Method (Easiest!)
1. **Double-click `RUN.bat`** - This starts everything!
2. Wait 10 seconds for services to start
3. Browser will auto-open to http://localhost:8080

### Option 2: Manual Method
**Terminal 1 (Backend):**
```powershell
cd backend
.\venv\Scripts\python server.py
```

**Terminal 2 (Frontend):**
```powershell
npm run dev
```

---

## 🛑 How to Stop
- **Double-click `STOP.bat`** - Kills all services
- Or press `Ctrl+C` in both terminals

---

## 🌐 Access Points
- **Frontend (User Interface):** http://localhost:8080
- **Backend API:** http://localhost:8000
- **API Documentation:** http://localhost:8000/docs
- **Interactive API:** http://localhost:8000/redoc

---

## 🎨 Features Ready to Use
1. **AI Threat Analysis** - Powered by Google Gemini 2.5 Flash
2. **URL Scanner** - Detect phishing and malicious sites
3. **SMS/Email Analysis** - Check suspicious messages
4. **Live Threat Map** - Geographical visualization
5. **Dark/Light Mode** - Toggle theme
6. **Hindi/English** - Language switcher

---

## 🐛 Troubleshooting

### Backend won't start?
```powershell
cd backend
.\venv\Scripts\python -m pip install -r requirements.txt
```

### Frontend won't start?
```powershell
npm install --legacy-peer-deps
```

### Port already in use?
- Run `STOP.bat` first
- Or manually kill processes:
```powershell
# Kill port 8000
netstat -ano | findstr :8000
taskkill /F /PID <PID_NUMBER>

# Kill port 8080
netstat -ano | findstr :8080
taskkill /F /PID <PID_NUMBER>
```

---

## 📁 Project Structure
```
RakshaNetra/
├── RUN.bat          ← START HERE!
├── STOP.bat         ← Stop services
├── backend/
│   ├── server.py    ← Main API server
│   ├── modules/     ← AI & security modules
│   └── venv/        ← Python environment
├── src/
│   ├── pages/       ← React pages
│   └── components/  ← UI components
└── package.json     ← Frontend config
```

---

## 🎓 First Time Setup (DONE ✅)
You don't need to do this again, but for reference:

1. ✅ Cloned repository
2. ✅ Created Python virtual environment
3. ✅ Installed backend dependencies
4. ✅ Installed frontend dependencies
5. ✅ Configured API keys in `.env`

---

## 🔑 API Keys Configuration
Location: `backend/.env`
```env
GOOGLE_API_KEY=***REMOVED***
```
✅ Already configured!

---

## 👨‍💻 Development Tips

### Hot Reload
- Backend: Auto-reloads on file changes
- Frontend: Auto-refreshes browser

### View Logs
- Backend logs appear in the backend terminal
- Frontend logs in browser console (F12)

### Test API Directly
Visit http://localhost:8000/docs for interactive testing

---

## 🏆 Team UrbanDons - SIH 2025

**You're all set! Just run `RUN.bat` and start hacking! 🚀**
