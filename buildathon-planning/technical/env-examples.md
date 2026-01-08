# Environment Variable Examples

**Purpose:** Clear templates for .env files with Firebase and Supabase

**When to share:** Pre-event email, cheat sheet, helper desk

---

## Firebase .env Template (Next.js)

**Filename:** `.env.local` (for Next.js)

**Template:**
```bash
# Firebase Configuration
# Get these from: https://console.firebase.google.com
# Navigate to: Project Settings > General > Your apps > SDK setup and configuration

# Your web app's Firebase configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key_here
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

# Optional: Firebase Measurement ID (for Analytics)
# NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your_measurement_id
```

### Where to Get These Values

1. **Go to:** https://console.firebase.google.com
2. **Select your project** (or create new one)
3. **Click gear icon** → Project Settings
4. **Scroll to "Your apps"** section
5. **Click "Web app" icon** (</>) or select existing web app
6. **Select "Config"** radio button
7. **Copy the values** from the `firebaseConfig` object

### Example (with fake values):
```bash
NEXT_PUBLIC_FIREBASE_API_KEY=AIzaSyAbCdEfGhIjKlMnOpQrStUvWxYz1234567
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=my-buildathon-project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=my-buildathon-project
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=my-buildathon-project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=123456789012
NEXT_PUBLIC_FIREBASE_APP_ID=1:123456789012:web:abcdef1234567890
```

### Important Notes:

- **File name:** Must be `.env.local` for Next.js (not `.env`)
- **Prefix:** All variables must start with `NEXT_PUBLIC_` to be accessible in browser
- **Git:** Add `.env.local` to `.gitignore` (Next.js does this by default)
- **No quotes:** Don't wrap values in quotes
- **No spaces:** No spaces around `=` sign

---

## Supabase .env Template (Vite / React)

**Filename:** `.env` (for Vite)

**Template:**
```bash
# Supabase Configuration
# Get these from: https://app.supabase.com
# Navigate to: Project Settings > API

# Project URL - found in "Project URL" section
VITE_SUPABASE_URL=https://your_project_id.supabase.co

# Anon/Public Key - found in "Project API keys" section
# This is safe to use in the browser
VITE_SUPABASE_ANON_KEY=your_anon_key_here

# Note: Keep your service_role key SECRET - never use it in the browser
# Only use anon/public key in frontend code
```

### Where to Get These Values

1. **Go to:** https://app.supabase.com
2. **Select your project** (or create new one)
3. **Click Settings** (gear icon in sidebar)
4. **Click "API"** in settings menu
5. **Copy "Project URL"** → This is your `VITE_SUPABASE_URL`
6. **Copy "anon public"** key → This is your `VITE_SUPABASE_ANON_KEY`

### Example (with fake values):
```bash
VITE_SUPABASE_URL=https://abcdefghijklmnop.supabase.co
VITE_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImFiY2RlZmdoaWprbG1ub3AiLCJyb2xlIjoiYW5vbiIsImlhdCI6MTYxNjM5MjAwMCwiZXhwIjoxOTMxOTY4MDAwfQ.fake_signature_here
```

### Important Notes:

- **File name:** Must be `.env` for Vite (not `.env.local`)
- **Prefix:** All variables must start with `VITE_` to be accessible in browser
- **Git:** Add `.env` to `.gitignore` (Vite templates usually do this)
- **Anon key:** Safe to use in browser (has Row Level Security)
- **Service role key:** NEVER use in browser code (keep secret)
- **No quotes:** Don't wrap values in quotes

---

## Python / FastAPI .env Template

**Filename:** `.env`

**Template:**
```bash
# Supabase Configuration for Backend
# Get these from: https://app.supabase.com > Project Settings > API

# Project URL
SUPABASE_URL=https://your_project_id.supabase.co

# Service Role Key (SECRET - for backend only)
# Found in Project Settings > API > service_role key
SUPABASE_SERVICE_KEY=your_service_role_key_here

# Optional: Anon Key (for public access patterns)
# SUPABASE_ANON_KEY=your_anon_key_here
```

### Loading in Python:

```python
# main.py
import os
from dotenv import load_dotenv
from supabase import create_client, Client

load_dotenv()  # Load .env file

supabase_url = os.getenv("SUPABASE_URL")
supabase_key = os.getenv("SUPABASE_SERVICE_KEY")

supabase: Client = create_client(supabase_url, supabase_key)
```

