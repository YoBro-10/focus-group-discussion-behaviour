# Culture Behaviors Alignment Boards

A specialized real-time tool for focus groups to identify, categorize, and prioritize **observable behaviors** within the Competing Values Framework (Clan, Adhocracy, Market, Hierarchy).

## 🚀 Live Access
- **Phase 1: Current Behaviors** -> `behave_index.html`
- **Phase 2: Preferred Behaviors** -> `behave_preferred.html`

## 🛠 Features
- **Behavioral Focus:** Specifically pre-loaded with action-oriented words (e.g., *Listening, Experimenting, Monitoring*).
- **Toggle Navigation:** A sticky top bar allowing participants to switch between "Current" and "Preferred" views instantly.
- **Visual Distinction:** - **Current:** Indigo/Slate theme (Status Quo).
    - **Preferred:** Rose/Amber theme (Aspiration).
- **Persistent Sessions:** Uses LocalStorage to ensure participants keep their unique User ID across both pages.

## 📋 Facilitator Guide

### Setting Up the Session
1. **Host the Files:** Upload `behave_index.html` and `behave_preferred.html` to your GitHub repository.
2. **Firebase Connection:** Ensure the `firebaseConfig` in both files points to your **Behavior-specific** Firebase project to keep data separate from the Values project.
3. **Participant Links:** Send the link to `behave_index.html` to start the "Current State" discussion.

## 📂 Data Nodes (Firebase)
- `baskets_current/`: Live data for the Current Behaviors board.
- `baskets_preferred/`: Live data for the Preferred Behaviors board.
- `status_current/` & `status_preferred/`: Real-time participant counters.

---
*Focus on what people DO, not just what they say they value.*
