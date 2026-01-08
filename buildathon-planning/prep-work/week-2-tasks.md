# Week 2 Tasks (Jan 13-16) - Polish & Prepare

**Goal:** Finalize materials, test everything, prepare physically
**Total Time:** ~6 hours spread over 4 days

---

## Day 8 (Jan 13, Monday): Physical Materials - 3 hours

### Task 1: Print All Materials (1 hour)

**What to print:**

**Decision Tree (11x17" if possible, or A3):**
- Source: [tech-stack-decision-tree.md](../print-materials/tech-stack-decision-tree.md)
- Quantity: 3-5 copies
- Paper: Bright colored (yellow, orange, or green)
- Location: Post on walls around venue

**Cheat Sheet (8.5x11" or A4):**
- Source: [cheat-sheet.md](../print-materials/cheat-sheet.md)
- Quantity: Number of participants + 5 extras
- Paper: Bright colored (different from decision tree)
- Location: Stack at entrance, helper desk, and around room

**Fake It License Poster (8.5x11" or 11x17"):**
- Source: [fake-it-license-poster.md](../print-materials/fake-it-license-poster.md)
- Quantity: 3-5 copies
- Paper: Bright yellow or orange
- Location: Post near every 2-3 workstations

**Printing tips:**
- Use office printer or FedEx/Staples
- Bright colors > white paper (stands out)
- Laminate posters if budget allows (reusable)
- Test print one of each first

---

### Task 2: Create Physical QR Codes (30 mins)

**QR codes needed:**

1. **Validator GPT** - Large QR code on poster
2. **Debugger GPT** - Large QR code on poster
3. **Stack Advisor GPT** - Large QR code on poster
4. **Timeline Coach GPT** - Large QR code on poster (if you built it)
5. **Shared Problem Statement Doc** - Medium QR code

**Steps:**
1. Use qr-code-generator.com or similar
2. Generate high-resolution QR codes
3. Test each one with your phone
4. Create simple poster for each:
   ```
   ┌─────────────────────┐
   │  VALIDATOR GPT      │
   │                     │
   │   [QR CODE HERE]    │
   │                     │
   │ Scope your idea to  │
   │ a working prototype │
   └─────────────────────┘
   ```
5. Print on 8.5x11" paper
6. Post around room

**Alternative:** Add QR codes directly to decision tree and cheat sheet

---

### Task 3: Prepare Cue Cards (Optional - 30 mins)

**Purpose:** Inter-team questions during lunch

**Skip if:**
- Small group (<10 people)
- Tight on time

**If doing it:**

1. Buy index cards (100 pack)
2. Write prompts on cards (10-15 unique prompts):
   - "What's your biggest technical challenge?"
   - "What stack are you using and why?"
   - "If you had 2 more hours, what would you add?"
   - "What did you have to cut from your original idea?"
   - "What surprised you so far?"

3. During lunch clustering, distribute 1-2 cards per team
4. Teams ask each other the questions

**Output:** Cue cards ready OR decision to skip

---

### Task 4: Setup Physical Helper Station (30 mins)

**Purpose:** Designated area for setup help (9-10am)

**What you need:**
- Table near entrance
- Sign: "SETUP HELP DESK - 9:00-10:00am"
- Laptop with:
  - All GPT links bookmarked
  - Starter repo links ready
  - Common setup guides open (Node.js, Git, Cursor)
- Printed cheat sheets
- Extension cord / power strip

**Optional:** Recruit a technical helper to staff this 9-10am

---

### Task 5: Send Pre-Event Email (30 mins)

**IMPORTANT: Send this on Jan 13th (4 days before event)**

**Steps:**
1. Review email draft from [pre-event-email.md](../communications/pre-event-email.md)
2. Add all QR codes and links
3. Update with final event details
4. Send to all registered participants
5. Monitor replies for questions

**Subject:** "Buildathon Survival Kit - Action Required Before Jan 17"

**Key sections:**
- Setup checklist (Git, Cursor, Node, Python, Firebase, Supabase accounts)
- What to expect
- What won't work in 12 hours
- Logistics (time, location, what to bring)

**Follow-up plan:**
- Check email daily for questions
- Send reminder on Jan 16 (day before)

---

## Day 9 (Jan 14, Tuesday): Dry Run & Testing - 2 hours

### Task 6: Dry Run Your Live Demos (1 hour)

**Purpose:** Ensure your demos work smoothly

**Demo 1: Zero to Deployed (1:30pm kickoff)**

**Practice:**
1. Start from scratch
2. Run through:
   - `npx create-next-app my-app`
   - Create simple component
   - Git commit
   - (Optional) Deploy to Vercel
3. Time yourself - should be 5 mins max
4. Identify what could go wrong
5. Prepare backup plan (slides/screenshots)

**Demo 2: Git Safety Ritual (5:15pm)**

**Practice:**
1. Create test repo with "broken" code
2. Show:
   ```bash
   git log --oneline
   git checkout <previous-commit>
   git checkout -b backup-broken
   ```
3. Explain each step clearly
4. Time yourself - should be 5 mins max

**Backup plan:**
- Have slides with commands ready
- Screenshots of each step
- Don't rely on live internet

---

### Task 7: Walk Through Full Event Timeline (30 mins)

**Purpose:** Internalize the flow

**Simulate the day:**

1. Open [timeline.md](../event-day/timeline.md) side by side with [facilitator-guide.md](../event-day/facilitator-guide.md)
2. For each time block, imagine:
   - Where you'll be
   - What you'll say
   - What could go wrong
   - How you'll intervene
3. Note any unclear moments
4. Prepare mental cues for hard gates

**Key moments to rehearse:**
- 12pm: Idea lock announcement
- 1:30pm: Coding kickoff
- 3pm: First checkpoint
- 5:15pm: Git safety
- 6pm: Feature freeze
- 7:30pm: Code complete

---

### Task 8: Verify All Links and Tools (30 mins)

**Check everything works:**

✅ **GPT Links:**
- Open each GPT in incognito window
- Verify they're publicly accessible
- Test one query in each

✅ **Starter Repos (if you made them):**
- Clone each repo fresh
- Follow setup instructions
- Verify they work

✅ **Shared Doc:**
- Open in incognito
- Verify edit permissions work
- Test adding content

✅ **QR Codes:**
- Scan each one with phone
- Verify they go to correct links

✅ **Venue Wifi:**
- If you have access, test speed
- Identify wifi name and password
- Prepare to share these on Jan 17

---

## Day 10 (Jan 15, Wednesday): Final Preparations - 1 hour

### Task 9: Create Day-of Setup Checklist (30 mins)

**Purpose:** Don't forget anything on event day

**Create checklist** (or use [day-of-setup.md](day-of-setup.md)):

8:30am Arrival:
- [ ] Printed materials (decision trees, cheat sheets, posters)
- [ ] Tape / pins for posting materials
- [ ] Laptop + charger + HDMI adapter
- [ ] Timer/countdown visible on TV/projector
- [ ] Helper desk setup
- [ ] WiFi credentials on whiteboard
- [ ] Markers for whiteboard (group photo)
- [ ] Snacks/drinks if you're providing

**Pack a bag:**
- All printed materials
- Laptop
- HDMI adapter
- Extension cords
- Tape, pins, markers
- Your notes/scripts

---

### Task 10: Final Confirmation (30 mins)

**Send to participants:**

```
Subject: Tomorrow's Buildathon - Final Details

Hey builders!

Super excited for tomorrow. Quick final reminders:

📍 LOGISTICS
- Arrival: 9:00am (setup help available)
- Start: 10:00am sharp
- Location: [Address + parking info]

🔑 BRING
- Laptop + charger
- Headphones
- Your rough idea (we'll refine it)
- Enthusiasm

✅ SETUP CHECK (DO THIS TONIGHT)
- Git installed? Try: git --version
- Cursor/Windsurf downloaded?
- Node.js installed? Try: node --version
- Firebase + Supabase accounts created?

If anything isn't working, come at 9am for help.

🚨 COME WITH AN IDEA
Even if rough. We'll scope it at 10am.
Don't show up blank.

💡 REMEMBER
- Idea locks at 12pm
- Feature freeze at 6pm
- Code complete at 7:30pm
- Demos at 8pm

Wifi: [Network name] / Password: [Password]

See you at 9am!

[Your name]
```

---

## Day 11 (Jan 16, Thursday): Buffer Day

### Task 11: Rest & Mental Prep

**DO NOT over-prepare on this day**

**Light tasks only:**
- Review timeline one more time
- Pack your bag (if not done)
- Charge all devices
- Get good sleep

**Mental prep:**
- You've done the work
- Trust your systems (GPTs, timeline, checkpoints)
- You'll be on your feet all day tomorrow
- Save your energy

---

### Task 12: Contingency Planning (Optional - 30 mins)

**What if scenarios:**

**Wifi goes down:**
- Have hotspot ready
- Know how to share your phone's connection
- Have offline docs/tools ready

**Projector fails:**
- Can you demo on your laptop screen?
- Have slides as backup for announcements

**Fewer people show up:**
- Still run the same structure
- Maybe skip team clustering
- Combine some checkpoints

**Too many people show up:**
- Recruit more helpers on the spot
- Extend checkpoint times
- Accept you can't help everyone equally

**Someone brings prohibited tools (rocket.new, etc.):**
- Politely but firmly redirect
- "We're locked to these stacks for a reason"
- Offer to help migrate to approved stack

---

## Week 2 Checklist

**By end of Jan 16, you should have:**

✅ All materials printed and ready
✅ QR code posters created
✅ Helper station planned
✅ Pre-event email sent (Jan 13)
✅ Final reminder sent (Jan 16)
✅ Live demos practiced and timed
✅ Full timeline walked through
✅ All links and tools verified
✅ Day-of checklist created
✅ Bag packed with all materials
✅ Good night's sleep planned
✅ Mental readiness for facilitation

---

## Optional: NotebookLM Post-Event Podcast (Skip for Now)

**IMPORTANT: Don't do this before the event**

**After Jan 17, if you have time:**

1. Collect:
   - Problem statements
   - Demo notes
   - What worked / didn't work
   - Participant feedback

2. Create NotebookLM podcast:
   - Upload all docs
   - Generate reflective discussion
   - Share with participants as recap

**Time investment:** 2 hours
**When:** Jan 18-20 (post-event)
**Priority:** Low - nice to have

---

## If You're Running Behind

**Priority order (cut from bottom up):**

1. ✅ Keep: Pre-event email (CRITICAL)
2. ✅ Keep: Final reminder email (CRITICAL)
3. ✅ Keep: Verify GPTs work (CRITICAL)
4. ✅ Keep: Practice live demos (HIGH VALUE)
5. ✅ Keep: Print cheat sheets (HIGH VALUE)
6. ⚠️ Cut if needed: Print decision trees (can show on screen)
7. ⚠️ Cut if needed: Fake It License posters (can announce verbally)
8. ⚠️ Cut if needed: QR code posters (can share links in chat)
9. ⚠️ Cut if needed: Cue cards (people will network anyway)
10. ⚠️ Cut if needed: Helper station setup (just announce "ask me")

**Absolute minimum to proceed:**
- Pre-event email sent
- GPTs working
- Timeline internalized
- Materials printed (at least cheat sheets)

---

## The Night Before (Jan 16)

**Final check:**
- [ ] Phone charged
- [ ] Laptop charged
- [ ] Bag packed
- [ ] Set 2 alarms for tomorrow
- [ ] Review timeline one more time (10 mins)
- [ ] Get 7-8 hours sleep

**Mental state:**
"I've prepared the systems. Tomorrow is about execution and adaptation."

**You got this.**
