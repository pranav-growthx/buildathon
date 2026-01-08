# Buildathon Planning Documentation

**Event Date:** Friday, Jan 17th, 2025
**Duration:** 12 hours (10am-10pm)
**Format:** AI-powered rapid prototyping sprint

---

## 🎯 Quick Start

**New here?** → Start with [INDEX.md](INDEX.md) for full navigation

**It's Jan 6-12?** → [Week 1 Tasks](prep-work/week-1-tasks.md)
**It's Jan 13-16?** → [Week 2 Tasks](prep-work/week-2-tasks.md)
**It's Jan 17 morning?** → [Day-of Setup](prep-work/day-of-setup.md)
**Event is happening now?** → [Event Timeline](event-day/timeline.md)

---

## 📁 What's Inside

This repository contains everything needed to run a successful 12-hour buildathon:

- **GPT Assistants** - 4 custom GPTs to guide participants (Validator, Debugger, Stack Advisor, Timeline Coach)
- **Event Day Guides** - Hour-by-hour timeline, facilitation scripts, checkpoint protocols
- **Prep Schedules** - Two-week runbook with daily tasks
- **Print Materials** - Cheat sheets, decision trees, posters (ready to print)
- **Communications** - Pre-event email, day-of announcements
- **Technical Resources** - Starter templates, .cursorrules, config files

---

## 🚨 Critical Success Factors

1. **Hard Gates** - Problem lock at 12pm, feature freeze at 6pm
2. **GPT Assistants** - Build these FIRST (Week 1, Day 1-2)
3. **Active Facilitation** - Walk around every 15 mins, intervene early
4. **Scope Control** - Stop "building Google" with Validator GPT
5. **Tech Stack Lock** - Cursor + Firebase/Supabase only

---

## 📋 High-Level Timeline

### Pre-Event (Jan 6-17)
- **Week 1:** Build GPTs, create infrastructure, test systems
- **Week 2:** Prepare materials, dry run, finalize logistics
- **Day Before:** Print materials, setup venue

### Event Day (Jan 17)
- **9:00-10:00am:** Arrival & setup help
- **10:00am-12:00pm:** Ideation (with Validator GPT)
- **12:00pm:** 🚨 IDEA LOCK (no changes after this)
- **12:30-1:30pm:** Lunch
- **1:30pm:** Coding kickoff (your 5-min demo)
- **1:30-5:00pm:** Sprint 1 (3pm checkpoint)
- **5:15pm:** Git safety ritual
- **6:00pm:** 🚨 FEATURE FREEZE (bug fixes only)
- **6:00-7:30pm:** Sprint 2
- **7:30-8:00pm:** Demo preparation
- **8:00-10:00pm:** Science fair demos & voting

---

## 🛠️ Tech Stack (Approved Only)

### Option A: Web App + Database
- Cursor + Next.js + Firebase

### Option B: Real-Time Features
- Cursor + React/Vite + Supabase

### Option C: Backend Heavy
- Cursor + Python/FastAPI + Supabase

🚫 **Banned:** rocket.new, lovable, bolt.new, React Native, Electron, raw Express/PostgreSQL

---

## 📞 Getting Help

- Full navigation: [INDEX.md](INDEX.md)
- Event timeline: [event-day/timeline.md](event-day/timeline.md)
- Facilitator guide: [event-day/facilitator-guide.md](event-day/facilitator-guide.md)
- GPT configs: [gpt-configs/](gpt-configs/)

---

## ⚡ Buildathon Philosophy

> **Working Prototype > Polished Mockup**

Participants are building v0.1 prototypes, not production apps. We actively encourage shortcuts:
- Hardcoded credentials (admin/admin123)
- No password reset flows
- Desktop-only (no mobile responsive)
- Fake data before database integration
- console.log() instead of error handling

See: [Fake It License Poster](print-materials/fake-it-license-poster.md)

---

**Ready to dive in?** → [Open INDEX.md](INDEX.md) for full navigation
