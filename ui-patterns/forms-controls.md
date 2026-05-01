# 🧾 Forms & Controls Pattern

## Definition

Forms & Controls is a simple UI pattern where the interface is split into:
- **Form (View):** UI layout (buttons, inputs, fields)
- **Code-behind (Controller logic):** Handles events and business actions

---

## How It Works

1. User interacts with UI (click, input, submit)
2. Event is triggered in code-behind
3. Logic executes (validation, API calls, updates)
4. UI is updated manually

---

## Characteristics

- UI and logic are tightly coupled
- No strict separation of concerns
- Common in desktop apps and legacy systems

---

## Advantages

- Very simple to implement
- Fast for small applications
- Minimal architecture overhead

---

## Disadvantages

- Code-behind becomes messy
- Hard to test
- Poor scalability
- Business logic mixed with UI

---

## Example

- Login form handling button click directly in UI file
- Desktop apps like WinForms or early WPF applications

---

## When to Use

- Small applications
- Prototypes
- Internal tools