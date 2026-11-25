<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=AI%20Voice%20Receptionist%20for%20HVAC%20Booking&fontSize=31&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Home%20Services%20%E2%80%A2%20AI%20voice%20agent&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="AI Voice Receptionist for HVAC Booking" />

**An AI voice receptionist built with n8n and GPT-4o that answers HVAC calls, qualifies leads, books jobs and flags emergencies.**

<p>
  <img src="https://img.shields.io/badge/Home%20Services-167dfe?style=flat-square" alt="Home Services" />
  <img src="https://img.shields.io/badge/AI%20voice%20agent-9533fa?style=flat-square" alt="AI voice agent" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/GPT--4o-231f20?style=flat-square" alt="GPT-4o" />
  <img src="https://img.shields.io/badge/Voice%20AI-231f20?style=flat-square" alt="Voice AI" />
  <img src="https://img.shields.io/badge/Vapi-231f20?style=flat-square" alt="Vapi" />
  <img src="https://img.shields.io/badge/Calendar-231f20?style=flat-square" alt="Calendar" />
  <img src="https://img.shields.io/badge/CRM-231f20?style=flat-square" alt="CRM" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#screens">Screens</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![AI voice agent call transcript and n8n workflow for HVAC booking](assets/cover.webp)

## Overview

An HVAC company missed calls and spent staff time qualifying leads and scheduling jobs. We built an AI voice agent that answers every call, collects the issue and verifies the address, qualifies the lead, checks availability and books the appointment. Cancellations and urgent heating or cooling failures are handled and flagged, so calls turn into booked jobs without staff handling every one.

## The challenge

Calls went unanswered at busy times, and the team spent hours qualifying callers and arranging technician visits by phone.

## The solution

A realtime voice agent (GPT-4o) connected to n8n tools: it collects issue details, verifies the service address, qualifies the lead, checks technician availability, books the job and escalates emergencies.

## How it works

```mermaid
flowchart LR
    A(["Every call answered"]) --> B
    B["Issue and<br/>address confirmed"] --> C
    C["Voice model<br/>and rules"] --> D
    D(["Availability checked,<br/>job booked"])

    classDef box fill:#1d1726,stroke:#167dfe,color:#e5e7eb
    classDef ends fill:#2e1065,stroke:#9533fa,color:#ffffff
    class B,C box
    class A,D ends
```

1. **Every call answered.** The voice agent answers in the company's name and asks what the problem is, in a natural conversation.
2. **Issue and address confirmed.** It asks the right questions about the fault, then reads the service address back to confirm it.
3. **Voice model and rules.** A realtime GPT-4o voice model runs with clear rules for emergencies, confirmations and which tools to use.
4. **Availability checked, job booked.** n8n tools check technician availability, book the appointment and log the lead in the CRM.

## Key features

- Answers every call in a natural voice
- Collects issue details and verifies the address
- Qualifies leads and checks availability
- Books appointments automatically
- Handles cancellations and flags emergencies

## Results

- Calls turn into booked appointments
- Emergencies flagged to the team immediately
- Staff no longer handle every routine call

## Tech stack

![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![GPT-4o](https://img.shields.io/badge/GPT--4o-1d1726?style=for-the-badge) ![Voice AI](https://img.shields.io/badge/Voice%20AI-1d1726?style=for-the-badge) ![Vapi](https://img.shields.io/badge/Vapi-1d1726?style=for-the-badge) ![Calendar](https://img.shields.io/badge/Calendar-1d1726?style=for-the-badge) ![CRM](https://img.shields.io/badge/CRM-1d1726?style=for-the-badge)

## Screens

![How AI Voice Receptionist for HVAC Booking works: Customer calls, AI voice receptionist, Issue and address verified, Availability checked, Job booked or emergency flagged](assets/screen-1.webp)

![AI Voice Receptionist for HVAC Booking: before and after](assets/screen-2.webp)

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/hvac-ai-voice-receptionist

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
