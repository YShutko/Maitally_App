<p align="center">
  <img src="Logo.png" alt="Maitally Logo" width="120"/>
</p>

# Maitally — AI-powered Document Assistant

> Behördenbriefe einfach verstehen · Making German bureaucracy manageable

[![Platform](https://img.shields.io/badge/Platform-Android-green)](https://play.google.com/store)
[![Flutter](https://img.shields.io/badge/Flutter-3.41.9-blue)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-europe--west3-orange)](https://firebase.google.com)
[![AI](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-purple)](https://cloud.google.com/vertex-ai)
[![GDPR](https://img.shields.io/badge/DSGVO-Compliant-brightgreen)](https://yshutko.github.io/maitally-privacy)

---

## Team

| Name | Role |
|---|---|
| **Prof. Dr.-Ing. Fabian Fürst** | Founder · Concept, Product Vision & Product Strategy |
| **M.Sc. Yulia Shutko** | Co-Founder · Lead Developer & Technical Architecture |


---

## About

Maitally is an AI-powered Flutter mobile application for the German market that helps users — especially non-native German speakers — manage official letters and bureaucratic documents (Behördenbriefe).

German bureaucracy is notoriously complex. Official letters from authorities, insurance companies, banks and employers are often long, formal and difficult to understand — especially for expats and immigrants. Maitally makes this manageable.

---

## Key Features

- **Document Scanning** — Scan or upload official documents (photo or PDF)
- **AI Analysis** — Gemini 2.5 Flash extracts key information, identifies urgency and deadlines
- **Smart Summaries** — Clear, readable summaries in the document's original language
- **Multi-language Translation** — All extracted information translated into the user's preferred language
- **Actionable To-Dos** — Automatically generated tasks and subtasks based on document content
- **AI Chat** — Ask questions about the document content directly in the app
- **Deadline Tracking** — Important dates and deadlines highlighted and tracked
- **Push Notifications** — Reminders for upcoming deadlines and weekly summaries
- **Biometric Authentication** — Optional fingerprint/Face ID lock for sensitive documents
- **Privacy by Design** — Original photos deleted immediately after AI analysis

---

## Tech Stack

### Frontend
- **Flutter** 3.41.9 · **FlutterFlow** (visual builder)
- **Dart** · Material Design
- Android (Google Play) · iOS coming soon

### Backend & Cloud
- **Firebase Firestore** — Document database (europe-west3)
- **Firebase Storage** — Document uploads (europe-west3)
- **Firebase Auth** — Email/Password + Google Sign-In
- **Firebase Cloud Messaging** — Push notifications
- **Python Cloud Functions** — Backend logic & AI orchestration

### AI
- **Vertex AI Gemini 2.5 Flash** — Document analysis, summarization, translation, chat
- Multimodal input (image + text)
- Structured JSON output
- RAG pattern for document chat

### Payments & Infrastructure
- **RevenueCat** — Subscription management
- **IONOS** — Email hosting (support@maitally.de)
- **Google Play** — App distribution

---

## Privacy & DSGVO Compliance

Maitally is built DSGVO/GDPR-compliant from the ground up:

- All data processed exclusively in the **EU (europe-west3, Frankfurt)**
- Original document photos **deleted immediately** after AI analysis
- No data shared with third parties
- No AI training on user data
- Full account deletion available in-app (Art. 17 DSGVO)
- Google Cloud Data Processing Agreement (DPA) in place

[Privacy Policy](https://yshutko.github.io/maitally-privacy) · [Delete Account](https://yshutko.github.io/maitally-privacy/delete-account.html)

---

## Subscription Plans

| Plan | Price | Scans/Month |
|---|---|---|
| **Basis** | Free | 1 scan |
| **Unlimited** | €4.90/month or €79.90/year | Unlimited |

---

## Status

Currently in **Internal Testing** on Google Play.

- [x] Core document analysis pipeline
- [x] AI Chat (RAG-based)
- [x] Multi-language translation
- [x] Push notifications & reminders
- [x] Biometric authentication
- [x] Subscription management
- [x] DSGVO compliance
- [ ] iOS release
- [ ] Public launch

---

## Screenshots

*Coming soon*

---

## Contact

- **Support:** support@maitally.de
- **Privacy:** https://yshutko.github.io/maitally-privacy
- **Developer:** [github.com/YShutko](https://github.com/YShutko)

---

*© 2026 Maitally · M.Sc. Yulia Shutko & Prof. Dr.-Ing. Fabian Fürst*
