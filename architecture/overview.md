# 🧠 KeepSafe Architecture Overview

KeepSafe is a cross-platform credential manager designed with a strong focus on **security, performance, and scalability**.

This document provides a high-level overview of the system architecture and design decisions.

---

## 🏗️ System Architecture

KeepSafe follows a **full-stack architecture** with clear separation of concerns:

- **Frontend:** Flutter (Android & Windows)
- **Backend:** PostgreSQL (Neon)
- **Communication:** REST API over HTTPS
- **Notifications:** Local (no backend dependency)

---

## 🔄 Data Flow (Simplified)

```text
User Action → Flutter App → API → PostgreSQL
                         ↓
                   Local Storage / Cache