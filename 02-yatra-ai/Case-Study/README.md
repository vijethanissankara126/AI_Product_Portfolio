# YatraAI — Multi-Agent AI Travel Planning

> An AI-native travel planning product designed to simplify fragmented group travel by coordinating research, consensus, budgeting, booking, support, and memory through a multi-agent system.

[Portfolio Case Study](#) · [Prototype](#) · [LinkedIn](#)

---

## Overview

Planning a trip is rarely a single task.

Travellers move between search engines, travel apps, maps, booking platforms, spreadsheets, messaging apps, and reviews to research destinations, compare options, coordinate with others, manage budgets, make bookings, and handle changes after booking.

YatraAI explores how an **agentic AI system** can bring these fragmented activities together into one coordinated travel-planning experience.

Instead of treating AI as a chatbot that answers travel questions, YatraAI is designed as a **multi-agent product system** where specialised agents collaborate around a shared user goal.

### Core Product Idea

**User Request → Research → Option Discovery → Consensus → Budget Optimisation → Booking → Support → Memory**

---

# The Problem

Travel planning becomes increasingly complex when multiple people, preferences, constraints, and budgets are involved.

### Key pain points

- Travel research is fragmented across multiple platforms
- Groups struggle to reach consensus on destinations, hotels, activities, and budgets
- Comparing options across price, preferences, reviews, and constraints is time-consuming
- Budget changes are difficult to track as plans evolve
- Booking is disconnected from the research and decision-making process
- Post-booking changes require users to repeat context across different services
- Previous travel preferences and decisions are rarely carried forward

### Product Opportunity

The opportunity is not simply to make travel search faster.

It is to create an **intelligent coordination layer** that can understand the traveller's intent, coordinate specialised AI capabilities, and help move the user from **intent → decision → action**.

---

# Product Vision

> **Make travel planning feel less like managing dozens of tabs and conversations, and more like delegating the planning to an intelligent travel team.**

YatraAI aims to become a coordinated travel intelligence layer that helps users:

**Discover → Decide → Optimise → Book → Manage → Remember**

---

# Product Discovery

The product exploration covered:

- User personas
- Travel planning journey
- Pain-point analysis
- Competitive analysis
- Raw signals and observations
- Problem framing
- Opportunity areas
- User stories
- Feature prioritisation
- AI capability mapping

### Target Personas

YatraAI was explored across five primary user groups:

1. **Urban Travellers**
2. **Bleisure Travellers**
3. **Tier-2/3 First-Time Flyers**
4. **Corporate Travel Managers**
5. **Creator-Led Trip Organisers**

These personas represent different travel-planning behaviours, constraints, and decision-making patterns.

---

# From Problem to Product

The product strategy evolved around one central question:

> **What happens when AI is responsible not just for answering questions, but for coordinating the entire travel-planning workflow?**

This led to the multi-agent architecture.

---

# Multi-Agent Architecture

YatraAI uses six specialised agents.

```text
                         ┌─────────────────────┐
                         │     USER REQUEST    │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │  ORCHESTRATION /    │
                         │   COORDINATION      │
                         └──────────┬──────────┘
                                    │
          ┌─────────────┬───────────┼───────────┬─────────────┐
          ▼             ▼           ▼           ▼             ▼
     Research       Consensus    Budget      Booking       Support
      Agent           Agent       Agent        Agent         Agent
          │             │           │           │             │
          └─────────────┴───────────┼───────────┴─────────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   Memory Agent      │
                         │ Preferences /       │
                         │ Context / History   │
                         └─────────────────────┘
