# 🎤 MVP (Model–View–Presenter)

## Definition

MVP is a UI pattern where the **Presenter acts as the middle layer between View and Model**, handling all logic.

---

## Structure

View ↔ Presenter ↔ Model

---

## Components

### Model
- Data and business logic
- Independent of UI

### View
- Displays UI
- Sends user actions to Presenter
- Very passive

### Presenter
- Handles all UI logic
- Updates Model
- Updates View manually

---

## Key Idea

The View is **dumb** → it only displays data.

---

## Variants

### 1. Passive View
- View has no logic at all
- Presenter controls everything

### 2. Supervising Controller
- View handles simple UI logic
- Presenter handles complex logic

---

## Advantages

- Highly testable
- Clear separation of logic
- Works well in desktop/mobile apps

---

## Disadvantages

- More boilerplate code
- Presenter can become large
- Manual UI updates required

---

## Real-world Use

- Desktop applications (WPF, WinForms)
- Android apps (older architecture styles)