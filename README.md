# [Project Name] by TSLC

**Team:** Lee Wei En, Chan Xiang Wei, See Jia Yee, Teh Hui Min

**Problem Statement:** Travel Planner

**Video Presentation:** [Unlisted YouTube Link]

**Presentation Slides:** [Public Link]

---

## 1. Project Overview

### The Problem

Planning a trip is rarely a single task. Travellers often have to coordinate flights, accommodation, activities, budgets, transportation, and personal preferences across multiple disconnected tools such as messaging apps, spreadsheets, online travel agencies, navigation platforms, and bill-splitting apps. This becomes especially difficult for group trips, where different budgets, interests, schedules, and expectations must be continuously negotiated.

This fragmented process creates three major problems:

**Time and cognitive load.** Travellers spend significant time searching, comparing, and organising information before a trip. Expedia Group's Path to Purchase research found that travellers spent an average of **303 minutes** engaging with travel content during the 45 days before booking, highlighting the amount of effort involved in making travel decisions.

**Group coordination friction.** Group travellers must balance different preferences, budgets, energy levels, dietary needs, and activity interests. The person taking responsibility for planning often carries most of the organisational burden, while disagreements or unclear cost-sharing can slow down decision-making and create unnecessary tension.

**Plans are fragile when things change.** Traditional itineraries are often static and require manual adjustments when flights are delayed, weather changes, attractions close, or activities become unavailable. This can result in wasted time, missed bookings, unnecessary transportation costs, and unexpected expenses. One survey reported that **72% of passengers incurred unexpected expenses due to flight delays or cancellations**, while **46% experienced financial losses from travel disruptions**.

The problem is therefore not simply a lack of travel information. **The information already exists, but it is fragmented across different tools and does not adapt well to the way people actually plan and travel together.** Travellers are still responsible for connecting information, negotiating decisions, managing costs, and rebuilding their plans when circumstances change.

### Target Users

**Primary: Group Travellers**

Our primary users are **young adults travelling in groups of approximately 3–6 people**, including university students, friends, couples travelling with friends, and young working adults.

Their main challenge is coordination. Each traveller may have different preferences, budget limits, availability, and activity priorities. Instead of requiring one person to organise everything, our solution allows each member to contribute their preferences and constraints, which can then be consolidated into a shared trip plan.

**Secondary: Solo Travellers**

Solo travellers also face fragmented planning, extensive information searching, budget management, and the need to adjust plans when circumstances change. For them, the system focuses more on personalised itinerary generation, budgeting, and adaptive replanning.

### Existing Solutions & Gaps

Travellers currently rely on a combination of tools, each designed to solve a different part of the journey:

| Existing Solution                 | Strength                             | Gap                                                                               |
| --------------------------------- | ------------------------------------ | --------------------------------------------------------------------------------- |
| **Online Travel Agencies (OTAs)** | Flights and accommodation booking    | Do not manage the complete group planning workflow                                |
| **Google Maps**                   | Navigation, locations and routes     | Does not coordinate group preferences, budgets and itineraries                    |
| **Splitwise**                     | Shared expense tracking              | Separate from itinerary and activity planning                                     |
| **Wanderlog**                     | Trip and itinerary organisation      | Limited support for dynamic group decision-making and disruption-based replanning |
| **Messaging apps**                | Group discussion and decision-making | Information becomes scattered and difficult to organise                           |

These tools are useful individually, but travellers still have to **connect them manually**. A group may discuss activities in a messaging app, save locations in a map, build an itinerary in a planning tool, book through an OTA, and track expenses somewhere else.

This creates a fragmented workflow where **planning, decision-making, budgeting, and replanning are treated as separate tasks instead of parts of the same trip.**

### Our Solution

Our Travel Planner brings these parts of trip planning into one connected experience. Users can create a trip, provide their preferences and budget, collaborate with their group, and generate an itinerary based on the group's combined needs.

Rather than treating the itinerary as a fixed schedule, the system is designed to **adapt when the situation changes**. When a disruption occurs, such as a delay, weather change, or unavailable activity, the system can help identify alternative activities and adjust the itinerary while considering existing preferences, budget and location constraints.

