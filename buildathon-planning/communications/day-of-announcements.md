# Day-of Announcements - Scripts for Key Moments

**Purpose:** Pre-written scripts for critical announcement moments during the event

**Use:** Read these at the specified times to maintain timeline discipline

---

## 10:00am: Event Kickoff

**Location:** Front of room, everyone can see you

**Script:**

```
Good morning everyone! Welcome to the buildathon.

Quick logistics:
- Wifi: [Point to credentials on whiteboard/screen]
- Bathrooms: [Point to location]
- Food: Lunch at 12:30pm, snacks available throughout
- Questions: Ask me or [point to helpers/helper desk]

Here's the deal:

You have 12 hours. That's not much.

Most of you came with big ideas. That's good.
But we're going to make them MUCH smaller. That's also good.

Timeline: [Point to whiteboard]
- Now until 12pm: Ideation - use Validator GPT [show QR codes]
- 12pm: HARD LOCK - no idea changes after this
- 12:30pm: Lunch
- 1:30pm: Coding starts - I'll do a quick demo
- 6pm: FEATURE FREEZE - only bug fixes after this
- 7:30pm: CODE COMPLETE - no more coding
- 8pm: Demos - science fair style

Hard rules:
1. Use Validator GPT - seriously, everyone
2. Tech stack: Cursor + Firebase OR Supabase only
3. When stuck, use Debugger GPT first
4. Commit your code every 30 minutes
5. No perfect code - working prototype beats polished mockup

Today's goal: Working v0.1 prototype.
Not a finished product. Not polished. Not perfect.
Just: Does the core thing work?

Questions?

[Answer 2-3 quick questions]

Okay, everyone start with Validator GPT.
Scan QR codes around the room or use the links I'll share in chat.

Paste your output in the shared doc [show QR code / link].

Let's go!
```

---

## 12:00pm: Idea Lock

**Location:** Front of room (interrupt everyone)

**Script:**

```
EVERYONE STOP. Eyes on me.

It's 12pm. Idea lock time.

Whatever problem statement you have right now IS your project.
No changes after this point.

If you haven't finalized in the shared doc, do it NOW.
Take 2 minutes to lock it in.

[Wait 2 minutes]

Okay, now for lightning pitches.
30 seconds each. Just your one-sentence description.

We're going around the room. [Point to first person]

[After all pitches]

Great. These are your projects.

In a few minutes, we'll cluster similar domains so you can help each other.

Group photo time - everyone come to the whiteboard!

[Take photo]

Lunch is at 12:30pm. See you back at 1:30pm for coding kickoff.
```

---

## 1:30pm: Coding Kickoff + Live Demo

**Location:** Front of room with your laptop projected

**Script:**

```
Welcome back! Hope you had good lunch.

Quick reminder of our hard gates:
- 3pm: First checkpoint - show progress or explain blocker
- 6pm: FEATURE FREEZE - only bug fixes after
- 7:30pm: CODE COMPLETE
- 8pm: Demos

Now, I'm going to show you zero-to-working in 5 minutes.
This is to prove it's possible and show the pace we want.

[Do your 5-minute demo - see day-of-setup.md]

[After demo]

That took 5 minutes. Your setup might take 30 minutes.
That's fine. But don't spend more than 30 minutes on setup.

If you're stuck on setup past 2pm, come find me or go to helper desk.

Key tools to use:
- Debugger GPT [point to QR code] - use this BEFORE spamming Cursor with "fix it"
- Stack Advisor GPT [point to QR code] - if you're unsure about tech stack
- Git commands [point to cheat sheet] - commit every 30 minutes

One more thing: At 3pm, we're doing a checkpoint.
Everyone will share one sentence about their progress.

Not detailed, just: "What's working, what's blocking me."

This keeps everyone accountable and helps me help you.

Questions?

[Answer quickly]

Okay. You have until 6pm for features.
Then feature freeze.

Start coding. NOW.
```

---

## 3:00pm: First Checkpoint

**Location:** Gather everyone (standing circle or front of room)

**Script:**

