# Custodian: Culture on Its Own Terms 🌍✨

> **Culture isn't content. It is community-owned knowledge.**

[![Live Demo](https://img.shields.io/badge/Live-Website-brightgreen?style=for-the-badge&logo=vercel)](https://custodian-chi.vercel.app/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/prathvikshettyy/vcet_custodian)
[![VCET Resurrect Hackathon](https://img.shields.io/badge/VCET-Resurrect_Hackathon_2026-blue?style=for-the-badge)]()
[![Track](https://img.shields.io/badge/Track-Culture_and_Community-orange?style=for-the-badge)]()

---

## 🚀 Overview

Traditional cultural tourism prioritizes visitors, leaving local custodians without control over their stories, access, and financial value. When culture travels without its custodians, meaning and value travel away.

**Custodian** is a custodian-first digital platform designed for discovering, experiencing, and preserving living culture on its own terms. Grounded in the core design principle that **"AI translates culture; it does not invent it,"** the platform ensures that consent, native language preservation, spatial context, and fair value return are embedded directly into every cultural interaction.

---

## 💡 Key Features

* **Custodian-Controlled Consent:** Custodians define what can be seen, shared, or booked. Consent acts as a first-class data layer where scope, audience, reuse rights, and revenue rules travel alongside every story.
* **Native-Language Storytelling:** Custodians record field notes and audio in their native regional dialects, preserving their authentic voice rather than providing a diluted summary.
* **AI-Assisted Multilingual Access:** Grounded translation allows travellers to listen and read in their preferred language without eroding local cultural authority.
* **Place-Led Map Discovery:** Interactive spatial discovery introduces genuine relationships and context rather than extracting content.
* **Direct Participation & Monetization:** Experience bookings, craft commissions, and direct support mechanisms return financial value straight to knowledge holders.
* **Acoustic Drone & Soundscape Synthesis:** Native Web Audio synthesizer provides harmonic tanpura drones and bronze temple bells to ground oral storytelling in authentic regional atmospheres.

---

## 🛠️ System Architecture

```text
┌────────────────────────────────────────────────────────────────────────┐
│                           USER INTERFACES                              │
│   [ Cultural Custodian ]     [ Traveller ]     [ Institutions / NGOs ] │
└───────────────┬───────────────────┬───────────────────────┬────────────┘
                │                   │                       │
                ▼                   ▼                       ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   FRONTEND (React 19 / Vite)                           │
│        Multilingual UI | Interactive Maps | Soundscapes | Storytelling │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   CUSTODIAN SERVICES & CORE ENGINES                    │
│ ┌──────────────────────┐ ┌───────────────────┐ ┌─────────────────────┐ │
│ │ Cultural Consent API │ │ Living Audio Eng. │ │ Spatial Waypoints   │ │
│ └──────────────────────┘ └───────────────────┘ └─────────────────────┘ │
│ ┌──────────────────────┐ ┌───────────────────┐                         │
│ │ Custodian Provenance │ │ Multilingual i18n │                         │
│ └──────────────────────┘ └───────────────────┘                         │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📂 Project Structure

```text
vcet_custodian/
├── public/
│   ├── audio/              # Authentic custodian spoken oral recordings (.wav)
│   ├── favicon.svg         # Platform favicon
│   └── icons.svg           # Scalable iconography
├── src/
│   ├── assets/             # Brand visual assets
│   ├── components/         # Modular React UI components
│   │   ├── AudioPlayer.jsx        # Synchronized audio & transcript player
│   │   ├── CustodianBoundary.jsx  # Protected cultural perimeter component
│   │   ├── CustodianProfile.jsx   # Verified custodian lineage & trust view
│   │   ├── JourneyComplete.jsx    # Expedition stamp seal & reflection ledger
│   │   ├── LanguageScreen.jsx     # Regional dialect & language selector
│   │   ├── LivingMap.jsx          # Interactive spatial cultural canvas
│   │   ├── NavigationHeader.jsx   # Top application header & breadcrumb
│   │   ├── StoryScroll.jsx        # Long-form narrative field-journal view
│   │   └── WelcomeScreen.jsx      # Orientation portal & cultural manifesto
│   ├── data/
│   │   ├── fieldNotesData.js      # Living cultural dataset & locales
│   │   └── translations.js        # Multilingual UI dictionaries (en, kn, tu, hi)
│   ├── styles/
│   │   ├── tokens.css             # Design system CSS variables & tokens
│   │   └── global.css            # Base typography, resets, animations
│   ├── utils/
│   │   └── audioEngine.js         # Web Audio API & Web Speech synthesis engine
│   ├── App.jsx                    # Root state machine & screen orchestrator
│   ├── index.css                  # Global CSS bundle entry
│   └── main.jsx                   # React 19 application entry point
├── ARCHITECTURE.md         # Detailed architectural specification
├── CONTRIBUTING.md         # Cultural consent & code guidelines
├── index.html              # HTML5 entry with OpenGraph metadata
├── package.json            # Node.js project manifest & scripts
├── vite.config.js          # Vite configuration
└── README.md
```

---

## ⚡ Quick Start

### Prerequisites
* Node.js 18+ (tested with Node 20 & 24)
* npm 9+

### Installation
```bash
# Clone the repository
git clone https://github.com/prathvikshettyy/vcet_custodian.git
cd vcet_custodian

# Install dependencies
npm install

# Start local development server
npm run dev
```

### Build for Production
```bash
npm run build
npm run preview
```

---

## 📜 Cultural Covenant

All traditions presented in this repository remain the intellectual and cultural property of the respective hereditary custodians, performers, and community elder councils. Commercial exploitation or artificial generation of protected lore is strictly prohibited under the Coastal Guild Living Culture Charter.
