## 🎯 Goals

- Low latency (<100ms)
- Horizontally scalable
- Highly available
- No database writes for presence updates

---

## 🧠 Core Idea

Presence data is **ephemeral (temporary)** and changes frequently.  
Therefore:

❌ Do NOT store presence in database  
✅ Store presence in **in-memory distributed cache (Redis)**  
✅ Broadcast updates using **Pub/Sub (Kafka)**  

---

## 🏗 High-Level Architecture
