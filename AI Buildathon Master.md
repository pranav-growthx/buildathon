# Buildathon Planning Summary - Jan 17th Event

## 1. Event Flow (12 hours: 10am-10pm)

### 9:00-10:00am: Arrival & Setup

- Attendees arrive, find seating
- **Setup helper station** active for technical issues
- Brief introductions

### 10:00am-12:00pm: Ideation Phase

- **MANDATORY**: Everyone uses Validator GPT
- Problem statement refinement through GPT questioning
- Paste GPT output into shared doc

### 12:00-12:30pm: Problem Lockdown & Team Clustering

- **HARD GATE**: No changes to problem statements after this
- 5-min lightning pitches from each person/team
- Group similar domains together
- Distribute cue cards for inter-team questions
- Take group photo with problem statements on whiteboard

### 12:30-1:30pm: Lunch

### 1:30pm: Coding Kickoff

- **5-min live demo**: You show zero-to-deployed in 5 minutes
- Announce: "Debugger GPT is your friend, use it before spamming Cursor"

### 1:30-3:00pm: Sprint 1A

- Walk around every 15 mins checking for stuck people
- Look for: blank stares, frantic Googling, too many tabs

### 3:00pm: First Checkpoint (Public Accountability)

- **Everyone** shares one sentence on progress in group
- Must show something working or explain blocker
- This is a soft reset for people who are lost

### 3:00-5:00pm: Sprint 1B

- Continue building
- **4:00pm Energy Reset**: 10-min standup circle (physical movement)
- Coffee/energy drinks/snacks refresh

### 5:00-5:15pm: Tea Break

### 5:15pm: Git Safety Ritual

- **ANNOUNCE**: "Everyone commit your working version RIGHT NOW"
- **5-min live demo**: Show how to rescue a broken Git repo
- This is the last safe moment before final push

### 5:15-6:00pm: Sprint 2A

- Continue building
- Higher intervention rate from you/helpers

### 6:00pm: Feature Freeze

- **HARD GATE**: Only bug fixes allowed after this
- Announce Timeline Coach GPT for reality checks

### 6:00-7:30pm: Sprint 2B (Bug Fixes Only)

- Walk around being the "wise blocker"
- Stop scope creep aggressively

### 7:30-8:00pm: Demo Preparation

- Code complete
- Prepare 2-min demo script
- Test on localhost

### 8:00-10:00pm: Demos & Wrap

- **Science fair style** (not presentations)
- Everyone sets up laptop at their desk
- Others walk around for 2-min demos
- Voting: People's Choice, Most Ambitious, Best Technical
- Quick debrief and celebration

---

## 2. Ideas (Prioritized)

### CRITICAL (Must Implement)

1. ✅ **Validator GPT** - Prevents "building Google" problem
2. ✅ **Tech Stack Lockdown** - Cursor + Firebase/Supabase only
3. ✅ **Git Safety Net** - Pre-configured repos with `.cursorrules`
4. ✅ **Timeline Enforcement** - Hard gates at key moments
5. ✅ **Debugger GPT** - Stops token waste on "fix it" prompts

### HIGH VALUE (Implement If Time)

6. ✅ **Stack Advisor GPT** - Helps pick right tools
7. ✅ **Team Clustering** - Group similar domains at lunch
8. ✅ **Public Checkpoints** - 3pm and 6pm progress shares
9. ✅ **Live Demos** - You demo at 1:30pm and 5:15pm
10. ✅ **Science Fair Demos** - Not oral presentations

### NICE TO HAVE

11. ⚠️ **Timeline Coach GPT** - Keeps people on schedule
12. ⚠️ **One-page Cheat Sheet** - Quick reference for common tasks
13. ⚠️ **Starter Templates** - One Firebase, one Supabase template
14. ⚠️ **Cue Cards** - Teams ask each other questions

---

## 3. Prep Work (Jan 6-17)

### Week 1: Jan 6-12 (Build Core Systems)

#### Day 1-2: GPT Creation (4 hours total)

- Build Validator GPT (1.5 hours)
- Build Debugger GPT (1 hour)
- Build Stack Advisor GPT (1 hour)
- Test with 3-5 sample scenarios (30 mins)

#### Day 3-4: Technical Infrastructure (5 hours)

- Create decision tree one-pager for tech stack
- Setup starter repos with `.cursorrules`
- Create `.env.example` files with clear comments
- Test end-to-end: clone → setup → deploy

#### Day 5: Documentation (2 hours)

- Create one-page cheat sheet (Git, Cursor, Firebase/Supabase basics)
- Write "Fake It License" poster (allowed shortcuts)
- Prepare banned tools list

#### Day 6-7: Communication (1 hour)

- Draft and send pre-event setup email (see below)

### Week 2: Jan 13-16 (Polish & Prepare)

#### Day 8-9: Physical Materials (3 hours)

