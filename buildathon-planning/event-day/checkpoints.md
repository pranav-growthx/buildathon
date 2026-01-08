# Event Checkpoints - Critical Progress Gates

These checkpoints provide public accountability and soft resets for people who are lost.

---

## 3:00pm Checkpoint: First Progress Share

**Purpose:** Public accountability + soft reset for struggling participants
**Duration:** 15-20 minutes (depending on group size)
**Format:** Round-robin sharing in group

### Setup

1. **Announce 5 mins before:** "Checkpoint in 5 minutes. Prepare one sentence about your progress."
2. **At 3pm:** "Everyone stop coding. Time for our first checkpoint."
3. **Form a circle or gather around** (physical movement helps reset energy)

---

### The Format

**Each person shares (1 minute max):**
1. **Project name** (one sentence)
2. **What's working** (show on screen if possible, or describe)
3. **Current blocker** (if any)

**Example Shares:**
```
✅ GOOD: "Task tracker app. I have tasks displaying from an array.
         Stuck on connecting Firebase."

✅ GOOD: "Recipe finder. Search box works. Nothing is saved yet,
         working on that now."

❌ TOO VAGUE: "Still working on my project, making progress."

❌ TOO DETAILED: "So I'm using Next.js with App Router and I tried
                  implementing server components but..."
```

---

### Your Role as Facilitator

**During Shares:**
- Keep time strictly (1 min per person)
- Take mental notes of who's struggling
- Don't problem-solve during the round-robin
- Acknowledge briefly: "Got it, keep going" / "We'll help after this"

**Red Flags to Note:**
- ❌ "I'm still setting up" → Major issue, needs immediate help after
- ❌ "Nothing works yet" → Scope too big, needs simplification
- ❌ "I changed my idea" → Didn't respect 12pm lock, needs redirect
- ❌ Vague/evasive answers → Probably very stuck, ashamed to admit it

**Green Flags to Celebrate:**
- ✅ "Here's my working prototype" (even if basic)
- ✅ Specific blocker identified
- ✅ Shows something on screen
- ✅ Realistic next steps

---

### After the Round-Robin (5-10 mins)

**Group Announcements:**

```
"Great progress everyone. Quick observations:

✅ [Number] of you have something working - excellent.

For those stuck:
- If you're still on setup: Talk to me or helper desk in next 5 mins
- If nothing works yet: Time to simplify. Use Validator GPT again.
- If you changed your idea: That's risky. Let's talk.

You have 4.5 hours of coding left until feature freeze.
Reality check: Can you finish what you're building?

Next checkpoint: 6pm (feature freeze)

Break for 5 minutes, then back to coding."
```

---

### Immediate Follow-ups (3:15-3:30pm)

**Triage your mental notes:**

**Priority 1 - Immediate Intervention (spend 5-10 mins each):**
- Anyone with nothing working
- Anyone still on setup/config
- Anyone who seems lost/confused

**Priority 2 - Quick Check-ins (2-3 mins each):**
- Specific blockers you can quickly solve
- People on wrong track (scope too big)

**Priority 3 - Leave Alone:**
- People making solid progress
- Minor blockers they can solve

**Intervention Template:**
```
"Hey, I noticed you're stuck on [X]. Let's spend 5 minutes on this.

What's the ONE thing blocking you right now?"

[Listen]

"Okay, here's what you should do: [specific action]

Try that for 30 minutes. I'll check back at 4pm."
```

---

## 6:00pm Checkpoint: Feature Freeze

**Purpose:** Hard gate - stop new features, focus on stability
**Duration:** 5-10 minutes
**Format:** Announcement + reality check

### The Announcement (Be Firm)

**Stand in center of room, speak loudly:**

```
"EVERYONE STOP CODING. Eyes on me.

It's 6pm. Feature freeze is now in effect.

What does this mean?

✅ ALLOWED:
- Fix bugs in existing features
- Test your demo flow
- Make what you have work reliably
- Improve existing functionality

❌ NOT ALLOWED:
- Adding new features
- Building new components
- "Just one more small thing"
- Trying to make it pretty
- Rewriting working code

You have 90 minutes of coding left.
Then 30 minutes for demo prep.

REALITY CHECK:
Whatever you have right now is what you're demoing.
Make peace with that. Make it work well.

Questions?"
```

---

### Reality Check Walk-Around (6:05-6:20pm)

**Visit each person/team individually:**

**Ask:**
1. "Show me your core feature working end-to-end."
2. "What breaks if you demo this right now?"
3. "What are you fixing in the next 90 minutes?"

