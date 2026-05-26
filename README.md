# Contact Message Form - AI Automation Workflow

## 📌 Overview

This project demonstrates a fully automated, LLM-powered contact management system built using n8n (workflow automation).

It intelligently processes user enquiries submitted via a contact form, categorises them, sends notifications, generates AI-based responses, and maintains structured records - significantly reducing manual effort and improving response efficiency.

---

## ❗ Problem Statement

Managing incoming messages manually from a portfolio or website can be:

- Time-consuming
- Error-prone
- Difficult to track and organise
- Slow in response time

There is a need for an automated system that can **classify, respond, and store messages efficiently**.

---

## 💡 Solution

This project automates the entire workflow using:

- AI (LLM) for message understanding
- n8n for workflow orchestration
- Airtable for structured storage
- Gmail for communication

The system:
- Classifies user intent
- Stores data in structured format
- Notifies the owner
- Generates a professional response
- Sends reply back to the user
- Tracks everything in Airtable

>  * Manual response time: 12-24 hours (read, classify, reply manually) -> under 2 minutes end-to-end automated
>  * Classification accuracy: LLM correctly routes to individual inquiry type sections without manual triage
>  * Record keeping: 0% structured before -> 100% logged in Airtable with response tracked per inquiry type

Why chosen: A single person managing a portfolio can't monitor email constantly. This ensures no inquiry goes unanswered or untracked, even at odd hours.

---

## 🧠 Architecture Overview
<img width="5535" height="952" alt="Contact Message Form Flow chart" src="https://github.com/user-attachments/assets/f3e2669e-fb6f-41aa-93f4-6d1cd3dd365c" />