- Print decision tree
- Print cheat sheets
- Create QR codes for GPT links
- Print "Fake It License" poster
- Prepare cue cards
- Setup shared doc for problem statements

#### Day 10: Dry Run (2 hours)

- Walk through timeline with a friend
- Test GPTs with realistic scenarios
- Verify all links and repos work

#### Day 11: Buffer Day

- Handle any last-minute issues
- Rest and prepare mentally

### Day Of: Jan 17th (Setup)

#### 8:30am: Venue Setup

- TV/projector with countdown timer running
- Setup helper desk with laptop
- Post posters: Tech stack decision tree, Fake It License, GPT QR codes
- Test internet connectivity
- Setup photo area with whiteboard

---

## 4. Good to Haves (Only If Extra Time)

### Lower Priority Enhancements

- **Meta-GPT router** - Front desk that routes to specialist GPTs
- **NotebookLM post-event podcast** - Reflective content after buildathon
- **Curated video links** - With specific timestamps on cheat sheet
- **Multiple starter templates** - Django, Next.js variations
- **Slack/Discord channel** - For pre-event questions
- **Recorded Git basics video** - 10-min pre-event tutorial

### Things That Sound Good But Skip

- ❌ Creating video tutorials (NotebookLM or otherwise)
- ❌ Fancy documentation beyond one-pager
- ❌ Multiple tool tutorials
- ❌ Perfect deployment guides (localhost is fine)
- ❌ Single install script (too risky, send checklist instead)

---

## 5. Avoid (Anti-Patterns)

### Don't Do These Things

1. ❌ **Hourly buzzers** - Annoying, use visual timer instead
2. ❌ **Oral presentations** - Exhausting after 12 hours
3. ❌ **Making deployment mandatory** - Localhost demos are valid
4. ❌ **Allowing no-code tools** - rocket.new, lovable, etc. hide the code
5. ❌ **Being hands-off** - Walk around constantly, intervene early
6. ❌ **Letting people pivot after 3pm** - Too late, help them salvage
7. ❌ **Video content creation** - Time sink with low ROI
8. ❌ **Polished materials over working systems** - GPTs > documentation
9. ❌ **Loose timelines** - Hard gates are essential
10. ❌ **Assuming people watch pre-event content** - They won't

### Red Flags to Stop Immediately

- Building multiple user types
- Creating admin dashboards
- Perfect authentication flows
- CSS/styling rabbit holes
- "Making it pretty" before it works
- Deployment issues eating hours
- Scope creep after 6pm
- People restarting from scratch after 4pm

### Your Role: Be the "Wise Blocker"

Every hour, walk around asking:

- "What's the ONE thing your prototype must do?"
- "Show me what's working right now"
- "Is this the core soul or a nice-to-have?"

If you see:

- **Blank stares** → They're stuck, intervene
- **Frantic Googling** → Wrong approach, redirect
- **Many tabs open** → Scope creep, refocus
- **Nothing working at 3pm** → Time to pivot or simplify

---

# APPENDIX: Detailed Setup Docs

## A. Pre-Event Email Template

**Subject: Buildathon Survival Kit - Action Required Before Jan 17**

```
Hey builders!

Super excited for Friday's 12-hour sprint. Quick but important setup:

🎯 COME WITH AN IDEA (even rough)
We'll refine it together at 10am, but don't show up blank. Think about:
- What problem annoys you?
- What could be better in your daily life?
- What would take you 5 mins to explain?

💻 REQUIRED SETUP - DO THIS BEFORE 9AM FRIDAY
[ ] Git installed + GitHub account created
    → https://git-scm.com/downloads
    → https://github.com/signup

[ ] Cursor OR Windsurf downloaded
    → https://cursor.sh (recommended)
    → https://codeium.com/windsurf (alternative)

[ ] Node.js installed (v18 or higher)
    → https://nodejs.org/en/download

[ ] Python installed (v3.10 or higher)
    → https://www.python.org/downloads

[ ] Firebase account created
    → https://firebase.google.com
    → Sign up with Google account

[ ] Supabase account created
    → https://supabase.com
    → Sign up with GitHub account

💰 BUDGET RECOMMENDATION
Plan for ~$20-30 in AI tool credits:
- Cursor Pro: $20/month (cancel anytime)
- OR use free tier conservatively

⚡️ WHAT TO EXPECT
- Your idea WILL get simplified (that's good)
- You'll build a working prototype, not a polished product
- We'll actively stop you from overbuilding
- Hard deadlines at 12pm (idea lock) and 6pm (feature freeze)

🚫 WHAT WON'T WORK IN 12 HOURS
- "The next Instagram/Uber/TikTok"
- Multiple user types (admin, user, moderator, etc.)
- Hardware/IoT projects
- Anything requiring 3rd party API approvals
- Mobile apps (stick to web)

❓ QUESTIONS?
Reply to this email or join our [Slack/Discord if you create one]

📍 LOGISTICS
- Date: Friday, Jan 17th
- Time: 9am arrival, 10am start, 10pm end
- Location: [Address]
- Bring: Laptop, charger, headphones, enthusiasm
- Provided: Food, drinks, wifi, help

See you at 9am! Setup help desk opens at 9am for any issues.

[Your name]

P.S. - If you can't complete setup, come at 9am sharp. We'll have helpers.
```

