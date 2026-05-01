# 📊 Data Consistency in Distributed Systems

## What is Consistency?

Consistency ensures that all nodes in a distributed system see the **same data at the same time**.

---

## Types of Consistency

### 1. Strong Consistency
- All reads return the latest write
- Slower but accurate

### 2. Eventual Consistency
- Data becomes consistent over time
- Faster and more scalable

### 3. Weak Consistency
- No guarantee of immediate consistency

---

## CAP Theorem

A distributed system can only guarantee **two out of three**:

- Consistency
- Availability
- Partition Tolerance

---

## Real-world Usage

- Banking systems → Strong consistency  
- Social media feeds → Eventual consistency  