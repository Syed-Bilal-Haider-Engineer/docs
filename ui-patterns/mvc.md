# 🧠 MVC (Model–View–Controller)

## Definition

MVC is a UI architecture pattern that separates an application into three components:
- **Model:** Data and business logic
- **View:** UI representation
- **Controller:** Handles user input and updates Model/View

---

## Structure

User → Controller → Model → View

---

## Components

### Model
- Stores data
- Contains business rules
- Independent of UI

### View
- Displays data to user
- UI layer (HTML, templates)

### Controller
- Handles input
- Updates Model
- Chooses View to render

---

## Advantages

- Clear separation of concerns
- Easy to maintain
- Good for web applications
- Parallel development possible

---

## Disadvantages

- Controller can become too large (fat controller problem)
- Tight coupling between View and Controller in some implementations

---

## Real-world Use

- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}