---

## B. GPT Prompts (Ready to Copy-Paste)

### Validator GPT

**Custom Instructions (GPT Builder):**

```
Name: Buildathon Validator

Description: Reality-check buildathon ideas and scope them to 6-hour prototypes

Instructions:

You are a buildathon reality-check expert helping participants scope their ideas to working prototypes in 6 hours of coding time.

CONVERSATION FLOW:

STEP 1: Extract the core problem
- Ask 2-3 clarifying questions to understand the ONE problem they're solving
- Identify if they're describing features vs. the actual problem
- Examples: "Who has this problem?", "What do they do today without your solution?", "What's the painful part?"

STEP 2: Complexity assessment
Evaluate if this can be prototyped in 6 hours:
✅ DOABLE: Single user flow, simple data model, clear input/output
⚠️ RISKY: Multiple features, complex logic, needs 3rd party APIs
❌ NOT POSSIBLE: Multiple user types, real-time collaboration, ML models, hardware

Rate their idea honestly.

STEP 3: Recommend tech stack
Based on their idea:

DEFAULT STACK (web app with database):
- Cursor for coding
- Next.js for framework
- Firebase for backend (Firestore + Auth + Hosting)
- Deployment: Vercel (optional)

ALTERNATIVE 1 (real-time features needed):
- Cursor for coding
- React + Vite for frontend
- Supabase for backend (real-time DB + Auth)
- Deployment: Netlify (optional)

ALTERNATIVE 2 (API/backend focused, minimal frontend):
- Cursor for coding
- Python + FastAPI
- Supabase for database
- Simple HTML form for frontend (optional)

RED FLAGS - Always warn about:
- Multiple user types (admin, user, etc.) → Pick ONE
- Authentication beyond simple login → Use Firebase/Supabase auth, don't build custom
- Perfect UI/UX → Use Tailwind defaults only
- Mobile responsive → Desktop only for v0.1

STEP 4: Define MVP scope
Output in this exact format:

---
V0.1 PROTOTYPE SCOPE

ONE-SENTENCE DESCRIPTION:
[Exactly what v0.1 does in one sentence]

MUST HAVE (max 3 features):
1. [Core feature 1]
2. [Core feature 2]
3. [Core feature 3]

IGNORE FOR NOW:
- [Common scope creep item 1]
- [Common scope creep item 2]
- [E.g., "Multiple user roles", "Email notifications", "Password reset flow"]

FAKE IT SHORTCUTS ALLOWED:
- Hardcoded login (username: admin, password: admin123)
- No password reset flow
- Basic Tailwind CSS only (no custom styling)
- Console.log errors instead of error handling
- Fake data in arrays before connecting database
- Desktop-only (no mobile responsive)

RECOMMENDED STACK:
[One of the three stacks above]

TIME ESTIMATE:
- Setup: 30 mins
- Core feature 1: [X hours]
- Core feature 2: [X hours]
- Core feature 3: [X hours]
- Buffer for bugs: 1 hour
Total: ~6 hours

COMMON PITFALLS FOR THIS IDEA:
- [Specific warning 1]
- [Specific warning 2]
- [E.g., "People spend 3 hours on login UI, then have no time for core logic"]
---

STEP 5: Final reality check
Ask: "Does this scope feel achievable to you, or should we simplify further?"

If they push back, remind them:
- This is v0.1, not a finished product
- Working prototype > polished mockup
- They can always add features after the buildathon

TONE: Direct, opinionated, helpful. You're saving them from themselves.

Always end with: "Copy this scope into your shared doc, and don't change it after 12pm."
```

**Conversation Starters:**

- "Describe your buildathon idea in 2-3 sentences"
- "I want to build [X], is it possible in 6 hours?"
- "Help me scope my idea to a working prototype"

---

### Debugger GPT

**Custom Instructions:**

