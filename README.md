# 🧳 AI Trip Planner ✈️🌍

## ⚠️ Important Note
This project showcases an **autonomous AI-powered travel assistant** that dynamically plans trips using **Agentic AI workflows**, **LangGraph**, and **LangChain tools**. The system generates **personalized itineraries**, handles **budget planning**, integrates **real-time data** such as weather, and supports **multi-city travel plans**.

---

## 🌟 Brief
Planning a trip can be overwhelming — travelers often juggle multiple sources for flights, hotels, activities, and budgets.

The **AI Trip Planner** solves this by combining **modular AI agents** with **real-time APIs** to automate research and itinerary building. Using **LangGraph**, the assistant mimics human decision-making to route between tools, refine choices, and provide **context-aware recommendations**.

A **Streamlit-based interface** makes it easy for users to interact with the planner, receive instant itineraries, and adapt plans on the go.

---

## 🛠️ Technology Stack
**Frontend**: Streamlit  
**Backend**: Python, LangGraph, LangChain  
**Tools Integrated**: Weather API, Tavily Search (destinations & attractions), Currency Conversion, Budget Planning utilities  
**LLMs**: Agentic AI via LangGraph orchestration  
**Deployment**: Streamlit Cloud / local runtime  
**Version Control**: GitHub

---

## ✨ Key Features
- 🗺️ **Autonomous Trip Planning**: Generates detailed multi-city itineraries.  
- 🌦️ **Weather-Aware Suggestions**: Incorporates climate forecasts to refine travel timing.  
- 💸 **Budget Optimization**: Provides cost breakdowns for transport, stay, and activities.  
- 💱 **Currency Conversion**: Displays expenses in the traveler’s preferred currency.  
- 🔄 **Adaptive Reasoning**: Uses memory and state chaining for contextual, human-like planning.  
- 💻 **Interactive UI**: Streamlit interface for an easy, responsive experience.

---

## 🏗️ Architectural Diagram
High-level architecture showing user request → LangGraph workflow → LangChain tools (weather, search, budget, currency) → itinerary generation → Streamlit interface.

---

## 🤖 AI Workflow Components
### 🌐 Destination Exploration
Searches for attractions, accommodations, and activities using Tavily Search.

### 🌦️ Weather Integration
Checks weather forecasts to suggest the best time to travel.

### 💸 Budget Planning
Analyzes estimated costs and breaks them down by city and activity.

### 💱 Currency Conversion
Converts total trip cost into the user’s preferred currency for global convenience.

---

## 🌟 Opportunities

### 🔍 How different is it from other travel apps?
- **Agentic Multi-Tool Integration**: Unlike static itinerary apps, this uses LangGraph to dynamically switch between tools, making responses **adaptive and personalized**.  
- **Context Memory**: Plans adapt during the conversation, remembering user preferences.  
- **Real-Time Data**: Incorporates live APIs for weather and costs, ensuring up-to-date recommendations.

### 👥 User-Centric Design
- A **simple conversational interface** that feels like talking to a travel assistant.  
- Users just enter trip details (e.g., destinations, days, budget), and the system generates a **ready-to-use plan**.  
- Focus on **clarity, personalization, and interactivity**.

---

## 🌍 How It Solves the Problem

### ✈️ Simplified Planning
Automates research across destinations, weather, and budgets into one seamless workflow.

### 💵 Budget Control
Keeps expenses transparent by showing detailed breakdowns in the user’s local currency.

### 🧩 Personalized Itineraries
Adapts to multi-city trips, preferences, and constraints while maintaining contextual memory.

### 📅 Time-Saving
Reduces planning time significantly by combining exploration, analysis, and itinerary design.

---

## 🌟 USP of the Solution
- 🔄 **Dynamic Agent Workflow**: LangGraph ensures adaptive reasoning for human-like planning.  
- 🌍 **Global Usability**: Currency conversion + real-time weather integration.  
- 🎯 **Highly Personalized**: Plans shaped by user preferences and adaptive memory.  
- ⏱️ **Efficiency**: Delivers usable itineraries in seconds instead of hours.

---

## 🌐 Application Pages

### 🏠 Home Page
Landing page where users enter destinations, dates, and budget preferences.

### 📝 Itinerary Page
Displays a complete multi-city travel plan, including activities, accommodations, and weather insights.

### 💡 Suggestions Page
Provides additional recommendations, local tips, and real-time adjustments.

---

## 📌 Key Takeaways
- Demonstrates how **Agentic AI** can be applied to real-world travel planning.  
- Combines **LangGraph**, **LangChain**, and **Streamlit** for an adaptive, modular architecture.  
- Provides an **intuitive, user-facing solution** for seamless trip planning.  