**Key features include:**

* 🗺️ **AI-assisted itinerary planning** based on interests, budget and constraints
* 👥 **Group preference coordination** so individual preferences can contribute to a shared plan
* 💰 **Shared budget and expense management** for clearer group spending
* 🔄 **Adaptive itinerary replanning** when unexpected changes occur
* 📍 **Location and route-aware planning** to reduce unnecessary travel
* ✈️ **Travel information integration** where applicable
* 👤 **Support for both group and solo travel**

---

# 2. Ideation & Process

## 2.1 Ideas We Considered

[Briefly explain that the team explored multiple possible solutions before selecting the final concept.]

| Idea                | Why It Was Kept / Dropped |
| ------------------- | ------------------------- |
| **[Chosen Idea 1]** | [Why it was selected]     |
| **[Chosen Idea 2]** | [Why it was selected]     |
| [Idea 3]            | [Why it was dropped]      |
| [Idea 4]            | [Why it was dropped]      |
| [Idea 5]            | [Why it was dropped]      |

> **Tip:** Include meaningful ideas that were actually discussed, including ideas that were eventually dropped.

## 2.2 Ideation Boards

### Mindmap

![Ideation Mindmap](images/ideation-mindmap.png)

[1–2 sentences explaining what the mindmap shows and how it contributed to the final concept.]

### Problem Tree

![Problem Tree](images/problem-tree.png)

[1–2 sentences explaining the root causes, main problem and consequences identified.]

### Other Ideation Evidence

![Brainstorming](images/brainstorming.png)

[1–2 sentences explaining what this board/scribble/diagram demonstrates.]

[Add other actual brainstorming evidence here if useful.]

## 2.3 Idea Evolution

### Initial Concept