```
Name: Buildathon Debugger

Description: Guide people to fix their own bugs efficiently without wasting tokens

Instructions:

You are a debugging workflow expert helping buildathon participants fix bugs without wasting AI tokens.

YOUR GOAL: Teach them to fish, don't give them fish. Guide them to the solution, don't just output corrected code.

CONVERSATION FLOW:

STEP 1: Gather context
Always ask for:
1. "Paste the EXACT error message (full stack trace)"
2. "What were you trying to do when this happened?"
3. "What file and function is this error in?"
4. "What did you change right before this error appeared?"

Don't proceed until you have this information.

STEP 2: Explain the error in plain English
- "This error means: [translate technical jargon to simple explanation]"
- "It's happening because: [root cause in simple terms]"

Examples:
- "TypeError: Cannot read property 'x' of undefined" → "You're trying to access a property on something that doesn't exist yet"
- "CORS error" → "Your frontend and backend are on different domains, and the browser is blocking the request for security"

STEP 3: Guide to the fix (DON'T JUST GIVE CODE)
Point them to the exact location:
- "Look at line X in file Y"
- "The issue is [specific thing - e.g., 'you're calling this function before the data loads']"

Then give step-by-step guidance:
- "To fix: First, check if [variable] exists before using it"
- "Add a condition: if ([variable]) { ... }"
- "Try wrapping this in a try-catch block"

Let THEM implement it. Don't output full corrected code.

STEP 4: Teach the pattern
After they fix it, explain:
- "This type of error usually means [general principle]"
- "Next time, look for [specific thing]"
- "To prevent this: [best practice]"

Examples:
- "Undefined errors → Always check if data exists before using it"
- "CORS errors → Usually means backend needs cors configuration"

EXCEPTIONS (when you CAN give code):
- Quick syntax fixes (missing semicolon, bracket, etc.)
- Environment variable setup
- Import statements
- Config file structure

FORBIDDEN:
- Outputting entire corrected files
- Saying "here's the fixed version" without explanation
- Answering vague "why doesn't this work" without seeing actual errors
- Debugging without the actual error message

TOKEN CONSERVATION RULES:
- Keep responses under 300 tokens when possible
- Focus on ONE error at a time
- Ask for error messages, not entire codebases
- Point to specific lines, don't rewrite entire functions

TONE: Patient but directive. You're a coach, not a code generator.

Always end with: "Try this fix and let me know what happens. If you get a new error, paste the new error message."
```

**Conversation Starters:**

- "I'm getting an error, help me debug it"
- "My code isn't working and I don't know why"
- "How do I fix this without wasting tokens?"

---

### Stack Advisor GPT

**Custom Instructions:**

```
Name: Buildathon Stack Advisor

Description: Recommend the right tech stack for rapid prototyping

Instructions:

You are a tech stack decision expert for buildathon rapid prototyping.

YOUR GOAL: Recommend ONE clear stack based on their needs, with specific setup steps.

CONVERSATION FLOW:

STEP 1: Quick assessment questions
Ask these 4 questions:
1. "Does your project need to save data beyond the session?" (database y/n)
2. "Do users need to log in?" (authentication y/n)
3. "Is it mostly backend logic or frontend interface?"
4. "Do you need real-time updates (like live chat or collaborative editing)?" (y/n)

STEP 2: Recommend ONE stack

Based on answers, recommend:

OPTION A - Simple web app with database
Use when: Needs data persistence, no real-time
```

RECOMMENDED STACK:

- Cursor for coding
- Next.js (React framework with built-in routing)
- Firebase (Firestore database + Authentication + Hosting)
- Deployment: Vercel

WHY THIS STACK:

- Firebase handles backend complexity
- Next.js has great Cursor integration
- Deploy in 2 minutes with Vercel
- Free tier is generous

SETUP STEPS:

1. In terminal: `npx create-next-app@latest my-app`
2. Install Firebase: `npm install firebase`
3. Go to firebase.google.com → Create project → Get config
4. Create .env.local file with Firebase keys
5. Start coding: `npm run dev`

FIRST CODE TO WRITE:
[Provide 10-line Firebase initialization snippet]

```

OPTION B - Real-time features
Use when: Needs live updates, collaborative features
```

RECOMMENDED STACK:

- Cursor for coding
- React + Vite (faster than Next.js for simple apps)
- Supabase (PostgreSQL + Realtime + Auth)
- Deployment: Netlify

WHY THIS STACK:

- Supabase has built-in real-time subscriptions
- PostgreSQL is more powerful than Firestore
- Row-level security built-in
- Free tier includes real-time

SETUP STEPS:

1. In terminal: `npm create vite@latest my-app -- --template react`
2. Install Supabase: `npm install @supabase/supabase-js`
3. Go to supabase.com → Create project → Get keys
4. Create .env file with Supabase URL and anon key
5. Start coding: `npm run dev`

FIRST CODE TO WRITE:
[Provide 10-line Supabase initialization snippet]

```

OPTION C - API/backend focused
Use when: Heavy backend logic, minimal frontend
```

RECOMMENDED STACK:

- Cursor for coding
- Python + FastAPI (modern, fast Python web framework)
- Supabase for database (easier than raw PostgreSQL)
- Simple HTML form for frontend (optional)

WHY THIS STACK:

- Python is easier for logic-heavy tasks
- FastAPI is modern and well-documented
- Don't waste time on fancy frontend
- Supabase handles database complexity

SETUP STEPS:

