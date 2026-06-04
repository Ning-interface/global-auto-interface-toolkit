# Global Auto Interface Toolkit

A static web-based portfolio project for customer-facing technical, business, and project interface workflows in automotive and global manufacturing contexts.

The toolkit demonstrates how customer feedback can be converted into structured issue records, action tracking, 8D-style problem-solving drafts, supplier risk visibility, controlled English customer communication, and printable case-pack reports.

**Live Demo:** `https://ning-interface.github.io/global-auto-interface-toolkit/`

---

## Overview

Global Auto Interface Toolkit is designed as a simulated workflow portal for interface roles that connect customers, engineering, quality, project teams, and suppliers.

The project is not intended to replicate any specific company’s internal system. Instead, it abstracts common workflow patterns found in automotive and global manufacturing environments:

* customer issue intake and clarification;
* internal owner assignment and action tracking;
* risk visibility before launch or SOP decisions;
* 8D-style problem-solving documentation;
* supplier risk follow-up;
* customer-facing English communication;
* standalone HTML case-pack export for interview demonstration.

The technical implementation is intentionally lightweight. The main value of this project is workflow design, communication structure, documentation logic, and role understanding.

---

## Scope and Disclaimer

All scenarios, customers, suppliers, and outputs in this project are simulated portfolio materials.

This project does not represent confidential information, real customer projects, internal company documents, or any official OEM / supplier-specific workflow.

The supplier risk model is a simplified portfolio model. It does not represent any formal supplier scorecard, OEM-specific evaluation standard, or company-specific quality system.

The 8D output is for structure demonstration only. It does not replace engineering verification, official quality systems, or customer-specific 8D formats.

---

## Core Workflow

The portal is organized around a simplified customer-facing issue workflow:

```text
Customer Feedback
→ Issue Log
→ Owner Assignment
→ Risk & 8D Review
→ Customer Response
→ Case Pack Export
```

The workflow focuses on how an interface role turns incomplete or unclear customer feedback into structured follow-up actions, risk visibility, and controlled communication.

---

## Main Modules

### Customer Issue Response Generator

Converts customer issue input into:

* issue summary;
* risk summary;
* action list;
* customer-facing English email draft.

This module is designed to demonstrate controlled wording before internal technical conclusions are fully finalized.

### 8D Report Generator

Converts a customer issue into a structured D1–D8 report draft:

* D1 — Team Formation;
* D2 — Problem Description;
* D3 — Temporary Containment;
* D4 — Root Cause Analysis;
* D5 — Corrective Action Plan;
* D6 — Verification;
* D7 — Prevention of Recurrence;
* D8 — Closure and Communication.

The 8D output is intentionally framed as a draft and structure demonstration.

### Supplier Risk Visualizer

Evaluates simplified supplier risk across four dimensions:

* quality;
* delivery;
* communication;
* compliance / documentation.

The output includes total risk score, risk level, follow-up recommendation, and suggested escalation items.

### Scenario Control Panel

Provides preset simulated business scenarios:

* Pre-SOP Noise Issue;
* Prototype Delivery Delay;
* Compliance Documentation Risk.

The control panel supports:

* one-click scenario loading;
* automatic output generation;
* copy actions;
* input validation;
* smooth navigation;
* English / Chinese / bilingual HTML report export.

### Case Pack Export

The export function generates a standalone HTML case pack containing:

* Executive Summary;
* Case Overview;
* Outlook-style Customer Email Draft;
* 8D Report Board;
* Supplier Risk Dashboard;
* Action Tracker;
* Portfolio Disclaimer.

The generated report can be opened directly in a browser or printed as PDF.

---

## Design Principles

This project follows a conservative B2B portal style rather than a decorative personal homepage style.

Key design principles:

* left-aligned business content for readability;
* centered page container with controlled width;
* minimal decoration and no artificial visual noise;
* consistent card hierarchy;
* clear separation between input, output, and exported report;
* explicit disclaimer for simulated content;
* English-first interface with optional Chinese / bilingual report export;
* no external icon library, backend service, database, or authentication layer.

---

## Technical Implementation

This is a static front-end project.

```text
HTML
CSS
Vanilla JavaScript
GitHub Pages
```

Main implementation features include:

* form-based workflow input;
* scenario preset loading;
* generated output rendering;
* input validation and error feedback;
* smooth navigation between workflow sections;
* copy-to-clipboard actions;
* standalone HTML report generation;
* English / Chinese / bilingual export logic;
* print-friendly report layout;
* embedded SVG icons;
* offline HTML usability.

---

## Release Contents

The stable release is intentionally compact:

```text
global-auto-interface-toolkit/
├── index.html
└── README.md
```

The project is implemented as a self-contained static portal. The `index.html` file includes the page structure, styling, interaction logic, scenario presets, validation, report export, and embedded icon system.

---

## Development Milestones

The following milestones are reconstructed from the development repository history and grouped for readability. They summarize the project’s design evolution rather than functioning as a production commit log.

### v0.1 — Documentation Foundation

Established the initial repository structure and documentation materials, including:

