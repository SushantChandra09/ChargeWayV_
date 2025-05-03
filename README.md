# ⚡ ChargeWayV AI Assistant Backend

This is the backend server for the ChargeWayV AI Assistant. It is built using Flask and provides endpoints for generating LiveKit tokens and handling AI assistant queries.

---

## 🚀 Features

- LiveKit token generation (`/getToken`)
- Health check endpoint (`/health`)
- AI Assistant endpoint (`/assistant`) for processing user queries

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/chargewayv-backend.git
cd chargewayv-backend
```

### 2. Set up the environment

Create a `.env` file in the root directory and add the following variables:

```
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret
LIVEKIT_WS_URL=your_livekit_ws_url
GEMINI_API_KEY=your_gemini_api_key (optional if using Gemini AI)
```

### 3. Install dependencies

Make sure you have Python 3.9+ installed. Then run:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` doesn't exist, install manually:

```bash
pip install flask flask-cors python-dotenv livekit
```

---

## ▶️ Running the Server

Start the Flask development server on port `5001`:

```bash
python app.py
```

Once running, you’ll see:

- `http://localhost:5001/health` – Health check
- `http://localhost:5001/getToken?name=YourName` – Get token
- `http://localhost:5001/assistant` – AI assistant (POST endpoint)

---

## 📎 Related Files

🔗 Google Drive Resource:  
[Click here to view/download](https://drive.google.com/file/d/1Se1_U6Jqb7NVvZZ630L_V1UumNUJx43Z/view?usp=sharing)

---

## 🛠️ Notes

- Make sure ports don’t conflict if you're using this alongside frontend or other backend servers.
- Enable CORS as needed for frontend interaction.

---

## 📧 Contact

For support, contact the ChargeWayV team.