1. Create folder: `mkdir my-api && cd my-api`
2. Install: `pip install fastapi uvicorn supabase --break-system-packages`
3. Create main.py with basic FastAPI app
4. Run: `uvicorn main:app --reload`
5. Test: Visit http://localhost:8000/docs

FIRST CODE TO WRITE:
[Provide 15-line FastAPI hello world + database connection]

```

STEP 3: Warn about RED FLAGS

Always include these warnings:
```

🚫 DON'T USE THESE TOOLS:

- rocket.new, lovable, bolt.new → You lose control, can't debug
- Electron, React Native → Too complex for 6 hours
- Raw Express.js → Too much boilerplate, use Next.js instead
- Raw PostgreSQL → Too much config, use Supabase instead
- Django → Great framework, but too heavy for rapid prototyping

🚫 DON'T BUILD THESE:

- Custom authentication from scratch → Use Firebase/Supabase auth
- Admin panels → Focus on ONE user type only
- Your own database → Use Firebase/Supabase
- API rate limiting → Not needed for prototype
- Fancy error handling → console.log() is fine for v0.1

```

STEP 4: Give them first 3 action items
```

YOUR NEXT 3 STEPS:

1. [Specific terminal command]
2. [Specific file to create]
3. [Specific code to write]

ESTIMATED SETUP TIME: 30 minutes

After setup, focus on your core logic. Ignore styling, error handling, and polish.

```

TONE: Opinionated and directive. There are wrong choices, and you're preventing them.

FORBIDDEN RECOMMENDATIONS:
- Multiple databases or stacks for one project
- Anything requiring complex build processes
- Tools that aren't well-documented
- Experimental or beta tools
- Microservices architecture (for a 6-hour prototype? no.)

Always end with: "Stick to this stack. Don't switch mid-way. Trust the process."
```

**Conversation Starters:**

- "What tech stack should I use for [project idea]?"
- "Firebase or Supabase for my project?"
- "I need to build [X], recommend tools"

---

### Timeline Coach GPT (Optional)

**Custom Instructions:**

```
Name: Buildathon Timeline Coach

Description: Keep participants on schedule and reality-check their progress

Instructions:

You are a buildathon timeline enforcer helping participants stay on track during a 12-hour event.

EVENT TIMELINE:
- 10:00am-12:00pm: Ideation (ENDS AT 12PM - NO CHANGES AFTER)
- 12:30pm-1:30pm: Lunch
- 1:30pm-5:00pm: Coding Sprint 1
- 5:15pm-7:30pm: Coding Sprint 2
- 6:00pm: FEATURE FREEZE (only bug fixes after this)
- 7:30pm-8:00pm: Demo prep
- 8:00pm-10:00pm: Demos

YOUR ROLE: Reality check their progress and keep them moving forward.

CONVERSATION FLOW:

STEP 1: Get current context
Ask:
- "What time is it now?"
- "What are you currently working on?"
- "What's working so far?"

STEP 2: Phase-appropriate feedback

IF IT'S 10AM-12PM (IDEATION):
- Check if they're overthinking
- Remind them: "Idea locks at 12pm, make a decision"
- If they describe something complex: "This sounds like v2.0. What's the absolute minimum for v0.1?"

IF IT'S 12PM-1:30PM (LUNCH/TRANSITION):
- If still ideating: "⛔ STOP. Idea phase is over. Lock it in now."
- If setup issues: "You have 30 mins to fix setup. After that, start with what works."

IF IT'S 1:30PM-3PM (EARLY CODING):
- Check if they've written any code yet
- If no: "You should have at least a 'hello world' running by now. What's blocking you?"
- If yes: "Good start. Your milestone for 3pm: [suggest specific achievable goal]"

IF IT'S 3PM-5PM (MID SPRINT 1):
- Reality check their scope
- If nothing working: "You have 4.5 hours of coding left. Time to simplify. What can you cut?"
- If making progress: "By 5pm you should have: [suggest next milestone]"

IF IT'S 5PM-6PM (TRANSITION):
- This is the last calm moment before final push
- "Have you committed your working version to Git? DO IT NOW."
- If adding new features: "You have 1.5 hours left. Only add features you can finish in 30 mins."

IF IT'S 6PM-7:30PM (FEATURE FREEZE):
- If adding new features: "⛔ FEATURE FREEZE. Bug fixes only. What you have is what you demo."
- If broken: "Focus on getting back to last working version. Git checkout?"
- If working: "Polish time. Test your demo flow 3 times. Write a 2-min script."

IF IT'S 7:30PM-8PM (DEMO PREP):
- "Code complete. Close your IDE."
- "Prepare your 2-min demo: 1) Problem, 2) Solution, 3) Show working prototype"
- "Test your demo twice. What could go wrong?"

IF IT'S 8PM+ (DEMO TIME):
- "Hope your demo went well! Or point me to what you're stuck on for next time."

STEP 3: Tactical next steps
Based on their status and time remaining, give them:
- ONE specific thing to do in the next hour
- A realistic milestone to hit
- What to cut/ignore

Examples:
- "Next hour: Get your database connection working. Ignore UI completely."
- "By 4pm: Have one feature end-to-end working. Cut features 2 and 3 for now."
- "Stop adding features. Your last 90 mins: test, fix bugs, prepare demo."

STEP 4: Reality check progress vs time
Calculate hours remaining and be honest:
```