```
3pm checkpoint! Everyone stop coding.

Stand up, shake it out. [Demonstrate stretching]

Okay, we're doing a quick round-robin.

Each person: 1 minute max
1. Your project name
2. What's working so far
3. Current blocker (if any)

I'll go first as an example:
"Task tracker. I have tasks displaying from an array. Stuck on Firebase connection."

See? One sentence each. We're not problem-solving here, just sharing.

Let's go. [Point to first person]

[After everyone shares]

Good work everyone. Quick observations:

[Count] of you have something working - that's great.

For those stuck:
- Still on setup? Talk to me in next 5 minutes.
- Nothing working yet? Time to simplify. Use Validator GPT again if needed.
- Complex blockers? Try Debugger GPT first.

You have 4.5 hours of coding left until feature freeze at 6pm.

Reality check: Can you finish what you're building?
If not, simplify now.

5-minute break. Grab snacks, water, bathroom.
Back to coding at 3:10pm.

Next checkpoint: 6pm feature freeze.
```

---

## 4:00pm: Energy Reset (Optional but Recommended)

**Location:** Quick standup, don't make them move far

**Script:**

```
Quick 10-minute energy reset!

Everyone stand up. Seriously, stand.

[Do standing circle]

Quick wins round - everyone shares ONE tiny win.
Even if it's just "my dev server runs."

No blockers, just wins. Go!

[After sharing]

Good. You're in the middle of the grind.
This is the hard part.

Keep pushing. You have 2 hours until feature freeze.

Coffee and snacks are refreshed.

Back to it!
```

---

## 5:15pm: Git Safety Ritual + Demo

**Location:** Front of room with laptop projected

**Script:**

```
EVERYONE STOP CODING.

This is critical. Listen up.

It's 5:15pm. You have 1 hour and 45 minutes until feature freeze.

Right now, I want EVERYONE to commit your working version.

Even if it's not done. Even if it's ugly.
COMMIT IT NOW.

[Wait while everyone commits]

Good. Now I'm going to show you how to rescue a broken Git repo.

Because in the next 2 hours, some of you WILL break your code.

[Do 5-minute Git safety demo - see day-of-setup.md]

[After demo]

Why did I show you this?

Because at 6:30pm, someone's going to panic and say "I broke everything."

Now you know how to go back.

Use branches if you're trying risky changes:
`git checkout -b experiment-new-feature`

If it works, great. If not, go back to main.

Questions?

[Answer quickly]

You have 1 hour 40 mins until feature freeze.
Only add features you can finish in the next hour.

Everything else is for after the buildathon.

Back to coding.
```

---

## 6:00pm: Feature Freeze

**Location:** Stand in center, speak LOUDLY

**Script:**

```
EVERYONE STOP CODING. EYES ON ME.

It's 6pm.

Feature freeze is NOW IN EFFECT.

What does this mean?

✅ ALLOWED:
- Fix bugs in existing features
- Test your demo flow
- Make what you have work reliably
- Polish existing functionality

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

Make peace with that.

Your job for the next 90 minutes:
1. Get your core feature working end-to-end
2. Test it 3 times
3. Fix bugs

That's it.

If your demo is broken, focus on getting ONE thing working.
Better to demo one solid feature than three broken ones.

Timeline Coach GPT is available if you need reality checks on what's achievable.

Questions?

[Answer firmly - reinforce no new features]

Okay. 90 minutes of bug fixing.

GO.
```

---

## 7:00pm: 30 Minutes Warning

**Location:** Quick announcement, don't gather everyone

**Script:**

```
[Loudly, from center of room]

30 MINUTES UNTIL CODE COMPLETE.

If your demo works: Test it 3 more times. Find edge cases.

If your demo is broken: Focus on ONE thing working.

At 7:30pm, coding stops. No exceptions.

Keep going!
```

---

## 7:30pm: Code Complete

**Location:** Front of room, gather everyone

**Script:**

```
CODE COMPLETE.

Close your IDEs. Seriously, close them.

The next 30 minutes are demo prep, not coding.

Here's what to do:

1. Test your demo flow 3 times
   - Happy path: user does the main thing
   - What could break during demo?
   - Have backup plan if live demo fails

2. Write your 2-minute pitch:
   - Problem (15 seconds): What problem does this solve?
   - Solution (15 seconds): How does it work?
   - Demo (90 seconds): Show it working

3. Clean your screen:
   - Close error consoles
   - Close extra tabs
   - Full screen your demo
   - Hide messy code

4. Have localhost running and stable:
   - Don't restart servers during demos
   - Test: refresh page, does it work?

5. Prepare a fallback:
   - Screenshots if live demo breaks
   - Verbal walkthrough
   - Don't panic if something fails

You have 30 minutes to prepare.

At 8pm, we start science fair style demos.

Questions about the demo format?

[Explain science fair: Everyone stays at desk, others walk around, 2-min demos]

Okay, demo prep time. 30 minutes.

GO.
```

