# Week 1 Tasks (Jan 6-12) - Build Core Systems

**Goal:** Create the foundational infrastructure that makes the buildathon work
**Total Time:** ~12 hours spread over 7 days

---

## Day 1-2 (Jan 6-7): GPT Creation - 4 hours total

### Task 1: Build Validator GPT (1.5 hours)

**Purpose:** Prevents "building Google" problem

**Steps:**
1. Go to chat.openai.com/gpts/editor
2. Copy instructions from [validator-gpt.md](../gpt-configs/validator-gpt.md)
3. Configure:
   - Name: "Buildathon Validator"
   - Description: "Reality-check buildathon ideas and scope them to 6-hour prototypes"
   - Instructions: [Paste from validator-gpt.md]
   - Conversation starters:
     - "Describe your buildathon idea in 2-3 sentences"
     - "I want to build [X], is it possible in 6 hours?"
     - "Help me scope my idea to a working prototype"
4. Test with 2-3 sample ideas:
   - "I want to build a social media app like Instagram"
   - "A simple task tracker with reminders"
   - "Real-time collaboration tool for teams"
5. Verify it scopes down ambitious ideas
6. Get shareable link
7. Create QR code: qr-code-generator.com

**Output:** Validator GPT link + QR code saved

---

### Task 2: Build Debugger GPT (1 hour)

**Purpose:** Stops token waste on "fix it" prompts

**Steps:**
1. Go to chat.openai.com/gpts/editor
2. Copy instructions from [debugger-gpt.md](../gpt-configs/debugger-gpt.md)
3. Configure:
   - Name: "Buildathon Debugger"
   - Description: "Guide people to fix their own bugs efficiently without wasting tokens"
   - Instructions: [Paste from debugger-gpt.md]
   - Conversation starters:
     - "I'm getting an error, help me debug it"
     - "My code isn't working and I don't know why"
     - "How do I fix this without wasting tokens?"
4. Test with sample errors:
   - "TypeError: Cannot read property 'x' of undefined"
   - "CORS error when calling my API"
5. Verify it guides rather than just giving code
6. Get shareable link
7. Create QR code

**Output:** Debugger GPT link + QR code saved

---

### Task 3: Build Stack Advisor GPT (1 hour)

**Purpose:** Helps pick right tools for rapid prototyping

**Steps:**
1. Go to chat.openai.com/gpts/editor
2. Copy instructions from [stack-advisor-gpt.md](../gpt-configs/stack-advisor-gpt.md)
3. Configure:
   - Name: "Buildathon Stack Advisor"
   - Description: "Recommend the right tech stack for rapid prototyping"
   - Instructions: [Paste from stack-advisor-gpt.md]
   - Conversation starters:
     - "What tech stack should I use for [project idea]?"
     - "Firebase or Supabase for my project?"
     - "I need to build [X], recommend tools"
4. Test with sample projects:
   - "A recipe finder with search"
   - "Real-time chat app"
   - "API for data processing"
5. Verify it recommends approved stacks only
6. Get shareable link
7. Create QR code

**Output:** Stack Advisor GPT link + QR code saved

---

### Task 4: Test GPTs Together (30 mins)

**Run through a complete flow:**

1. **Start with Validator:**
   - Input: "I want to build a marketplace like Airbnb"
   - Verify: Gets scoped down to simple listing + booking

2. **Move to Stack Advisor:**
   - Input: Result from Validator
   - Verify: Recommends one of the 3 approved stacks

3. **Test Debugger:**
   - Input: A realistic error message
   - Verify: Guides to solution without giving full code

**Adjustments:** Note any issues, refine instructions

---

## Day 3-4 (Jan 8-9): Technical Infrastructure - 5 hours

### Task 5: Create Tech Stack Decision Tree (1.5 hours)

**Purpose:** Visual one-pager for quick stack selection

