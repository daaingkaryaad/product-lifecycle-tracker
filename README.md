# Development of a Platform for Product Lifecycle Tracking

## Overview
A web-based prototype designed to record, manage, and retrieve product lifecycle information through a unified tracking system. The system maintains structured records of products, digital product passports, and chronological lifecycle event histories.

## Problem Statement, Target Users, and Expected Outcomes
* **Problem Statement:** Information about a product's lifecycle (registration, movement, maintenance, transfers, and retirement) is often stored in separate, fragmented records across different organizations. Retrieving complete product history currently requires manually locating and comparing information from multiple sources.
* **Target Users:** Inventory managers, service personnel, and employees responsible for registering products, managing movement/condition, and logging lifecycle operations. System administrators manage user accounts and access permissions.
* **Expected Outcomes:** A functioning web-based prototype demonstrating product registration, lifecycle event tracking, searchable history retrieval, and role-based access control, supported by requirement specifications and architectural documentation.

## Team Members, Responsibilities, and Supervisor
* **Farida Dovletbayeva** (Software Engineering Student, Group SE-2403)  Database design, Backend development, Lifecycle Event Management, Authentication, Access Control, and System Architecture.
* **Ingkar Adilbek** (Software Engineering Student)  Frontend development, Search, Filtering, Lifecycle History Visualization, and Reporting.
* **Supervisor:** Shyngys Alshynov

## Project Scope and Current Development Status
* **Current Status:** Pre-defense 1 completed (`pre-defense-1` tag).
* **In Scope:** Product identification and registration, chronological event history logging, current status tracking, role-based access control between organizations, search and filtering, and basic reporting.
* **Out of Scope:** Automated hardware testing, third-party payment processing, physical warehouse logistics, and real-time physical GPS tracking.

## Selected Technologies
* **Frontend:** React.js, Bootstrap
* **Backend:** Python (FastAPI / REST API)
* **Database:** PostgreSQL
* **Tools & Infrastructure:** Docker, Git, GitHub, YouTrack

## Project Documentation (`/docs`)
* [`01-PROJECTPROPOSAL.md`](docs/01-PROJECTPROPOSAL.md) — Project title, problem statement, objectives, scope, and target users.
* [`02-RELEVANCEEVIDENCE.md`](docs/02-RELEVANCEEVIDENCE.md) — Evidence of relevance and initial user research analysis.
* [`03-LITERATURE-REVIEW.md`](docs/03-LITERATURE-REVIEW.md) — Literature review of 14 scientific publications on digital product passports.
* [`04-EXISTING-SYSTEMS.md`](docs/04-EXISTING-SYSTEMS.md) — Comparison matrix of existing tracking systems (RepairDesk, Phonecheck, CheckMEND, Circularise).
* [`05-TECHNOLOGY-COMPARISON.md`](docs/05-TECHNOLOGY-COMPARISON.md) — Comparison of backend frameworks, databases, and API architectures.
* [`06-REQUIREMENTS.md`](docs/06-REQUIREMENTS.md) — Functional and non-functional requirements specification with priorities.
* [`07-ARCHITECTURE.md`](docs/07-ARCHITECTURE.md) — Architectural overview including System Context, Use Case, and Component diagrams.
* [`08-UX-MOCKUPS.md`](docs/08-UX-MOCKUPS.md) — Wireframes, key user scenarios, and link to Figma prototype.
* [`09-VERIFICATION-PLAN.md`](docs/09-VERIFICATION-PLAN.md) — Testing plan, outcome metrics, and spreadsheet-based baseline comparison.
* [`10-RISK-MANAGEMENT.md`](docs/10-RISK-MANAGEMENT.md) — Responsibilities, milestones, risk evaluation matrix, and project boundaries.

## YouTrack Project Link
* **YouTrack Task Management Board:** [Product Lifecycle Tracker Board](https://product-lifecycle-tracker.youtrack.cloud)

## Setup, Execution, and Testing Instructions
* **Setup:** Instructions for local deployment will be added upon code integration in subsequent milestones.
* **Testing:** Verification procedures follow the criteria outlined in `docs/09-VERIFICATION-PLAN.md`.