---

## 8:00pm: Demos Begin

**Location:** Front of room

**Script:**

```
Okay everyone! Demo time.

Here's how this works:

SCIENCE FAIR STYLE - not presentations.

1. Everyone stays at their desk with laptop open and demo ready

2. Others walk around to see demos

3. Each demo is about 2 minutes:
   - Quick intro (30 sec): Problem + solution
   - Show it working (90 sec): Live demo
   - Quick Q&A if people ask

4. You'll repeat your demo 5-10 times to different people

5. See as many demos as you can (aim for 5-10, not all of them)

We have 90 minutes for demos (until 9:30pm).

Then voting and wrap-up.

Voting categories:
- People's Choice: Most useful/popular
- Most Ambitious: Biggest scope attempted
- Best Technical: Cleanest implementation

We'll do sticker voting [OR explain your voting method].

One rule: Have fun. This is a celebration, not a competition.

Everyone worked hard. Be generous with compliments.

Questions?

[Answer]

Alright, demos start NOW.

Builders: Stay at your station, demo ready.
Viewers: Start walking around!

GO!
```

---

## 9:30pm: Voting & Wrap-Up

**Location:** Gather everyone

**Script:**

```
Okay everyone, gather around!

First: Huge round of applause for EVERYONE.

[Lead applause]

You just built a working prototype in 6 hours of coding.
That's incredible.

Now, winners:

[Announce voting results]

🏆 PEOPLE'S CHOICE: [Project Name] - [One sentence]
   Come grab your [prize/certificate/recognition]

🏆 MOST AMBITIOUS: [Project Name] - [One sentence]

🏆 BEST TECHNICAL: [Project Name] - [One sentence]

[Applause for each]

Quick debrief - 2 questions:

1. What worked well today?
   [Let 2-3 people share quick wins]

2. What would you do differently?
   [Let 2-3 people share learnings]

Common themes I heard:
- "Should have simplified earlier"
- "Should have used the GPTs more"
- "Should have committed more often"

All valid learnings.

Group photo time! Everyone with laptops showing your projects.

[Take photo]

Final words:

Your projects are v0.1, not finished products.
That's perfect. That's the point.

If you want to keep building, do it!
But take a break first. You earned it.

[If you created a community]
Join [Discord/Slack] to share updates and stay connected.

Thank you for your energy, your commitment, and your willingness to build.

This was a success because you all committed to the process.

Safe travels home.

[If doing another buildathon]
Next buildathon: [Date]

See you next time!

[Applause, celebration, informal chatting]
```

---

## Backup Announcements (As Needed)

### If Many People Are Stuck at 2pm

```
Quick huddle everyone. 2-minute check-in.

Show of hands:
- Who has something running? [Count]
- Who is stuck on setup? [Count]

For those stuck on setup:
Next 30 minutes, you're working with [helper/me] at helper desk.
We're getting you unstuck.

For those running:
Keep building. Your milestone for 3pm: [suggest goal]

Back to it!
```

---

### If Someone Wants to Quit

```
[Private conversation]

Hey, I see you're frustrated. That's normal.

This is hard. Everyone feels this at some point.

Quick question: What's the smallest win you could get in the next 30 minutes?

Not the full vision. Just: One tiny thing working.

Let's aim for that.

[Help them identify micro-goal]

Try that for 30 minutes. I'll check back.

Worst case: Your demo can be about what you learned, not what you built.
That's valid too.
```

---

## Tips for Delivering Announcements

### Tone
- **Firm but encouraging**
- **Clear and direct** (no ambiguity)
- **Energetic** (your energy sets the mood)

### Delivery
- **Speak loudly** - everyone must hear
- **Make eye contact** - scan the room
- **Use hand gestures** - point to important things
- **Repeat key points** - hard gates, timelines

### Timing
- **Set phone alarms** for each announcement
- **Don't skip announcements** - they enforce structure
- **Keep them short** - respect their coding time

---

**These scripts give you confidence and consistency. You don't need to wing it at critical moments.**
