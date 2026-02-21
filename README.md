# PolicyBot 

## Overview

PolicyBot is a policy exploration platform that enables users to understand government and legal documents through a conversational interface grounded in evidence.

This repository contains the complete UI/UX architecture and frontend implementation of the platform, including:

- Landing page
- Policy Notebooks interface
- ChatGPT-style chatbot UI
- Responsive layout system
- Modular component architecture

I worked as the UI/UX Developer and Frontend Engineer, designing and implementing the full user interface for the platform.

---

## Problem Statement

Government and institutional policy documents are:

- Long  
- Complex  
- Difficult to interpret  
- Hard to navigate efficiently  

PolicyBot solves this by allowing users to:

- Ask questions in natural language  
- Receive answers grounded in original policy text  
- View clear source citations for verification  

---

## What PolicyBot Does

### 1. Chat-Based Policy Exploration

Users can ask questions in plain language.

The system:

- Retrieves relevant policy sections  
- Generates responses grounded in the original document  
- Displays clear citations  
- Avoids hallucinated content  

The UI is inspired by modern conversational AI interfaces (ChatGPT-style design).

---

### 2. Preloaded Policy Collections

Policy notebooks are structured thematic collections of public policies.

Examples included in the UI:

- AI Governance  
- Union Budget 2026–2027  
- Education Policy in India (NEP 2020)  

Each notebook provides:

- Structured summaries  
- Document-level breakdowns  
- Quick exploration links  
- Search functionality  

---

### 3. Bring Your Own Documents

The interface supports:

- Uploading policy documents  
- Organizing documents into collections  
- Structured exploration via chat  

---

### 4. Privacy & Responsible Use

The UI emphasizes:

- Workspace-based document access  
- Clear communication on data usage  
- Responsible AI positioning  
- Non-legal advisory disclaimer  

---

## Repository Structure


policybot-frontend-suite/
│
├── frontend/ # Chat UI (Next.js app)
│ ├── components/
│ ├── hooks/
│ ├── lib/
│ └── app/
│
├── Homepage/ # Landing page + Notebook UI
│
└── README.md


---

## Folder Breakdown

### frontend/

- ChatGPT-style conversational interface  
- Markdown rendering  
- Source citation UI  
- Sidebar with policy collections  
- Model selector  
- Responsive mobile-first layout  

### Homepage/

- Landing page  
- Policy collections page  
- Notebook detail page  
- FAQ section  
- Structured navigation  
- Collaboration branding layout (CeRAI, IITM, WSAI)  

---

## Tech Stack

- Next.js  
- React  
- TypeScript  
- Tailwind CSS  
- Component-driven architecture  
- Responsive design principles  
- Modular UI pattern  

---

## UI/UX Design Approach

### 1. Evidence-First Interaction

The interface was designed to:

- Prioritize clarity  
- Display citations prominently  
- Reduce cognitive overload  
- Avoid cluttered layouts  

---

### 2. Structured Navigation

Navigation includes:

- Overview  
- Policy Notebooks  
- FAQ  
- GitHub  
- Collaboration Section  

The goal was to mimic structured research workflows.

---

### 3. Modern Conversational Interface

The chat interface includes:

- Distinct Human / AI message components  
- Clean typography hierarchy  
- Markdown support  
- Document-linked references  
- Mobile-responsive design  

---

### 4. Accessibility Considerations

- Readable font scaling  
- Clear color contrast  
- Structured spacing system  
- Logical visual hierarchy  

---

## Key UI Features Implemented

- Modular component system  
- Dynamic notebook routing  
- Document search UI  
- Clean grid-based layouts  
- Sidebar-based notebook exploration  
- Interactive upload interface  
- Chat loading states  
- AI response formatting  
- Source-based citation rendering  

---

## Example Policy Collections Represented in UI

### AI Governance

- National AI Strategy (AI for All)  
- RBI FREE-AI framework  
- Responsible AI governance models  

### Union Budget 2026–2027

- Fiscal strategies  
- Economic survey summaries  
- 16th Finance Commission insights  

### Education Policy in India

- NEP 2020 (5+3+3+4 structure)  
- Samagra Shiksha scheme  
- ICT-enabled classrooms  
- Inclusive education initiatives  

---

## My Role

I was responsible for:

- Complete frontend architecture  
- UI/UX design implementation  
- Chat interface structure  
- Responsive layout system  
- Component organization  
- Interaction flow design  
- Navigation structure  

Backend logic and AI pipeline were handled separately.  
This repository focuses exclusively on the frontend engineering and interface design.