### Important Notes:

- **File name:** `.env` in project root
- **No prefix:** Variables don't need prefixes for backend
- **Git:** Add `.env` to `.gitignore` IMMEDIATELY
- **Service key:** This is SECRET - never commit or expose
- **Install dotenv:** `pip install python-dotenv`

---

## .gitignore Templates

### For Next.js (Firebase)
```gitignore
# Environment variables
.env.local
.env*.local

# Next.js
.next/
out/
build/

# Dependencies
node_modules/

# Misc
.DS_Store
*.log
```

### For Vite (Supabase)
```gitignore
# Environment variables
.env
.env.local

# Vite
dist/
dist-ssr/

# Dependencies
node_modules/

# Misc
.DS_Store
*.log
```

### For Python (FastAPI)
```gitignore
# Environment variables
.env
.env.local

# Python
__pycache__/
*.py[cod]
*$py.class
venv/
.venv/

# Misc
.DS_Store
*.log
```

---

## Common Issues & Solutions

### Issue 1: "Firebase not initialized" or "Supabase client error"

**Cause:** .env file not loaded or wrong variable names

**Solution:**
- Check file name: `.env.local` (Next.js) vs `.env` (Vite)
- Check variable prefixes: `NEXT_PUBLIC_` vs `VITE_`
- Restart dev server after creating .env file
- Verify .env is in project root, not subfolder

---

### Issue 2: "process.env.NEXT_PUBLIC_FIREBASE_API_KEY is undefined"

**Cause:** Missing `NEXT_PUBLIC_` prefix or wrong .env file name

**Solution:**
- All Next.js env vars must start with `NEXT_PUBLIC_`
- File must be named `.env.local` not `.env`
- Restart `npm run dev` after adding .env.local

---

### Issue 3: "import.meta.env.VITE_SUPABASE_URL is undefined"

**Cause:** Missing `VITE_` prefix or wrong .env file name

**Solution:**
- All Vite env vars must start with `VITE_`
- File must be named `.env` in project root
- Restart `npm run dev` after adding .env

---

### Issue 4: Git shows .env file (security risk!)

**Cause:** .env not in .gitignore

**Solution:**
```bash
# Add to .gitignore
echo ".env.local" >> .gitignore  # For Next.js
echo ".env" >> .gitignore        # For Vite/Python

# If already committed, remove from Git
git rm --cached .env.local
git rm --cached .env
git commit -m "Remove .env from Git"
```

---

## Quick Setup Checklist

**For Firebase (Next.js):**
- [ ] Create `.env.local` in project root
- [ ] Copy template from above
- [ ] Get values from Firebase console
- [ ] Paste values (no quotes)
- [ ] Verify `.env.local` is in `.gitignore`
- [ ] Restart `npm run dev`

**For Supabase (Vite):**
- [ ] Create `.env` in project root
- [ ] Copy template from above
- [ ] Get values from Supabase dashboard
- [ ] Paste values (no quotes)
- [ ] Verify `.env` is in `.gitignore`
- [ ] Restart `npm run dev`

**For Python (FastAPI):**
- [ ] Create `.env` in project root
- [ ] Copy template from above
- [ ] Install `python-dotenv`: `pip install python-dotenv`
- [ ] Load in code: `load_dotenv()`
- [ ] Verify `.env` is in `.gitignore`
- [ ] Restart server

---

## Distributing These Templates

### Pre-Event Email:
Attach as text file or link to this document

### Day-of Event:
- Post on helper desk
- Include in cheat sheet
- Share in chat/Discord
- Have printed copies

### Helper Desk:
Keep these templates ready to copy-paste for people with setup issues

---

## Security Reminders

**NEVER commit .env files to Git**

**Public (safe to expose):**
- Firebase: All `NEXT_PUBLIC_*` variables
- Supabase: `VITE_SUPABASE_ANON_KEY` only

**Secret (must stay private):**
- Firebase: Admin SDK credentials (if used)
- Supabase: `service_role` key
- Any API keys with write access

**For buildathon prototypes:**
- Anon keys with RLS (Row Level Security) are fine
- Service role keys should only be used in backend code, never exposed

---

**These templates save 15-30 minutes of setup time per person. Worth having ready.**
