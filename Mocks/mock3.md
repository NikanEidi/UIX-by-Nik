# UIX544 — Practice Midterm Test | Mock 3

**Duration:** 100 minutes  
**Total:** 20 marks / 5 marks each

---

## Scenario — Campus Food Court Pre-Order App

A college campus wants to modernize its food court experience by introducing a mobile pre-order feature. The app allows students to browse food stalls, select one stall, choose a meal item, customize it, select a pickup window, review the order, and confirm. The goal is to help students skip the line and pick up their food between classes without waiting or wasting time.

---

## Persona — Between-Class Rusher

Jordan is a full-time college student with a packed schedule. He has a 20-minute break between classes and uses it to grab food from the campus food court. He is very comfortable with mobile apps and hates waiting. He gets frustrated when apps slow him down with unnecessary screens or unclear buttons. He always knows what he wants before opening the app.

He says: *"I already know what I want — I just need to order it fast and know it'll be ready when I get there."*

---

## Part A — User Goal & Task Flow *(5 marks)*

**Suggested Answer Structure:**
```
The user's main goal is to...
The main needs or pain points are...
A suitable task flow is: Start → ... → ... → ... → End
System feedback is needed when... because...
One possible friction point is... The design could reduce this by...
```

### ✅ Answer

The user's main goal is to quickly select a food stall, place an order, and confirm the pickup time without being slowed down by unnecessary screens or unclear buttons.

The main needs or pain points are: having only 20 minutes between classes with no time to waste, getting frustrated when unclear buttons or extra screens slow the ordering process down, and needing a clear confirmation with the pickup window location so he can go directly there after class.

A suitable task flow is: `Start → Browse food stalls and select one → Choose and customize meal item → Select pickup window → Review and confirm order → End`

System feedback is needed when the user presses the confirm button, because Jordan needs to know his order was received and see the pickup window location before leaving the app.

One possible friction point is having too many separate screens before reaching the order. The design could reduce this by merging the stall browsing and selection into one screen, and using clearly labeled buttons throughout so Jordan never slows down looking for the next action.

---

## Part B — Design Priorities & Content Decisions *(5 marks)*

**Suggested Answer Structure:**
```
The most important information for the user is...
The easiest actions to access should be...
These priorities fit the persona because...
One design decision that reduces effort or confusion is...
```

### ✅ Answer

The most important information for the user is the available food stalls, meal options, and pickup window locations — all visible early in the flow so Jordan can move through the app without searching.

The easiest actions to access should be the stall selection, meal and customization buttons, and the confirm order button. All cards should display stall information clearly, and all selection buttons should be large, clearly labeled, and placed within easy thumb reach.

These priorities fit the persona because Jordan already knows what he wants before opening the app and only has 20 minutes between classes. Surfacing the right information immediately and keeping every action fast and obvious lets him complete the order without slowing down.

One design decision that reduces effort or confusion is merging the stall browsing and selection into a single screen, so Jordan can browse and choose in one step without navigating through extra windows.

---

## Part C — Screen Type & Screen Purpose *(5 marks)*

### ✅ Answer

| Screen | Screen Type / Model | Reason | Key UI Element | User Progress |
|--------|---------------------|--------|----------------|---------------|
| Browse Food Stalls | Overview | Jordan needs to see all available stalls at once and select one quickly | Stall cards, stall name, select button | User is reviewing available stalls and choosing one |
| Select Pickup Window | Focus | After choosing his meal, Jordan is focused on one specific decision — which window to pick up from | Radio buttons, pickup window list, Next button | User is selecting the pickup location based on proximity to class |
| Review and Confirm Order | Do | User completes the final action of submitting the order | Confirm button, order summary, pickup window location | User has confirmed the order and can see full details including pickup window and estimated ready time |

---

## Part D — Navigation, Interaction & Design Justification *(5 marks)*

**Suggested Answer Structure:**
```
One useful navigation or wayfinding decision is...
The first interaction design principle is... A specific UI decision is...
The second interaction design principle is... A specific UI decision is...
Together, these decisions support the persona because...
```

### ✅ Answer

One useful navigation decision is placing a Back button on every screen, so Jordan can quickly correct a wrong stall, meal, topping, or pickup window selection without losing his progress or restarting the flow.

The first interaction design principle is Fitts's Law. A specific UI decision is placing a large Confirm button at the bottom of the screen within easy thumb reach, and making all stall and meal selection buttons a comfortable tap size, so Jordan can move through the entire flow quickly without struggling with small or misplaced targets.

The second interaction design principle is the Feedback Principle. A specific UI decision is displaying a clear response after every action — particularly a success message after confirming the order — so Jordan always knows his action was registered and can see the pickup window location before closing the app.

Together, these decisions support the persona because Jordan has only 20 minutes between classes, already knows what he wants, and needs an app that keeps up with him — fast tappable buttons, zero uncertainty, and a clear confirmation so he can walk straight to the pickup window.

---

> ✍️ *Writed by Nikan Eidi*
