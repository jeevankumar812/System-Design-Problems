# Day 1 – WhatsApp: Real-Time Presence at Scale

## 📌 Problem Statement

WhatsApp has over 2 billion users. When a user opens the app, they instantly see which of their contacts are **Online** or **Last Seen**.

Design a **Presence Service** that:

- Handles **50 million concurrent WebSocket connections**
- Shows Online / Offline / Last Seen in real-time
- Broadcasts presence updates to millions of followers
- Avoids creating a massive **write bottleneck** in the database

---
