# Facilitator Guide - Your Role During the Event

**Your Job:** Be the "Wise Blocker" - actively prevent common buildathon failures

---

## Core Philosophy

You are NOT a hands-off observer. You are an active interventionist who:
- Stops scope creep before it kills projects
- Redirects stuck people quickly
- Enforces timeline gates firmly
- Celebrates small wins loudly

**Key Principle:** It's better to deliver a working simple prototype than a broken ambitious one.

---

## Your Intervention Protocol

### Every 15 Minutes: Visual Scan

Walk around the room looking for:

**🚨 RED FLAGS - Intervene Immediately:**
- **Blank stares** → They're stuck, go talk to them
- **Frantic Googling** → Wrong approach, redirect
- **Too many tabs open** → Scope creep, refocus
- **Same error for 20+ mins** → Point to Debugger GPT
- **Still designing/planning past 2pm** → Push them to write code
- **Restarting from scratch after 4pm** → STOP THEM

**✅ GREEN FLAGS - Brief Encouragement:**
- Code on screen, typing actively
- Testing in browser
- Console.log debugging happening
- Git commits visible
- Focused, not distracted

---

## The One Question Framework

Every hour, ask these questions to different people:

### "What's the ONE thing your prototype must do?"
**Why:** Forces them to identify core functionality
**Follow-up if unclear:** "If you could only demo ONE feature, what would it be?"

### "Show me what's working right now"
**Why:** Reveals if they're building or just planning
**Follow-up if nothing works:** "What's blocking you from having a hello world?"

### "Is this the core soul or a nice-to-have?"
**Why:** Stops feature creep
**Follow-up if "nice-to-have":** "Cut it. Focus on core."

---

## Intervention Scripts by Scenario

### Scenario 1: Nothing Working at 3pm Checkpoint

**What You See:**
- Person says "I'm still setting up" or "Nothing works yet"

**Your Response:**
```
"You have 4.5 hours of coding left. Let's radically simplify.

What's the absolute minimum you need to demo?
- Not the full vision
- Not production-ready
- Just: What's the core interaction?

Let's get THAT working in the next 90 minutes. Everything else is v2."
```

**Action:** Sit with them for 5 minutes and help them cut scope in half.

---

### Scenario 2: Scope Creep (Adding Features Mid-Build)

**What You See:**
- "I'm adding user profiles / admin dashboard / email notifications"

**Your Response:**
```
"Stop. That's v2.0 thinking.

Do you have your CORE feature working end-to-end?
- Can a user do the main thing?
- Does it work reliably?

If NO → Don't add anything new. Fix the core.
If YES → You have X hours left. Can you finish this AND test it? Really?
```

**Action:** Make them demo the core feature to you right now. If broken, redirect.

---

### Scenario 3: Authentication Rabbit Hole

**What You See:**
- Person has spent 2+ hours on custom login/signup flows

**Your Response:**
```
"You're building auth from scratch? Hard stop.

Use Firebase Auth or Supabase Auth. It's 5 lines of code.
Or better: Hardcoded login for the prototype.

Username: admin
Password: admin123

Your demo doesn't need real auth. It needs a working prototype.
```

**Action:** Point them to Stack Advisor GPT or show them Firebase Auth quickstart.

---

### Scenario 4: Perfectionism (CSS/Styling Rabbit Hole)

**What You See:**
- Tweaking colors, fonts, spacing while core features broken

**Your Response:**
```
"Does it work? Yes or no.

If NO → Why are you styling it?
If YES → You have X hours left. Styling should take 15 minutes max.

Tailwind defaults are fine. Ugly but working beats pretty but broken.
```

**Action:** Literally tell them to close the CSS file and focus on functionality.

---

### Scenario 5: Deployment Hell

**What You See:**
- 90+ minutes fighting with Vercel/Netlify/Railway configs

**Your Response:**
```
"Localhost demos are 100% valid. Stop deploying.

You can deploy AFTER the buildathon if you want.
Right now: Make it work on your machine. That's the demo.
```

**Action:** Get them back to localhost development immediately.

---

### Scenario 6: Restarting from Scratch (After 4pm)

**What You See:**
- "I'm going to rebuild this with [different framework]"

**Your Response:**
```
"Absolutely not. You have 3.5 hours left.

Restarting from zero guarantees you'll have nothing working.

What you have now might be messy, but it's SOMETHING.
Let's salvage this. What's the smallest working demo we can extract?
```

**Action:** Force them to commit current code, then help identify salvageable pieces.

---

### Scenario 7: Still Ideating After 12pm

**What You See:**
- Person is still changing their idea, Googling market research

**Your Response:**
```
"STOP. Idea phase ended at 12pm.

Whatever you have right now IS your idea.
Lock it in. Move to implementation.

You can't build if you're still deciding what to build.
```

**Action:** Physically help them write down their one-sentence problem statement and pin it to their screen.

---

