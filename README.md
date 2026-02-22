# Recruit-AI
Agentic AI Hiring Assistant for Small & Mid-Sized Companies

---

## Problem

Small and mid-sized companies receive hundreds of resumes per open role but lack the HR bandwidth to screen efficiently.

Manual resume screening results in:
- Slow hiring cycles
- Decision fatigue
- Delayed candidate communication
- Poor candidate experience

Persona:
Sarah – Founder / Talent Acquisition Manager  
Company Size: 20–100 employees  

---

## Solution

Recruit-AI is an agentic AI system that:

- Screens resumes against job descriptions
- Scores candidates
- Recommends shortlists
- Automates interview scheduling
- Responds to candidates within 24 hours

Built as an MVP focused on high-impact automation: screening + scheduling.

---

## Why Agentic AI?

The workflow requires:
- Understanding unstructured resume data
- Applying decision criteria
- Producing structured outputs
- Triggering downstream actions

This makes it ideal for an agent-based AI system.

---

## System Architecture

Core Components:
- Resume vs JD matching engine
- Structured JSON output for scoring
- LLM chain for reasoning
- Automation trigger for interview scheduling

Design Decisions:
- Used structured JSON output for predictable automation
- Selected Basic LLM Chain for clarity & flexibility
- Lower temperature for scoring reliability

---

## Success Metrics

- Resume screening time ↓ 70%
- Time-to-hire ↓ 40%
- Candidate response time < 24 hours
- Recruiter NPS > 50

---

## Product Roadmap

MVP:
- Resume vs JD screening
- Candidate scoring
- Recommendation engine

6 Months:
- Bulk resume upload
- Automated interview scheduling

1 Year:
- ATS integrations
- Candidate ranking dashboard

---

## Trade-offs

- Accuracy vs Speed → prioritized faster screening
- Manual text input instead of full PDF parsing for MVP

---

## Key Learnings

- Prompt clarity directly impacts output consistency
- Lower temperature improves scoring reliability
- Simplifying workflows speeds debugging

---

## Demo & Assets

Pitch Deck:  
https://gamma.app/docs/The-Hiring-Bottleneck-Every-Recruiter-Faces-f5zxbzi6u2cpwxu

Wireframes:  
https://www.figma.com/make/HqaQOpJy2EJdHKz5sWAu3z/Job-Application-Workflow

Frontend Prototype:  
https://id-preview--9dcb0b67-5c08-4ac0-8ebb-4278675a5ded.lovable.app

Backend Workflow:  
https://drive.google.com/file/d/1C_Z5RaqCATFTidpTVWK4vD9M3pr0zR7X/view

5-min Video Pitch:  
https://www.loom.com/share/d2987a369a534b2b9a302f8f7999beb3