* issue workflow draft;
* issue log template;
* action list template;
* meeting follow-up email template;
* SOP risk decision email template;
* meeting minutes template;
* risk register template;
* pre-SOP abnormal noise case background;
* issue log and action list for the pre-SOP case;
* final response email sample;
* role map and JD keyword map.

Representative development commits included:

```text
Initial commit
Add customer issue workflow
Add issue log template
Add action list template
Add meeting follow-up email template
Add SOP risk decision email template
Add meeting minutes template
Add risk register template
Add pre-SOP abnormal noise case background
Add issue log for pre-SOP case
Add action list for pre-SOP case
Add final response email sample
Add target role map
Add JD keywords map
```

### v0.2 — Case Study Expansion

Expanded the simulated pre-SOP case with additional structured artifacts:

* case summary;
* 5Why analysis sample;
* risk register for the pre-SOP case;
* issue confirmation email template.

Representative development commits included:

```text
Add case summary for pre-SOP issue
Add 5Why analysis sample
Add risk register for pre-SOP case
Add issue confirmation email template
```

### v0.3 — Web Portal Foundation

Converted the repository from a document-oriented project into a web-based portfolio portal.

Key work included:

* README project overview update;
* GitHub Pages portal page;
* live demo link;
* portfolio identity update;
* clearer public-facing project positioning.

Representative development commits included:

```text
Update README project overview
Update README with role map and case details
Add portfolio portal page
Add live demo link to README
Add live demo link
Update live demo link
Update portfolio identity
```

### v0.4 — Interactive Tool Modules

Added the first major interactive workflow modules:

* Customer Issue Response Generator;
* 8D Report Generator;
* Supplier Risk Visualizer;
* tool module navigation.

Representative development commits included:

```text
Add 8D report generator
Add supplier risk visualizer
Add tool modules section
```

### v0.5 — Data Sanitization and Portfolio Boundaries

Generalized customer-facing samples and removed real customer references from public-facing outputs.

Key work included:

* replacing real customer names with neutral sample names;
* generalizing customer email samples;
* clarifying simulated portfolio positioning.

Representative development commits included:

```text
Replace real customer name with sample customer
Generalize customer email sample
```

### v0.6 — Portal Layout and Workflow Positioning

Improved the web portal structure and role positioning.

Key work included:

* portal layout upgrade;
* contact links;
* refined workflow positioning;
* clearer interface-role framing.

Representative development commits included:

```text
Upgrade portal layout and contact links
Refine portal workflow positioning
```

### v0.7 — Scenario Control and Workflow Actions

Added scenario-driven interaction and workflow utility actions.

Key work included:

* scenario presets;
* one-click output generation;
* copy actions;
* export actions;
* smooth scrolling and navigation improvements.

Representative development commits included:

```text
Add scenario presets and export actions
Add validation and smooth scroll navigation
```

### v0.8 — Report Export Foundation

Upgraded the output from plain generated text to a standalone HTML case-pack report.

Key work included:

* HTML report export;
* report structure upgrade;
* script repair after report export refactoring;
* case pack layout improvement.

Representative development commits included:

```text
Upgrade case pack export to HTML report
Upgrade exported case pack layout
Fix broken script after report export upgrade
```

### v0.9 — Bilingual Report Export

Added multilingual report output while keeping the website interface English-first.

Key work included:

* English report export;
* Chinese report export;
* bilingual report export;
* improved bilingual report layout;
* section icon system.

Representative development commits included:

```text
Add bilingual report export option
Polish bilingual report layout and add icon system
```

### v1.0 — Portal Visual Review

Refined the portal interface and navigation.

Key work included:

* improved portal layout and navigation;
* conservative visual polish;
* reduced unnecessary decoration;
* clearer card hierarchy.

Representative development commits included:

```text
Polish portal layout and navigation
Conservative polish for portal layout
```

### v1.1 — Stable Portfolio Refinement

Finalized the public-facing version with a more conservative, professional interface and complete contact links.

Key work included:

* refined portal layout;
* LinkedIn link integration;
* GitHub / LinkedIn / email contact entries;
* cleaner report output;
* simplified hero preview;
* reduced visual noise;
* clarified simulated-content boundaries.

Representative development commits included:

```text
Refine portal layout and add LinkedIn link
```

---

## Suggested Use Cases

This project can be used as:

* a portfolio link in a resume;
* an interview demonstration portal;
* a discussion artifact for overseas technical support, project coordination, customer quality, application engineering, or technical-business interface roles;
* a self-contained offline HTML demo if GitHub Pages is not accessible.

---

## Contact

**LinkedIn:** `https://www.linkedin.com/in/jyunning-zyu-1018a6326`
**GitHub:** `https://github.com/ning-interface`
**Email:** `zyujyunning@outlook.com`

---

## Positioning Statement

This project is not positioned as a software engineering portfolio.

It is positioned as a workflow and communication portfolio demonstrating:

* structured communication;
* customer-facing English documentation;
* project interface thinking;
* issue follow-up logic;
* risk visibility;
* simulated automotive manufacturing workflow awareness.

The technical implementation is intentionally simple. The intended value is in workflow design, communication structure, documentation logic, and role understanding.