## Phase-Specific Intervention Rates

### 10am-12pm: Low Intervention
- Let Validator GPT do the work
- Only intervene if completely stuck
- Focus on setup issues

### 12pm-3pm: Medium Intervention
- Check in every 15 mins
- Quick questions: "What are you working on?"
- Light redirects if needed

### 3pm-6pm: High Intervention
- Active walking around
- Stop scope creep aggressively
- Help unstick people quickly

### 6pm-7:30pm: Maximum Intervention
- Feature freeze enforcement
- Block new features physically ("No, don't code that")
- Help people stabilize what they have

### 7:30pm-8pm: Coaching Only
- Demo prep advice
- No more coding interventions
- Help with pitch structure

---

## Red Flags: Stop These Immediately

### Technical Red Flags
- Building multiple user types (admin, regular user, moderator)
- Creating admin dashboards
- Custom authentication from scratch
- CSS frameworks beyond Tailwind
- Animations/transitions
- Mobile responsive design
- API rate limiting
- Comprehensive error handling
- Email notifications
- Password reset flows

### Process Red Flags
- "Making it pretty" before it works
- Restarting from scratch after 4pm
- Changing core idea after 12pm
- Adding features after 6pm
- Deployment issues eating hours
- Still Googling tutorials at 5pm
- No Git commits by 3pm

---

## Positive Interventions (Encouragement)

### Celebrate These Moments
- First successful localhost load
- First database read/write
- First end-to-end user flow working
- Good Git commit messages
- Using Debugger GPT effectively
- Cutting scope proactively

### Encouragement Scripts
```
"This is exactly the right approach - simple and working!"
"Great Git commit. Keep doing that every 30 mins."
"You simplified perfectly. This is a solid demo."
"This is what v0.1 should look like. Well done."
```

---

## Time-Based Reality Checks

### At 3pm (4.5 hours left)
- Everyone should have SOMETHING rendering
- Database connections tested (even if fake data)
- Git repo with at least 3 commits

### At 5pm (2.5 hours left)
- Core feature working end-to-end (even if buggy)
- Clear demo flow identified
- No new features being added

### At 6pm (1.5 hours left)
- FEATURE FREEZE enforced
- Bug fixing only
- Demo script drafted

### At 7pm (1 hour left)
- Code stabilization only
- No major changes
- Demo rehearsal starting

---

## Energy Management

### Your Energy Matters
- Stay positive but realistic
- Don't sugarcoat ("You're behind, let's simplify")
- Take short breaks yourself (every 90 mins)
- Eat lunch, stay hydrated

### Participant Energy
- **4pm Energy Reset** is critical - make everyone stand up
- Refresh snacks/drinks at 3pm and 6pm
- Acknowledge the grind: "You're in the hard part, push through"

---

## Communication Tone Guide

### What to Say
✅ "Let's simplify this"
✅ "What's blocking you?"
✅ "Show me what works"
✅ "That's v2.0, focus on v0.1"
✅ "Cut that, focus on core"

### What NOT to Say
❌ "You got this!" (when they clearly don't)
❌ "Just keep trying" (without specific guidance)
❌ "Maybe add [feature]" (scope creep)
❌ "That's a cool idea!" (when it's too ambitious)
❌ "You have plenty of time" (false hope)

---

## Emergency Protocols

### If Someone is Truly Stuck (30+ mins no progress)

1. **Stop them from coding**
2. **Ask:** "If you could only show ONE thing working, what would it be?"
3. **Help them create a 30-min micro-goal**
4. **Sit with them for 5 mins to start**
5. **Check back in 30 mins**

### If Multiple People Are Stuck

- Call a 5-min group huddle
- Ask who's stuck on similar issues
- Group problem-solving session
- Point to relevant GPT assistant

### If Someone Wants to Quit

- Normalize the struggle: "This is the hard part, everyone feels this"
- Reframe: "What's the smallest win you can get in 30 mins?"
- Pair them with someone further along
- Last resort: "Make your demo about what you learned, not what you built"

---

## Your Success Metrics

### Good Buildathon:
- 80%+ have SOMETHING working by 8pm
- No one restarted after 4pm
- Feature freeze respected
- Demos are energetic (not exhausted)

### Great Buildathon:
- 90%+ have working prototypes
- People proactively use GPT assistants
- Scope stays controlled throughout
- Multiple "wow" moments during demos

### Warning Signs:
- 50%+ have nothing working at 6pm
- Widespread frustration/quitting energy
- Feature freeze ignored
- You're fixing everyone's code personally

---

## Final Tips

1. **Trust your judgment** - If something feels off, intervene
2. **Be firm on gates** - Hard gates are there for a reason
3. **Don't code for them** - Guide, don't do
4. **Celebrate small wins** - Momentum is everything
5. **Enforce breaks** - Burnt-out builders don't finish

**Remember:** Your job is to maximize the number of working prototypes, not perfect projects.
