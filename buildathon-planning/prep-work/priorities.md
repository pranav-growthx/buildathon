# Prep Work Priorities - What to Build vs Skip

**Time Available:** Jan 6-17 (11 days)
**Your Constraints:** Limited time, need to focus on high-impact items

---

## ✅ CRITICAL (Must Implement)

**These are non-negotiable. Without these, the buildathon will struggle.**

### 1. Validator GPT
**Why Critical:** Prevents the #1 failure mode - "building Google"
**Time Investment:** 1.5 hours
**Impact:** Saves 50% of participants from scope creep
**When:** Week 1, Day 1-2

Without this, people will:
- Build impossibly ambitious projects
- Waste time pivoting mid-event
- Have nothing working by demo time

---

### 2. Tech Stack Lockdown
**Why Critical:** Decision paralysis kills momentum
**Time Investment:** 2 hours (decision tree + docs)
**Impact:** Eliminates 3+ hours of "which framework?" debates
**When:** Week 1, Day 3-4

Approved stacks ONLY:
- Cursor + Next.js + Firebase
- Cursor + React/Vite + Supabase
- Cursor + Python/FastAPI + Supabase

Everything else is banned.

---

### 3. Git Safety Net
**Why Critical:** Prevents "I broke everything" disasters
**Time Investment:** 2 hours (create templates)
**Impact:** Saves projects at 5pm when people break working code
**When:** Week 1, Day 3-4

Deliverables:
- Pre-configured repos with .cursorrules
- Git rescue commands cheat sheet
- 5-min Git safety demo prepared

---

### 4. Timeline Enforcement
**Why Critical:** Without hard gates, everyone runs out of time
**Time Investment:** 1 hour (prepare announcement scripts)
**Impact:** Gets 80%+ to working prototypes vs 50%
**When:** Week 1, Day 5

Hard gates to enforce:
- 12pm: Idea lock
- 6pm: Feature freeze
- 7:30pm: Code complete

Prepare scripts for each announcement.

---

### 5. Debugger GPT
**Why Critical:** Stops token waste on "fix it" prompts
**Time Investment:** 1 hour
**Impact:** Teaches people to fish, not just give them fish
**When:** Week 1, Day 1-2

Without this, people spam Cursor with:
- "Fix my code" (wastes tokens)
- No error messages
- No understanding of what broke

---

## ⚠️ HIGH VALUE (Implement If Time)

**These significantly improve the experience but aren't deal-breakers if skipped.**

### 6. Stack Advisor GPT
**Why Valuable:** Helps people pick right tools quickly
**Time Investment:** 1 hour
**Impact:** Reduces setup time by 30-60 mins per person
**When:** Week 1, Day 1-2
**Skip If:** You're willing to answer stack questions manually

---

### 7. Team Clustering
**Why Valuable:** Creates peer support, reduces isolation
**Time Investment:** 30 mins (plan the clustering process)
**Impact:** People help each other, less reliance on you
**When:** Week 2, Day 8
**Skip If:** Small group (<10 people)

---

### 8. Public Checkpoints
**Why Valuable:** Accountability + soft resets
**Time Investment:** 1 hour (prepare checkpoint protocols)
**Impact:** Catches struggling people early
**When:** Week 1, Day 5
**Skip If:** You're confident walking around will catch everyone

See: [checkpoints.md](../event-day/checkpoints.md) for detailed protocols

---

### 9. Live Demos (1:30pm and 5:15pm)
**Why Valuable:** Sets expectations, shows it's possible
**Time Investment:** 2 hours (prep + practice)
**Impact:** Reduces "how do I even start?" anxiety
**When:** Week 2, Day 10 (dry run)
**Skip If:** Participants are experienced developers

Demos to prepare:
- 1:30pm: Zero to deployed in 5 mins
- 5:15pm: Git rescue / rollback demo

---

### 10. Science Fair Demos
**Why Valuable:** More energetic than oral presentations
**Time Investment:** 30 mins (plan logistics)
**Impact:** People actually enjoy demo time
**When:** Week 2, Day 8
**Skip If:** Group is tiny (<8 people) - just do circle demos

See: [demo-format.md](../event-day/demo-format.md)

---

## 🤷 NICE TO HAVE

**These are good ideas but low priority. Only do if you have extra time.**

### 11. Timeline Coach GPT
**Time Investment:** 1 hour
**When:** Week 2, Day 8-9
**Alternative:** You can coach people manually

---

### 12. One-Page Cheat Sheet
**Time Investment:** 2 hours
**When:** Week 2, Day 8-9
**Alternative:** People can Google basic commands

---

### 13. Starter Templates
**Time Investment:** 3 hours (one Firebase, one Supabase)
**When:** Week 1, Day 3-4
**Alternative:** People can use npx create-next-app

