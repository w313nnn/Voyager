# ✈️ Voyager by TSLC

> **CodeNection 2026 — Lifestyle Track: Planning an Escape**

**Team:** Chan Xiang Wei, Lee Wei En, See Jia Yee, Teh Hui Min

**Problem Statement:** Lifestyle Track: Planning an Escape - Travel Planner

**Video Presentation:** [Unlisted YouTube Link](https://youtu.be/GvF9M3HBSh8?si=T0fovRQdq-b1ijRY)

**Presentation Slides:** [Public Link](https://www.figma.com/deck/5pLBlRw19CGLIqTF3TpWtW/Voyager-Presentation-Slides?node-id=90-74&t=yqWdoJ6gcpzFznCy-1)

**UI Prototype:** [Voyager Interactive Prototype](https://domain-whale-37161544.figma.site)

---

# 1. Project Overview

## 🧩 The Problem

Planning a trip is rarely a single task. Travellers often have to coordinate **flights, accommodation, activities, budgets, transportation, and personal preferences** across multiple disconnected tools such as messaging apps, spreadsheets, online travel agencies, navigation platforms, and bill-splitting apps. This becomes especially difficult for group trips, where different budgets, interests, schedules, and expectations must be continuously negotiated.

This fragmented process creates three major problems:

### ⏳ Time and Cognitive Load

Travellers spend significant time searching, comparing, and organising information before a trip. Expedia Group's Path to Purchase research found that travellers spent an average of **303 minutes** engaging with travel content during the 45 days before booking, highlighting how much effort can go into making travel decisions.

### 👥 Group Coordination Friction

Group travellers must balance different **preferences, budgets, energy levels, dietary needs, and activity interests**. The person taking responsibility for planning often carries most of the organisational burden, while disagreements or unclear cost-sharing can slow down decision-making and create unnecessary tension.

### 🔄 Plans Are Fragile When Things Change

Traditional itineraries are often static and require manual adjustments when:

* Flights are delayed
* Weather changes
* Attractions close
* Activities become unavailable

This can result in wasted time, missed bookings, unnecessary transportation costs, and unexpected expenses.

One recent survey reported that **72% of passengers incurred unexpected expenses due to flight delays or cancellations**, while **46% experienced financial losses from travel disruptions**.

Existing travel platforms address individual parts of the journey, but travellers are still left to connect these pieces themselves. This creates an opportunity for a more integrated travel planning experience that can coordinate **preferences, budgets, itineraries, and changes in one place**.

---

## 👥 Target Users

### **Primary: Group Travellers**

Our primary users are **young adults travelling in groups of approximately 3–6 people**, including:

* University students
* Friends
* Couples travelling with friends
* Young working adults

Their main challenge is **coordination**. Each traveller may have different preferences, budget limits, availability, and activity priorities.

Instead of requiring one person to organise everything, our solution allows each member to contribute their **preferences and constraints**, which can then be consolidated into a shared trip plan.

### **Secondary: Solo Travellers**

Solo travellers also face:

* Fragmented planning
* Extensive information searching
* Budget management
* The need to adjust plans when circumstances change

For them, the system focuses more on **personalised itinerary generation, budgeting, and adaptive replanning**.

---

## 🔎 Existing Solutions & Gaps

Current travel platforms generally focus on individual parts of the travel journey, such as:

| Platform / Tool                          | Main Purpose                           |
| ---------------------------------------- | -------------------------------------- |
| **Online Travel Agencies (OTAs)**     | Bookings for flights and accommodation |
| **Navigation and map platforms**     | Locations, routes, and directions      |
| **Spreadsheets / planning documents** | Custom itineraries and budgets         |
| **Messaging platforms**               | Group discussions and decision-making  |
| **Bill-splitting apps**               | Tracking shared expenses               |

While these tools are useful individually, they are **not designed to work together as a unified planning workflow**.

Group preferences, budgets, itinerary decisions, and unexpected changes often still have to be coordinated manually.

---

## 💡 Our Solution

Our Travel Planner brings the major parts of trip planning into **one connected experience**. Users can create a trip, provide their preferences and budget, collaborate with their group, and generate an itinerary that reflects the group's needs. When plans change, the system can help users adapt their itinerary instead of requiring them to rebuild their plans manually.

### ✨ Feature Set

* **AI-Assisted Itinerary Planning** — based on interests, budget, and constraints
* **Group Preference Collection and Coordination**
* **Shared Budget and Expense Management**
* **Adaptive Itinerary Replanning** when disruptions occur
* **Location and Route-Aware Activity Planning**
* **Integration with Travel Information and Availability** where applicable
* **Support for Both Group and Solo Travel**

---

# 2. Ideation & Process

## 2.1 Ideas We Considered

| **Idea**                                    | **Why it was dropped / kept**                                                                                                                                                                                    |
| ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **All-in-One Travel Management Hub**        | ✅ **Kept:** Combines itineraries, accommodations, transport, budgeting, and expense tracking into a single platform, eliminating app-switching fatigue.                                                          |
| **AI-Powered Collaborative Travel Planner** | ✅ **Kept:** Uses AI for personalised itinerary generation, group preference coordination, and adaptive real-time replanning, making trip planning more flexible and suitable for both group and solo travellers. |
| **AI Travel Chatbot**                       | ❌ **Dropped:** Limited to basic recommendations and Q&A; lacks a comprehensive, collaborative trip-planning workflow.                                                                                            |

---

## 2.2 Ideation Boards

### 🌳 Problem Tree

A structured breakdown tracing trip planning challenges from **root causes to ultimate impacts**.

![Problem Tree](https://github.com/w313nnn/Voyager/blob/main/problem_tree.jpeg?raw=true)

---

### 🐟 Fishbone Diagram Analysis

A structured cause-and-effect breakdown of inefficient travel planning categorised into four main factors:

* **Information**
* **People / Group**
* **Planning Process**
* **Adaptability**

![Fishbone Diagram](https://github.com/w313nnn/Voyager/blob/main/fishbone.jpeg?raw=true)

---

### 🗺️ Feature Mind Map

A structural overview of the collaborative travel planner, categorised into five core pillars:

* **Adaptive AI**
* **Group Hub**
* **Itinerary Plan**
* **Shared Budget**
* **Unified Bookings Hub**

![Feature Mind Map](https://github.com/w313nnn/Voyager/blob/main/mindmap.PNG?raw=true)

---

## 2.3 Idea Evolution

### 🌱 Initial Concept

Our initial concept was a basic travel itinerary planner that allowed travellers to organise destinations, activities, accommodation, and transportation in a single itinerary.

However, this still required users to manually make most planning decisions and did not sufficiently address the challenges of group travel.

### 🚀 Major Changes / Pivots

#### 1️⃣ Iteration 1: Added AI-Personalized Itinerary Generation

We introduced an AI-assisted itinerary generator that creates personalised travel plans based on users' **travel style, budget, preferred pace, and interests**.

This reduced the effort required to manually search for and arrange suitable activities.

#### 2️⃣ Iteration 2: Expanded from Individual Planning to Group Collaboration

We expanded the concept to support **group travel planning**, allowing multiple travellers' preferences, budgets, interests, and schedules to be considered.

Group coordination features were added to make collective decision-making easier.

#### 3️⃣ Iteration 3: Developed an Integrated and Adaptive Travel Platform

We further expanded the system by integrating:

* Budget and expense management
* Location-aware route planning
* Travel information
* Adaptive itinerary replanning

This transformed the concept from a simple itinerary generator into an **all-in-one travel management platform** that can also adapt when travel plans change.

---

### 🗑️ Dropped Directions

The team initially considered developing a standalone **AI travel chatbot** that would provide travel recommendations and answer users’ questions.

However, this direction was dropped because it only addressed a small part of the overall travel planning process and did not sufficiently support:

* Group collaboration
* Budgeting
* Route planning
* Itinerary management

Instead, AI capabilities were integrated into the final platform through **personalised itinerary generation and adaptive replanning**.

---

### 🕐 Evolution Timeline

```text
Create an all-in-one travel planner
                ↓
Initial Concept:
Basic single-user manual itinerary manager
                ↓
Iteration 1:
Added AI-personalised itinerary generation
                ↓
Mentor Feedback:
Streamlined scope to focus strictly on core features
                ↓
Iteration 2 and 3:
Expanded to group collaboration,
budget tracking and adaptive replanning
                ↓
Final Concept:
Integrated All-in-One Collaborative Travel Platform
```

---

## 2.4 Mentor Consultation

| **Date**       | **Mentor**        | **Feedback Received**                                                                                                           | **What Was Changed**                                                                                                                          |
| -------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **08.09.2026** | **Teh Ming En**   | Prototype was solid but overloaded with features. Recommended focusing strictly on core functionalities.                        | Streamlined scope and removed non-essential features, such as showing details of upcoming days on the home page, including days and schedule. |
| **09.09.2026** | **Khor Jia Quan** | Suggested improving typography contrast, adding multi-emoji support for activities, and utilising real-life imagery/countdowns. | Upgraded font size/contrast, added custom activity icons, and enhanced flight/hotel UI with real-life imagery.                                |

---

# 3. Design & Prototype

## 🔗 UI Prototype

**[Open Voyager Interactive Prototype](https://domain-whale-37161544.figma.site)**

> The prototype showcases the key user flows and interfaces of Voyager.

---

## 🔐 User Onboarding

Sign in or create an account to access the travel planner.

### Interaction

* 🚀 User enters Voyager
* 🔑 Sign In
* 📝 Create Account
* 🔵 Continue with Google

![User Onboarding](onboarding.png)

---

## 🏠 Trip Dashboard

Provides an overview of upcoming trips, travellers, budget and important alerts.

### Interaction

* Upcoming trip
* Travel disruption alert
* Number of travellers
* Group total
* Trip status

![Trip Dashboard](dashboard.png)

---

## 🤖 AI-Powered Itinerary

Users can generate and manage a **day-by-day travel itinerary**.

### Interaction

* View activities
* Add Activity
* AI Suggest
* Users can view, add and manage activities for each day

![AI-Powered Itinerary](itinerary.png)

---

## 👥 New Trip and Group Management

Users can create a new trip group or join an existing group.

### Interaction

* ➕ New Trip
* 🔗 Join Group

![New Trip and Group Management](group-management.png)

---

## 💰 Group Budget

Tracks shared expenses and calculates each member's balance.

### Interaction

* Group Total
* Per Person
* Expenses

![Group Budget](budget.png)

---

## ✈️ Booking Management

Users can view and manage **flights, hotels and activities** in one place.

![Booking Management](booking.png)

---

# 4. What Makes It Different

## 4.1 Novel Features

### 🤖 AI-Assisted Personalised Itinerary Planning

Voyager generates personalised itineraries based on travellers' **interests, budget, travel pace, and other constraints**.

Unlike basic itinerary planners that require users to manually organise activities, the AI helps create a travel plan that better matches individual or group preferences.

---

### 👥 Group Preference Coordination

Voyager collects and considers the **preferences, budgets, interests, and schedules** of multiple travellers when planning a group trip.

This makes the approach distinctive by helping groups find suitable plans without relying heavily on discussions across different messaging and planning applications.

---

### 🔄 Adaptive Itinerary Replanning

Voyager allows travellers to re-plan their itinerary when unexpected changes or disruptions occur.

Instead of manually reorganising the entire trip, the system can suggest alternative activities or arrangements while considering the:

* Existing itinerary
* Preferences
* Budget
* Location

---

## 4.2 Differentiation from Existing Solutions

| **Capability**                         | **Existing Solutions**                                                  | **Our Solution**                                                                                    |
| -------------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Itinerary planning**             | Relies on manual searching and structuring of activities.               | Uses AI-driven personalised itinerary generation based on interests, budget, pace, and constraints. |
| **Group preferences**               | Requires scattered discussions across external messaging apps.          | Centralised collection and coordination of group preferences when planning.                         |
| **Budget management**               | Budgeting and expense splitting are often handled using separate tools. | Integrates shared budget and expense management directly with the trip plan.                        |
| **Dynamic replanning**              | Requires manually modifying the user's itinerary when plans change.     | Supports adaptive replanning by suggesting suitable alternatives when disruptions occur.            |
| **Location / Route-Aware Planning** | Often ignores geographical distance and transit efficiency.             | Considers activity locations and routes to create a more practical travel schedule.                 |

---

### 🌟 Our Key Difference

Our core strength lies in combining:

> **AI-powered personalisation + Group coordination + Budgeting + Route awareness + Adaptive replanning**

into a **single, unified platform**.

Rather than requiring travellers to use separate applications for different parts of their trip, Voyager brings the entire planning process together in one place.

By seamlessly balancing the individual needs and schedules of multiple travellers, it eliminates the friction of group coordination and effortlessly adapts the itinerary whenever travel plans change.

---

# 5. Technical Architecture & Feasibility

## 💻 Tech Stack

| **Component**      | **Technology**                   | **Why we chose it**                                                                                               | **Expected constraint**                                                      |
| ------------------ | -------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **Frontend**    | React Native & Expo              | Builds cross-platform mobile interfaces smoothly based on our UI prototypes.                                      | Advanced native mobile features may require custom configuration.            |
| **Backend**     | Supabase & Node.js API           | Provides rapid backend services, authentication, and custom API endpoints without building a server from scratch. | Free tier usage and resource limits apply.                                   |
| **Database**   | PostgreSQL (via Supabase)        | Stores user accounts, trips, itineraries, bookings, and expense information in a structured way.                  | Schema design must be carefully planned as features expand.                  |
| **Data & APIs** | External Travel APIs & Mock Data | Integrates third-party APIs (or mock data) to simulate live flight details, schedules, and disruption alerts.     | External API rate limits and reliance on mock data for real-time edge cases. |
| **Hosting**     | Supabase Cloud + Expo            | Enables seamless cloud deployment for both app services and database management.                                  | Cloud hosting free tiers have bandwidth and data limitations.                |

---

## 🏗️ System Architecture

*Optional: Add the system architecture diagram here if your team has one.*

![System Architecture](system-architecture.png)

---

## 📦 Build Plan & Scope

The building phase will focus on the **core functions required to demonstrate the main travel planning experience**.

### 1. User Account

* Create an account
* Sign in
* Continue with Google
* Store basic user information

### 2. Trip Management

* Create and save a trip
* Set travel dates
* Add destinations
* Display trip overview on the Home page

### 3. Itinerary Management

* Create a daily itinerary
* Add activities to each day
* Display activity time and location
* View different days of the trip
* Edit itinerary details

### 4. Booking Management

* Add and view flight bookings
* Add and view hotel bookings
* Display booking status
* Highlight disrupted bookings
* Access the re-planning function for affected flights

### 5. Budget Management

* Set a total trip budget
* Record travel expenses
* Display total spending
* Display spending for each traveller
* Show remaining budget

### 6. Flight Disruption & Re-planning

* Simulate a flight disruption
* Display the impact on the itinerary
* Identify affected activities or bookings
* Display alternative flight options
* Allow users to select an alternative flight

---

## ✅ In Scope

The building phase will focus on:

* User registration and login
* Trip creation and management
* Daily itinerary planning
* Flight and hotel booking management
* Budget and expense tracking
* API-integrated flight disruption
* Alternative flight selection and re-planning

---

## 🚫 Out of Scope

To keep the project realistic and achievable within the development timeline, the following features will not be fully implemented:

* Real flight ticket purchasing
* Real hotel booking
* Real payment processing
* Real-time airline booking availability
* Real-time flight disruption data
* Full-scale AI travel planning
* Social networking between travellers

---

# 6. Impact & Future Potential

## 6.1 Expected Impact

Voyager aims to reduce the time and effort required to plan a trip while making group decision-making more manageable and travel itineraries more resilient to unexpected changes.

The platform addresses these issues by connecting previously fragmented activities into a **single workflow**.

| **Before**                                               | **With Our Solution**                                                   |
| -------------------------------------------------------- | ----------------------------------------------------------------------- |
| Information scattered across multiple apps            | Trip information is organised in one centralised workspace          |
| One person handles most planning                      | Group members actively contribute and coordinate preferences         |
| Group preferences discussed manually                  | Preferences are collected and considered systematically              |
| Budget tracked separately in external tools           | Budgeting is integrated directly with itinerary planning             |
| Static itineraries that are hard to change            | Dynamic itineraries that adapt when circumstances change             |
| Disruption management requires manual replanning      | The system identifies affected plans and proposes smart alternatives |
| Travellers repeatedly search for information          | AI-assisted recommendations reduce manual searching                 |
| Popular activities dominate, ignoring minority choices | Recommendations fairly weigh individual and group preferences        |

---

## 🎁 Benefits to Target Users

* **Reduced Effort:** Minimises manual legwork through AI-assisted itinerary generation.
* **Lower Cognitive Load:** Centralises key trip details into a single unified workspace.
* **Streamlined Group Coordination:** Automatically reconciles individual preferences and budgets.
* **Enhanced Budget Awareness:** Connects day-to-day spending directly with itinerary decisions.
* **Disruption Resilience:** Provides adaptive replanning workflows when travel plans go off track.
* **Context-Aware Insights:** Generates recommendations based on location, time, budget, and personal preferences.

---

## 6.2 Scalability & Future Development

While our initial MVP focuses on **small group travel**, Voyager is engineered for broad expansion.

### 👨‍👩‍👧 Larger User Groups

The platform could support:

* Larger travel groups
* Family trips
* School trips
* Corporate travel
* Organised tours

### 🌍 Global Destinations

The system can be expanded to support more destinations by integrating additional:

* Location APIs
* Activity APIs
* Transportation APIs
* Weather APIs
* Travel-information APIs

### 🔌 Expanded API Integrations

Future versions could integrate:

* Flight APIs
* Hotel APIs
* Public transportation APIs
* Attraction booking APIs
* Weather services
* Currency exchange services

This would allow the system to provide **more accurate real-time planning**.

### 🧠 Advanced Personalisation

Future versions could build long-term traveller profiles containing:

* Preferred activities
* Typical budget
* Travel pace
* Food preferences
* Accommodation preferences
* Preferred transportation

This could make future itinerary generation **more personalised**.

### 🤝 Ecosystem Partnerships

The platform could eventually partner with:

* Local activity providers
* Restaurants
* Accommodation providers
* Transportation providers
* Tourism organisations

---

# 🔗 Project Links

|                            | Link                                                          |
| -------------------------- | ------------------------------------------------------------- |
| 🎥 **Video Presentation**  | [Unlisted YouTube Link](https://youtu.be/GvF9M3HBSh8?si=T0fovRQdq-b1ijRY) |
| 🎨 **UI Prototype**        | [Voyager Interactive Prototype](https://domain-whale-37161544.figma.site) |
| 📊 **Presentation Slides** | [Public Link](https://www.figma.com/deck/5pLBlRw19CGLIqTF3TpWtW/Voyager-Presentation-Slides?node-id=90-74&t=yqWdoJ6gcpzFznCy-1) |

---

# 👥 Team TSLC

**CodeNection 2026 — Lifestyle Track: Planning an Escape**

* **Lee Wei En**
* **Chan Xiang Wei**
* **See Jia Yee**
* **Teh Hui Min**

---

# ✈️ Voyager AI-Powered Collaborative Travel Planner

> **TravelSmarter, Together**
