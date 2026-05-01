# 🧅 Onion Architecture

## Core Idea

The **business logic is at the center**, and everything depends on it—not the other way around.

---

## Layers

### 1. Domain (Core)
- Business logic
- Entities

### 2. Domain Services
- Business rules
- Interfaces

### 3. Application Layer
- Orchestration

### 4. Infrastructure
- Database
- APIs

---

## Key Principle

➡️ Dependency flows inward

---

## Advantages

- Highly testable
- Decoupled architecture
- Flexible infrastructure

---

## Disadvantages

- More complex
- Requires experience