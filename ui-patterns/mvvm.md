# ⚛️ MVVM (Model–View–ViewModel)

## Definition

MVVM is a modern UI pattern that uses **data binding** to connect UI and logic without direct coupling.

---

## Structure

View ↔ ViewModel ↔ Model

---

## Components

### Model
- Business logic and data
- Independent of UI

### View
- UI layer
- Uses data binding
- No direct logic

### ViewModel
- Connects View and Model
- Contains presentation logic
- Exposes data via observable properties

---

## Key Feature

✔ Two-way data binding  
✔ No direct View–Model dependency  

---

## How It Works

1. View binds to ViewModel
2. ViewModel updates automatically reflect in UI
3. User input updates ViewModel directly

---

## Advantages

- Clean separation of concerns
- Highly testable
- Great for data-driven UIs
- Reduces boilerplate UI code

---

## Disadvantages

- Complex for beginners
- Debugging binding issues can be hard
- Overkill for small apps

---

## Real-world Use

- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}
- :contentReference[oaicite:4]{index=4}