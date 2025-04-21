# 🎮 SCOREX - Gaming Leaderboard App

SCOREX is a dynamic gaming leaderboard web application that allows users to:

✅ Create and manage new games  
✅ Add and view player scores  
✅ Auto-calculate rankings for each game leaderboard  
✅ Use simple, clean forms to input data  

---

## 🚀 Tech Stack
- **Frontend**: HTML, CSS, Django Templates
- **Backend**: Django (Python)
- **Database**: SQLite (default)


---

## ⚙️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/Yallappagouda/Game-Leaderboard.git
   cd Game-Leaderboard


## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Yallappagouda/Game-Leaderboard.git
cd Game-Leaderboard

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
