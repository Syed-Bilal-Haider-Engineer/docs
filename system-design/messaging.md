# 📨 Messaging in System Design

## What is Messaging?

Messaging allows services to communicate **asynchronously** using events or messages.

---

## Why Messaging?

- Decouples services
- Improves scalability
- Handles failures gracefully
- Supports asynchronous workflows

---

## Types of Messaging

### 1. Message Queue
- One-to-one communication
- Example: RabbitMQ, SQS

### 2. Publish/Subscribe (Pub/Sub)
- One-to-many communication
- Example: Kafka, Redis Pub/Sub

---

## Advantages

- Loose coupling
- High scalability
- Fault tolerance

---

## Real-world Example

Order placed → Payment Service → Notification Service