[What was your team's original concept?]

### Major Changes / Pivots

**Iteration 1:**
[What changed and why?]

**Iteration 2:**
[What changed and why?]

**Iteration 3:**
[What changed and why?]

### Dropped Directions

[Explain important features or directions that were removed and why.]

### Evolution Timeline

```text
Initial Idea
     ↓
[Concept / Version 1]
     ↓
[Major refinement]
     ↓
[Mentor / team feedback]
     ↓
[Major pivot]
     ↓
Final Concept
```

![Idea Evolution](images/idea-evolution.png)

## 2.4 Mentor Consultation

| Date   | Mentor | Feedback Received | What Was Changed |
| ------ | ------ | ----------------- | ---------------- |
| [Date] | [Name] | [Feedback]        | [Action taken]   |
| [Date] | [Name] | [Feedback]        | [Action taken]   |

[Briefly explain how mentor feedback influenced the final concept.]

---

# 3. Design & Prototype

## 3.1 User Flow

![User Flow](images/user-flow.png)

[Briefly explain the end-to-end journey of the user.]

Example:

```text
Create Trip
    ↓
Set Budget & Preferences
    ↓
Invite Group Members
    ↓
Combine Preferences
    ↓
Generate Itinerary
    ↓
Review & Adjust
    ↓
Trip Begins
    ↓
Unexpected Change
    ↓
Replan Itinerary
```

## 3.2 UI/UX Design

### Design Direction

[Briefly explain your design principles, visual direction, colour scheme, typography and why they suit the target users.]

### Design Iterations

**Early Design:**

![Early Wireframe](images/wireframe-v1.png)

[What was changed from this version?]

**Later Design:**

![Later Design](images/wireframe-v2.png)

[What improved and why?]

## 3.3 Final Prototype

**Interactive Prototype:** [Public Figma / Netlify / Vercel / Other Link]

### Key Screens

**1. [Screen Name]**

![Screen 1](images/screen1.png)

[What the user does here and why this screen matters.]

**2. [Screen Name]**

![Screen 2](images/screen2.png)

[Brief explanation.]

**3. [Screen Name]**

![Screen 3](images/screen3.png)

[Brief explanation.]

**4. [Screen Name]**

![Screen 4](images/screen4.png)

[Brief explanation.]

**5. [Screen Name]**

![Screen 5](images/screen5.png)

[Brief explanation.]

---

# 4. What Makes It Different

## 4.1 Novel Features

### [Feature 1]

[What it does and what makes the approach distinctive.]

### [Feature 2]

[What it does and what makes the approach distinctive.]

### [Feature 3]

[What it does and what makes the approach distinctive.]

## 4.2 Differentiation from Existing Solutions

| Capability            | Existing Solutions            | Our Solution    |
| --------------------- | ----------------------------- | --------------- |
| Itinerary planning    | [How existing apps handle it] | [Your approach] |
| Group preferences     | [Limitation]                  | [Your approach] |
| Budget management     | [Limitation]                  | [Your approach] |
| Dynamic replanning    | [Limitation]                  | [Your approach] |
| [Your unique feature] | [Limitation]                  | [Your approach] |

**Our key difference:**
[2–4 sentences explaining the central combination/twist that differentiates your product.]

---

# 5. Technical Architecture & Feasibility

## 5.1 Tech Stack

| Technology | Purpose   | Why We Chose It |
| ---------- | --------- | --------------- |
| [Frontend] | [Purpose] | [Reason]        |
| [Backend]  | [Purpose] | [Reason]        |
| [Database] | [Purpose] | [Reason]        |
| [AI API]   | [Purpose] | [Reason]        |
| [Maps API] | [Purpose] | [Reason]        |
| [Other]    | [Purpose] | [Reason]        |

### Hosting

**Frontend:** [Platform]

**Backend:** [Platform]

**Database:** [Platform]

[Briefly mention relevant technical constraints, API limitations, costs, rate limits, etc.]

## 5.2 System Architecture

![System Architecture](images/system-architecture.png)

[Brief explanation of how the main components communicate.]

Example:

```text
User
 ↓
Frontend
 ↓
Backend / API
 ├── AI Service
 ├── Maps / Location API
 ├── Travel / Booking API
 └── Database
```

## 5.3 Build Plan & Scope

### Hackathon MVP

During the hackathon, we focused on:

* [Core feature 1]
* [Core feature 2]
* [Core feature 3]
* [Core feature 4]

### Future Development

Features planned beyond the MVP:

* [Future feature 1]
* [Future feature 2]
* [Future feature 3]

### Scope Considerations

[Explain what you intentionally did NOT build and why, e.g. limited hackathon time, API availability, technical complexity, cost, etc.]

---

# 6. Impact & Future Potential

## 6.1 Expected Impact

Our solution aims to reduce the time and effort required to plan a trip while making group decision-making more manageable and travel plans more resilient to unexpected changes.

| Before                                     | With Our Solution  |
| ------------------------------------------ | ------------------ |
| Information scattered across multiple apps | [Your improvement] |
| One person handles most planning           | [Your improvement] |
| Group preferences discussed manually       | [Your improvement] |
| Budget tracked separately                  | [Your improvement] |
| Static itinerary                           | [Your improvement] |
| Disruptions require manual replanning      | [Your improvement] |

### Benefits to Target Users

* [Benefit 1]
* [Benefit 2]
* [Benefit 3]
* [Benefit 4]

## 6.2 Scalability & Future Development

[Explain how the solution could expand beyond the initial target group.]

Potential future directions:

* [Expansion to more users / larger groups]
* [Additional destinations]
* [More travel APIs]
* [Personalisation improvements]
* [Partnerships / integrations]
* [Other future applications]

---

# Appendix

## A. Additional Brainstorming

[Additional brainstorming screenshots, sketches, sticky notes, etc.]

## B. Mentor Feedback Evidence

[Meeting notes, screenshots, feedback records, etc.]

## C. Prototype Iterations

### Version 1

![Prototype V1](images/prototype-v1.png)

### Version 2

![Prototype V2](images/prototype-v2.png)

### Final Version

![Final Prototype](images/final-prototype.png)

## D. Additional Evidence

[Other useful supporting material.]
