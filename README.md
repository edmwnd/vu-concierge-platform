# Concierge Platform

> A reusable front-end and automation framework for Enterprise Service Management.

---

## Vision

The Concierge Platform provides a consistent digital front door for Enterprise Services.

Rather than building individual kiosks, forms, or portals for each department, the platform provides a common framework that can be adapted for different services while maintaining a familiar user experience and shared automation architecture.

The first implementation is **VUIT Walk-Up Assistance**, but the platform is intended to support additional university services over time.

Examples include:

- Information Technology
- Libraries
- Facilities
- Human Resources
- Student Services
- Research Administration

---

# Objectives

The Concierge Platform aims to:

- Deliver a modern, accessible visitor experience.
- Provide a reusable UI framework for walk-up and self-service interactions.
- Separate presentation from business logic.
- Centralize automation through an Automation Gateway.
- Support multiple departments without duplicating development effort.
- Create a consistent experience regardless of service area.

---

# Design Principles

The platform follows a number of guiding principles.

## Automation First

The user interface captures intent.

Automation performs the work.

Business logic should not live in the front end.

---

## Channel Independent

The same automation should support multiple channels.

Examples include:

- Walk-Up Kiosk
- Teams
- Web
- Mobile
- AI Assistants

---

## Service Independent

The platform is designed to support multiple university services.

Departments should configure the platform rather than build separate solutions.

---

## Consistent Experience

Visitors should encounter familiar interaction patterns regardless of department.

Consistency reduces training and increases confidence.

---

# Current Implementation

Current implementation:

**VUIT Concierge**

Walk-Up Assistance

Features include:

- TeamDynamix Dynamic Form
- Vanderbilt branded interface
- Responsive touch-first design
- Automated ticket creation
- Success screen with automatic return
- Shared design system

---

# Architecture

```
Visitor

      │

      ▼

Concierge UI

      │

      ▼

Automation Gateway

      │

 ┌────┼───────────────┐

 ▼    ▼               ▼

TDX  Teams       Enterprise Services

      │

      ▼

Analytics / Reporting
```

---

# Repository Structure

```
vu-concierge-platform/

README.md

CHANGELOG.md

ROADMAP.md

docs/

shared/

frontend/

automation/

implementations/

assets/
```

---

# Roadmap

## Phase 1

✔ Concierge UI Framework

✔ Walk-Up Assistance

✔ Success Experience

---

## Phase 2

Automation Platform

- Automation Gateway
- Teams Integration
- Adaptive Cards
- Multi-location Routing
- Analytics

---

## Phase 3

Enterprise Adoption

- Library Concierge
- Facilities Concierge
- Student Services Concierge
- HR Concierge

---

## Phase 4

AI Concierge

- Intelligent routing
- Knowledge suggestions
- Conversational interactions
- Copilot integration

---

# Technology

Current platform components include:

- TeamDynamix ITSM
- TeamDynamix iPaaS

Additional platforms may be added over time.

---

# Status

Current Release

**v1.2.0 (Release Candidate)**

---

# License

Copyright © Vanderbilt University.

Internal project.
