# AI Voice Receptionist for HVAC Booking

**An AI voice receptionist built with n8n and GPT-4o that answers HVAC calls, qualifies leads, books jobs and flags emergencies.**

![Home Services](https://img.shields.io/badge/Home%20Services-167dfe?style=flat-square) ![AI voice agent](https://img.shields.io/badge/AI%20voice%20agent-9533fa?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-231f20?style=flat-square) ![GPT-4o](https://img.shields.io/badge/GPT--4o-231f20?style=flat-square) ![Voice AI](https://img.shields.io/badge/Voice%20AI-231f20?style=flat-square) ![Vapi](https://img.shields.io/badge/Vapi-231f20?style=flat-square) ![Calendar](https://img.shields.io/badge/Calendar-231f20?style=flat-square) ![CRM](https://img.shields.io/badge/CRM-231f20?style=flat-square)

![AI voice agent call transcript and n8n workflow for HVAC booking](assets/cover.webp)

## Overview

An HVAC company missed calls and spent staff time qualifying leads and scheduling jobs. We built an AI voice agent that answers every call, collects the issue and verifies the address, qualifies the lead, checks availability and books the appointment. Cancellations and urgent heating or cooling failures are handled and flagged, so calls turn into booked jobs without staff handling every one.

## The challenge

Calls went unanswered at busy times, and the team spent hours qualifying callers and arranging technician visits by phone.

## The solution

A realtime voice agent (GPT-4o) connected to n8n tools: it collects issue details, verifies the service address, qualifies the lead, checks technician availability, books the job and escalates emergencies.

## How it works

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

n8n · GPT-4o · Voice AI · Vapi · Calendar · CRM

## Screens

![How AI Voice Receptionist for HVAC Booking works: Customer calls, AI voice receptionist, Issue and address verified, Availability checked, Job booked or emergency flagged](assets/screen-1.webp)

![AI Voice Receptionist for HVAC Booking: before and after](assets/screen-2.webp)

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/hvac-ai-voice-receptionist
- Built by **Ch Muhammad Samiullah** ([GitHub](https://github.com/samiullah156-creator)) at [Lexvaxa](https://lexvaxa.com)
