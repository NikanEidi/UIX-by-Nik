# UIX544 — Practice Midterm Test | Mock 2

**Duration:** 100 minutes  
**Total:** 20 marks / 5 marks each

---

## Scenario — Pharmacy Prescription Refill App

A local pharmacy chain wants to simplify its mobile prescription refill feature. The app allows customers to view their active prescriptions, select one to refill, choose a pickup location, select a preferred pickup time, review the refill request, and confirm the order. The goal is to make the refill process fast and stress-free, especially for users who are managing ongoing medications and need a reliable, clear experience.

---

## Persona — Routine Manager

Diana is a 38-year-old working professional who manages monthly prescription refills for herself and her elderly mother. She uses mobile apps regularly but prefers straightforward, no-surprise experiences. She gets anxious when she is unsure whether an action went through correctly and dislikes having to repeat steps. She always double-checks before confirming anything important.

She says: *"I just need to know it's been sent and when I can pick it up — I don't have time to figure out a complicated app."*

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

The user's main goal is to quickly select and confirm a prescription refill for herself and her mother, without confusing steps or uncertain actions, and to receive a clear confirmation that includes the pickup time.

The main needs or pain points are: feeling anxious when unsure whether an action was completed correctly, frustration with repetitive or unnecessary steps, and needing a clear summary after confirming to feel confident the request was sent.

A suitable task flow is: `Start → View active prescriptions → Select prescription to refill → Choose pickup location and time → Review refill request → Confirm refill → End`

System feedback is needed when the user confirms the refill, because Diana needs to know the request has been successfully sent and see the exact pickup time before leaving the app.

One possible friction point is having too many separate steps for selecting location and time. The design could reduce this by merging pickup location and time into a single screen, and adding clear labels and a response after every action so Diana never feels uncertain about what happened.

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

The most important information for the user is the list of active prescriptions, available pickup locations and times, and a confirmation summary showing that the refill request was sent along with the pickup details.

The easiest actions to access should be the prescription selection, the pickup location and time selectors, and the confirm button. All key actions should be large, clearly labeled, and provide immediate visual feedback after each tap.

These priorities fit the persona because Diana manages refills for two people, prefers a straightforward experience with no surprises, and needs to feel confident that every action was registered correctly before moving forward.

One design decision that reduces effort or confusion is adding a Back button on every screen, so Diana can correct a selection without starting the entire flow over — reducing anxiety and the risk of repeating steps.

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
| View Active Prescriptions | Overview | Diana needs to browse all active prescriptions before selecting one to refill | Prescription list, patient name label, Select button | User is reviewing available prescriptions and choosing one |
| Choose Pickup Location and Time | Focus | User is focused on one specific decision — where and when to pick up | Radio buttons for location, time slot selector, Next button | User is narrowing down the refill details based on availability |
| Confirm Refill | Do | User completes the final action of submitting the refill request | Confirm button, refill summary, pickup location and time | User has confirmed the refill and can see full details in the confirmation summary |

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

One useful navigation decision is adding a progress indicator at the top of each screen, so Diana always knows which step she is on and how many remain — reducing anxiety and helping her feel in control of the process.

The first interaction design principle is the Feedback Principle. A specific UI decision is displaying a visible response after every action — such as a checkmark when a prescription is selected and a success message after confirming — so Diana never feels uncertain whether her action was registered.

The second interaction design principle is Fitts's Law. A specific UI decision is placing the Confirm button large and at the bottom of the screen within easy thumb reach, and making all selection buttons a comfortable tap size, so Diana can move through the flow quickly without struggling with small targets.

Together, these decisions support the persona because Diana is an anxious user who needs constant reassurance that her actions are working, dislikes repeating steps, and wants to finish the refill quickly and confidently without any surprises.

---

> ✍️ *Writed by Nikan Eidi*