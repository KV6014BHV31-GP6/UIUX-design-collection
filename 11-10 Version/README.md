# ROSE · PULSE — Complete UI/UX Designer Deliverables (`11-10 Version`)

**Course & Team:** KV6014 Group 6 (`KV6014BHV31-GP6`)

**System:** ROSE · PULSE Community Health Screening & Offline-Resilient Event Management Portal

**Baseline Date:** `2026-11-10` (62 Interactive Pure-Web `1440×900` States · Synchronized with Frontend & Backend RBAC)

## Directory Overview & Quick Navigation

| Folder | Contents | File Count | Primary Audience | 
| ----- | ----- | ----- | ----- | 
| **`01_Design_Specs_and_User_Flows/`** | Comprehensive User Flow Diagrams (`EN` & Bilingual `.pdf`), Designer Specification & UX Differentiation (`.docx`), and Figma Design Tokens & Auto-Layout Component Library (`.docx` & `.pdf`). | 5 | Assessors, Report Lead & QA | 
| **`02_Developer_Handoff_Tokens_and_Matrix/`** | Production CSS Custom Properties (`rose-design-tokens-and-components.css`) and full DOM / REST API / User-Story Alignment Matrix (`ROSE Developer Alignment Matrix DOM APIs UserStories.xlsx`). | 2 | Frontend & Backend Engineers | 
| **`03_Figma_Prototype_Source_and_Wiring_Blueprints/`** | Native Figma project archive (`ROSE PULSE — 62 States Interactive Prototype(11-10).fig`) plus 4 end-to-end node-by-node Prototype Wiring Blueprints (`.svg`). | 5 | UI/UX Designers & Figma Reviewers | 
| **`04_Figma_Vector_SVGs_62_States/`** | All 62 editable `1440×900` vector UI artboards organized into 4 role-scoped folders (`Role1_Participant_27_States`, `Role2_Community_Leader_13_States`, `Role3A_Organizer_Core_12_States`, `Role3B_Organizer_US09_CheckIn_10_States`). | 62 | UI/UX Designers & Frontend | 
| **`05_HiRes_PNG_Previews_66_Files/`** | High-resolution `.png` renders of all 62 UI states and 4 prototype wiring blueprints for instant browser inspection on GitHub without opening Figma. | 66 | All Team Members & Assessors | 

## Role Architecture & Core UX Capabilities (`62 States`)

1. **Role 1 — Participant & Public Guest (`role="user"` · `27 States`, `P-01`–`P-20`)**

   * **Interactive Bilingual Toggle (`EN ⇄ BM`)**: Instant switching between English and Bahasa Melayu across public event discovery and registration screens.

   * **Frictionless Guest Registration (`P-03`–`P-09C`)**: 6-field public event application (`First Name`, `Last Name`, `DOB`, `Gender`, `Phone`, `National ID`) and Guest Status Check (`P-09B`/`P-09C`) with zero mandatory login barrier, plus retained-input duplicate ID feedback (`P-06E`) and waitlist offer-hold support (`P-09`).

   * **Account Sign-Up, SMS OTP & My Registrations (`P-10`–`P-20`)**: Dedicated Sign-In (`P-14`/`P-14B`), Sign-Up with 6-digit SMS OTP verification (`P-15`–`P-18`), personal booking management & cancellation (`P-10`–`P-13`), Profile (`P-19`), and Help Center (`P-20`).

2. **Role 2 — Community Leader Assisted Offline Intake (`role="leader"` · `13 States`, `L-01`–`L-13`)**

   * **100% Zero-OCR Manual Offline Entry (`L-06`–`L-12`)**: Privacy-first 6-field manual intake that persists drafts locally across browser restarts (`L-07`), enforces resident consent & local duplicate checks (`L-08`), and performs batch synchronization with organizer review receipts (`L-10`–`L-12`).

3. **Role 3A — Event Organizer Core Portal (`role="organizer"` · `12 States`, `O-01`–`O-12`)**

   * **Simplified Event Creation & Bilingual Registration Review**: Streamlined 3-photo event publishing (`O-03`–`O-06`), bilingual registration queue (`O-07` EN ⇄ `O-08` BM), **150% Supporting Document Lightbox Modal** (`O-09`), quota reallocation (`O-10`), 5,000-persona simulation analytics (`O-11`), and CSV export (`O-12`).

4. **Role 3B — Organizer Event-Day Check-In & Walk-In Sub-Function (`US-09` · `10 States`, `F-01`–`F-10`)**

   * **Operational Sub-Function under `role="organizer"`**: Offline-capable preloaded roster (`F-01`–`F-04`), 6-field on-site walk-in registration (`F-05`–`F-07`), duplicate check-in prevention (`F-08`), batch reconnect sync (`F-09`), and session attendance summary drawer (`F-10`).

## Quick Import Guide

* **Import Full Prototype into Figma**: Open Figma Desktop or Web, click **Import file**, and select `03_Figma_Prototype_Source_and_Wiring_Blueprints/ROSE PULSE — 62 States Interactive Prototype(11-10).fig`.

* **Frontend Styling & Token Integration**: Import `02_Developer_Handoff_Tokens_and_Matrix/rose-design-tokens-and-components.css` and cross-reference field IDs, routes, and status badges against `ROSE Developer Alignment Matrix DOM APIs UserStories.xlsx`.