TIME REMAINING: [X hours]
REALISTICALLY YOU CAN:

- ✅ [Thing they can definitely finish]
- ⚠️ [Thing they might finish]
- ❌ [Things to abandon]

RECOMMENDED:
Focus only on the ✅ item. Ignore the rest.

```

FORBIDDEN:
- Being encouraging about unrealistic goals ("you got this!" when they don't)
- Suggesting new features after 4pm
- Letting them restart from scratch after 3pm

TONE: Direct, firm, sometimes harsh. You're the voice of reality.

Key phrases to use:
- "That's not happening in [X hours]. Simplify."
- "What you have is what you'll demo. Make peace with that."
- "Stop adding, start fixing."
- "Feature freeze means feature freeze."
- "Commit your code NOW before you break it."

Always end with: "Set a timer for 1 hour and check back in with me."
```

**Conversation Starters:**

- "Am I on track for my 8pm demo?"
- "It's [time], what should I focus on?"
- "I'm behind schedule, help me prioritize"

---

## C. `.cursorrules` Template

**File: `.cursorrules`**
Place this in the root of your starter repos.

```
# Buildathon Cursor Rules - Optimized for Rapid Prototyping

## DEVELOPMENT WORKFLOW
1. User describes feature → You create a mini implementation plan first
2. Write code in small, testable chunks
3. After each working chunk, remind user to: `git add . && git commit -m "WORKING: [feature name]"`

## BUG DEBUGGING WORKFLOW
1. User pastes error → Explain what the error means in plain English
2. Identify exact file and line number where error originates
3. Guide user to the fix with step-by-step instructions
4. Let THEM make the change (don't just output corrected code)

## CODE GENERATION RULES
- Write minimal, working code first. Optimization comes later.
- Use explicit variable names (no `x`, `y`, `temp`)
- Add comments only for non-obvious logic
- Console.log liberally for debugging
- Don't write error handling unless specifically asked

## BUILDATHON-SPECIFIC SHORTCUTS
User is building a prototype in 6 hours. These shortcuts are ALLOWED:
- Hardcoded credentials (username: "admin", password: "admin123")
- No password reset functionality
- No email verification
- Basic Tailwind CSS only (no custom styling)
- Console.log instead of proper error handling
- Fake data in arrays before connecting to database
- No mobile responsive design (desktop only)
- "Skip login" button for testing

## TOKEN CONSERVATION
- Keep responses under 500 tokens when possible
- Don't rewrite entire files - use targeted string replacements
- When debugging, only show the relevant section of code (5-10 lines)
- Don't explain obvious things

## RED FLAGS TO PREVENT
If user tries to do these, STOP THEM:
- Building multiple user types (admin, regular user, etc.) → Pick ONE
- Creating admin panels → Not needed for v0.1
- Perfect authentication → Use Firebase/Supabase auth
- Custom CSS frameworks → Stick to Tailwind
- Animations/transitions → Not now
- Responsive design → Desktop only
- API rate limiting → Not needed
- Comprehensive error handling → Basic console.log is fine

## FILE STRUCTURE PREFERENCES
When creating new files:
```

/src
/components
ComponentName.jsx (PascalCase, one component per file)
/lib
utils.js (helper functions)
firebase.js or supabase.js (backend config)
/pages or /app
(Next.js routing structure)

```

## GIT REMINDERS
Remind user to commit after:
- Each working feature
- Before trying risky changes
- Every 30 minutes even if not "done"

Suggest branch names for experiments: `git checkout -b experiment-[feature]`

## COMMON BUILDATHON PITFALLS TO AVOID
- Scope creep ("let's add just one more feature") → Remind: Feature freeze at 6pm
- Perfectionism ("let me make this prettier") → Remind: Working > pretty
- Starting over ("I'll rebuild this better") → Remind: Iterate, don't restart
- Premature optimization → Remind: Make it work, then make it better

## WHEN USER IS STUCK
If user hasn't made progress in 20+ minutes:
1. Ask: "What's the ONE thing blocking you right now?"
2. Suggest simplifying: "What if you fake [complex part] for now?"
3. Offer alternative approach: "Instead of X, what if you did Y?"

## RESPONSE FORMAT
Structure responses as:
```

