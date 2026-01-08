# Event Day Timeline - Jan 17th

**Total Duration:** 12 hours (10am-10pm)
**Arrival Time:** 9am for setup help

---

## 9:00-10:00am: Arrival & Setup

**Activities:**
- Attendees arrive, find seating
- **Setup helper station** active for technical issues
- Brief introductions

**Your Tasks:**
- Greet participants
- Direct setup issues to helper desk
- Ensure posters are visible (Tech Stack Decision Tree, Fake It License, GPT QR codes)

---

## 10:00am-12:00pm: Ideation Phase

**Activities:**
- **MANDATORY**: Everyone uses Validator GPT
- Problem statement refinement through GPT questioning
- Paste GPT output into shared doc

**What to Watch For:**
- People overthinking their ideas
- "Building the next Instagram/Uber/TikTok"
- Scope creep before they even start

**Interventions:**
- Walk around checking if people are stuck on ideation
- Remind: "Validator GPT will help you scope this down"
- Point to decision tree poster for tech stack questions

---

## 12:00-12:30pm: Problem Lockdown & Team Clustering

**🚨 HARD GATE: No changes to problem statements after this**

**Activities:**
- 5-min lightning pitches from each person/team
- Group similar domains together
- Distribute cue cards for inter-team questions
- Take group photo with problem statements on whiteboard

**Your Tasks:**
- Facilitate lightning pitches (set timer, keep moving)
- Physically rearrange seating to cluster similar projects
- Take group photo for social media/memories
- **Announce clearly:** "This is your scope. It locks NOW. No changes after lunch."

---

## 12:30-1:30pm: Lunch

**Activities:**
- Lunch break
- Informal networking
- Setup troubleshooting if needed

**Your Tasks:**
- Use this time to review problem statements
- Identify which projects might struggle
- Prepare your 5-min demo for 1:30pm

---

## 1:30pm: Coding Kickoff

**🎯 KEY MOMENT - Set the tone**

**Activities:**
- **5-min live demo**: You show zero-to-deployed in 5 minutes
- Announce: "Debugger GPT is your friend, use it before spamming Cursor"
- Remind timeline: 3pm checkpoint, 6pm feature freeze

**Your Demo Should Show:**
- npx create-next-app OR vite setup
- One component rendering
- Git commit
- (Optional) Quick deploy to Vercel/Netlify

**Key Message:**
"Working prototype beats perfect code. Use shortcuts. Don't build Google."

---

## 1:30-3:00pm: Sprint 1A

**Activities:**
- Participants coding
- Walk around every 15 mins checking for stuck people

**Look For These Red Flags:**
- Blank stares → They're stuck, intervene
- Frantic Googling → Wrong approach, redirect
- Too many tabs → Scope creep, refocus
- Still on setup at 2pm → Direct to helper desk

**Intervention Script:**
"What's the ONE thing your prototype must do?"
"Show me what's working right now."
"Is this the core soul or a nice-to-have?"

---

## 3:00pm: First Checkpoint (Public Accountability)

**🎯 SOFT RESET MOMENT**

**Activities:**
- **Everyone** shares one sentence on progress in group
- Must show something working OR explain blocker
- This is a soft reset for people who are lost

**What to Listen For:**
- "I'm still setting up" → Red flag, needs help
- "Nothing works yet" → Scope is too big, time to simplify
- "I got stuck on authentication" → Redirect to Firebase/Supabase auth

**Your Role:**
- Facilitate quick round-robin (1 min per person max)
- Take mental notes of who's struggling
- Don't problem-solve in the group, do it 1-on-1 after

---

## 3:00-5:00pm: Sprint 1B

**Activities:**
- Continue building
- **4:00pm Energy Reset**: 10-min standup circle (physical movement)
- Coffee/energy drinks/snacks refresh

**Higher Intervention Rate:**
- Check in with struggling people every 20 mins
- By 4pm, everyone should have SOMETHING working
- If someone has nothing at 4pm: time to radically simplify

**4:00pm Energy Reset:**
- Stand in circle
- Quick stretch
- Each person shares one win (even tiny)
- Refresh snacks/drinks

---

## 5:00-5:15pm: Tea Break

**Activities:**
- Short break
- Bathroom, snacks, fresh air

**Your Prep:**
- Prepare for Git Safety Ritual demo

---

## 5:15pm: Git Safety Ritual

