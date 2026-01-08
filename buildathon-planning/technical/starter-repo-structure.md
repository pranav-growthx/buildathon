# Starter Repo Structure

**Purpose:** Pre-configured templates with .cursorrules for rapid setup

**When to create:** Week 1, Day 3-4 (Jan 8-9) - Optional

**Decision:** Build these OR skip and just use official CLI tools

---

## Should You Create Starter Repos?

### ✅ Create Them If:
- You have 2-3 hours in Week 1
- You're very familiar with Next.js + Firebase or React + Supabase
- You want to pre-configure .cursorrules
- You want to test the exact setup participants will use

### ❌ Skip Them If:
- You're short on prep time
- Participants are experienced with these stacks
- You're okay with people using official CLI tools directly
- You prefer simpler infrastructure

**Alternative:** Just tell people to use:
- `npx create-next-app@latest` for Firebase projects
- `npm create vite@latest -- --template react` for Supabase projects

Then share .cursorrules separately.

---

## If You Decide to Create Them

### Repo 1: Firebase Starter (Next.js)

**GitHub repo name:** `buildathon-firebase-starter`

#### Setup Steps:

1. **Create the project:**
```bash
npx create-next-app@latest buildathon-firebase-starter
# Select: TypeScript (optional), Tailwind CSS (yes), App Router (yes)
cd buildathon-firebase-starter
```

2. **Install Firebase:**
```bash
npm install firebase
```

3. **Add .cursorrules:**
- Copy from [cursorrules-template.md](cursorrules-template.md)
- Place in project root

4. **Add .env.example:**
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key_here
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

5. **Create `lib/firebase.js`:**
```javascript
// lib/firebase.js
import { initializeApp } from 'firebase/app';
import { getFirestore } from 'firebase/firestore';
import { getAuth } from 'firebase/auth';

const firebaseConfig = {
  apiKey: process.env.NEXT_PUBLIC_FIREBASE_API_KEY,
  authDomain: process.env.NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN,
  projectId: process.env.NEXT_PUBLIC_FIREBASE_PROJECT_ID,
  storageBucket: process.env.NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET,
  messagingSenderId: process.env.NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID,
  appId: process.env.NEXT_PUBLIC_FIREBASE_APP_ID
};

const app = initializeApp(firebaseConfig);
export const db = getFirestore(app);
export const auth = getAuth(app);
```

6. **Create README.md:**
```markdown
# Buildathon Firebase Starter

Quick setup for Jan 17th buildathon.

## Setup (30 minutes)

1. Clone this repo:
   ```
   git clone https://github.com/[your-username]/buildathon-firebase-starter.git
   cd buildathon-firebase-starter
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create Firebase project:
   - Go to firebase.google.com
   - Create new project
   - Enable Firestore Database
   - Enable Authentication (Email/Password)
   - Copy config from Project Settings

4. Create `.env.local` file:
   - Copy `.env.example` to `.env.local`
   - Paste your Firebase config values

5. Run dev server:
   ```
   npm run dev
   ```

6. Open http://localhost:3000

## What's Included

- Next.js with App Router
- Tailwind CSS
- Firebase SDK
- Pre-configured .cursorrules for AI coding
- Basic Firebase initialization

## Next Steps

Start building! The .cursorrules file will guide Cursor/Windsurf.

## Getting Help

- Debugger GPT: [QR code / link]
- Stack Advisor GPT: [QR code / link]
- Organizer: [your contact]
```

7. **Push to GitHub:**
```bash
git init
git add .
git commit -m "Initial commit: Buildathon Firebase starter"
git branch -M main
git remote add origin https://github.com/[your-username]/buildathon-firebase-starter.git
git push -u origin main
```

8. **Test end-to-end:**
- Clone in new folder
- Follow README
- Should work in <30 mins

---

### Repo 2: Supabase Starter (React + Vite)

**GitHub repo name:** `buildathon-supabase-starter`

#### Setup Steps:

1. **Create the project:**
```bash
npm create vite@latest buildathon-supabase-starter -- --template react
cd buildathon-supabase-starter
npm install
```

2. **Install Supabase:**
```bash
npm install @supabase/supabase-js
```

3. **Add Tailwind (optional but recommended):**
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Update `tailwind.config.js`:
```javascript
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Add to `src/index.css`:
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

4. **Add .cursorrules:**
- Copy from [cursorrules-template.md](cursorrules-template.md)
- Place in project root