Only build these if:
- You're experienced with these stacks
- You have time to test them thoroughly
- You want to include pre-configured .cursorrules

---

### 14. Cue Cards for Inter-Team Questions
**Time Investment:** 30 mins
**When:** Week 2, Day 8
**Alternative:** People will naturally ask each other questions

---

## ❌ SKIP (Sounds Good But Low ROI)

**Don't waste time on these, even if they sound appealing.**

### Video Tutorials (NotebookLM or Otherwise)
**Why Skip:** No one watches pre-event content
**Time Sink:** 4-6 hours
**Better Alternative:** Live demos during the event (5 mins)

If people haven't set up their tools, they come at 9am for help.

---

### Fancy Documentation Beyond One-Pager
**Why Skip:** People won't read it
**Time Sink:** 3-5 hours
**Better Alternative:** Quick reference cheat sheet (30 mins to make)

---

### Multiple Tool Tutorials
**Why Skip:** You locked the tech stack, remember?
**Time Sink:** 2-4 hours per tool
**Better Alternative:** Point to official docs

---

### Perfect Deployment Guides
**Why Skip:** Localhost demos are valid
**Time Sink:** 2-3 hours
**Better Alternative:** Make deployment optional

---

### Single Install Script
**Why Skip:** Too risky - fails on different OS/configurations
**Time Sink:** 3-5 hours of debugging edge cases
**Better Alternative:** Send checklist, offer setup help at 9am

---

### Meta-GPT Router
**Why Skip:** Overcomplicated for 15-30 people
**Time Sink:** 2 hours
**Better Alternative:** Post QR codes for each GPT

---

### Curated Video Links with Timestamps
**Why Skip:** No one watches them
**Time Sink:** 2-3 hours
**Better Alternative:** Live demos (5 mins each)

---

### Multiple Starter Templates (Django, etc.)
**Why Skip:** Dilutes focus, creates choice paralysis
**Time Sink:** 4-6 hours
**Better Alternative:** Lock stack to 3 options only

---

### Slack/Discord Pre-Event Channel
**Why Skip:** Low engagement before event
**Time Sink:** 1 hour setup + ongoing moderation
**Better Alternative:** Email for questions, instant responses

**Exception:** Create AFTER event for community building

---

### Recorded Git Basics Video
**Why Skip:** People skip it, then ask questions anyway
**Time Sink:** 2 hours
**Better Alternative:** 5-min live demo at 5:15pm

---

## Time Budget Summary

### Must Do (Critical) - 7.5 hours
- Validator GPT: 1.5h
- Debugger GPT: 1h
- Tech stack decision tree: 2h
- Git safety net: 2h
- Timeline scripts: 1h

### Should Do (High Value) - 6 hours
- Stack Advisor GPT: 1h
- Team clustering plan: 0.5h
- Checkpoint protocols: 1h
- Live demo prep: 2h
- Science fair logistics: 0.5h
- Print materials: 1h

### Could Do (Nice to Have) - 6.5 hours
- Timeline Coach GPT: 1h
- Cheat sheet: 2h
- Starter templates: 3h
- Cue cards: 0.5h

**Total Recommended: 13.5 hours over 11 days = ~1.25 hours/day**

Totally doable if you stick to priorities.

---

## Decision Framework

**When deciding whether to do something, ask:**

1. **Does this prevent a common failure mode?**
   - YES → Critical priority
   - NO → Move to next question

2. **Can I do this live during the event instead?**
   - YES → Skip pre-work, do it live
   - NO → Move to next question

3. **Will participants actually use this?**
   - YES → Consider it
   - NO → Skip it

4. **How much time will this save participants?**
   - 30+ mins per person → High value
   - 10-30 mins per person → Nice to have
   - <10 mins per person → Skip

---

## What Success Looks Like

**With just the CRITICAL items done:**
- 70-80% have working prototypes
- Hard gates respected
- Minimal "I wasted 3 hours on [wrong thing]"
- You're not overwhelmed answering the same questions

**With CRITICAL + HIGH VALUE done:**
- 80-90% have working prototypes
- Strong peer support
- Positive energy throughout
- Clear structure keeps everyone on track

**With everything (including NICE TO HAVE):**
- Marginal improvement over above
- You're stressed from prep work
- Diminishing returns on effort

---

## Final Recommendation

**Week 1 (Jan 6-12): Focus on CRITICAL items**
- Build the 3 GPTs (Validator, Debugger, Stack Advisor)
- Create tech stack decision tree
- Setup Git safety templates
- Prepare timeline announcement scripts

**Week 2 (Jan 13-16): Add HIGH VALUE items as time permits**
- Checkpoint protocols
- Live demo prep
- Print materials
- Science fair logistics

**Skip everything in the SKIP section.**

Trust that you can handle many things live during the event. You don't need to pre-solve every possible issue.