**Steps:**
1. Use template from [tech-stack-decision-tree.md](../print-materials/tech-stack-decision-tree.md)
2. Create visual version:
   - Tool options: Canva, Figma, or Google Slides
   - Make it printer-friendly (11x17" or A3)
   - High contrast, large fonts
3. Include QR code to Stack Advisor GPT
4. Export as PDF
5. Test print on regular printer

**Output:** decision-tree.pdf ready to print

---

### Task 6: Setup Starter Repos with .cursorrules (2 hours)

**Purpose:** Pre-configured templates that guide AI coding

**Option A: Minimal (Recommended - 1 hour)**

Create 2 repos:
1. **buildathon-firebase-starter**
   - Run: `npx create-next-app@latest buildathon-firebase-starter`
   - Add `.cursorrules` from [cursorrules-template.md](../technical/cursorrules-template.md)
   - Add `.env.example` with Firebase keys template
   - Add README with 3-step setup
   - Push to GitHub
   - Test: Clone, setup, run

2. **buildathon-supabase-starter**
   - Run: `npm create vite@latest buildathon-supabase-starter -- --template react`
   - Add `.cursorrules`
   - Add `.env.example` with Supabase keys template
   - Add README with 3-step setup
   - Push to GitHub
   - Test: Clone, setup, run

**Option B: Skip This (0 hours)**

Just tell people to use:
- `npx create-next-app@latest` for Firebase projects
- `npm create vite@latest -- --template react` for Supabase projects

They can add `.cursorrules` themselves.

**Output:** 2 GitHub repo links OR decision to skip

---

### Task 7: Create .env.example Files (30 mins)

**Purpose:** Clear templates for environment variables

**Firebase .env.example:**
```
# Firebase Configuration
# Get these from: https://console.firebase.google.com
# Project Settings > General > Your apps > SDK setup and configuration

NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key_here
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

**Supabase .env.example:**
```
# Supabase Configuration
# Get these from: https://app.supabase.com
# Project Settings > API > Project URL and anon/public key

VITE_SUPABASE_URL=https://your_project.supabase.co
VITE_SUPABASE_ANON_KEY=your_anon_key_here
```

**Save these in your starter repos OR share separately**

**Output:** .env.example files ready

---

### Task 8: Test End-to-End Setup (1 hour)

**Simulate participant experience:**

**For Firebase stack:**
1. Clone starter repo (or run create-next-app)
2. Follow setup instructions
3. Add Firebase config
4. Run dev server
5. Time yourself: Should take <30 mins

**For Supabase stack:**
1. Clone starter repo (or run create vite)
2. Follow setup instructions
3. Add Supabase config
4. Run dev server
5. Time yourself: Should take <30 mins

**If it takes >30 mins:** Simplify your instructions

**Output:** Verified working setup process

---

## Day 5 (Jan 10): Documentation & Communication - 2 hours

### Task 9: Create One-Page Cheat Sheet (1 hour)

**Purpose:** Quick reference for common tasks

**Use template from:** [cheat-sheet.md](../print-materials/cheat-sheet.md)

**Steps:**
1. Copy template content
2. Update with your specific:
   - Event date/time
   - GPT QR codes
   - Your contact info
   - Shared doc URL
3. Format for printing (8.5x11" or A4)
4. Test print
5. Proofread

**Output:** cheat-sheet.pdf

---

### Task 10: Write Timeline Announcement Scripts (30 mins)

**Purpose:** Pre-written scripts for key moments

**Create short scripts for:**

**1:30pm Coding Kickoff:**
```
[Your demo]

"You just saw zero to working in 5 minutes. That's the pace we want.

Key reminders:
- Use Debugger GPT before spamming Cursor
- Commit working code every 30 mins
- Hard gates: 6pm feature freeze, 7:30pm code complete

Let's build!"
```

**5:15pm Git Safety:**
```
[Your demo]

"EVERYONE commit your working version RIGHT NOW.

You have 2.5 hours left. Don't break what works.

Git is your safety net. Use it."
```

**6:00pm Feature Freeze:**
```
"FEATURE FREEZE.

Whatever you have is what you're demoing.
Only bug fixes from now on.

No new features. No exceptions.

Make what you have work reliably."
```

**Save these:** In [day-of-announcements.md](../communications/day-of-announcements.md)

**Output:** Announcement scripts ready

---

### Task 11: Draft Pre-Event Email (30 mins)

**Purpose:** Set expectations, ensure setup

**Use template from:** [pre-event-email.md](../communications/pre-event-email.md)

**Customize:**
- Add your event date/time/location
- Add your contact info
- Update any specifics for your audience
- Add QR codes if ready

**DON'T send yet** - Send on Jan 13th (Week 2)

**Output:** Email draft ready to send

---

## Day 6-7 (Jan 11-12): Buffer & Refinement

### Task 12: Review & Refine (1-2 hours)

**Test all GPTs again:**
- Run through 3-5 complete scenarios
- Verify instructions are clear
- Check that they're enforcing your constraints

**Review all docs:**
- Proofread cheat sheet
- Verify decision tree is clear
- Test starter repos (if you made them)

**Create QR codes for everything:**
- Validator GPT
- Debugger GPT
- Stack Advisor GPT
- Timeline Coach GPT (if you built it)
- Shared Google Doc (create it now)

---

### Task 13: Create Shared Problem Statement Doc (15 mins)

**Purpose:** Centralized place for all ideas

**Setup:**
1. Create Google Doc: "Buildathon Jan 17 - Problem Statements"
2. Set permissions: Anyone with link can edit
3. Add template:

```
# Buildathon Jan 17 - Locked Problem Statements

Instructions: After using Validator GPT, paste your v0.1 scope here.
Deadline: 12pm (no changes after this)

---

## [Your Name] - [Project Name]

ONE-SENTENCE DESCRIPTION:
[Paste from Validator GPT]

MUST HAVE (max 3 features):
1. [Feature 1]
2. [Feature 2]
3. [Feature 3]

RECOMMENDED STACK:
[From Stack Advisor GPT]

---

[Repeat template for each participant]
```

4. Get shareable link
5. Create QR code

**Output:** Shared doc link + QR code

---

## Week 1 Checklist

**By end of Jan 12, you should have:**

✅ Validator GPT (built + tested + QR code)
✅ Debugger GPT (built + tested + QR code)
✅ Stack Advisor GPT (built + tested + QR code)
✅ Tech stack decision tree (designed + PDF ready)
✅ Starter repos OR decision to skip them
✅ .cursorrules template ready
✅ .env.example files ready
✅ One-page cheat sheet (designed + PDF ready)
✅ Timeline announcement scripts written
✅ Pre-event email drafted (not sent yet)
✅ Shared problem statement doc created
✅ All QR codes generated and saved

---

## If You're Running Behind

**Priority order (cut from bottom up):**

1. ✅ Keep: Validator GPT (CRITICAL)
2. ✅ Keep: Debugger GPT (CRITICAL)
3. ✅ Keep: Stack Advisor GPT (HIGH VALUE)
4. ✅ Keep: Tech stack decision tree (HIGH VALUE)
5. ✅ Keep: Timeline scripts (CRITICAL)
6. ✅ Keep: Pre-event email (CRITICAL)
7. ⚠️ Cut if needed: One-page cheat sheet (people can Google)
8. ⚠️ Cut if needed: Starter repos (people can use official CLI tools)
9. ⚠️ Cut if needed: .cursorrules (share it separately if needed)

**Absolute minimum to proceed:**
- 3 GPTs working
- Pre-event email sent (Week 2)
- Timeline announcement scripts ready

Everything else can be improvised on event day.
