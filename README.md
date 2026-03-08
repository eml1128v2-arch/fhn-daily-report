# FHN Daily Macro Report — Render.com Deployment

## Setup Instructions

### 1. Create a GitHub account (if you don't have one)
Go to github.com and sign up for free.

### 2. Create a new GitHub repository
- Click "New repository"
- Name it: fhn-daily-report
- Set to Public
- Click "Create repository"

### 3. Upload these files to GitHub
Upload all files in this folder to your new repository.

### 4. Deploy to Render
- Go to render.com and sign up for free
- Click "New" → "Web Service"
- Connect your GitHub repository
- Settings:
  - Build Command: npm install
  - Start Command: node server.js
- Click "Create Web Service"

### 5. Add your API key
- In Render dashboard, go to your service
- Click "Environment" in the left sidebar
- Add: ANTHROPIC_API_KEY = your-key-here
- Click "Save Changes" — Render will auto-redeploy

### 6. Open your live URL and click Generate Report!
