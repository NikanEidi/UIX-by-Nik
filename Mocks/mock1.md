# UIX544 — Practice Midterm Test

**Duration:** 100 minutes  
**Total:** 20 marks / 5 marks each

---

## Scenario — Library Study Room Booking App

A university library wants to improve its mobile room booking feature. The app allows students to browse available study rooms, select a date and time slot, choose room features (whiteboard, projector, capacity), review the booking details, and confirm the reservation. The goal is to make the booking process quick and straightforward, especially for students who need a room on short notice.

---

## Persona — Last-Minute Planner

Marcus is a second-year university student who often books study rooms the same day he needs them. He is familiar with mobile apps but tends to skip reading instructions and just taps through quickly. He gets frustrated when there are too many filters or steps before he can see available rooms. He wants to find a room fast, confirm it without confusion, and get back to studying.

He says: *"I just want to see what's free right now and book it in under a minute."*

---

## Part A — User Goal & Task Flow *(5 marks)*

Based on the scenario and persona above, explain what the user is trying to accomplish and how they would move through the app feature to complete the task.

Your answer should:
- Define the user's main goal
- Describe the user's main needs or pain points
- Present a clear task flow from start to completion
- Identify where system feedback is needed and why
- Explain how one possible friction point could be reduced through design

**Suggested Answer Structure:**
```
The user's main goal is to...
The main needs or pain points are...
A suitable task flow is: Start → ... → ... → ... → End
System feedback is needed when... because...
One possible friction point is... The design could reduce this by...
```

### ✅ Answer

The user's main goal is to quickly find and confirm an available study room on the same day, without going through too many steps or filters, so he can get back to studying as fast as possible.

The main needs or pain points are: getting frustrated by too many filters and steps before seeing available rooms, needing to book a room on short notice with limited time, and wanting a clear confirmation so he knows the reservation was successful.

A suitable task flow is: `Start → Browse available rooms and time slots → Select a room → Choose room features → Review booking details → Confirm reservation → End`

System feedback is needed when the user confirms the reservation, because Marcus needs to know his booking was successful before leaving the app and returning to his studies.

One possible friction point is the number of filters and steps before reaching the available rooms screen. The design could reduce this by showing a real-time availability table directly on the main screen, so Marcus can browse rooms and time slots immediately without extra steps.

---

## Part B — Design Priorities & Content Decisions *(5 marks)*

Based on the scenario and persona, explain what information and actions should be prioritized in the app feature.

Your answer should:
- Identify the most important information the user needs before making a decision
- Explain which actions should be easiest to access
- Justify why these priorities fit the user's goal, context, and pain points
- Explain one design decision that reduces unnecessary effort or confusion

**Suggested Answer Structure:**
```
The most important information for the user is...
The easiest actions to access should be...
These priorities fit the persona because...
One design decision that reduces effort or confusion is...
```

### ✅ Answer

The most important information for the user is the list of available study rooms for the current date, their available time slots, key features (capacity, whiteboard, projector), and the booking confirmation details.

The easiest actions to access should be the room selection from the availability table, the feature selection buttons, and the confirm reservation button. These should be large, clearly labeled, and placed within easy thumb reach at the bottom of the screen.

These priorities fit the persona because Marcus books rooms the same day he needs them and gets frustrated by too many steps. Showing availability immediately and keeping actions simple and direct matches his goal of booking a room in under a minute.

One design decision that reduces effort or confusion is using a real-time availability table that combines room numbers and open time slots in one view, eliminating the need for multiple filter screens before the user can see their options.

---

## Part C — Screen Type & Screen Purpose *(5 marks)*

Choose **three important screens** from your proposed task flow and explain the purpose of each screen.

For each screen:
- Identify an appropriate screen type or interaction model covered in class
- Justify why it fits that moment in the task
- Explain what key UI element belongs on that screen
- Explain how that screen helps the user move closer to completing the task

**Suggested Answer Structure:**

| Screen | Screen Type / Model | Reason | Key UI Element | User Progress |
|--------|---------------------|--------|----------------|---------------|
| | | | | |
| | | | | |
| | | | | |

### ✅ Answer

| Screen | Screen Type / Model | Reason | Key UI Element | User Progress |
|--------|---------------------|--------|----------------|---------------|
| Room Availability Table | Overview | Marcus needs to browse all available rooms and time slots at once before making a decision | Availability table, room cards, current date label | User is observing options and selecting a room |
| Choose Room Features | Focus | User is focused on configuring one specific room based on his needs | Checkbox list (capacity, whiteboard, projector), Next button | User is personalizing the booking based on requirements |
| Confirm Reservation | Do | User completes the final action of securing the study room | Confirm button, booking summary, room details, time slot | User has confirmed the reservation and can now see full booking details |

---

## Part D — Navigation, Interaction & Design Justification *(5 marks)*

Explain how the app should guide the user through the task and support clear interaction.

Your answer should:
- Describe one navigation or wayfinding decision and why it helps the user
- Apply **two interaction design principles** covered in class to specific UI decisions
- Show how these decisions reduce confusion, save time, prevent errors, or support the persona

**Suggested Answer Structure:**
```
One useful navigation or wayfinding decision is...
The first interaction design principle is... A specific UI decision is...
The second interaction design principle is... A specific UI decision is...
Together, these decisions support the persona because...
```

### ✅ Answer

One useful navigation decision is placing a Back button on every screen, so Marcus can easily go back and change his selected room, time slot, or features without losing progress or starting over.

The first interaction design principle is Hick's Law. A specific UI decision is combining room availability and time slots into a single table on the main screen, reducing the number of choices and filters Marcus has to go through before taking action.

The second interaction design principle is Fitts's Law. A specific UI decision is placing the Confirm button large and at the bottom of the screen, within easy thumb reach, so Marcus can finalize his booking quickly without struggling to tap a small or misplaced button.

Together, these decisions support the persona because Marcus is always in a hurry, gets frustrated by too many steps, and just wants to book a room fast and get back to studying. These choices minimize friction, reduce decision overload, and make every key action easy to reach.

---

> ✍️ *Writed by Nikan Eidi*
