# KeepSafe Architecture Overview

KeepSafe is a cross-platform credential manager focused on security, performance, and user experience.

## 🧠 Architecture

- Frontend: Flutter (Android & Windows)
- Backend: PostgreSQL (Neon)
- Security: bcrypt, AES-GCM (planned E2E)
- Notifications: Local (no backend dependency)

## 🔐 Security Approach

- Passwords are hashed using bcrypt
- Secure transport via HTTPS (TLS)
- Future roadmap includes end-to-end encryption (E2E)
- Local encrypted backups supported

## ⚙️ Design Principles

- Minimalist UX
- Offline-first capabilities
- Security by design
- Scalable architecture

## 🚀 Key Features

- Secure credential storage
- Search and quick access
- Password update reminders
- Local encrypted backups

## ⚠️ Note

For security reasons, detailed implementation and database structure are not publicly available.