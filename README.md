# EngagIn — Employee Engagement Platform

A modern employee recognition & engagement platform. 100% frontend, no backend required.

---

## 🚀 Quick Start (Run Locally)

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev
```

Then open **http://localhost:3000** in your browser.

---

## 🌐 Deploy to Vercel (Free — Recommended)

### Option A: Deploy via GitHub (Easiest)

1. **Create a GitHub account** at https://github.com (free)

2. **Create a new repository**:
   - Go to https://github.com/new
   - Name it `engagin`
   - Click "Create repository"

3. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop ALL files from this folder
   - Click "Commit changes"

4. **Deploy on Vercel**:
   - Go to https://vercel.com and sign up (free, use your GitHub account)
   - Click "Add New Project"
   - Click "Import" next to your `engagin` repository
   - Leave all settings as-is
   - Click **"Deploy"** ✅

5. **Your app is live!** Vercel gives you a URL like:
   `https://engagin-yourname.vercel.app`

---

### Option B: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel

# Follow the prompts — it's free and takes ~30 seconds
```

---

## 📁 Project Structure

```
engagin/
├── public/
│   ├── index.html      ← Landing page (users see this first)
│   └── app.html        ← The full EngagIn app
├── package.json        ← Scripts and dev dependencies
├── vercel.json         ← Vercel deployment config
└── README.md           ← This file
```

---

## 🔑 Demo Login Credentials

| Role     | Email                           | How to login                    |
|----------|---------------------------------|---------------------------------|
| Admin    | juhi.k@decisionfoundry.com      | Click "Admin" quick-login button |
| Employee | ryan@decisionfoundry.com        | Click "Employee" quick-login button |

Or type any `@decisionfoundry.com` email on the login screen.

---

## 💾 How Data is Stored

This app uses **browser localStorage** — all data lives in the user's browser. 
- No database needed
- No backend needed  
- No server costs
- Perfect for demos

---

## ✅ No Environment Variables Needed

This is a pure static site. There are no API keys, secrets, or environment variables required.

---

## 🆓 Why It's Free Forever

| Service | Free Tier Limits |
|---------|-----------------|
| Vercel  | 100GB bandwidth/month, unlimited deployments |
| GitHub  | Unlimited public repos |

Both are more than enough for a demo or small company deployment.
