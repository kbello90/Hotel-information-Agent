# 🏨 Hotel Information Agent

An AI-powered hotel information agent designed to answer guest questions accurately, consistently, and safely.  
The agent supports common hotel inquiries such as amenities, restaurant hours, and check-in/check-out policies, and is built following enterprise AI best practices using **Azure AI Foundry**.

This project demonstrates how to design, deploy, and evaluate a production-oriented AI agent with clear boundaries, reliable responses, and structured testing.

---

## 📌 Project Overview

Hotels receive a high volume of repetitive guest questions that require fast, accurate, and consistent answers.  
This AI agent acts as a **virtual hotel concierge**, providing instant responses while ensuring information is sourced from approved knowledge and handled in a guest-friendly manner.

The project focuses on:
- Reliable question answering
- Controlled agent behavior
- Clear response boundaries
- Evaluation and testing readiness

---

## ✨ Key Features

- Answers guest questions about:
  - Hotel amenities
  - Restaurant hours
  - Check-in and check-out times
- Uses structured prompts to ensure:
  - Consistent tone
  - Accurate responses
  - Graceful handling of unclear or missing information
- Designed with **enterprise evaluation and testing** in mind
- Ready for extension with:
  - RAG (Retrieval-Augmented Generation)
  - Multilingual support
  - Image or document analysis

---

## 🧠 Architecture & Technologies

**Platform**
- Azure AI Foundry

**Model**
- `gpt-5-mini` (or equivalent deployed model)

**Agent Design**
- Single-agent architecture
- Clear role definition and response boundaries
- Deterministic behavior for factual queries

**High-level Flow**
