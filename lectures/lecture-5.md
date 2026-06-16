# 📓 Lecture 5 — Navigation

> Navigation is how users move through your app — and how they never get lost.

---

## 🧭 The Three Questions

Good navigation always answers:

```mermaid
flowchart LR
    A[Where am I?] --> B[Where can I go?] --> C[How do I get back?]
    style A fill:#caa24a,color:#1a1a1a
    style B fill:#e0c97f,color:#1a1a1a
    style C fill:#f0e4c0,color:#1a1a1a
```

If a user can answer all three at any moment, your navigation works.

---

## 🧱 Types of Navigation

| Type | What It Is | Best For |
|------|-----------|----------|
| **Tab Bar** | 4–5 icons at the bottom | Mobile |
| **Hamburger Menu** ☰ | Hidden slide-out menu | Mobile with many options |
| **Top Navigation** | Menu across the top | Desktop |
| **Back Button** | Return to previous screen | Everywhere |
| **Progress Indicator** | Shows position in a process | Forms, checkout |

---

## 📱 Mobile vs Desktop

```mermaid
flowchart TB
    subgraph Mobile
    M[Tab Bar at the BOTTOM]
    end
    subgraph Desktop
    D[Navigation at TOP or LEFT]
    end
    style M fill:#caa24a,color:#1a1a1a
    style D fill:#e0c97f,color:#1a1a1a
```

- **Mobile** → bottom tab bar (easy thumb reach).
- **Desktop** → top or left-side menu (more space).

---

## 📊 Progress Indicators

For multi-step tasks, show users where they are:

```mermaid
flowchart LR
    A((1<br/>Select)) --> B((2<br/>Customize)) --> C((3<br/>Review)) --> D((4<br/>Confirm))
    style B fill:#caa24a,color:#1a1a1a
```

This answers **"Where am I?"** and reduces anxiety — the user always knows how much is left.

---

## 🔁 Helping Users Recover

- A clear **Back button** lets users undo a wrong turn.
- **Breadcrumbs** show the path taken.
- Predictable placement (back = top-left, menu = top-right) builds confidence.

---

## ✅ Quick Reference

| Need | Solution |
|------|----------|
| Mobile main nav | Tab Bar |
| Many hidden options | Hamburger Menu |
| Know your position | Progress Indicator |
| Go back safely | Back Button |

---



---
> ✍️ *Writed by Nikan Eidi*