**Red Flags:**
- They show you broken code → "Get this working first, nothing else matters"
- They mention adding features → "No. Feature freeze. What bugs need fixing?"
- They're styling/polishing → "Does it work reliably? If not, stop styling."
- They can't demo the core flow → "You have 90 mins to get the happy path working"

---

### Common Pushback & Responses

**Pushback:** "But I'm almost done with [new feature]!"

**Response:**
```
"How long to finish it AND test it?
If more than 30 minutes, cut it.
You need time to test what you already have.

Better to demo 3 solid features than 5 broken ones."
```

---

**Pushback:** "I just need to add [X] or the demo won't make sense!"

**Response:**
```
"Fake it. Hardcode it. Mock it.
You're demoing a prototype, not a finished product.

Can you fake [X] with an array or a hardcoded value?
Do that instead of building it properly."
```

---

**Pushback:** "Nothing works yet, can I keep building?"

**Response:**
```
"You have 90 minutes. Let's get ONE thing working.

What's the absolute minimum for a demo?
- Not the full vision
- Not all features
- Just: What's the core interaction?

Show me that working in 90 minutes. Cut everything else."
```

---

### The "Wise Blocker" Protocol (6:20pm-7:30pm)

**Your role for the next 90 minutes:**

Walk around every 10-15 minutes. If you see:

**❌ New features being added:**
- Physically intervene: "What are you doing?"
- "That's a new feature. Feature freeze. Stop."
- Redirect to bug fixes

**❌ Rewriting working code:**
- "Does the old version work? Yes? Then don't rewrite it."
- "Leave it ugly and working. That's the right choice."

**❌ Deployment struggles:**
- "Localhost demos are fine. Stop deploying."
- Get them back to local development

**✅ Bug fixing:**
- "Good. Keep going."
- Offer quick help if stuck

**✅ Testing demo flow:**
- "Excellent. Test it 3 more times."

---

### 7:00pm Mini-Checkpoint (30 mins before code complete)

**Quick announcement:**

```
"30 minutes of coding left.

If your demo works: Test it 3 times. Find edge cases.
If your demo is broken: Focus on ONE thing working.

At 7:30pm, code complete. No exceptions.
You'll have 30 mins for demo prep after that."
```

---

### 7:30pm: Code Complete

**Final hard gate - absolutely no coding after this**

**Announcement:**

```
"CODE COMPLETE. Close your IDEs.

Next 30 minutes:
1. Test your demo flow 3 times
2. Write your 2-minute pitch:
   - Problem (15 sec)
   - Solution (15 sec)
   - Show working prototype (90 sec)
3. Close unnecessary tabs
4. Have localhost running
5. Prepare fallback if live demo breaks

At 8pm, science fair style demos begin."
```

---

## Checkpoint Success Metrics

### 3pm Checkpoint - Success Indicators:
- 70%+ have something rendering/working
- Clear blockers identified
- Energy still high (not defeated)
- People know their next steps

### 3pm Checkpoint - Warning Signs:
- 50%+ have nothing working
- Vague/evasive answers
- Low energy, frustration visible
- People don't know what to do next

### 6pm Feature Freeze - Success Indicators:
- Core features exist (even if buggy)
- People accept the freeze without much pushback
- Focus shifts to stability
- Demo flow is clear

### 6pm Feature Freeze - Warning Signs:
- Major features still missing
- Resistance to feature freeze
- People trying to sneak in "just one more thing"
- No clear demo path

---

## Facilitation Tips

### Keep Checkpoints Short
- Don't let them drag on
- 1 minute per person, strictly
- Do deep dives 1-on-1 after, not during

### Make Them Stand Up
- Physical movement resets energy
- Helps people shift mental context
- Breaks the "stare at screen" loop

### Be Honest But Supportive
- Don't sugarcoat if someone is behind
- But frame it as "here's how to recover"
- "You're behind, let's simplify" vs "You're doing great!" (when they're not)

### Use Public Accountability
- Saying progress out loud creates commitment
- People don't want to admit lack of progress next time
- Gentle peer pressure to make progress

---

## Emergency Checkpoint (If Needed)

**When to call an unscheduled checkpoint:**
- Multiple people visibly stuck/frustrated
- Energy is very low
- You sense widespread scope creep

**Emergency checkpoint script:**
```
"Quick huddle everyone. 5 minutes.

Show of hands:
- Who has something working right now? [count]
- Who is stuck? [count]

For those stuck: Let's do quick 2-minute troubleshooting round-robin.
For those working: Take a 5-min break, you've earned it.

[Quick triage of stuck people]

Okay, back to it. Next checkpoint at [time]."
```

---

**Remember:** Checkpoints are resets, not performances. Keep them functional and focused.