**🚨 CRITICAL MOMENT - Last safe checkpoint**

**Activities:**
- **ANNOUNCE**: "Everyone commit your working version RIGHT NOW"
- **5-min live demo**: Show how to rescue a broken Git repo
- This is the last safe moment before final push

**Your Demo Should Cover:**
```bash
git add .
git commit -m "WORKING: before final features"
git push

# Show recovery:
git log --oneline
git checkout <commit-id>
```

**Key Message:**
"You have 2.5 hours left. Commit what works NOW. Don't break it in the final stretch."

---

## 5:15-6:00pm: Sprint 2A

**Activities:**
- Continue building
- Higher intervention rate from you/helpers

**Watch For:**
- People adding new major features → "Do you have time to finish that?"
- Broken code → "Did you commit before this? Let's roll back."
- Perfectionism → "Is this core functionality or polish?"

---

## 6:00pm: Feature Freeze

**🚨 HARD GATE: Only bug fixes allowed after this**

**Activities:**
- **ANNOUNCE LOUDLY**: "Feature freeze. Only bug fixes from now on."
- Announce Timeline Coach GPT for reality checks

**Your Announcement Script:**
"It's 6pm. Feature freeze is now in effect. Whatever you have is what you'll demo. Focus on:
1. Making what you have WORK reliably
2. Fixing bugs
3. Testing your demo flow

Do NOT:
- Add new features
- Try to make it pretty
- Rebuild anything from scratch

You have 1.5 hours of coding left."

---

## 6:00-7:30pm: Sprint 2B (Bug Fixes Only)

**Activities:**
- Bug fixing only
- Walk around being the "wise blocker"
- Stop scope creep aggressively

**Your Role - "Wise Blocker":**
- If you see someone adding features: STOP THEM
- "That's a feature, not a bug fix. Feature freeze means feature freeze."
- Help people get back to their last working version if broken

**Reality Check Questions:**
- "Does your demo work end-to-end right now?"
- "What breaks if you demo this in 90 minutes?"
- "Can you show me the happy path working?"

---

## 7:30-8:00pm: Demo Preparation

**Activities:**
- Code complete
- Prepare 2-min demo script
- Test on localhost

**Your Tasks:**
- Announce: "Code complete. Close your IDE. Demo prep time."
- Help people structure their 2-min pitch:
  1. Problem (15 sec)
  2. Solution (15 sec)
  3. Show working prototype (90 sec)

**Demo Prep Checklist (announce this):**
- [ ] Test your demo flow 3 times
- [ ] Have localhost running
- [ ] Close unnecessary tabs/apps
- [ ] Prepare fallback if live demo breaks
- [ ] Write 2-3 sentences to say while demoing

---

## 8:00-10:00pm: Demos & Wrap

**Format: Science Fair Style (NOT presentations)**

**Setup:**
- Everyone sets up laptop at their desk
- Others walk around for 2-min demos
- Each builder demos their project multiple times (to different people)

**Why Science Fair vs Stage Presentations:**
- No exhaustion from sitting through 15+ presentations
- More interactive, conversational
- People can see 5-10 demos instead of all 15+
- Less pressure, more fun

**Voting Categories:**
- **People's Choice** - Most popular/useful
- **Most Ambitious** - Biggest scope attempted
- **Best Technical** - Cleanest implementation

**Wrap (9:30-10:00pm):**
- Announce winners
- Quick debrief: "What worked? What would you do differently?"
- Celebration
- Group photo

---

## Timeline Summary (Quick Reference)

| Time | Activity | Type |
|------|----------|------|
| 9:00am | Arrival & Setup | Logistics |
| 10:00am | Ideation | Planning |
| 12:00pm | **IDEA LOCK** 🚨 | Hard Gate |
| 12:30pm | Lunch | Break |
| 1:30pm | Coding Kickoff Demo | Kickoff |
| 3:00pm | Checkpoint 1 | Accountability |
| 4:00pm | Energy Reset | Break |
| 5:15pm | Git Safety Ritual | Critical |
| 6:00pm | **FEATURE FREEZE** 🚨 | Hard Gate |
| 7:30pm | **CODE COMPLETE** 🚨 | Hard Gate |
| 8:00pm | Science Fair Demos | Showcase |
| 10:00pm | End | Wrap |

---

**Keep this open on your laptop during the event for quick reference.**
