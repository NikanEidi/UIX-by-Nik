# UIX544 — Practice Midterm Test | Mock 4

**Duration:** 100 minutes  
**Total:** 20 marks / 5 marks each

---

## Scenario — Gym Class Booking App

A fitness centre wants to improve its mobile class booking feature. The app allows members to browse available fitness classes, select a class, choose a time slot, add the class to their schedule, review the booking, and confirm. The goal is to make the booking process fast and straightforward, especially for members who want to plan their weekly workouts without spending too much time in the app.

---

## Persona — Weekly Planner

Priya is a 27-year-old marketing professional who goes to the gym 3 to 4 times per week. She books her classes every Sunday for the upcoming week. She is comfortable with mobile apps but gets frustrated when she has to repeat steps or loses her selections after navigating away from a screen. She prefers to see all available classes at a glance and book multiple sessions in one sitting.

She says: *"I want to plan my whole week in one go — I don't want to start over every time I pick a new class."*

---

## Part A — User Goal & Task Flow *(5 marks)*

### ✅ Answer

The user's main goal is to quickly browse and book multiple fitness classes for the upcoming week in one sitting, without losing her selections or repeating steps every time she picks a new class.

The main needs or pain points are: getting frustrated when selections are lost after navigating away from a screen, wasting time on repetitive steps when booking multiple classes, and needing to see all available classes at a glance without being overwhelmed by too many options at once.

A suitable task flow is: `Start → Select date from weekly calendar → Browse available classes and time slots for selected date → Select class and add to schedule → Repeat for other dates → Review all bookings → Confirm → End`

System feedback is needed when the user confirms the booking, because Priya needs to know all her selected classes were successfully booked and can see a full weekly schedule summary before leaving the app.

One possible friction point is showing all classes for the entire week at once, which overwhelms the user with too many choices. The design could reduce this by using a weekly calendar where Priya selects a date first, and only the available classes for that specific date are shown — applying Hick's Law to reduce decision overload.

---

## Part B — Design Priorities & Content Decisions *(5 marks)*

### ✅ Answer

The most important information for the user is the weekly calendar view, available class names and time slots for each selected date, and a running summary of already selected classes so Priya can track her weekly plan as she builds it.

The easiest actions to access should be the date selector on the calendar, the class selection buttons, the Add to Schedule button, and the final Confirm button. All buttons should be large, clearly labeled, and placed within easy thumb reach at the bottom of the screen.

These priorities fit the persona because Priya books every Sunday for the full week ahead and wants to plan multiple sessions in one sitting. Showing the right information at the right time — date first, then classes for that date — lets her move through the flow without confusion or repeated steps.

One design decision that reduces effort or confusion is persisting her selected classes across screens so that when she navigates back to pick a class for another date, her previous selections are saved and visible — directly addressing her frustration of losing selections after navigating away.

---

## Part C — Screen Type & Screen Purpose *(5 marks)*

### ✅ Answer

| Screen | Screen Type / Model | Reason | Key UI Element | User Progress |
|--------|---------------------|--------|----------------|---------------|
| Weekly Calendar | Overview | Priya needs to see the full week at a glance and select which dates to book classes for, without being overwhelmed by all classes at once | Weekly calendar grid, date selector, already-booked indicators | User is selecting which days she wants to book and building a mental picture of her week |
| Available Classes for Selected Date | Focus | After selecting a date, Priya is focused on one specific decision — which class and time slot to pick for that day | Class cards, time slot selector, Add to Schedule button | User is choosing a class for one specific day, keeping decisions manageable |
| Review and Confirm Bookings | Do | User completes the final action of confirming all selected classes for the week | Confirm button, full weekly booking summary, class names and times | User has confirmed all bookings and can see the complete weekly schedule |

---

## Part D — Navigation, Interaction & Design Justification *(5 marks)*

### ✅ Answer

One useful navigation decision is placing a Back button on every screen so Priya can return to the calendar and adjust a class selection for a specific day without losing her other bookings or restarting the entire flow.

The first interaction design principle is Hick's Law. A specific UI decision is filtering the class list by selected date, so instead of showing all classes for the entire week at once, Priya only sees the available options for one day at a time — reducing decision overload and making each choice faster.

The second interaction design principle is the Feedback Principle. A specific UI decision is showing a persistent mini-summary of already selected classes at the top of the screen while Priya continues booking, so she always knows what she has picked and never feels like her selections were lost.

Together, these decisions support the persona because Priya books her entire week in one sitting every Sunday, gets frustrated when selections disappear, and needs to move through multiple booking decisions quickly and confidently without starting over.

---

> ✍️ *Writed by Nikan Eidi*