5. **Add .env.example:**
```
VITE_SUPABASE_URL=https://your_project.supabase.co
VITE_SUPABASE_ANON_KEY=your_anon_key_here
```

6. **Create `src/lib/supabase.js`:**
```javascript
// src/lib/supabase.js
import { createClient } from '@supabase/supabase-js';

const supabaseUrl = import.meta.env.VITE_SUPABASE_URL;
const supabaseAnonKey = import.meta.env.VITE_SUPABASE_ANON_KEY;

export const supabase = createClient(supabaseUrl, supabaseAnonKey);
```

7. **Create README.md:**
```markdown
# Buildathon Supabase Starter

Quick setup for Jan 17th buildathon.

## Setup (30 minutes)

1. Clone this repo:
   ```
   git clone https://github.com/[your-username]/buildathon-supabase-starter.git
   cd buildathon-supabase-starter
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create Supabase project:
   - Go to supabase.com
   - Create new project
   - Wait for database to initialize
   - Go to Settings > API
   - Copy Project URL and anon/public key

4. Create `.env` file:
   - Copy `.env.example` to `.env`
   - Paste your Supabase URL and anon key

5. Run dev server:
   ```
   npm run dev
   ```

6. Open http://localhost:5173

## What's Included

- React with Vite
- Tailwind CSS
- Supabase client
- Pre-configured .cursorrules for AI coding
- Basic Supabase initialization

## Next Steps

Start building! The .cursorrules file will guide Cursor/Windsurf.

## Getting Help

- Debugger GPT: [QR code / link]
- Stack Advisor GPT: [QR code / link]
- Organizer: [your contact]
```

8. **Push to GitHub:**
```bash
git init
git add .
git commit -m "Initial commit: Buildathon Supabase starter"
git branch -M main
git remote add origin https://github.com/[your-username]/buildathon-supabase-starter.git
git push -u origin main
```

9. **Test end-to-end:**
- Clone in new folder
- Follow README
- Should work in <30 mins

---

## File Structure Reference

### Firebase Starter Structure
```
buildathon-firebase-starter/
├── .cursorrules
├── .env.example
├── .gitignore
├── README.md
├── package.json
├── next.config.js
├── tailwind.config.js
├── lib/
│   └── firebase.js
├── app/
│   ├── layout.js
│   └── page.js
└── [standard Next.js files]
```

### Supabase Starter Structure
```
buildathon-supabase-starter/
├── .cursorrules
├── .env.example
├── .gitignore
├── README.md
├── package.json
├── vite.config.js
├── tailwind.config.js
├── index.html
├── src/
│   ├── lib/
│   │   └── supabase.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
└── [standard Vite files]
```

---

## Sharing the Repos

### In Pre-Event Email:
```
🔧 STARTER TEMPLATES (Optional)

If you want a head start:

Firebase (Next.js):
https://github.com/[your-username]/buildathon-firebase-starter

Supabase (React + Vite):
https://github.com/[your-username]/buildathon-supabase-starter

These have .cursorrules pre-configured.

OR just use:
- npx create-next-app@latest (for Firebase)
- npm create vite@latest -- --template react (for Supabase)
```

### On Event Day:
- Post links on whiteboard
- Include in cheat sheet
- Helper desk has links ready

---

## Maintenance

**If you create these:**
- Test them 2-3 times before the event
- Update if dependencies have breaking changes
- Keep .cursorrules in sync with your template
- Document any gotchas in README

**If they break:**
- Have backup: Official CLI commands
- Don't waste time fixing on event day
- Just point people to standard setup

---

## Alternative: No Starter Repos

**Instead, provide:**

**Firebase Quick Start:**
```bash
npx create-next-app@latest my-app
cd my-app
npm install firebase
# Download .cursorrules from [link]
# Download firebase.js from [link]
npm run dev
```

**Supabase Quick Start:**
```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
npm install @supabase/supabase-js
# Download .cursorrules from [link]
# Download supabase.js from [link]
npm run dev
```

**This is simpler and works just as well.**

---

## Decision Matrix

| Factor | Starter Repos | Official CLI Only |
|--------|---------------|-------------------|
| Prep time | 2-3 hours | 30 mins |
| Setup time (participant) | ~20 mins | ~30 mins |
| Maintenance | Medium | None |
| Flexibility | Less (locked to your setup) | More |
| .cursorrules distribution | Built-in | Separate file |

**Recommendation:** Skip starter repos unless you have extra time and want tighter control.

---

**Either approach works. Don't overthink this. The .cursorrules file is more important than the starter repos.**