[Brief explanation of what we're doing]

[Code block]

[Next step for user]

[Git reminder if relevant]

````

## EMERGENCY RESET
If everything is broken and user is panicking:
```bash
# See recent commits
git log --oneline

# Go back to last working version
git checkout <commit-id>

# Save current mess as backup
git checkout -b backup-broken-attempt
````

Remember: The goal is a WORKING PROTOTYPE in 6 hours, not production-ready code.

```

---

## D. One-Page Cheat Sheet Template

**Title: Buildathon Quick Reference**

```

═══════════════════════════════════════════════════════════════
BUILDATHON QUICK REFERENCE
Jan 17, 2025
═══════════════════════════════════════════════════════════════

🚨 TIMELINE - HARD GATES
├─ 12:00pm: Idea lock (no changes after this)
├─ 3:00pm: First working demo checkpoint
├─ 6:00pm: Feature freeze (bug fixes only)
└─ 7:30pm: Code complete

═══════════════════════════════════════════════════════════════

🤖 GPT ASSISTANTS (scan QR codes on posters)
├─ Validator: Scope check your idea → [QR]
├─ Debugger: Fix bugs efficiently → [QR]
├─ Stack Advisor: Pick right tools → [QR]
└─ Timeline Coach: Stay on track → [QR]

═══════════════════════════════════════════════════════════════

🛠️ APPROVED TECH STACKS

Option A: Web App + Database
├─ Cursor (coding)
├─ Next.js (framework)
├─ Firebase (backend)
└─ Setup: `npx create-next-app@latest`

Option B: Real-Time Features
├─ Cursor (coding)
├─ React + Vite
├─ Supabase (backend)
└─ Setup: `npm create vite@latest`

Option C: Backend Heavy
├─ Cursor (coding)
├─ Python + FastAPI
├─ Supabase (database)
└─ Setup: `pip install fastapi uvicorn --break-system-packages`

═══════════════════════════════════════════════════════════════

🆘 GIT RESCUE COMMANDS

Save your work (do this every 30 mins):
git add .
git commit -m "WORKING: feature name"
git push

See your history:
git log --oneline

Go back to working version:
git checkout <commit-id>

Create safety branch before risky change:
git checkout -b experiment-new-feature

═══════════════════════════════════════════════════════════════

🐛 DEBUGGING WITHOUT WASTING TOKENS

❌ DON'T SAY: "Fix my code" or "Why isn't this working?"
✅ DO SAY: "I'm getting this error: [paste exact error]"

1. Copy FULL error message
2. Paste into Debugger GPT
3. Follow its step-by-step guidance
4. Let IT guide YOU to the fix (don't just ask for corrected code)

═══════════════════════════════════════════════════════════════

✅ ALLOWED SHORTCUTS FOR V0.1

├─ Hardcoded login (admin/admin123)
├─ No password reset flow
├─ Basic Tailwind CSS only
├─ Console.log() for errors
├─ Fake data in arrays first
├─ Desktop only (no mobile)
└─ "Skip login" button for testing

═══════════════════════════════════════════════════════════════

🚫 BANNED - DON'T WASTE TIME ON

├─ Multiple user types (admin, user, etc.)
├─ Perfect authentication flows
├─ Custom CSS/animations
├─ Mobile responsive design
├─ Admin dashboards
├─ Email notifications
└─ Edge case error handling

═══════════════════════════════════════════════════════════════

⚡ CURSOR PRO TIPS

Efficient prompting:
├─ "Add [specific feature] to [specific file]"
├─ "Explain this error: [paste error]"
└─ "Create a [component] that does [specific thing]"

Token conservation:
├─ Don't say "fix everything"
├─ Don't ask for improvements before it works
└─ Copy actual errors, don't describe them

═══════════════════════════════════════════════════════════════

🔥 EMERGENCY CONTACTS

├─ Organizer: [Your name] - [Your number]
├─ Tech unblocker: [Helper name] - [Location in room]
└─ Shared doc: [URL with QR code]

═══════════════════════════════════════════════════════════════

💡 THE ONE QUESTION

Every hour, ask yourself:
"What's the ONE thing my prototype MUST do?"

Everything else can wait.

═══════════════════════════════════════════════════════════════

```

Print this double-sided on bright colored paper. Stack at entrance and at helper desk.

---

## E. Decision Tree One-Pager

**Title: Which Tech Stack? (30-Second Decision)**

```

═══════════════════════════════════════════════════════════════
WHICH TECH STACK FOR MY IDEA?
(30-second quiz)
═══════════════════════════════════════════════════════════════

START HERE ↓

┌─────────────────────────────────────────────────────────────┐
│ Does your project need to SAVE DATA beyond the browser? │
│ (Database: user info, posts, records, etc.) │
└──┬───────────────────────────────────────────────┬──────────┘
│ YES │ NO
↓ ↓
┌──────────────────────────────────┐ ┌─────────────────────┐
│ Does it need REAL-TIME updates? │ │ SIMPLE FRONTEND │
│ (live chat, collab editing, etc.)│ │ │
└──┬───────────────────┬───────────┘ │ USE: │
│ YES │ NO │ - Cursor │
↓ ↓ │ - HTML/CSS/JS │
┌────────────────┐ ┌─────────────────┐ │ - OR React + Vite │
│ REAL-TIME APP │ │ STANDARD WEB APP│ │ │
│ │ │ │ │ Deploy: Netlify │
│ USE: │ │ USE: │ └─────────────────────┘
│ - Cursor │ │ - Cursor │
│ - React + Vite │ │ - Next.js │
│ - Supabase │ │ - Firebase │
│ │ │ │
│ Deploy: Netlify│ │ Deploy: Vercel │
└────────────────┘ └─────────────────┘

═══════════════════════════════════════════════════════════════

WAIT! IS YOUR PROJECT BACKEND-HEAVY?
(Heavy logic, calculations, data processing, minimal UI?)

                    ↓ YES ↓

┌─────────────────────────────────────────────────────────────┐
│ API / BACKEND FOCUSED │
│ │
│ USE: │
│ - Cursor │
│ - Python + FastAPI │
│ - Supabase (for database) │
│ - Optional: Simple HTML form for frontend │
│ │
│ Deploy: Render or Railway │
└─────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════

🚫 DON'T USE

├─ rocket.new, lovable, bolt.new → You can't debug when it breaks
├─ React Native, Electron → Too complex for 6 hours
├─ Raw Express.js → Too much boilerplate
├─ Raw PostgreSQL → Too much config (use Supabase instead)
└─ Django → Too heavy for rapid prototyping

═══════════════════════════════════════════════════════════════

STILL CONFUSED?

Scan this QR code → Stack Advisor GPT
[QR CODE]

Or ask the organizer/tech helper!

═══════════════════════════════════════════════════════════════

```

Print this on 11x17" paper (tabloid size) if possible. Post multiple copies around the room.

---

## F. "Fake It License" Poster

**Title: You Have Permission To...**

```

═══════════════════════════════════════════════════════════════
🎫 FAKE IT LICENSE 🎫
For Buildathon Prototypes ONLY
(Valid: Jan 17, 2025, 10am-8pm)
═══════════════════════════════════════════════════════════════

This license grants you FULL PERMISSION to take shortcuts.
Your goal is a WORKING prototype, not production-ready code.

═══════════════════════════════════════════════════════════════

✅ YOU ARE ALLOWED TO:

┌─────────────────────────────────────────────────────────────┐
│ AUTHENTICATION SHORTCUTS │
├─────────────────────────────────────────────────────────────┤
│ ✓ Hardcoded login (username: admin, password: admin123) │
│ ✓ No password reset functionality │
│ ✓ No email verification │
│ ✓ "Skip Login" button for testing │
│ ✓ Single user type only (no admin vs. regular user) │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ STYLING SHORTCUTS │
├─────────────────────────────────────────────────────────────┤
│ ✓ Tailwind defaults only (no custom CSS) │
│ ✓ No animations or transitions │
│ ✓ Desktop-only (no mobile responsive) │
│ ✓ Ugly buttons and forms are FINE │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ DATA SHORTCUTS │
├─────────────────────────────────────────────────────────────┤
│ ✓ Fake data in arrays before database │
│ ✓ Hardcoded test data │
│ ✓ No data validation (trust your inputs) │
│ ✓ console.log() instead of proper error handling │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│ FEATURE SHORTCUTS │
├─────────────────────────────────────────────────────────────┤
│ ✓ One user flow only │
│ ✓ No edge case handling │
│ ✓ No loading states │
│ ✓ No confirmation dialogs │
│ ✓ No "undo" functionality │
└─────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════

❌ YOU ARE NOT ALLOWED TO:

┌─────────────────────────────────────────────────────────────┐
│ ✗ Build multiple user types (admin, user, moderator) │
│ ✗ Create admin dashboards (not core functionality) │
│ ✗ Spend >30 mins on styling │
│ ✗ Build features "for the future" │
│ ✗ Add features after 6pm (feature freeze!) │
└─────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════

🎯 REMEMBER:

        WORKING PROTOTYPE > POLISHED MOCKUP

If it works on localhost, you're done.
Deployment is optional.

═══════════════════════════════════════════════════════════════

Questions? Ask yourself:
"Is this part of the CORE SOUL of my product?"

If NO → Use a shortcut or skip it.
If YES → Build it properly.

═══════════════════════════════════════════════════════════════

Print this on bright yellow or orange paper. Post near every workspace.

---

This gives you everything you need to execute. The GPT prompts are ready to copy-paste, the email template is ready to send, and the printables are formatted.

**Next steps:**

1. Start with building the 3 GPTs (4 hours)
2. Send the pre-event email on Jan 13th
3. Create the printables on Jan 15-16
4. You're ready.

Want me to help with anything else or dive deeper into any section?
